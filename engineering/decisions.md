# Decisions — engineering

Record key decisions made at engineering level.

- **2026-06-07:** Multiple staging and production deployments were executed, including fixes for signal lifecycle backend, anti-resurfacing guard for usage signals, and net-new % suppression.
- **2026-06-07:** A currency bug for Velatir was resolved on production, with further fixes planned to address the root cause.
- **2026-06-07:** Ongoing work on improving signal accuracy, including addressing a signal-agnostic evidence highlighting bug and preemptive AI summary generation.
- **2026-06-07:** Executive Involvement false positives are being addressed, with a re-extraction step identified.
- **2026-05-26:** Resolved a HubSpot/Nango sync bug on production.
- **2026-05-26:** Investigated a bug with stage names not showing due to orphaned HubSpot data, proposing to treat it as a customer data quality issue.
- **2026-05-26:** Significant effort was put into resolving issues with Velatir's email analysis getting stuck, with multiple fixes deployed.
- **2026-05-16:** The team demonstrated a proactive security posture by quickly identifying and assessing a potential supply chain vulnerability in a third-party library, confirming that the product was not impacted.
- **2026-05-13:** Numerous production deployments were successfully executed, fixing critical bugs, including NRR calculation for churned accounts and an SSL redirect issue.
- **2026-05-13:** A new internal outreach application is being built by Ben Heinkel using Cloudflare and Resend to scale outbound email efforts.
- **2026-06-07:** Mohit fixed FE currency issue on dashboard, deployed within 10 minutes.
- **2026-06-10:** Decision to use a separate HubSpot app for the staging environment to prevent conflicts and ensure isolated testing.
