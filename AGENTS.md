# AGENTS.md — the job outreach garden

A Quartz site (taxkcd/jobsgarden -> https://taxkcd.github.io/jobsgarden) generated from the job-outreach
ledger in Taimour's Atuin inventory. Do not edit `jobs/` or `companies/` pages by hand: the
generator (`sources/jobs/job-outreach/joboutreach/jobgarden.py`, `action=garden atuin scripts run
job-outreach`) rewrites every page whose `generator` front matter says managed. `private/` is
never published. Deploy = push to main; the workflow builds Quartz and publishes GitHub Pages.
