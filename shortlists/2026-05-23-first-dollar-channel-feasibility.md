# First dollar channel feasibility

Status: draft verdict
Owner: alexmorgan
Verified: 2026-05-23

## Goal

Check which fast online monetization paths have a chance of earning the first
dollar for Lazurio Example Organization overnight or within 24-48 hours,
without copying anyone else's identity, sending spam, bypassing ToS or
promising unverified results.

## Criteria

- Can it start without building a product?
- Can a payment be accepted today?
- Is there a current demand signal?
- Does it need marketplace reputation, or is warm distribution enough?
- What are the legal, ToS and reputation guardrails?

## Verdict

| Path | Works today | Demand signal | Payment friction | Distribution | Verdict |
|---|---|---|---|---|---|
| Direct Agent Automation Desk + Stripe/Ko-fi checkout | High | High | Low, if Alex has an active Stripe/Ko-fi/PayPal | Warm outreach | Test first |
| Ko-fi/Gumroad low-ticket digital product | Medium | Medium | Low | Weak without an audience | Use only as a checkout/support asset |
| PromptBase prompt/skill listing | Medium | Medium | Medium, waits for platform approval | Marketplace + own link | Defer, not overnight |
| Fiverr automation gig | Medium | High | Low after setup | Marketplace discovery, but a new seller is slow | Set up later as an inbound channel |
| Upwork proposals | Low for tonight | High | Connects + account/proposal friction | Marketplace bidding | Do not start now; suitable later with a profile and a case study |
| Polymarket / prediction markets | Low as a revenue engine | High market volume, but without our edge | Trading capital + regulatory/KYC friction | Market microstructure, not customer distribution | Do not run with real money; use only for paper-trade/data research |

## 1. Direct Agent Automation Desk + checkout

### Mechanism

Offer a concrete 48h AI ops triage or a 14-day pilot to fictional sample
prospects: the customer sends one manual process and the company returns a
fit/no-fit verdict, an automation blueprint and a proposal for the first useful
output.

### Evidence

- Stripe Payment Links let you create a no-code payment page and share a link
  without your own website.
- According to the official global availability list, Stripe is available in
  the Czech Republic.
- Fiverr publicly shows a large automations/workflows category and specific
  AI/Make/Zapier/n8n offers.
- The Fiverr Business Trends Index 2026 reports growing demand for AI agents,
  workflow tools and Make.com specialists.

### Guardrails

- No mass outbound.
- No guaranteed leads, revenue or sales calls.
- No work with client accounts or sensitive data without a separate approval.
- Every external message and checkout link waits for human confirmation.

### Verdict

The best path to the first dollar. It needs neither a marketplace ranking nor a
product. The real obstacle is not technology but an approved checkout, a
prospect list and the sending itself.

## 2. Ko-fi or Gumroad low-ticket digital product

### Mechanism

Sell a small digital product: a checklist, a prompt pack, an AI ops triage
worksheet or a "first automation brief" template.

### Evidence

- Ko-fi Shop lets you sell digital products without a listing fee; the free
  plan takes a 5% service fee and payments go through PayPal or Stripe.
- Gumroad offers a fast digital checkout, but according to its help center it
  charges direct sales 10% + 0.50 USD plus payment processing; marketplace
  sales carry a 30% fee.
- The Gumroad payout documentation lists the Czech Republic as a supported
  payout country.

### Guardrails

- Do not present an AI-generated template as your own manually verified
  result unless it has really been tested.
- Do not sell PLR, prohibited content, services disguised as a digital product
  or anything that conflicts with payment processor rules.

### Verdict

Technically workable, but weak overnight without an audience. Useful as a
checkout for a deposit or as an add-on to direct outreach, not as a standalone
overnight engine.

## 3. PromptBase prompt/skill listing

### Mechanism

List an AI prompt or a `SKILL.md` workflow as a sellable asset.

### Evidence

- PromptBase lets you sell AI prompts or agent skills (`SKILL.md`).
- PromptBase states 0% fees through your own link and a 20% fee through the
  marketplace.
- PromptBase accepts only prompt templates with a high use-case factor, in
  English, without plagiarism, unsafe content, model-rule bypasses or
  AI-generated prompts.

### Guardrails

- Create a truly original workflow template, not a repackaged public prompt.
- Expect approval friction and platform rules.

### Verdict

Interesting for a later "agent skill marketplace" direction, but not a reliable
overnight path to the first dollar.

## 4. Fiverr automation gig

### Mechanism

Set up a gig for a small AI/automation service: a Make/Zapier/n8n audit, a
workflow blueprint, or a fix for one small automation problem.

### Evidence

- Fiverr Automations & Workflows publicly shows thousands of results and low
  entry offers ranging from single digits to tens of EUR.
- Fiverr officially supports AI workflow services, but requires compliance with
  AI, privacy and third-party ToS rules.
- A new seller must complete onboarding and create the gig on desktop; a new
  seller has a limited number of gigs.
- The Fiverr earnings page shows an example where the seller receives 16 USD
  from a 20 USD order, so the marketplace cut is significant and must be
  factored into prices.

### Recommended gig

The entry offer should not be "I will build an AI agent" but a narrow triage
service:

- Basic: [BASIC] for a fit/no-fit verdict on one workflow.
- Standard: [STANDARD] for an automation blueprint.
- Premium: [PREMIUM] for a prototype plan + handoff.

The draft is ready in `workspace/experiments/assets/fiverr-agent-automation-gig-draft.md`.

### Guardrails

- Do not create a gig for scraping against ToS, spam, fake engagement,
  deepfakes or manipulative automation.
- Do not promise "AI agent will make revenue".
- Keep communication and payment inside Fiverr if the platform is used.

### Verdict

Workable as a future inbound channel, but not the best choice for tonight. A
new seller without a reputation may wait a long time for an order and will get
noise/spam. Launch it after the direct checkout test, or in parallel only as a
low-cost inbound surface, not as the main first-dollar bet.

## 5. Upwork proposals

### Mechanism

Respond to jobs such as Zapier/Make/OpenAI automation.

### Evidence

- Upwork lists AI & Automation, Automation Experts and N8N Experts among its
  main categories.
- Upwork uses Connects for proposals; a Basic account gets a limited number of
  free Connects per month and more can be bought.
- Upwork states a freelancer service fee on earnings; the exact amount is shown
  before a proposal or before accepting a contract.

### Guardrails

- Do not send generic proposal spam.
- Do not bypass marketplace communication or payments.
- Do not use external bots for bulk proposal sending.

### Verdict

Good for validating demand and for later outbound, but a low chance of the
first dollar overnight without a profile, a Connects budget and a case study.

## 6. Polymarket / prediction markets

### Mechanism

Making money on a prediction market means having a better probability estimate
than the market, faster execution, access to liquidity or a
market-making/reward edge. That is not the same type of monetization as
selling a service; it is trading with a risk of losing capital.

### Evidence

- Polymarket International geoblocks a number of countries, including the
  United States, and explicitly prohibits VPNs or similar ways of bypassing
  geographic restrictions.
- The Polymarket US documentation describes the US version as a
  CFTC-regulated exchange, fiat-based, for US residents, with identity
  verification before trading/API.
- The Polymarket US documentation states a taker/maker fee model; maker/taker
  and rebate details may change according to the fee schedule.
- Research on Polymarket NBA markets shows that arbitrage opportunities exist,
  but they are short-lived, limited by liquidity and better suited to fast
  execution than to a manual overnight experiment.

### Guardrails

- Do not bypass geoblocking through a VPN.
- Do not use non-public, confidential or insider information.
- Do not run a bot with real money without explicit approval, a loss limit,
  logging and a legal/tax review.
- Do not mistake a referral, a bonus or a gambling/trading win for a repeatable
  business mechanism of the company.

### Verdict

Do not run it as an overnight path to the first dollar. Polymarket is
interesting as a data source and a paper-trading sandbox for agentic market
research, but without a proven edge, real trading is just speculation. If it is
explored, do it without capital first: download public market data, simulate
strategies after fees/slippage and decide only after a multi-day paper-trade
result.

## Recommended overnight test

1. Create one checkout:
   - primary: `Agent Automation Desk 14-day pilot` for [PILOT PRICE],
   - fallback: `48h AI ops triage deposit` for [DEPOSIT].
2. Prepare a list of fictional sample prospects, not cold scraping.
3. Send a short message only after Alex's explicit approval.
4. Measure only hard signals: a deposit, a paid pilot, "send the invoice", or
   a qualified call.

## Sources

- Stripe Payment Links: https://stripe.com/us/payments/payment-links
- Stripe global availability: https://stripe.com/global
- Ko-fi Shop: https://ko-fi.com/shop/
- Ko-fi content guidelines: https://help.ko-fi.com/hc/en-us/articles/360007937553-Ko-fi-Content-Guidelines
- Gumroad fees: https://gumroad.com/help/article/66-gumroads-fees
- Gumroad payouts: https://gumroad.com/help/article/13-getting-paid.html
- Gumroad prohibited products: https://gumroad.com/prohibited
- PromptBase sell: https://promptbase.com/sell
- PromptBase guidelines: https://promptbase.com/prompt-guidelines
- Fiverr automations/workflows category: https://www.fiverr.com/categories/programming-tech/software-development/automations-workflows
- Fiverr AI guidelines: https://help.fiverr.com/hc/en-us/articles/37554976380177-Using-AI-on-Fiverr-guidelines-for-freelancers-and-clients
- Fiverr Business Trends Index 2026: https://investors.fiverr.com/node/9566/pdf
- Fiverr create gig docs: https://help.fiverr.com/hc/en-us/articles/360010451397-Creating-a-Gig
- Fiverr earnings page: https://help.fiverr.com/hc/en-us/articles/9234443621137-Your-earnings-page
- Upwork freelancer flow: https://www.upwork.com/i/how-it-works/freelancer/
- Upwork Connects: https://support.upwork.com/hc/en-us/articles/34955398999699-Connects
- Polymarket geographic restrictions: https://help.polymarket.com/en/articles/13364163-geographic-restrictions
- Polymarket US overview: https://docs.polymarket.us/getting-started/what-is-polymarket-us
- Polymarket US quickstart: https://docs.polymarket.us/getting-started/quickstart
- Polymarket US fee schedule: https://isvdocs.polymarket.us/polymarket-learn/trading/prices-and-fees/trading-fees
- Polymarket liquidity rewards: https://docs.polymarket.com/market-makers/liquidity-rewards
- Arbitrage Analysis in Polymarket NBA Markets: https://arxiv.org/abs/2605.00864
