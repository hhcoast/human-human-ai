# Release gate | Human–Human–AI public experience

Status: **NOT PUBLISHED** · 14 November 2026

## Independent release architecture

Target: a **new public GitHub repository** named `human-human-ai` under `hhcoast`, with its own `index.html` at repository root and GitHub Pages configured to deploy from `main / (root)`.

The existing `human-centred-ai-2026` repository is private and contains different webinar materials. **Never change its visibility or deploy it for this launch.**

Proposed public URL **only after creation and successful deployment**, not a verified active address: `https://hhcoast.github.io/human-human-ai/`.

Canonical source for export: `feature/human-human-ai-public-experience:human-human-ai/index.html`.
Documentation: `feature/human-human-ai-public-experience:human-human-ai/README.md`.

## Public positioning

**Human–Human–AI | The Human Connection**

*AI can generate. Humans must connect.*

An interactive, research-informed exploration of how AI changes human learning, relationships, judgement, responsibility and effective action.

No webinar, employer or partner branding. Goldmonkeys / Human Orientation Project is the conceptual originator. The scenarios are fictional.

## Mandatory pre-publication checks

### Accessibility
- Keyboard-only interaction, logical focus order, skip link, operable choices and controls.
- Screen reader announces choice feedback, step changes and screening results appropriately.
- Visible focus, contrast and 200/400% zoom checks; no horizontal scroll at 320 CSS px.
- Test at least VoiceOver or TalkBack and another browser/screen reader setup.
- Test with reduced motion and mobile portrait.
- Plain-language review; create an accurate English version rather than relying on automatic translation.
- Run automated axe/WAVE/Lighthouse checks **plus manual checks**. No unverified WCAG-conformance claim.

### Research and content
- Expert-review all decision feedback; avoid one-size-fits-all claims.
- Keep GM-HHAI-01 labelled *exploratory and not validated*.
- Recheck every primary-source link.
- Distinguish observation, hypothesis, normative requirement and own concept.
- Do not claim partnership, certification or endorsement by UNESCO, WUD, ISO, W3C or NIST.

### Data protection and security
- Inspect all network requests in browser developer tools. Only intended first-party page assets and deliberate external links should load.
- No analytics, external libraries, forms that submit to a server, trackers or cookies.
- Local TXT export only, with clear user notice and no confidential-data request.
- Review security headers feasible on GitHub Pages and outbound link attributes.
- Confirm all materials and logos may be published.

### Functional
- Test all 9 choice responses, step advancement, reset, back-to-start and result generation.
- Test every selection state including *insufficient evidence*.
- Test text export in Firefox, Chrome and Safari where available.
- Check no broken links and no JavaScript errors.

### Publication
1. Create a new repository in GitHub: `hhcoast/human-human-ai`, **Public**, with no preexisting webinar files.
2. Copy reviewed `human-human-ai/index.html` to new repository root as `index.html`, plus the dedicated `README.md` and any final LICENSE / privacy / accessibility statements.
3. In the new repository select Settings → Pages → Deploy from branch → `main` / `(root)`.
4. Confirm Pages deployment succeeds.
5. Open the final URL in a **logged-out** browser and run the checks above.
6. Only then share the actual URL on LinkedIn.

## Post-publication learning loop

Invite voluntary, non-identifying feedback through an explicitly configured transparent channel. Do not pretend that interaction logs are measured if none are collected.

Record issues, evidence gaps, accessibility findings and user-research outcomes publicly where appropriate. The instrument should evolve through documented versions and cautious claims, not merely collect positive reactions.
