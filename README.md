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
2. Experience: three fictional decisions about AI outputs, human collaboration and transfer into real practice. Every choice produces an explanation. A visible progress bar and an explicit **choose → submit → read feedback → continue** sequence support mobile use. Each transition scrolls and moves focus to the next relevant control or result, accounting for the sticky header.
3. Apply: GM-HHAI-01 exploratory eight-dimension screening, including "insufficient evidence"; the final scenario reflection now translates the choices into three explicit insights, verification questions, practical evidence indicators and one selectable 15-minute action. Visitors can copy or download their learning transfer locally.
4. Evidence: direct primary-source links and explicit methodological limitations.

## Integrity and permissions

- This is an **exploratory educational prototype**, not a validated scientific instrument, formal risk audit, certification or legal compliance assessment.
- The scenarios are **fictional**. They are not official materials from any employer or health provider, and do not provide medical guidance.
- No visitor inputs are transmitted to a server. There are no remote scripts, tracking cookies, analytics or API requests. The optional reflection file is generated locally.
- External primary-source links are citations, not endorsements or collaboration claims.
- This repository is an independent Goldmonkeys / HOP project, with no webinar or employer affiliation.
- The source code is public, but the actual GitHub Pages launch and browser/accessibility checks must be verified separately. Publication does not imply scientific validation.

## Implementation status

- 14 November 2026: tightened mobile navigation (non-sticky compact header), kept choices and submission distinct, revealed the next-step button only after feedback, and added a scenario-specific practical reflection question in German and English. Restart is prioritised at completion rather than at each decision. Changes committed, not yet verified through device/screen-reader regression tests.


- November 14, 2026: independent public repository created.
- Added three-step progress, post-selection guidance, extended scenario reflection, and mobile scroll/focus handling.
- Added full English route at `en/` and bidirectional language links.
- Added explicit answer submission and accessible focus/scroll handoffs for both languages, including screening results.
- Added an upfront visitor-value preview and an outcome-oriented completion flow (insight → verification question → action → evidence → personal next step), with local copy/TXT export. No performance scoring or impact claim.
- Both inline JavaScript blocks pass syntax compilation and no duplicate HTML IDs were detected. **No claim of WCAG 2.2 conformance or comprehensive browser QA is made.**

## Next QA and publication gates

- [ ] Conduct an actual fairness-by-design review with participants: understandability of choices, freedom to change answers, absence of pressure and practical value of the resulting transfer.
- [ ] Record observable changes in learner understanding and action through consent-based evaluation; do not infer impact from page completion.


- [ ] Check responsive UI on mobile and desktop.
- [ ] Test keyboard navigation, focus, screen-reader labels, 200% zoom and contrast.
- [ ] Review content and primary-source URLs.
- [x] Static source checks for JavaScript syntax and unique HTML IDs (DE/EN).
- [ ] Test all 3×3 decision choices, restarts, focus transitions (selection, submission, next step and screening result), progress indicators, screening selections, new transfer copy/download actions and local TXT download in real browsers.
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

The GM-HHAI-01 screening is a *reflection scaffold*. Its criteria and choice rationales need expert review, user research and methodological validation before any effectiveness or comparability claims can be made.
