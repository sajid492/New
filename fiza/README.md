# Fiza

Personal operations dashboard, published as a claude.ai artifact: https://claude.ai/artifact/MeafKMX58gFcPey1xP11ru

- **Artifacts tab:** CSAT, Voice of customer, CS/OPS Quality, RiskOps Quality and O2C cards. Each card links to its full dashboard. Card numbers live in the artifact's `kpis` collection, so Claude can refresh them without republishing the page.
- **Work inbox tab:** one card per connector (Slack, Linear, Gmail, Revolut People, BambooHR). Shows what is waiting on you and what is waiting on others since the date you choose (default 26 Oct 2026). From each item you can reply, react (Slack), star (Gmail), send reminders one at a time or in bulk, mark it done, or turn it into a personal task.
- **My tasks tab:** private task list. You can schedule Slack reminders for every open task or send yourself a digest DM.
- **Admin tab:** turn cards and connectors on or off, edit the reminder wording, set the auto-refresh interval, manage connector access, and pick from nine planet themes, each with light and dark versions.

Connector calls run as the person viewing the page, through claude.ai connectors. BambooHR shows a setup card until a BambooHR connector is available.
