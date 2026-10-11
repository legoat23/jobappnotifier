# JobAppNotifier

A local app for finding full-time jobs explicitly tied to the 2027 new-graduate cohort, with application tracking and optional locally configured Telegram alerts.

Every match requires employer-stated evidence that its graduation cohort or window includes your selected graduation date. Generic entry-level roles without that evidence are excluded. The graduation year is editable; “possible match” only means other eligibility details still need verification.

Application source: [`site/`](site/). Follow [`site/README.md`](site/README.md) to install dependencies, initialize the local database, and run the app on your computer. No hosting or deployment is needed. Run `npm run monitor` from `site/` in a second terminal for minute-by-minute local checks; the computer, app server, and monitor must stay running.
# jobappnotifier
