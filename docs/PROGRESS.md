# Progress

Updated at the end of every task. This file is the project's memory between chat sessions.

## Status

| Task | Status | Branch | PR | Notes |
|---|---|---|---|---|
| G0 Repo setup | DONE (merged) | `chore/G0-repo-setup` | merged | |
| G1a Requirements + DB design | IN REVIEW | `docs/G1a-requirements-db` | - | `docs/requirements.md` (52 PDF FR-IDs + 63 new IDs), `docs/database-design.md` (36 PDF + 18 new tables), source PDFs in `docs/source/` |
| G1b Screens + content | DONE (merged) | `docs/G1b-screens-content` | merged (#1) | `docs/screens.md` (65 screens across 13 functional sections, including Developer Dashboard SCR-19 from PDF 2.2 #4), `docs/content/faq.md`, `docs/content/pricing.md`, `docs/content/how-it-works.md`, headings added to all 4 `docs/legal/*.md` files. PDF successfully inspected. |

## Decisions needed from both founders (before A2/A3/A8 start)
Answer these in `docs/requirements.md` section 17 (and `docs/decisions.md` if a rule changes):
- **Q1** compensation after work started on 2nd/3rd client cancellation (affects A8)
- **Q2** meaning of project status `under_review` (affects A3)
- **Q3** OCR / contact scan of attachments and deliverables in Phase 1 (affects A6)
- **Q4** Places "interests" format (affects A2, F2)
- **Q5** deadline as date vs days for the 70% rule (affects A3)
- **Q6** how stage due dates are calculated (affects A5, A8)
- **Q7** where the admin AI rate table lives (affects B2, F5)
- **Q8** escrow and fee when a developer cancels before starting (affects A8)
- **Q9** client-ended assignment = full abandonment penalties? (affects A8)
- **Q10** alert when moderation queue waits > 2 h (affects A13)
- **C7** merged account_status values (affects A2)

Each question has a proposed answer. If both founders accept the proposals, write "accepted as proposed" with the date.

## Next step
1. Review and merge G1a.
2. Run G1b (screens + content). Then A1, B1 and F1 can start in parallel.
3. Answer Q1-Q10 and C7 before the task that needs each one.
4. L1 non-coding items: platform Gmail account + App Password, JazzCash/Easypaisa merchant enquiry (sandbox credentials), lawyer, tax advisor.

## Open blockers
- None for G1b or A1. A2 waits for C7 + Q4; A3 for Q2 + Q5; A8 for Q1, Q6, Q8, Q9.

## Notes
- Code moves between AI chats as `Project_Hubbb.zip` (no GitHub connector): see `CONTRIBUTING.md`.
- Deployment, hosting, CD, SSL and domain are out of scope of the current pack.
