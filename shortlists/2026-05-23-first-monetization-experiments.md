# First monetization experiments shortlist

Status: recommended
Owner: jannovak
Prepared: 2026-05-23

## Rozhodnutí

První doporučený experiment je **Agent Automation Desk**: produktizovaná
agentní automation služba inspirovaná mechanismem DesignJoy, ale adaptovaná na
výzkum, enrichment, interní operace a malé automatizace.

Důvod: nejkratší cesta k první fakturaci bez stavby SaaS, vysoká agentní
leverage, nízký technický budget a bezpečný ruční approval model.

## Scoring

Skóre 1-5, vyšší je lepší. Váhy:

- Revenue evidence: 20 %
- Time to first dollar: 25 %
- Agent leverage: 20 %
- Distribution access: 15 %
- Risk fit: 10 %
- Delivery margin: 10 %

| Kandidát | Evidence | Time | Agent leverage | Distribuce | Risk fit | Margin | Váženě | Verdikt |
|---|---:|---:|---:|---:|---:|---:|---:|---|
| Agent Automation Desk | 4 | 5 | 5 | 4 | 4 | 4 | 4.50 | Testovat první |
| White-label AI support agent | 5 | 4 | 4 | 3 | 4 | 4 | 4.15 | Testovat druhý |
| AI visibility audit | 5 | 4 | 4 | 3 | 3 | 4 | 3.95 | Testovat po guardrails |
| Simple local website service | 5 | 4 | 3 | 3 | 4 | 3 | 3.75 | Parkovat |
| Vertical template / operating system | 5 | 3 | 4 | 3 | 5 | 4 | 3.75 | Parkovat |
| AI SDR ops | 5 | 4 | 5 | 2 | 2 | 4 | 3.65 | Později, vysoké outreach riziko |
| Niche data/API utility | 5 | 2 | 4 | 2 | 3 | 4 | 3.35 | Později, delší build |
| AI video/content factory | 5 | 3 | 4 | 2 | 2 | 3 | 3.20 | Později, reputační riziko |
| AI asset generator | 5 | 2 | 4 | 2 | 3 | 3 | 3.15 | Později, build + kvalita |
| Curated paid feed/newsletter | 4 | 2 | 4 | 2 | 5 | 3 | 3.05 | Později, pomalý audience build |

## Experiment cards

### 1. Agent Automation Desk

- Mechanismus: fixed monthly fee, async queue, jeden aktivní request, rychlé
  dodání malých operativních výstupů.
- Inspirace: DesignJoy fixed monthly subscription, Trello/request board,
  one-at-a-time delivery a productized service positioning.
- AgentMint adaptace: agent připravuje research, enrichment, SOP, report,
  no-code automation blueprint nebo lokální prototyp; člověk schvaluje externí
  akce.
- ICP: B2B founder, malá agentura nebo ops lead, který má opakované ruční
  výzkumné / provozní úkoly, ale nechce najímat interního automation specialistu.
- První metrika: 1 placený pilot nebo 3 kvalifikované discovery cally do 14 dní.
- Stop condition: po 20 ručně schválených osloveních nejsou aspoň 3 odpovědi
  nebo 1 discovery call.
- Proč první: dá se prodat před stavbou produktu a každý delivery výstup
  zároveň učí, co později automatizovat.

### 2. White-label AI support agent

- Mechanismus: nastavení specializovaného AI support widgetu pro agentury a
  jejich klienty.
- Inspirace: Chatwith / Chatbase pattern.
- AgentMint adaptace: done-with-you setup nad veřejným webem nebo daty dodanými
  se souhlasem; bez kopírování cizích botů.
- ICP: web/design/marketing agentury se support-heavy klienty.
- První metrika: 1 paid setup nebo 10 discovery callů.
- Stop condition: agentury vidí zájem, ale nechtějí nést delivery/support riziko.
- Proč druhý: silný B2B signál, ale vyžaduje víc technického a integračního
  závazku než Agent Automation Desk.

### 3. AI visibility audit

- Mechanismus: placený audit toho, jak značka vypadá ve vyhledávání, Redditu,
  komunitách a AI odpovědích, plus transparentní content plan.
- Inspirace: Launch Club / Reddit Agency / AI-search visibility pattern.
- AgentMint adaptace: reputačně bezpečný audit bez fake accounts, stealth
  posting nebo manipulace.
- ICP: B2B SaaS, agentury a expertní služby, které řeší důvěru a discovery.
- První metrika: 5 placených auditů po fixní ceně.
- Stop condition: zájem je jen o free insight, ne o placený audit.
- Proč ne první: vysoké revenue signály, ale reputačně citlivé hranice; nejdřív
  potřebuje tvrdší guardrails.

## Parking list

- AI SDR ops: blízko peněz, ale nejvyšší riziko spamu, deliverability a GDPR.
- AI video/content factory: rychlá poptávka, ale snadno sklouzne do low-quality
  content treadmillu.
- Niche data/API utility: silná B2B hodnota, ale delší build a compliance.
- Curated paid feed/newsletter: reputačně bezpečné, ale pomalý čas k příjmu.
- AI asset generator: dobrý mechanismus, ale vyžaduje kvalitu výstupu a handling
  práv k obrázkům.

## Zdroje

- DesignJoy official site: https://www.designjoy.co/
- The Futur, DesignJoy productized service interview: https://thefutur.com/watch/how-to-run-a-million-dollar-solo-design-agency
- AgentMint longlist: ../../../company/archive/derived/research-sprints/2026-05-22-online-projects-longlist.md
- AgentMint copyable projects scan: ../../../company/agents/reference/research-sprint-2026-05-22-copyable-online-projects.md
