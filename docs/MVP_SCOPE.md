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