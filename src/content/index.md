---
title: Job outreach
date: 2026-10-23
---

Every job Taimour has an outreach draft for, the company behind it and the people found there.
Pages are written by the `job-outreach` job (`atuin scripts run job-outreach`) after each batch; newest first.

## Sections

- [[jobs/index|Jobs]] — one page per drafted role: why it fits, the role, who was written to
- [[companies/index|Companies]] — what each company builds, its job boards, the people found on its own pages

> [!note] How this stays alive
> `action=process atuin scripts run job-outreach` drafts the week's emails, then `action=garden`
> rewrites these pages and deploys. Hand edits to managed pages are overwritten; put notes in `private/`.
