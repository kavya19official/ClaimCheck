# ClaimCheck — Exam Misinformation Verification

**An evidence-first platform for verifying exam and admission-related claims.**

ClaimCheck aims to help students investigate suspicious exam paper-leak claims, forged notices, exam postponements, admit-card announcements and misleading admission cutoffs using publicly available evidence.

## Problem Statement

Exam-related misinformation can spread rapidly through messaging platforms and social media. Outdated notices, fabricated announcements and misleading cutoff information can create confusion and cause students to miss important deadlines.

Students need a simple way to check these claims against relevant, authoritative sources.

## Proposed Solution

ClaimCheck accepts a claim, website URL or notice screenshot and aims to:

- Extract key information such as exam name, year, dates and category.
- Research relevant official examination and admission portals.
- Collect source links, relevant excerpts and available publication dates.
- Compare claims with applicable official announcements and amendments.
- Present an explainable result with evidence and limitations.

## Planned Verification Outcomes

- **Verified:** Sufficient applicable evidence supports the claim.
- **Likely False:** Reliable, applicable evidence contradicts the claim.
- **Unverified:** Available evidence is insufficient, ambiguous or conflicting.

## Core Features

1. Multi-format claim submission.
2. AI-assisted claim extraction and OCR.
3. Official-source evidence discovery using TinyFish.
4. Evidence-based claim verification.
5. Examination notice and amendment comparison.
6. Admission cutoff context checking.
7. Evidence reports with source links and excerpts.
8. Uncertainty handling and human review for unresolved cases.

## Proposed Technology Stack

- **Frontend:** Existing HTML interface; additional technologies to be confirmed from the implementation.
- **Backend:** Python and FastAPI.
- **Web research:** TinyFish integration, subject to API availability and configuration.
- **AI and document processing:** To be selected based on implementation requirements.

## Project Status

ClaimCheck is under development. Features listed as proposed or planned should not be considered implemented until they have been built and tested.

## Getting Started

Setup instructions will be added after the frontend and backend dependencies are finalized.

## Responsible Verification

ClaimCheck aims to provide traceable evidence rather than unsupported conclusions. Missing evidence is not automatically proof that a claim is false. Source applicability, notice versions and unresolved contradictions must be considered before a verdict is presented.

## Future Scope

- Notice version history and amendment detection.
- Monitoring selected official examination portals.
- Multilingual claim verification.
- Detection of duplicated rumours and shared source origins.
- Shareable verification reports.

## Contribution

Contributions should improve the reliability, usability, evidence traceability or maintainability of ClaimCheck. Test changes before submitting them and document any limitations.

---

*ClaimCheck — Verify the evidence. Understand the claim. Protect the student.*