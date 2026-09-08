# NLS Hiring Site

Public recruitment pages for Next Level Systems, served at **hiring.nextlevelsystems.co** via GitHub Pages.

| URL | Page |
| --- | --- |
| `/` | Open roles index |
| `/coach/` | Transformation Coach — role + application |
| `/closer/` | High-ticket Closer — role + application |

Source of truth for these pages is the private `jakemspear/NLS` repo (`pages/careers-coach.html`, `pages/careers-closer.html`). Edit there, then copy across.

## Known gap

Both application modals currently call `submitApp()`, which logs to the browser console and shows the success state — **no data is sent anywhere**. Wire the `TODO` in each page to a CRM/webhook endpoint before running traffic.
