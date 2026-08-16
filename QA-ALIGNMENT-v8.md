# Courseware QA and Alignment — v8.0

Course: TGS-2023020567 — Unlocking Business Potential with Strategic Negotiation Tactics  
QA date: 16 August 2026

## Release decision

**PASS — ready for controlled Drive, LMS-TMS and GitHub publication.**

Exact-artifact publication manifest (regenerated and rechecked 16 August 2026):

- Activity tree: 102 files; SHA-256 manifest `6d14a832894ba7ce68faac0279f940cc36325cfb9957b489b4b43ae892fc4006`.
- Trainer PPTX: SHA-256 `ab533f01ab4149b771f0c8fba2d35f850465ff4fb62ba5de87cac3391c72e6b7`.
- Learner slide PDF: SHA-256 `74c7cecea9c9898214c20d3962b401d1db17e6c48e39f4e9fc9ea8854b4887a2`.
- Learner Guide PDF: SHA-256 `da25e22defeb190ca42270ebb99d6652c9d2876a63cc91333b1d6f28397c69c3`.
- Lesson Plan PDF: SHA-256 `a035c47b7982af66bd583e77da3db8ffa5763a2b4d50a573f32b2fe573c86d2e`.

## Build inventory

- Trainer deck: 141 slides in editable PPTX and learner PDF formats.
- Learner Guide: DOCX and 30-page PDF with full activity procedures.
- Lesson Plan: DOCX and 8-page PDF; both training days total 480 minutes excluding lunch.
- Activities: 10 individual folders, 41 Markdown files, 41 same-basename printable PDFs, 10 additional scenario PDFs and 10 mock-data CSV files.
- Assessment: 6-question WA-SAQ plus answer key; 2-question Case Study plus answer key.

## Alignment checks

- Course code, title, TSC `ICT-BIN-3105-1`, K1–K6, A1–A5 and both learning outcomes are consistent across the deck, LG, LP and assessments.
- The final slide map places Topic 1 at slides 20–73, Topic 2 at slides 74–131 and wrap-up at slides 132–141; the Lesson Plan was regenerated from this map.
- The supplied 109-slide v7 deck was treated as the coverage floor. BATNA, WATNA, ZOPA, roles, venue, information exchange, first offers, mutual gain, difficult behaviour, pressure and delay tactics, impasse, consensus, closure and negotiation records remain covered.
- All ten approved enrichment-source links appear in the source register and the Learner Guide.
- No wellness-course, BCM, ISO 22301, Jamboard or unrelated AI-ethics material remains in the release.

## Procedure and activity checks

- No numbered step-by-step activity procedure appears in the PPT.
- Detailed procedures, scenarios, questions, checkpoints, deliverables and acceptance criteria appear in the Learner Guide and each activity `README.md`.
- Every activity has its own `activities/activity-*` folder; no `labs/` directory exists.
- Every activity Markdown file has a same-basename PDF counterpart; the recursive parity check passed 41/41.
- Every case distinguishes realistic workplace context from fictional training assumptions.
- Each activity block includes an editable native decision artifact, such as an outcome control panel, authority map, value model, impasse map or coalition map.

## Visual QA

- Full-deck contact sheets and selected 170-dpi individual renders were inspected.
- A fix-and-verify cycle corrected recap-card clipping and high-resolution source, consensus and decision-artifact renders.
- A second cycle added ten editable decision artifacts to increase activity-block visual variety.
- Final native PowerPoint PDF export and individual 170-dpi renders passed with no blocking overflow, overlap, off-canvas objects or bad image crop observed.

## Assessment QA

- WA paper: six open-ended questions, one each for K1–K6, 1 hour, open book.
- Case Study: two integrated questions covering A1–A5, 1 hour, open book.
- Candidate papers use cover page 1, trainee information/instructions/grading on page 2, and assessment content from page 3.
- Answer keys are separate trainer-confidential documents with suggestive answers and course traceability.
- Rendered-PDF structural verifier result: all four documents passed.

## Publication controls

- Public GitHub scope excludes `.env`, references, build tooling, QA renders, assessment papers and answer keys.
- LMS links must include candidate question papers only; answer keys remain trainer-only.
- Drive publication requires folder-identity verification, dry-run, write, inventory readback and permission audit before LMS-TMS update.
