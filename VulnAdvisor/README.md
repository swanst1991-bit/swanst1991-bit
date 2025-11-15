# VulnAdvisor Project
Decision-making assistant for vuln customers at Snap Finance. FCA/Consumer Duty-aligned, supports MI and Freshdesk/Webio bots.

## Files
- `fca_updates.md`: FCA vuln/Consumer Duty changes.
- `consumer_duty_kpis.json`: MI KPIs for reporting.
- `freshdesk_api_changelog.json`: Freshdesk bot rules.
- `webio_flows.md`: Webio bot scripts.
- `update_project.py`: Auto-update script.

## Setup
1. Clone repo or copy to drive.
2. Run `python update_project.py` weekly (cron: `0 0 * * 1`).
3. Feed files to Grok: "Use fca_updates.md for triage."

## Updates
- Check fca.org.uk/news monthly.
- Monitor aryza.com for Webio API shifts.
