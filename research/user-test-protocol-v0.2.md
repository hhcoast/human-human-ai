# Human–Human–AI v0.2 | Exploratory User Test Protocol
**Version:** 0.1 · 14 November 2026
**Status:** Ready for recruitment and manual testing; no participants tested and no evidence of impact collected.
**Scope:** `learning-opportunities.html` and `en/learning-opportunities.html` in draft pull request #1.

## Purpose
Test whether visitors (a) understand the distinction between AI-assisted output and human learning, judgment and agency, (b) can use the decision scenario independently, and (c) can propose a concrete verification action for their own context.

This is a **formative usability and comprehension pilot**, NOT a validation study of a capability assessment and NOT evidence that participation improves real-world judgment.

## Participants and safeguards
Recruit 4–6 adult volunteers with diverse AI familiarity, language experience and accessibility needs. Recruitment should be independent of assessment or employment decisions. Do not pressure colleagues or learners to participate. Invite at least one person less familiar with AI, and offer German or English. Do not equate language proficiency with cognitive capability.

Moderator reads a neutral information statement: Participation is voluntary, questions can be skipped, and the session can be stopped at any time without giving a reason. Agree in advance whether anonymous notes are permitted; do not record audio/video/screens or identifiable workplace cases without separate explicit consent. Use fictional tasks, no private data, no names in public GitHub issues. Keep local notes securely and agree to a deletion schedule before beginning.

## Session (approx. 20–25 minutes)
### A. Before viewing (3 minutes)
Ask the participant: 'A colleague generates a convincing analysis with AI. What would demonstrate that the colleague has learned to analyse?' Record the response in their own words, without prompting or marking correct/incorrect.

### B. Explore independently (6 minutes)
Give only this instruction: 'Please open the Learning Before Delegation scenario, choose what you would do, read the feedback, and complete any part of the reflection that seems useful.' Avoid explaining the intended answer.

Moderator observes:
- Can they find the activity from the main page?
- Can they recognise the three choices, select, submit, read the feedback, reconsider and change answer?
- Can they find optional reflection and copy action?
- Are wording, focus, scroll, touch targets or feedback confusing?
- Do they feel pushed toward a preferred response?

Use event notes: **task / observed behaviour / exact quotation (if agreed) / severity / likely cause / suggested repair**. Do not enter names or personal details.

### C. Comprehension and transfer (6 minutes)
Without reopening the explanatory text, ask:
1. 'What is the difference between a good AI-generated result and the human ability to do similar work?'
2. 'What might disappear from a job when AI completes a beginner's tasks? Does that necessarily mean learning is lost?'
3. 'What would you change in your own learning or work process?'
4. 'How could you check later whether that change helped someone learn?'

Use a simple qualitative rubric for each answer:
- **0:** no relevant explanation or no specific action articulated;
- **1:** partially relevant distinction or generic action;
- **2:** clear distinction and a concrete, context-relevant justification/action.
Rubric is for internal descriptive coding only. Not a validated score, ranking of people, or pass/fail threshold.

### D. UX and agency debrief (5 minutes)
Ask: 'What was hard to understand?', 'Could you freely disagree with the feedback?', 'Was the choice of action yours?', 'Was anything unnecessary or intrusive?', 'What should be changed before this is shared publicly?'
Optionally ask for one 1–5 self-report of ease of use, clearly separate from actual performance.

### E. Optional delayed check (7–10 days)
With distinct opt-in, ask participants to apply the four LOP reflection prompts to a **new fictional** case, without looking at the scenario. This checks near transfer of reasoning, not professional competence or behavioural impact. Track follow-up attrition; do not infer causal learning gain from a small uncontrolled pilot.

## Accessibility / device matrix
Manual checks required on at least:
- Android Chrome, including Samsung/Chrome if available; narrow viewport and 200/400% zoom.
- iOS Safari if available.
- Desktop keyboard-only, visible focus order, no keyboard trap.
- Screen reader interaction (TalkBack or VoiceOver and desktop equivalent where possible).
- Reduced motion, sufficient contrast, screen reader announcements, form labels, selection status, copy feedback.
- Network offline after page load, confirming no remote submission of typed reflections.

Record environment/version, steps, actual behaviour and severity. No WCAG 2.2 AA claim until a separate, documented accessibility audit passes.

## Decision rules after the pilot
- **Critical:** lost user control, data leak, inaccessible primary interaction, misleading assessment claim → fix before release.
- **Major:** persistent navigation or comprehension failure, incorrect translation, focus loss → fix and retest.
- **Moderate:** ambiguity or cumbersome step without task failure → prioritise iteration.
- **Minor:** polish, copy, layout → backlog.

Do not average rubric values into an apparent scientific learning index. Report counts by task, representative anonymised observations, uncertainty, and limitations; distinguish observed behaviour from participant opinion and researcher interpretation.

## Blank per-session record (copy locally, never put participant responses into public repository)
Session code: ___ ; date: ___ ; language: ___ ; device/browser: ___ ; consent to anonymous notes: yes/no
Initial explanation: ___
Navigation: success / help / failed ; issue: ___
Choice and feedback: success / help / failed ; issue: ___
Reflection and copy: success / help / failed / skipped ; issue: ___
Independent comprehension (0–2 each, descriptive only): Q1 __ Q2 __ Q3 __ Q4 __
Observed critical issues: ___
Participant-suggested correction: ___
Moderator interpretation (separate from observations): ___
Optional delayed follow-up consent: yes/no

## Readout template
- Participants and sampling limitations:
- Successful and unsuccessful task attempts:
- Comprehension observations, with contrary examples:
- Agency and fairness observations:
- Accessibility blockers:
- Changes recommended, severity and rationale:
- Decisions postponed pending further evidence:
- No causal efficacy or validated assessment claim.

## Research context and sources
See [LOP conceptual basis](./learning-opportunity-preservation-v0.2.md) and the direct primary sources linked there. WCAG reference: https://www.w3.org/TR/WCAG22/
