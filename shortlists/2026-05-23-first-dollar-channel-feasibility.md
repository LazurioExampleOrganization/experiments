# First dollar channel feasibility

Status: draft verdict
Owner: jannovak
Verified: 2026-05-23

## Cíl

Prověřit, které rychlé online monetizační cesty mají šanci získat první dolar
pro AgentMint přes noc nebo během 24-48 hodin, aniž bychom kopírovali cizí
identitu, spouštěli spam, obcházeli ToS nebo slibovali neověřené výsledky.

## Kritéria

- Dá se spustit bez stavby produktu?
- Dá se přijmout platba dnes?
- Existuje aktuální poptávkový signál?
- Potřebuje marketplace reputaci, nebo stačí warm distribuce?
- Jaké jsou legal, ToS a reputační guardrails?

## Verdikt

| Cesta | Funkčnost dnes | Poptávkový signál | Platební friction | Distribuce | Verdikt |
|---|---|---|---|---|---|
| Direct Agent Automation Desk + Stripe/Ko-fi checkout | Vysoká | Vysoký | Nízký, pokud má Jan aktivní Stripe/Ko-fi/PayPal | Warm outreach | Testovat první |
| Ko-fi/Gumroad low-ticket digital product | Střední | Střední | Nízký | Slabá bez audience | Použít jen jako checkout/support asset |
| PromptBase prompt/skill listing | Střední | Střední | Střední, čeká na platform approval | Marketplace + vlastní link | Odložit, není overnight |
| Fiverr automation gig | Střední | Vysoký | Nízký po setupu | Marketplace discovery, ale nový seller je pomalý | Založit později jako inbound kanál |
| Upwork proposals | Nízká pro dnešní noc | Vysoký | Connects + account/proposal friction | Marketplace bidding | Nepouštět teď, vhodné až s profilem a case study |
| Polymarket / prediction markets | Nízká jako revenue engine | Vysoký objem trhu, ale bez našeho edge | Trading capital + regulatory/KYC friction | Market microstructure, ne zákaznická distribuce | Nepouštět s reálnými penězi; použít jen paper-trade/data research |

## 1. Direct Agent Automation Desk + checkout

### Mechanismus

Nabídnout konkrétní 48h AI ops triage nebo 14denní pilot fiktivním ukázkovým zájemcům:
zákazník pošle jeden ruční proces a AgentMint vrátí fit/no-fit verdikt,
automation blueprint a návrh prvního užitečného výstupu.

### Evidence

- Stripe Payment Links umožňují vytvořit no-code platební stránku a sdílet link
  bez vlastního webu.
- Stripe je podle oficiálního global availability seznamu dostupný v Czech
  Republic.
- Fiverr veřejně ukazuje velkou kategorii automations/workflows a konkrétní
  AI/Make/Zapier/n8n offers.
- Fiverr Business Trends Index 2026 uvádí růst poptávky po AI agentech,
  workflow nástrojích a Make.com specialistech.

### Guardrails

- Žádný masový outbound.
- Žádné garantované leady, revenue nebo sales cally.
- Žádná práce s klientskými účty nebo citlivými daty bez samostatného approvalu.
- Každá externí zpráva a checkout link čeká na lidské potvrzení.

### Verdikt

Nejlepší cesta k prvnímu dolaru. Nevyžaduje marketplace ranking ani produkt.
Skutečná překážka není technologie, ale schválený checkout, prospect list a
odeslání.

## 2. Ko-fi nebo Gumroad low-ticket digital product

### Mechanismus

Prodávat malý digitální produkt: checklist, prompt pack, AI ops triage worksheet
nebo "first automation brief" template.

### Evidence

- Ko-fi Shop umožňuje prodávat digitální produkty bez listing fee; free plan
  bere 5% service fee a platby jdou přes PayPal nebo Stripe.
- Gumroad umí rychlý digitální checkout, ale podle help centra účtuje přímým
  prodejům 10% + 0.50 USD plus payment processing; marketplace sales mají 30%
  fee.
- Gumroad payout dokumentace uvádí Czech Republic jako podporovanou payout
  zemi.

### Guardrails

- Neprezentovat AI-generovaný template jako vlastní ručně ověřený výsledek,
  pokud není opravdu otestovaný.
- Neprodávat PLR, zakázaný obsah, services skryté jako digitální produkt nebo
  věci v rozporu s payment processor pravidly.

### Verdikt

Technicky funkční, ale přes noc slabé bez audience. Hodí se jako checkout pro
deposit nebo doplněk k direct outreach, ne jako samostatný noční engine.

## 3. PromptBase prompt/skill listing

### Mechanismus

Zalistovat AI prompt nebo `SKILL.md` workflow jako prodejný asset.

### Evidence

- PromptBase umožňuje prodávat AI prompts nebo agent skills (`SKILL.md`).
- PromptBase uvádí 0% fees přes vlastní link a 20% fee přes marketplace.
- PromptBase přijímá jen prompt templates s high use-case faktorem, anglicky,
  bez plagiarismu, unsafe obsahu, model-rule bypassu nebo AI-generated promptů.

### Guardrails

- Vytvořit skutečně originální workflow template, ne přebalený veřejný prompt.
- Počítat s approval friction a platform pravidly.

### Verdikt

Zajímavé pro pozdější "agent skill marketplace" směr, ale není to spolehlivá
overnight cesta k prvnímu dolaru.

## 4. Fiverr automation gig

### Mechanismus

Založit gig pro malou AI/automation službu: Make/Zapier/n8n audit, workflow
blueprint, nebo fix jednoho malého automation problému.

### Evidence

- Fiverr Automations & Workflows má veřejně tisíce výsledků a nízké entry
  offers v jednotkách až desítkách EUR.
- Fiverr oficiálně podporuje AI workflow služby, ale vyžaduje dodržení AI,
  privacy a third-party ToS pravidel.
- Nový seller musí projít onboardingem a vytvořit gig na desktopu; nový seller
  má omezený počet gigů.
- Fiverr earnings page ukazuje příklad, kde ze 20 USD objednávky seller dostane
  16 USD, tedy marketplace cut je významný a musí být započítaný do cen.

### Doporučený gig

Entry offer nemá být "postavím AI agenta", ale úzká triage služba:

- Basic: [BASIC] za fit/no-fit verdikt jednoho workflow.
- Standard: [STANDARD] za automation blueprint.
- Premium: [PREMIUM] za prototype plan + handoff.

Draft je připravený v `modules/experiments/assets/fiverr-agent-automation-gig-draft.md`.

### Guardrails

- Nevytvářet gig pro scraping proti ToS, spam, fake engagement, deepfakes nebo
  manipulativní automatizaci.
- Neslibovat "AI agent will make revenue".
- Držet komunikaci a platbu uvnitř Fiverru, pokud se platforma použije.

### Verdikt

Funkční jako budoucí inbound kanál, ale není nejlepší pro dnešní noc. Nový
seller bez reputace může čekat dlouho na objednávku a dostane šum/spam.
Spustit po direct checkout testu, nebo paralelně jen jako low-cost inbound
surface, ne jako hlavní first-dollar bet.

## 5. Upwork proposals

### Mechanismus

Reagovat na jobs typu Zapier/Make/OpenAI automation.

### Evidence

- Upwork řadí AI & Automation, Automation Experts a N8N Experts mezi hlavní
  kategorie.
- Upwork používá Connects pro návrhy; Basic account dostává omezený počet
  free Connects měsíčně a další lze kupovat.
- Upwork uvádí freelancer service fee na earnings; přesná výše se ukazuje před
  návrhem nebo přijetím kontraktu.

### Guardrails

- Neposílat generické proposal spam.
- Neobcházet marketplace komunikaci ani platby.
- Nepoužívat externí automaty na hromadné proposal sending.

### Verdikt

Dobré pro validaci poptávky a pozdější outbound, ale nízká šance na první dolar
přes noc bez profilu, connects budgetu a case study.

## 6. Polymarket / prediction markets

### Mechanismus

Vydělat na predikčním trhu znamená mít lepší pravděpodobnostní odhad než trh,
rychlejší exekuci, přístup k likviditě nebo market-making/reward edge. To není
stejný typ monetizace jako prodej služby; je to trading s možností ztráty
kapitálu.

### Evidence

- Polymarket International geoblockuje řadu zemí včetně United States a
  explicitně zakazuje VPN nebo podobné obcházení geografických omezení.
- Polymarket US dokumentace popisuje US verzi jako CFTC-regulated exchange,
  fiat-based, pro US residents, s identity verification před tradingem/API.
- Polymarket US dokumentace uvádí taker/maker fee model; maker/taker a rebate
  detaily se mohou měnit podle fee schedule.
- Výzkum nad Polymarket NBA trhy ukazuje, že arbitrážní příležitosti existují,
  ale jsou krátké, likviditou omezené a vhodné spíš pro rychlou exekuci než pro
  ruční noční experiment.

### Guardrails

- Neobcházet geoblocking přes VPN.
- Nepoužívat neveřejné, důvěrné nebo insider informace.
- Nepouštět bota s reálnými penězi bez explicitního approvalu, loss limitu,
  loggingu a právní/daňové kontroly.
- Nezaměňovat referral, bonus nebo gambling/trading win za opakovatelný
  business mechanismus AgentMintu.

### Verdikt

Nepouštět jako cestu k prvnímu dolaru přes noc. Polymarket je zajímavý jako
datový zdroj a paper-trading sandbox pro agentní market research, ale bez
ověřeného edge je reálný trading jen spekulace. Pokud ho zkoumat, tak nejdřív
bez kapitálu: stáhnout veřejná market data, simulovat strategy po fees/slippage
a teprve po vícedenním paper-trade výsledku rozhodnout.

## Doporučený noční test

1. Vytvořit jeden checkout:
   - primární: `Agent Automation Desk 14-day pilot` za [CENA PILOTU],
   - fallback: `48h AI ops triage deposit` za [ZÁLOHA].
2. Připravit seznam fiktivních ukázkových zájemců, ne studený scraping.
3. Poslat krátkou zprávu jen po explicitním Janově schválení.
4. Měřit jen tvrdé signály: deposit, paid pilot, "pošli fakturu", nebo
   kvalifikovaný call.

## Zdroje

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
