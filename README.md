# Human–Human–AI | The Human Connection

**Goldmonkeys / Human Orientation Project** · Conceptual, interactive prototype v0.1 · 14 November 2026

## Public-facing concept

AI can generate. Humans must understand, connect, judge and act.

Human–Human–AI examines three relationships: people learning and deciding with other people; people interacting critically with AI; and human relationships changed through AI mediation. The proposed outcome is **consequential human capability**, not AI adoption or output volume alone.

## Cross-cutting quality principles

**Human Agency First. Fairness by Design. Observable Consequences.**

These principles apply to the content, UX, scenarios, learner transfer, product iterations and research of Human–Human–AI:

- **Agency:** Users can understand options, make informed choices, challenge outputs and retain human control.
- **Fairness:** No manipulative choice architecture, coercive progression or addictive engagement mechanics; accessible and inclusive explanations.
- **Consequences:** Evaluate comprehension, human relationships and real actions, not just clicks, completion or time saved. Evidence gaps must remain visible.

The [European Commission's Digital Fairness Act initiative](https://commission.europa.eu/law/law-topic/consumer-protection-law/digital-fairness-act_en) is a legislative proposal as of 11 November 2026 and is cited as a relevant policy reference, **not** as enacted law or automatically applicable legal obligations for this educational prototype. These principles do not constitute a certification or validated scientific instrument.

## Try the prototype

The website entry point is [`index.html`](./index.html) (German). The English experience is [`en/index.html`](./en/index.html). Once GitHub Pages is enabled and its deployment checked, the public experience will be accessible at `https://hhcoast.github.io/human-human-ai/`. No login, API key or build tool is required.

The experience contains:

1. Explain: the three relationships, human agency and responsibility, with direct German/English navigation.
2. Experience: three fictional decisions about AI outputs, human collaboration and transfer into real practice. Every choice produces an explanation. A visible progress bar and an explicit **choose → submit → read feedback → continue** sequence support mobile use. Each transition is designed to scroll and move focus to the next relevant control or result. After submission the options collapse and the feedback replaces them in the same stable decision panel; a separate change-answer control reopens the options. Two animation frames allow browser layout to settle before repositioning. A global CSS `[hidden]` rule prevents state-specific controls from remaining visible.
3. Apply: explore eight perspectives on the human consequences of AI, including what remains unknown. Results now map each selected status to a context-specific question, a feasible verification action and suggested observable evidence. Critical entries are listed before missing evidence, then partial and self-reported satisfied entries. A single next action is suggested without averaging scores. Visitors can copy or save the action plan locally. The final scenario reflection separately translates decisions into three insights and a selectable 15-minute action.
4. Evidence: direct primary-source links and explicit methodological limitations.

## Integrity and permissions

- This is an **exploratory educational prototype**, not a validated scientific instrument, formal risk audit, certification or legal compliance assessment.
- The scenarios are **fictional**. They are not official materials from any employer or health provider, and do not provide medical guidance.
- No visitor inputs are transmitted to a server. There are no remote scripts, tracking cookies, analytics or API requests. The optional reflection file is generated locally.
- External primary-source links are citations, not endorsements or collaboration claims.
- This repository is an independent Goldmonkeys / HOP project, with no webinar or employer affiliation.
- The source code is public, but the actual GitHub Pages launch and browser/accessibility checks must be verified separately. Publication does not imply scientific validation.

## Mobile and export refinement (14 November 2026)

- Updated both German and English snapshot layouts with tighter A4 print styles, including smaller margins and compact tile/legend spacing.
- At narrow viewports (up to 390 CSS px), status tiles and the legend use a single column for reading comfort.
- Clearer self-report terminology: a selected positive status must **not** imply that any evidence was submitted or independently verified.
- Retained the three-scenario modal flow and the local-only reflection.
- **QA distinction:** JavaScript compilation, duplicate HTML IDs and code-level feature checks completed. A one-page A4 PDF, 400% zoom/reflow, keyboard-only navigation, TalkBack and VoiceOver cannot yet be certified from these checks. Mobile A4 preview and screen-reader testing remain launch gates.

## Visual Snapshot v0.5 (November 14, 2026)

- **DE and EN:** eight accessible status tiles, symbol-and-text legend, critical/missing/partial first, and a practical next-step recommendation. Statuses reflect **self-reports**, never an independently verified score.
- The first visible reflection result is a visual snapshot; the detailed action plan is available in a collapsible disclosure.
- A reusable four-question Human–Human–AI reminder is available as a locally generated SVG without project or personal details.
- A print-friendly snapshot can be saved as PDF through the browser's print dialog; the detailed TXT export and copy action remain optional.
- **QA limit:** static JS compilation and duplicate-ID checks passed in both languages. Real-device tests of mobile rendering, SVG download, browser printing and assistive technology are still required.

## Implementation status

- 14 November 2026: tightened mobile navigation (non-sticky compact header), kept choices and submission distinct, revealed the next-step button only after feedback, and added a scenario-specific practical reflection question in German and English. Restart is prioritised at completion rather than at each decision. Changes committed, not yet verified through device/screen-reader regression tests.


- November 14, 2026: independent public repository created.
- Added three-step progress, post-selection guidance, extended scenario reflection, and mobile scroll/focus handling.
- Added full English route at `en/` and bidirectional language links.
- Added explicit answer submission and accessible focus/scroll handoffs for both languages, including reflection results.
- November 14: rebuilt the mobile answer→submit→feedback flow in DE/EN to use a stable panel, explicit choice editing, deferred focus/scroll positioning, and real hidden-control semantics.
- Added an upfront visitor-value preview and an outcome-oriented completion flow (insight → verification question → action → evidence → personal next step), with local copy/TXT export. No performance scoring or impact claim.
- Both inline JavaScript blocks pass syntax compilation and no duplicate HTML IDs were detected. **No claim of WCAG 2.2 conformance or comprehensive browser QA is made.**

- November 14: expanded the eight-perspective reflection (DE/EN) from generic advice to an evidence-aware, non-scoring review plan with prioritized next steps and local export. The accepted decision modal was left unchanged.

## Next QA and publication gates

- [ ] Conduct an actual fairness-by-design review with participants: understandability of choices, freedom to change answers, absence of pressure and practical value of the resulting transfer.
- [ ] Record observable changes in learner understanding and action through consent-based evaluation; do not infer impact from page completion.


- [ ] Check responsive UI on mobile and desktop.
- [ ] Test keyboard navigation, focus, screen-reader labels, 200% zoom and contrast.
- [ ] Review content and primary-source URLs.
- [x] Static source checks for JavaScript syntax and unique HTML IDs (DE/EN).
- [ ] Manually test on Samsung/Chrome (including browser toolbar scrolling), Safari/iOS and at least one desktop browser. The GitHub connector cannot itself verify mobile browser rendering.
- [ ] Test 8-tile matrix, text/symbol status distinctions, SVG sharing, snapshot printing/PDF, and expand/collapse on real mobile browsers.
- [ ] Manually test reflection with eight empty selections, all critical, mixed statuses, all supported, reset, copy, export, and screen-reader announcement.
- [ ] Test all 3×3 decision choices, restarts, focus transitions (selection, submission, next step and reflection result), progress indicators, reflection choices, new transfer copy/download actions and local TXT download in real browsers.
- [x] Add complete English UI and scenario translations (implementation, not independently language-reviewed).
- [ ] Review both language versions with real learners and native-level reviewers.
- [x] Create the independent public repository `hhcoast/human-human-ai` and place its entry point in the root.
- [ ] Activate and verify GitHub Pages from `main` / `(root)`.
- [ ] After release, check the actual published URL in an unauthenticated browser before sharing on LinkedIn.

## Sources

- [World Usability Day Austria 2026](https://worldusabilityday.at/)
- [UNESCO: Guidance for Generative AI in Education and Research](https://www.unesco.org/en/articles/guidance-generative-ai-education-and-research)
- [UNESCO: AI Competency Framework for Teachers](https://www.unesco.org/en/articles/ai-competency-framework-teachers)
- [ISO 9241-210](https://www.iso.org/standard/77520.html)
- [NIST AI Risk Management Framework](https://airc.nist.gov/airmf-resources/airmf/5-sec-core/)
- [W3C WCAG 2.2](https://www.w3.org/TR/WCAG22/)

## Research framing

**Question:** Under what conditions does human-centred AI support preserve or strengthen human judgement, interpersonal learning and consequential human capability?

The public activity is an exploratory prompt for reflecting on practice, not a formal test. The underlying methodological structure is maintained for research and iteration. Its criteria and choice rationales need expert review, user research and methodological validation before any effectiveness or comparability claims can be made.


## Plain-language and empty-answer correction (14 November 2026)

Mobile user feedback identified two issues in the eight-perspective snapshot: specialist terms such as “evidence” were hard to understand, and an entirely blank questionnaire generated misleading unknown-status tiles and a recommendation.

Changes applied to DE/EN:
- Eight display headings are now plain-language descriptions, keeping the original research dimensions conceptually intact.
- The user-facing unknown option is “Ich weiß es noch nicht” / “I am not sure yet”.
- A blank answer is now a distinct “Nicht beantwortet” / “Not answered” state, not a judgement about missing evidence.
- An entirely empty form does not generate a snapshot; it asks for at least one response.
- In a partly filled form, unanswered dimensions remain visible but are excluded from the priority list and next-action selection.
- The summary shows how many of eight questions were answered.
- Static checks: embedded JavaScript syntax and duplicate HTML IDs passed in both languages. Real-device testing and published Pages verification remain pending.

Decision: a participant's silence is not evidence of an unmet criterion. More systematic plain-language review remains open.
