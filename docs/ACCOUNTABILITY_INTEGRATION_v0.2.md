# GM-ABD-001 | Human Human AI Accountability Integration v0.2
Date: 2026-11-14
Status: implemented in development branch; not merged, not published, not user-tested.
Branch: `feature/hhai-v0-2-learning-opportunities`
PR: https://github.com/hhcoast/human-human-ai/pull/1

## Purpose
Translate Human Agency First, Fairness by Design, Observable Consequences and Accountability by Design into an actionable and non-scoring, privacy-first reflection. Not a compliance certification, clinical or psychometric test, or independently verified assessment.

## Implemented
- Separate DE/EN accessible-by-link pages at `accountability.html` and `en/accountability.html`, linked from corresponding Experience navigation.
- Six dimensions: Agency, Evidence, Fairness, Responsibility, Consequence, Correction.
- Three self-report categories: not checked, partly, applies in my view; optional notes.
- Decision ownership question and one self-chosen next action.
- Client-side preview; locally generated print layout for personal PDF using browser print (no PDF server).
- Independent general A4 reminder print page with six questions.
- Email draft to `goldmonkeys@outlook.com`, opened explicitly by the visitor. Email is never sent automatically. Long `mailto` URL gets an explanatory warning.
- Reset with confirmation; no app-side submission, analytics, cookies or remote scripts.

## Important limits
- Email preview is on page but native mail clients may truncate long prefilled content. User must review recipients/content in their mail client.
- No server-side sending, inbox monitoring or feedback receipt/processing claims.
- No personal outcomes are saved; closing/reloading clears entries.
- Print dialog and PDFs require real-browser testing. Mobile layout, zoom, screen reader, keyboard and Mailto integration must be tested.
- Legislative background (Wales) provides a comparative accountability case, not a legal mandate for this product.
- Research effect remains unverified.

## QA gates
- [ ] Visit all routes from main and EN main.
- [ ] Test every select state, optional notes, text encoding and reset.
- [ ] Test print to single or intentional multi-page A4 PDF in Chrome/Samsung and desktop browsers.
- [ ] Test generic reminder print independently from personal results.
- [ ] Test mailto handoff, recipient verification, oversize body and cancel without sending.
- [ ] Test 320px width, 200/400% zoom, keyboard-only, focus order, TalkBack/VoiceOver, contrast.
- [ ] German/English editorial and domain review, consent/privacy copy.
- [ ] Pilot 4–6 participants; document any misunderstanding or pressure.
- [ ] Update functionality and evidence status after observed testing.

## Feedback accountability register (internal, not in browser)
Ticket ID | Date | Category | Report (minimized) | Responsible person | Status | Decision + reason | Fix evidence | Recheck date
No automatic promises to respondents about handling/response times. Any eventual feedback process needs capacity, purpose and retention controls.
