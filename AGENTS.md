# Project requirements

- Keep development local until the user explicitly asks to deploy. Do not publish or push updates to Sites, create hosted schedules, or change the hosted audience.
- The app lives in `site/`. Run `npm run dev -- --hostname 127.0.0.1` there; use `npm run monitor` in another terminal for local polling.
- Suggested jobs and alerts must have employer evidence of the selected graduation cohort (2027 by default) or a graduation window containing that date. Generic junior or undated new-grad roles do not qualify. Possible matches still require cohort evidence; only secondary eligibility details may be uncertain.
- Preserve local job notes, stages, preferences, and database state. Keep notification credentials in ignored `.dev.vars`; never commit them.
