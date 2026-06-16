# AGENTS — For When You Delegate

## Purpose
This file defines how sub-agents should operate when spawned to work on this case.

## Pro Se Litigant Profile
- **Name:** Donald Lynn Thompson Jr.
- **Communication style:** Terse, direct, single-line responses preferred
- **Expectation:** Workspace updated proactively without prompting; git commits happen without asking
- **Handle:** @Donnie-Bad-Day-2023 on GitHub (remote: github.com/Donnie-Bad-Day-2023/Donnie-Bad-Day-Federal-Case)

## Case Parameters (always include in sub-agent context)
- Case: 3:25-cv-00253, U.S.D.C. S.D. Tex. Galveston
- Judge: Jeffrey Vincent Brown
- Claims: § 1983 civil rights — unlawful arrest, fabricated prosecution, Brady violations, Monell
- No defense MDS or answer filed as of last known record

## Knowledge Base Location
All case knowledge is in `/opt/workspaces/Donnie-Bad-Day-Federal-Case/`:
- `SOUL.md` — workspace identity and case summary
- `MEMORY.md` — litigation memory and persistent facts
- `TIMELINE.md` — incident and case timeline
- `EVIDENCE.md` — exhibits and evidence log
- `AUTHORITIES.md` — legal authorities and research
- `COURT_RULES.md` — applicable procedural rules
- `TASKS.md` — outstanding tasks
- `case/filings/` — extracted docket filings (Dkt 1–48)
- `case/exhibits/` — extracted exhibits

## Filing Instructions
After any file modification:
```
git add -A && git commit -m "agent: <description>" && git push origin main
```
Remote is pre-configured. Do NOT ask — just commit.

## Communication Protocol
- Proactive updates only — do not ask permission to save or commit
- Documents shared via Google Drive links only — no local uploads
- Respond in plain English; no jargon without definition