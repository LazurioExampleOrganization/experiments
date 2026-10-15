# Experiment spec: Agent Automation Desk

Status: ready for human approval
Owner: alexmorgan
Prepared: 2026-05-23
Mechanism: DesignJoy-for-automation

## Hypothesis

Small B2B companies, agencies and founder-led teams have repeated operational
tasks such as research, enrichment, reporting, writing SOPs and small
automations. They do not want to hire an in-house automation specialist or buy
generic AI tooling for that. They will pay for a productized service with one
active request queue if the result is concrete, fast and safely approved by a
human.

## Offer

Working name: **Agent Automation Desk**

Pilot offer:

- A 14-day paid pilot.
- Price to test: [PILOT PRICE] (fictional illustrative value).
- One active request at a time.
- Small requests delivered within 2 business days; more complex requests first
  as a scope proposal.
- Asynchronous communication through a shared board or an email thread.

What can be ordered:

- a research brief with cited sources
- lead/account enrichment from legally available sources
- an internal SOP or checklist for a repeated process
- a report from data provided by the client
- a no-code / low-code automation proposal
- a local workflow prototype that does not communicate externally without
  approval

What is not part of the pilot:

- a guaranteed number of leads, sales calls or revenue
- mass outbound
- stealth posting or fake engagement
- scraping against ToS
- work with non-public customer data without explicit consent
- production automation connected to client accounts without a separate
  approval

## Target customer

Primary ICP:

- a B2B founder or the owner of a small agency
- already has repeated manual operational tasks
- understands the value of AI but does not want to manage tools and prompts
- can pay for a pilot without a procurement process

Secondary ICP:

- an ops lead in a small company
- a consultant / freelancer with a repeated research and reporting workflow
- a team that has already tackled AI adoption but has no in-house capacity for
  day-to-day operation

## Channel

First channel: manually approved contact with fictional sample prospects and
B2B contacts.

The agent may prepare locally:

- an ICP definition
- a list of candidates without non-public data
- personalized message drafts
- a one-page offer text
- a call agenda

A human must confirm:

- whom to contact
- the final wording of the message
- sending the messages
- the price
- any payment or invoicing step

## Primary metric

The experiment succeeds if at least one of these happens within 14 days of
approving the outreach phase:

- 1 paid pilot
- 1 written "yes, send the invoice / checkout"
- 3 qualified discovery calls with a clear repeated pain and a willingness to
  pay to solve it

## Budget

- Paid ads: 0 CZK
- Paid tools: 0 CZK without a separate approval
- Founder time: max 6 hours
- Agent prep time: as needed, but without external actions
- Delivery budget of the first pilot: max 8 hours of work before
  stop/renegotiate

## Stop condition

Stop or change the offer if:

- after 20 manually approved outreach messages there are not at least 3
  replies or 1 discovery call
- discovery calls repeatedly show that the problem is "nice to have"
- the first customer wants a custom software project instead of a productized
  service
- delivery of the first pilot is estimated to exceed 8 hours with no chance of
  a higher price

## Scale condition

Continue to the next iteration if:

- 1 paid pilot is closed and delivery fits within 8 hours
- or 3 discovery calls name the same pain and at least one buyer accepts the
  price
- buyers repeatedly understand the "one active request at a time" model

Next iteration after a signal:

- raise the price to [MONTHLY PRICE] based on the market (fictional
  illustrative value)
- pick one niche instead of a generic automation desk
- turn repeated requests into a playbook
- build a simple request portal only after 2-3 paid pilots

## Delivery workflow

1. Intake: the customer describes the request, the target outcome and the
   available data.
2. Triage: Lazurio Example Organization confirms whether the request falls
   within the pilot scope.
3. Agent prep: the agent prepares research, a proposal, a workflow or an
   output.
4. Human review: a human checks quality, risks and sensitive information.
5. Delivery: the output is handed over to the client.
6. Log: the result is recorded in a run log in `runs/`.
7. Learn: the request is marked as repeatable / one-off / out-of-scope.

## Guardrails

- No mass outreach.
- No fake references, fake urgency or revenue claims.
- No signing in to client accounts without a separate approval.
- No automation that sends messages or changes external systems without human
  confirmation.
- Sensitive data stays out of Git; only anonymized evidence goes into the run
  log.

## Minimum assets before the start

- one-page offer draft
- 10-20 hand-picked prospects
- 2 outreach message variants
- discovery call script
- intake template for the first request
- run log template

## Mechanism sources

- DesignJoy official site: https://www.designjoy.co/
- The Futur, DesignJoy productized service interview: https://thefutur.com/watch/how-to-run-a-million-dollar-solo-design-agency
- Lazurio Example Organization shortlist: ../shortlists/2026-05-23-first-monetization-experiments.md

## Launch status

Not started. Waiting for human confirmation:

1. confirm the pilot price
2. confirm the ICP for the first 20 outreach messages
3. approve the outreach text
4. approve the specific prospect list
