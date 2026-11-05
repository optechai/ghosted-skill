# Ghosted by Lorikeet: Claude Skill

Ask Claude why customers leave, and what they do before they go, instead of reading the report.

This skill gives Claude the full [Ghosted](https://www.lorikeetcx.ai/content/ghosted?utm_source=github&utm_medium=referral&utm_campaign=ghosted-report-nov-2026&utm_content=skill-readme) report by [Lorikeet](https://www.lorikeetcx.ai/?utm_source=github&utm_medium=referral&utm_campaign=ghosted-report-nov-2026&utm_content=skill-readme): a survey of 1,000 US adults who left a fintech, insurance or health provider in the last 12 months, fielded October 28, 2026.

## What you can ask

- **Get the numbers.** "Do customers give any warning before they cancel?"
- **Size it for your business.** "We're an insurer losing 40,000 customers a year. How much revenue are we leaving on the table?"
- **Score your setup.** Describe how you spot and handle customers who might leave and ask "Are we acting in the retention window?" Claude scores it against the report's findings (signal watching, timing of outreach, what outreach leads with, memory, measurement) and ranks your next 3 steps.
- **Decide what to do.** "Should our save desk lead with a discount or with fixing the problem?"

Claude answers with the report's figures and its caveats: why getting in touch doesn't on its own make customers stay, why the fix vs. sell comparison is directional, and why the revenue figure is an estimate, not a forecast.

Once installed, call it directly with `/ghosted-report`, for example: `/ghosted-report Are we acting in the retention window?`

## What's inside

- All seven findings: customers take weeks to leave, they show it, almost none hear from their provider in time, what providers say matters, one fix would have kept them, attention only on the way out, and the revenue that walked out the door
- Chart data: time to leave, signals before leaving, whether the provider got in touch, stay rate by kind of contact, what would have kept them, paired statements
- Methodology, the idea in brief, verbatim customer quotes, what acting in the window means, and the five priorities for leaders

## Install

### Claude.ai (web, desktop)

1. Download [`ghosted-report.zip`](https://github.com/optechai/ghosted-skill/raw/main/ghosted-report.zip).
2. In Claude, go to **Customize > Skills**.
3. Click **+**, then **Create skill**, then **Upload a skill**, and select the ZIP.

Skills need **Code execution and file creation** turned on under **Settings > Capabilities**.

### Claude Code

```bash
git clone https://github.com/optechai/ghosted-skill.git /tmp/ghosted-skill \
  && cp -r /tmp/ghosted-skill/ghosted-report ~/.claude/skills/
```

## Methodology

1,000 US adults from a national online research panel who chose to leave or not renew a fintech (592), insurance (291) or health (116) product in the last 12 months, fielded October 28, 2026. 16 questions, no brand and no mention of AI. Results are unweighted; margin of error about ±3.1 points, wider for subgroups. Full methodology is in the [report](https://www.lorikeetcx.ai/content/ghosted?utm_source=github&utm_medium=referral&utm_campaign=ghosted-report-nov-2026&utm_content=skill-readme-methodology).

## About Lorikeet

[Lorikeet](https://www.lorikeetcx.ai/?utm_source=github&utm_medium=referral&utm_campaign=ghosted-report-nov-2026&utm_content=skill-readme-about) is an AI customer support platform for complex and regulated businesses, with AI agents that work across voice, chat and email. Lorikeet Dreamweaver increases customer lifetime value by giving every customer their own account manager.
