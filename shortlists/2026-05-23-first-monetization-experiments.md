# First monetization experiments shortlist

Status: recommended
Owner: alexmorgan
Prepared: 2026-05-23

## Decision

The first recommended experiment is **Agent Automation Desk**: a productized
agentic automation service inspired by the DesignJoy mechanism, but adapted to
research, enrichment, internal operations and small automations.

Reason: the shortest path to a first invoice without building SaaS, high agent
leverage, a low technical budget and a safe manual approval model.

## Scoring

Score 1-5, higher is better. Weights:

- Revenue evidence: 20%
- Time to first dollar: 25%
- Agent leverage: 20%
- Distribution access: 15%
- Risk fit: 10%
- Delivery margin: 10%

| Candidate | Evidence | Time | Agent leverage | Distribution | Risk fit | Margin | Weighted | Verdict |
|---|---:|---:|---:|---:|---:|---:|---:|---|
| Agent Automation Desk | 4 | 5 | 5 | 4 | 4 | 4 | 4.50 | Test first |
| White-label AI support agent | 5 | 4 | 4 | 3 | 4 | 4 | 4.15 | Test second |
| AI visibility audit | 5 | 4 | 4 | 3 | 3 | 4 | 3.95 | Test after guardrails |
| Simple local website service | 5 | 4 | 3 | 3 | 4 | 3 | 3.75 | Park |
| Vertical template / operating system | 5 | 3 | 4 | 3 | 5 | 4 | 3.75 | Park |
| AI SDR ops | 5 | 4 | 5 | 2 | 2 | 4 | 3.65 | Later, high outreach risk |
| Niche data/API utility | 5 | 2 | 4 | 2 | 3 | 4 | 3.35 | Later, longer build |
| AI video/content factory | 5 | 3 | 4 | 2 | 2 | 3 | 3.20 | Later, reputation risk |
| AI asset generator | 5 | 2 | 4 | 2 | 3 | 3 | 3.15 | Later, build + quality |
| Curated paid feed/newsletter | 4 | 2 | 4 | 2 | 5 | 3 | 3.05 | Later, slow audience build |

## Experiment cards

### 1. Agent Automation Desk

- Mechanism: fixed monthly fee, async queue, one active request, fast delivery
  of small operational outputs.
- Inspiration: DesignJoy fixed monthly subscription, Trello/request board,
  one-at-a-time delivery and productized service positioning.
- Adaptation for the company: the agent prepares research, enrichment, an SOP,
  a report, a no-code automation blueprint or a local prototype; a human
  approves external actions.
- ICP: a B2B founder, a small agency or an ops lead who has repeated manual
  research / operational tasks but does not want to hire an in-house
  automation specialist.
- First metric: 1 paid pilot or 3 qualified discovery calls within 14 days.
- Stop condition: after 20 manually approved outreach messages there are not
  at least 3 replies or 1 discovery call.
- Why first: it can be sold before building a product, and every delivery
  output also teaches what to automate later.

### 2. White-label AI support agent

- Mechanism: setting up a specialized AI support widget for agencies and their
  clients.
- Inspiration: Chatwith / Chatbase pattern.
- Adaptation for the company: a done-with-you setup on top of a public website
  or data provided with consent; no copying of other people's bots.
- ICP: web/design/marketing agencies with support-heavy clients.
- First metric: 1 paid setup or 10 discovery calls.
- Stop condition: agencies see interest but do not want to carry the
  delivery/support risk.
- Why second: a strong B2B signal, but it requires more technical and
  integration commitment than Agent Automation Desk.

### 3. AI visibility audit

- Mechanism: a paid audit of how a brand appears in search, on Reddit, in
  communities and in AI answers, plus a transparent content plan.
- Inspiration: Launch Club / Reddit Agency / AI-search visibility pattern.
- Adaptation for the company: a reputation-safe audit without fake accounts,
  stealth posting or manipulation.
- ICP: B2B SaaS, agencies and expert services that deal with trust and
  discovery.
- First metric: 5 paid audits at a fixed price.
- Stop condition: the interest is only in a free insight, not in a paid audit.
- Why not first: high revenue signals, but reputation-sensitive boundaries; it
  first needs stricter guardrails.

## Parking list

- AI SDR ops: close to money, but the highest risk around spam, deliverability
  and GDPR.
- AI video/content factory: fast demand, but it easily slides into a
  low-quality content treadmill.
- Niche data/API utility: strong B2B value, but a longer build and compliance.
- Curated paid feed/newsletter: reputation-safe, but a slow time to revenue.
- AI asset generator: a good mechanism, but it requires output quality and
  handling of image rights.

## Sources

- DesignJoy official site: https://www.designjoy.co/
- The Futur, DesignJoy productized service interview: https://thefutur.com/watch/how-to-run-a-million-dollar-solo-design-agency
- Lazurio Example Organization longlist: [research module, `sprints/2026-05-22/online-projects-longlist.md`](https://github.com/LazurioExampleOrganization/research/blob/main/sprints/2026-05-22/online-projects-longlist.md)
- Lazurio Example Organization copyable projects scan: [research module, `sprints/2026-05-22/copyable-online-projects.md`](https://github.com/LazurioExampleOrganization/research/blob/main/sprints/2026-05-22/copyable-online-projects.md)
