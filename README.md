# Learn To Look v6 — Expanded Questions & Clinical Cases

A standalone educational web-app prototype for UK medical students and foundation doctors.

## What changed

- Bottom navigation is now **Home → Learn → Questions → Clinical Cases → Examination**.
- **Questions** now contains **60 content-based single-best-answer questions** rather than clinical vignettes.
- **Clinical Cases** now contains **50 five-part cases** covering assessment, diagnosis, immediate management, treatment and follow-up/prognosis.
- Clinical Cases are separate from the Questions bank to reduce repetition.
- Question and case completion are saved locally in the browser.
- Course Progress still uses the existing rule: a learning item only counts after the learner reads all content to the bottom and completes its topic question. Questions and Clinical Cases are additional practice and do not inflate Course Progress.
- The reset flow remains protected by a confirmation modal and clears all saved progress.

## Content basis

The educational content was written for this prototype and should be clinically reviewed before public release or use in patient care. Current UK reference points used during this build include:

- NICE NG81: Glaucoma — diagnosis and management (last updated 26 January 2022).
- NICE NG82: Age-related macular degeneration.
- NICE NG242: Diabetic retinopathy — management and monitoring (published 13 August 2024).
- Royal College of Ophthalmologists guidance/resources, including emergency eye care, cataract, retina and current educational materials.

## Copyright / rights

No third-party clinical photographs or copied question-bank content were intentionally embedded. The UI, teaching diagrams, question bank and clinical cases were written/created for this project. Any future external images must be added only with documented permission or an appropriate licence, and patient-identifiable material requires appropriate governance and consent.

## Run

Open `index.html` in a modern browser. No build system or server is required.


## Learn To Look — Final Release Candidate

This release includes the complete current educational structure, 60 content-based questions, 50 multi-part clinical cases, persistent course progress, topic completion requirements, reset confirmation, reliable back navigation, and responsive mobile/PWA presentation.

This is an educational resource and should undergo formal clinical review before public release.


## E-learning use and evidence
Learn To Look is designed as an educational e-learning tool with structured learning content, questions, clinical cases, progress tracking and mobile/PWA presentation.

For UK Ophthalmology ST1 applications, the current NHS England scoring guidance lists **designing an e-learning tool** as a 0.5-point item within Education and Teaching (maximum 2 points for this group). The guidance also states that specific evidence demonstrating impact of e-learning projects must be presented. This app does not itself guarantee any recruitment points. Applicants should use the current recruitment guidance and retain objective evidence of their own contribution, completion/date/version, deployment and impact (for example, documented learner use and feedback) before claiming any score.
