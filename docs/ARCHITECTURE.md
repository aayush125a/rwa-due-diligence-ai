# Architecture

See the diagram at `assets/diagrams/architecture.png` (add the exported
image there once finalized).

## Components

- **Frontend** — upload UI, AI report view, human review screen, listing
  confirmation screen.
- **Backend** — receives uploaded documents, orchestrates the AI call,
  returns the structured report to the frontend, triggers the on-chain
  transaction after human approval.
- **AI Engine** — takes extracted document text, returns a structured JSON
  report (see `docs/API_SPEC.md` for the exact shape).
- **Smart Contract (TRON testnet)** — stores a hash of the due diligence
  report and basic metadata, emits an event. Raw documents never go on-chain.

## Data flow (label every arrow like a sentence)

1. User uploads documents → Frontend
2. Frontend sends documents → Backend
3. Backend sends extracted text → AI Engine
4. AI Engine returns structured report → Backend → Frontend
5. Human reviewer approves → Frontend → Backend
6. Backend calls smart contract → stores hash + metadata on TRON testnet
7. Backend returns tx reference → Frontend shows confirmation/listing screen

Keep this file in sync with the diagram — if one changes, update the other.
