# Sakariye Sagadi

**Cloud DevOps Engineer — London, UK**

I spend most of my time in operations: on-call across several services and regions, incident response, and unblocking deployment pipelines. What I actually enjoy is the part after the incident — spotting the pattern underneath it and building the automation so nobody has to handle it by hand again. If I'm doing something manually more than twice, I'd rather spend an afternoon making it disappear.

That instinct runs through everything here — the operational tooling I build at work, and the smaller apps I build at home for things in my own life.

## What I care about

- Cutting operational toil, so on-call time goes to the problems that actually need a human
- Making a team's health visible at a glance instead of buried in spreadsheets
- Using LLMs where they genuinely save time — summarising, triaging, handovers
- Root-cause analysis and finding the systemic pattern behind recurring issues

## Work

**Operational Health Dashboard**
End-to-end serverless data pipeline giving 5 engineering teams (~60 engineers) automated daily health visibility, replacing manual spreadsheet reporting entirely. I took the project over mid-flight, drove the architecture decisions, and shipped to production against a hard deadline.

- Python Lambda ETL → S3 → QuickSight, with EventBridge cron, Step Functions orchestration, SNS alerting, and CDK infrastructure.
- Six data domains: ticket SLA/backlog/MTTR, change management, deployment pipelines, on-call burden, KTLO pressure, and first-contact resolution.
- RED/YELLOW/GREEN health scoring with automated alerts on degradation.
- Weekly natural-language trend summaries generated with Bedrock.

**Compliance Drift Detection**
Audits access-control groups for divergence from approved baselines and auto-generates remediation tickets with manager routing and false-positive filtering. Cut a 2.5-hour manual audit to under 10 minutes at full coverage.
*Python, boto3, IAM / access-control APIs, SigV4A.*

**On-Call Handover Bot**
Slack bot that builds a structured shift-handover briefing from seven data sources — tickets, deployments, alarms, and more — with severity-tiered summaries posted straight to Slack. Built in a two-day hackathon and adopted organically by several teams. Handover prep dropped from 30–45 minutes to under a minute.
*Lambda, API Gateway, DynamoDB, S3, Bedrock, Slack API.*

**Alarm Investigation & Threshold Tuning**
Investigated a recurring false-positive alarm pattern (24 self-resolving tickets in 5 weeks), traced the root causes through Lambda error logs — race conditions and misconfigured thresholds — and recommended fixes that would eliminate all of the observed noise.

**Cross-Functional Programme Leadership**
Led an org-wide rebranding programme spanning security, engineering, training, and customer-facing teams — coordinating 8+ contributors, handling external stakeholder communications, and driving scope and execution decisions.

## Side projects

The repos on this profile — smaller apps I built for things in my own life.

- **[football-organiser](https://github.com/sakariyesagadi/football-organiser)** — organises weekly 5-a-side: availability, balanced teams, subs tracking. Next.js, Prisma, Postgres.
- **[matchday-infra](https://github.com/sakariyesagadi/matchday-infra)** — the football backend rebuilt as serverless AWS infrastructure. CDK, single-table DynamoDB, EventBridge, SES, Cognito.
- **[padel-matcher](https://github.com/sakariyesagadi/padel-matcher)** — finds padel courts and players at your level. FastAPI, PostGIS spatial queries, React.
- **[life-dashboard](https://github.com/sakariyesagadi/life-dashboard)** — email, calendar, and tasks in one screen with a priority engine. OAuth across Microsoft Graph, Google, and Todoist.

## Skills

**Languages:** Python, TypeScript, JavaScript, Bash
**AWS:** Lambda, S3, EventBridge, SNS, CDK, Step Functions, Athena, QuickSight, Bedrock, DynamoDB, API Gateway, CloudWatch, IAM, STS
**Infrastructure:** CDK (TypeScript), CloudFormation, serverless architecture
**Data:** ETL pipelines, QuickSight dashboards, Athena/SQL, S3 data lakes
**Operations:** on-call (8 services, 10 regions), incident response, alarm investigation, pipeline troubleshooting
**Other:** Bedrock/Claude integration, SigV4 / SigV4A authentication, Slack bots, cross-network debugging, API integration

## Contact

London, UK · [LinkedIn](https://linkedin.com/in/sakariyesagadi) · [Email](mailto:sakariyework@gmail.com)
