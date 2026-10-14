# CLAUDE.md — PROJECT: LIFE!

This repo belongs to Matthew Weinhoffer's personal life and is **completely separate from his work at BAYADA Home Health Care.**

## ⚠️ HARD BOUNDARY — READ THIS FIRST

**This repo and the MAP repo (`mathwine/MAP`) must NEVER cross-contaminate. This is an absolute non-negotiable.**

| This repo (PROJECT-LIFE) | MAP repo |
|---|---|
| Personal life ops | BAYADA work only |
| Job search (confidential) | Marketing operations |
| Resume, cover letters | Teamwork, campaigns |
| PROJECT: LIFE! tasks | Figma, Notion, Zoom, Airtable |

### Never do any of the following:
- Reference, clone, read, or write to `mathwine/MAP` from any session working on PROJECT-LIFE content
- Reference, clone, read, or write to `mathwine/PROJECT-LIFE` from any session doing BAYADA/MAP work
- Use BAYADA-connected tools (Teamwork, Notion, Figma, Airtable, Zoom) for anything in this repo
- Mention the job search to anyone at BAYADA or in any BAYADA-connected tool
- Mix Matthew's personal contact info (mathwine@gmail.com, 267-377-7487) with his BAYADA identity (mweinhoffer@bayada.com)

**If you are in a BAYADA/MAP context and accidentally encounter anything from this repo — stop, do not proceed, and flag it to Matthew.**

---

## Job Search — STRICTLY CONFIDENTIAL

Matthew is conducting a confidential job search. It must never be revealed to BAYADA or anyone connected to his current employer.

### Master files (in `job-search/`)
- `Matthew-Weinhoffer_Resume_2026_MASTER.docx` — his formatted resume; use as-is, never recreate
- `Matthew-Weinhoffer_Cover-Letter_2026_MASTER.docx` — has `[Date]`, `[Company Name]`, `[Position Title]` placeholders; fill only those, preserve all formatting

### File naming convention for applications
`Matthew-Weinhoffer_{CompanySlug}_Resume_2026.docx`
`Matthew-Weinhoffer_{CompanySlug}_Cover-Letter_2026.docx`

### Security rules (absolute — never violate)
- NEVER enter SSN, passport number, government ID, or bank account number
- NEVER bypass CAPTCHAs — log as blocked and move on
- NEVER enter current salary — skip the field or enter 0
- Workday accounts MAY be created autonomously
- NEVER create accounts on non-Workday platforms

### How the scheduled task accesses files
The daily job search scheduled task clones this repo at the start of every session:
```bash
git clone --depth 1 https://github.com/mathwine/PROJECT-LIFE.git /tmp/project-life
```
Master files are then at:
- `/tmp/project-life/job-search/Matthew-Weinhoffer_Resume_2026_MASTER.docx`
- `/tmp/project-life/job-search/Matthew-Weinhoffer_Cover-Letter_2026_MASTER.docx`

---

## Matthew's contact info (personal — never use BAYADA channels)
- Email: mathwine@gmail.com
- Phone: 267-377-7487
- Location: Philadelphia, PA 19125
- LinkedIn: https://www.linkedin.com/in/matthew-weinhoffer
