# Sakariye Sagadi

**Cloud engineer, London.** I build the infrastructure that keeps services running when nobody's watching — pipelines, event-driven backends, the plumbing. Then I go home and build apps to fix small annoyances in my own life.

The through-line in everything here: start with a real problem I actually have, ship the simplest thing that solves it, then rebuild it properly once I understand where it hurts.

---

### What I'm building

| Project | The itch | What it taught me |
|---|---|---|
| ⚽ [**football-organiser**](https://github.com/sakariyesagadi/football-organiser) | WhatsApp polls every Tuesday, arguments about fair teams, nobody paying subs | Full-stack Next.js, Prisma schema design, a greedy team-balancing algorithm |
| ☁️ [**matchday-infra**](https://github.com/sakariyesagadi/matchday-infra) | "What if the football app didn't live on someone else's platform?" | Single-table DynamoDB, event-driven design, writing CDK properly instead of copying examples |
| 🎾 [**padel-matcher**](https://github.com/sakariyesagadi/padel-matcher) | Every venue has its own app; no way to find people at my level | FastAPI + PostGIS spatial queries, a weighted matchmaking model |
| 🗓️ [**life-dashboard**](https://github.com/sakariyesagadi/life-dashboard) | Living in 15 browser tabs across Outlook, Calendar, and Todoist | OAuth across three providers, a priority engine that answers "what do I do *right now*" |

Each one is deliberately harder than the last — that's the point.

---

### Toolbox

**Cloud** &nbsp;AWS · CDK · Lambda · DynamoDB · API Gateway · EventBridge · SES · CloudWatch
**Backend** &nbsp;TypeScript · Python · Node · FastAPI · PostgreSQL · PostGIS · Prisma
**Frontend** &nbsp;Next.js · React · Vite · Tailwind
**Ops** &nbsp;Docker · Terraform · CI/CD pipelines

---

### How I think about side projects

- **Ship the ugly version first.** football-organiser ran on Vercel before I cared about architecture. It worked, people used it, *then* I rebuilt the backend as serverless infra because I'd earned the right to know what mattered.
- **Pick the boring-hard thing on purpose.** Single-table DynamoDB, spatial indexing, OAuth token refresh — the stuff that's tedious to get right is exactly what's worth learning outside a job where someone else already solved it.
- **Every repo should be readable in an interview.** If I can't walk someone through the commit history and explain each decision, it's not done.

---

📍 London &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/sakariyesagadi) &nbsp;·&nbsp; [Email](mailto:sakariye.sagadi@gmail.com)
