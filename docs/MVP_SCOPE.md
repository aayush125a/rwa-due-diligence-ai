# MVP Scope

---

# 1. Purpose

This document defines the exact scope of the Minimum Viable Product (MVP) for
RWA Due Diligence AI, developed for the HTX Genesis Hackathon 2026.

Its purpose is to ensure the team remains focused on delivering a complete,
working demonstration of the core product within the hackathon timeline.

The MVP prioritizes the most important user journey while intentionally
excluding non-essential features that can be developed after the hackathon.

This document serves as the project's execution guide and should be referenced
before adding any new functionality.

---

# 2. MVP Goal

The goal of the MVP is to demonstrate how Artificial Intelligence can
significantly reduce the time and manual effort required to perform due
diligence on Real-World Assets before tokenization.

Rather than building a complete production platform, the MVP focuses on a
single end-to-end workflow that showcases the platform's core value.

The MVP will demonstrate the following journey:

1. A business uploads trade finance documents.
2. The AI Due Diligence Engine analyzes the documents.
3. An Exchange-Ready Due Diligence Package is generated.
4. A Compliance Officer reviews the AI findings.
5. Approved assets receive a verification hash on the TRON blockchain.
6. HTX receives a standardized package for review.

The MVP is designed to validate the product concept, demonstrate technical
feasibility, and clearly communicate the long-term vision of AI-assisted Due
Diligence Infrastructure for Real-World Asset tokenization.

---

# 3. Target Users

The MVP is designed for three primary user groups, each with a clearly defined
role within the due diligence workflow.

---

## 1. Business Users

Business users are companies seeking to tokenize Real-World Assets, such as
trade finance invoices.

Typical examples include:

- Exporters
- Small and Medium Enterprises (SMEs)
- Trade Finance Companies

Their responsibilities include:

- Creating a new asset submission
- Uploading required documents
- Reviewing AI-generated findings
- Responding to requests for additional documents
- Tracking the status of their submission

---

## 2. Compliance Officers

Compliance Officers are responsible for validating AI-generated findings and
making the final approval decision.

Their responsibilities include:

- Reviewing the Exchange-Ready Due Diligence Package
- Examining AI-generated explanations
- Verifying compliance requirements
- Approving, rejecting, or requesting additional documents
- Recording review decisions and notes

The platform is designed to assist Compliance Officers, not replace them.

---

## 3. HTX Reviewers

HTX Reviewers consume the standardized Due Diligence Package after compliance
approval.

Their responsibilities include:

- Reviewing the summarized due diligence report
- Viewing compliance and risk scores
- Verifying the TRON verification hash
- Accessing the audit trail
- Making the final exchange review decision

The MVP focuses on presenting a professional, read-only review interface for
HTX rather than replicating internal exchange systems.

---

# 4. Happy Path Demo

The MVP demonstrates a complete end-to-end Due Diligence workflow using a
single example asset.

Scenario:

A Vietnamese coffee export company has issued a commercial invoice worth
$500,000 to an overseas buyer.

Instead of waiting 60 days for payment, the company wants to tokenize the
invoice after completing AI-assisted due diligence.

The demonstration follows this exact sequence:

---

## Step 1 — Business Creates a Submission

The business logs into the platform and creates a new asset submission.

The business selects:

- Asset Type: Trade Finance Invoice
- Asset Name: Coffee Export Invoice
- Invoice Value: $500,000

---

## Step 2 — Document Upload

The business uploads the required documents.

Example:

- Commercial Invoice
- Purchase Order
- Bill of Lading
- Business Registration
- Tax Certificate
- Insurance Certificate

The platform verifies that all required documents have been submitted before AI
analysis begins.

---

## Step 3 — AI Due Diligence Analysis

The AI Due Diligence Engine processes the uploaded documents.

The analysis includes:

- Document Analysis
- Fraud Signal Detection
- Compliance Checklist
- Risk Assessment
- Valuation Summary
- Confidence Score

The user can observe each processing stage as it completes.

---

## Step 4 — Exchange-Ready Due Diligence Package

After analysis, the platform generates a standardized Due Diligence Package.

The report includes:

- Authenticity Score
- Compliance Score
- Risk Score
- Confidence Score
- Explainable Findings
- Missing Documents (if any)
- Valuation Summary
- AI Recommendation

---

## Step 5 — Compliance Officer Review

A Compliance Officer reviews the AI-generated report.

The officer can:

- Approve
- Reject
- Request Additional Documents

For the MVP demonstration, the asset is approved.

The AI provides recommendations, while the Compliance Officer makes the final
decision.

---

## Step 6 — TRON Verification

After approval, the platform records a verification hash on the TRON
blockchain.

The confirmation includes:

- Verification Hash
- Timestamp
- Report Version
- Issuer Wallet Address

Sensitive business documents remain off-chain.

Only verification metadata is recorded.

---

## Step 7 — HTX Review Package

The approved asset is presented as a professional, standardized review package.

The package includes:

- Due Diligence Report
- Compliance Summary
- Risk Summary
- Explainable Findings
- TRON Verification Hash
- Audit Trail

This demonstrates how HTX reviewers receive a structured package instead of
manually reviewing large collections of business documents.

---

## MVP Completion

The demonstration is complete when the asset successfully progresses from
document submission to AI-assisted due diligence, human approval, blockchain
verification, and HTX-ready review.

This workflow represents the core value proposition of the platform and serves
as the foundation for future product development.

---

# 5. In Scope (Build)

The MVP focuses exclusively on demonstrating the complete AI-assisted Due
Diligence workflow from document submission to blockchain verification.

The following features are included in the MVP.

---

## Business Portal

- Business Dashboard
- Create New Asset Submission
- Document Upload
- Submission Status Tracking

---

## AI Due Diligence Engine

- OCR Document Processing
- Document Analysis
- Fraud Signal Detection
- Compliance Checklist
- Risk Assessment
- Valuation Summary
- Confidence Score
- Explainable Findings
- AI Recommendation

---

## Exchange-Ready Due Diligence Package

Generate a professional Due Diligence Report containing:

- Authenticity Score
- Compliance Score
- Risk Score
- Confidence Score
- Explainable Findings
- Missing Documents
- Valuation Summary
- AI Recommendation

---

## Compliance Officer Portal

- Review Due Diligence Report
- View AI Findings
- Approve Submission
- Reject Submission
- Request Additional Documents
- Officer Notes
- Audit Trail

---

## TRON Integration

After approval, the platform will:

- Create a verification record
- Generate a TRON verification hash
- Store report metadata
- Store report version
- Store timestamp

Sensitive business documents remain off-chain.

---

## HTX Review Package

Generate a standardized review package including:

- Due Diligence Report
- Compliance Summary
- Risk Summary
- Explainable Findings
- TRON Verification Hash
- Audit Trail

---

## Core Dashboard

The MVP dashboard displays:

- Total Assets
- Assets Under Review
- Approved Assets
- Rejected Assets
- Average Risk Score
- Average Compliance Score

---

## Authentication

Simple role-based authentication for:

- Business Users
- Compliance Officers
- HTX Reviewers

The MVP uses lightweight authentication sufficient for demonstration purposes.

# 6. Out of Scope (Post-MVP)

To ensure the successful delivery of the hackathon MVP, several features are
intentionally excluded from the initial implementation.

These capabilities are part of the long-term product vision and may be
developed after the hackathon.

---

## AI Trust Lifecycle Engine

The continuous monitoring system for approved assets is part of the future
platform vision.

This includes:

- Continuous issuer monitoring
- Automated risk score recalculation
- Document expiry monitoring
- Sanctions and regulatory updates
- Suspicious wallet activity detection
- Versioned Due Diligence Reports
- Trust Score history

---

## Advanced AI Models

The MVP uses a simplified AI workflow.

Future versions may include:

- Multi-model AI validation
- Industry-specific Due Diligence Models
- Adaptive fraud detection models
- Continuous model retraining
- Explainability enhancements

---

## Production Security

The MVP prioritizes functionality over enterprise deployment.

Future improvements include:

- Multi-factor Authentication (MFA)
- Single Sign-On (SSO)
- Hardware Security Modules (HSM)
- Encryption key management
- Enterprise identity providers

---

## Advanced Blockchain Features

The MVP demonstrates TRON verification through report metadata.

Future blockchain enhancements include:

- Multiple blockchain support
- Cross-chain verification
- On-chain permission management
- Smart contract upgrades
- Automated token issuance workflows

---

## Enterprise Integrations

Future versions may integrate directly with external systems, including:

- ERP platforms
- Trade finance platforms
- Banking systems
- Compliance providers
- Government verification services
- Identity verification providers

---

## Analytics & Reporting

Future releases may include:

- Organization-wide analytics
- Compliance performance dashboards
- AI accuracy reporting
- Risk trend analysis
- Executive reporting
- Operational insights

---

## Public APIs

The MVP focuses on the web application experience.

Future versions may provide:

- Public REST APIs
- SDKs
- Webhooks
- Third-party integrations
- Developer Portal

---

## Mobile Applications

The MVP is designed for desktop web usage.

Native mobile applications are planned for future releases.

# 7. MVP Success Criteria

The MVP will be considered successful if it demonstrates the complete
AI-assisted Due Diligence workflow from document submission to blockchain
verification.

The following outcomes define a successful demonstration.

---

## Functional Success

The platform allows a Business User to:

- Create a new asset submission
- Upload required trade finance documents
- Submit documents for AI analysis

The AI Due Diligence Engine successfully:

- Processes uploaded documents
- Performs document analysis
- Detects fraud signals
- Evaluates compliance requirements
- Assesses risk
- Generates explainable findings
- Produces a valuation summary
- Calculates confidence and readiness scores

The platform generates an Exchange-Ready Due Diligence Package.

A Compliance Officer can:

- Review AI-generated findings
- Approve or reject the submission
- Request additional documents
- Record review notes

After approval, the platform:

- Generates a TRON verification hash
- Stores verification metadata
- Displays a tokenization confirmation

Finally, the platform presents a professional HTX Review Package containing:

- Due Diligence Report
- Compliance Summary
- Risk Summary
- Explainable Findings
- TRON Verification Hash
- Audit Trail

---

## Demo Success

The complete happy-path demonstration can be performed without errors from:

Business Submission

↓

Document Upload

↓

AI Due Diligence Analysis

↓

Exchange-Ready Due Diligence Package

↓

Compliance Officer Approval

↓

TRON Verification

↓

HTX Review Package

---

## Project Success

Beyond technical implementation, the MVP successfully demonstrates the project's
core vision:

- AI assists compliance teams rather than replacing them.
- Human reviewers remain responsible for final decisions.
- Blockchain provides transparent and verifiable proof of review.
- The platform reduces manual due diligence effort through explainable AI.
- Real-World Assets can move toward tokenization through a standardized,
  trusted verification workflow.

The MVP serves as the foundation for a larger AI-powered Due Diligence
Infrastructure capable of supporting the future growth of Real-World Asset
tokenization.