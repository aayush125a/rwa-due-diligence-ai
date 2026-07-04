# MVP Scope

This document defines exactly what is built for this hackathon submission,
and what is intentionally left for later. Nothing outside "Built" should be
implied as working in the README, demo, or pitch.

## Built (hackathon submission)

- [ ] Upload flow for a small set of trade documents (invoice, purchase order)
- [ ] AI step that reads uploaded documents and returns a structured report:
      extracted values, basic cross-document consistency check, a simple
      risk score, and plain-English explanation of findings
- [ ] Human review screen: Approve / Reject / Request More Documents
- [ ] One smart contract call on TRON testnet that stores a hash of the
      due diligence report plus metadata, and emits an event
- [ ] Confirmation / listing screen showing the on-chain transaction

## Explicitly NOT built (long-term vision only — Future Works)

- Real fraud/forgery detection, sanctions/regulatory screening, company
  registry verification
- Real exchange integration (e.g., HTX) — hackathon version is a mocked
  listing screen only
- Continuous post-listing monitoring, automated re-scoring, new report
  versions
- Any real capital-raising, investor-facing, or fund-transfer mechanism

## Why this split matters

Every claim in the README, demo script, and pitch deck must map to a
checked box above. If it's not built, it goes in Future Works and nowhere
else.
