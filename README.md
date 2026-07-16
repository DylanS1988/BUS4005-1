# BUS4005-1
# BUS4005 Assessment 1: AI Prompt Library for Pharmaceutical Manufacturing

## Project title

AI Prompt Library for Quality Event, BPR Improvement and Product Complaint Support in Pharmaceutical Manufacturing

## Project overview

This repository contains a 10-prompt AI library designed for pharmaceutical manufacturing workflows. The prompt library supports three GMP-adjacent business workflows:

1. Quality event support
2. Batch Process Record (BPR) improvement
3. Product complaint support

The library is designed to convert fragmented operational, quality and complaint information into structured draft outputs for human review.

## Business field

The selected business field is pharmaceutical manufacturing, with a focus on GMP documentation, investigation support, quality event handling, BPR usability and product complaint management.

## Important limitation

This prompt library produces draft support material only. It does not approve BPR changes, determine final quality impact, close investigations, approve CAPAs, decide complaint reportability, admit product fault or replace QA, SME, validation, document-control or regulatory review.

## Prompt library structure

| Flow | Prompt IDs | Purpose |
|---|---|---|
| Flow 1: Quality event support | P01–P04 | Initiation, escalation, investigation, corrective action and final quality impact support |
| Flow 2: BPR improvement | P05–P07 | Critical step identification, checklist formatting and review-point identification |
| Flow 3: Product complaint support | P08–P10 | Complaint intake, investigation planning, recommendations and response drafting |

## Repository structure

- `01_business_context/` — business problem, workflow map, scope and stakeholders
- `02_prompt_library/` — final 10-prompt library
- `03_iteration_evidence/` — prompt testing and refinement evidence
- `04_sample_inputs_outputs/` — fictional examples used to test prompts
- `05_research/` — evidence matrix and references
- `06_report_and_video/` — report and video planning materials
- `07_submission/` — final submission checklist and link notes

## Data privacy note

All examples in this repository are fictional, de-identified or generalised. No confidential company information, real batch records, customer details, product names, batch numbers or internal SOP content should be uploaded.
