# GCA & PMR Rapid Access

A browser-based assessment tool for rheumatology fast-track clinics, covering **giant cell arteritis (GCA)** and **polymyalgia rheumatica (PMR)**, plus a patient-facing **pre-clinic questionnaire**.

**Live site:** https://dos1984.github.io/GCA-PMR-rapid-access/
**Questionnaire:** https://dos1984.github.io/GCA-PMR-rapid-access/questionnaire.html?t=gca (or `t=pmr`)

## What it does

- **GCA tab** – referral and triage (red flags, GCAPS, 2022 ACR/EULAR score), same-day management, temporal and axillary ultrasound proforma (OGUS, 72-hour window), temporal artery biopsy, decision matrix, follow-up taper and patient passport.
- **PMR tab** – core features, pre-steroid investigations, 2012 EULAR/ACR classification, start of treatment, response review with PMR-AS, taper, relapse rules and passport.
- **Pre-clinic questionnaire** – the clinician generates a link with a random reference; the patient answers on their phone and emails a code back; pasting that code into *Referral information* fills the form. Answers are marked PATIENT.

## Privacy

- No patient identifiers are collected: no name, date of birth, NHS number, address or phone. Age and sex only.
- Everything runs in the browser. Nothing is stored on a server; data is cleared when the tab is closed or reloaded.
- The questionnaire reference is the only link to the patient and should be noted in the patient's own record.
- AI reading of letters and photos only works when the app is opened inside Claude; on this website the import works for questionnaire codes and the form is filled by hand otherwise.

## Guidelines

GCA: BSR 2020, EULAR 2023 imaging and 2025 management recommendations, ACR/VF 2021, 2022 ACR/EULAR classification criteria, NICE TA518.
PMR: BSR 2026, EULAR 2025, 2012 EULAR/ACR classification criteria, PMR activity score (Leeb 2004).

**Before clinical use:** enter and verify the Southend GCAPS weights, confirm local tapers with pharmacy and the MDT, and obtain information-governance approval. This tool supports clinical judgement and does not replace it.
