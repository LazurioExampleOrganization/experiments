# Experiment spec: Agent Automation Desk

Status: ready for human approval
Owner: jannovak
Prepared: 2026-05-23
Mechanism: DesignJoy-for-automation

## Hypotéza

Malé B2B firmy, agentury a founder-led týmy mají opakované provozní úkoly
typu research, enrichment, reporting, SOP tvorba a malá automatizace. Nechtějí
kvůli tomu najímat interního automation specialistu ani kupovat obecný AI
tooling. Zaplatí za produktizovanou službu s jednou aktivní request frontou,
pokud bude výsledek konkrétní, rychlý a bezpečně schvalovaný člověkem.

## Nabídka

Pracovní název: **Agent Automation Desk**

Pilot offer:

- 14denní placený pilot.
- Cena k otestování: [CENA PILOTU] (fiktivní ilustrativní hodnota).
- Jeden aktivní request v jednu chvíli.
- Malé requesty dodání do 2 pracovních dnů, složitější requesty nejdřív jako
  scope proposal.
- Komunikace asynchronně přes sdílený board nebo e-mail thread.

Co se dá objednat:

- research brief s citovanými zdroji
- lead/account enrichment z legálně dostupných zdrojů
- interní SOP nebo checklist pro opakovaný proces
- report z dat dodaných klientem
- návrh no-code / low-code automatizace
- lokální prototyp workflow, který nekomunikuje externě bez schválení

Co není součástí pilotu:

- garantovaný počet leadů, sales calls nebo revenue
- masový outbound
- stealth posting nebo fake engagement
- scraping proti ToS
- práce s neveřejnými zákaznickými daty bez explicitního souhlasu
- produkční automatizace připojená na klientské účty bez samostatného approvalu

## Cílový zákazník

Primary ICP:

- B2B founder nebo owner malé agentury
- už má opakované ruční provozní úkoly
- chápe hodnotu AI, ale nechce spravovat nástroje a prompty
- může zaplatit pilot bez procurement procesu

Secondary ICP:

- ops lead v malé firmě
- consultant / freelancer s opakovaným research a reporting workflow
- tým, který už řešil AI adopci, ale nemá interní kapacitu na každodenní provoz

## Kanál

První kanál: ručně schválený kontakt s fiktivními ukázkovými zájemci a
B2B kontaktů.

Agent smí lokálně připravit:

- ICP definici
- seznam kandidátů bez neveřejných dat
- personalizované message drafty
- one-page offer text
- call agenda

Člověk musí potvrdit:

- koho oslovit
- finální znění zprávy
- odeslání zpráv
- cenu
- jakýkoliv payment nebo invoicing krok

## Primární metrika

Experiment uspěje, pokud do 14 dní od schválení outreach fáze nastane aspoň
jedno:

- 1 placený pilot
- 1 písemné "ano, pošli fakturu / checkout"
- 3 kvalifikované discovery cally s jasnou opakovanou bolestí a ochotou řešit
  ji placeně

## Budget

- Paid ads: 0 Kč
- Paid tools: 0 Kč bez samostatného approvalu
- Founder time: max 6 hodin
- Agent prep time: podle potřeby, ale bez externích akcí
- Delivery budget prvního pilotu: max 8 hodin práce před stop/renegotiate

## Stop condition

Zastavit nebo změnit nabídku, pokud:

- po 20 ručně schválených osloveních nejsou aspoň 3 odpovědi nebo 1 discovery
  call
- discovery cally opakovaně ukážou, že problém je "nice to have"
- první zákazník chce custom software projekt místo produktizované služby
- delivery prvního pilotu odhadem přesáhne 8 hodin bez šance na vyšší cenu

## Scale condition

Pokračovat do další iterace, pokud:

- 1 placený pilot je uzavřený a delivery se vejde do 8 hodin
- nebo 3 discovery cally pojmenují stejnou bolest a aspoň jeden buyer akceptuje
  cenu
- buyer opakovaně rozumí modelu "one active request at a time"

Další iterace po signálu:

- zvýšit cenu na [MĚSÍČNÍ CENA] podle trhu (fiktivní ilustrativní hodnota)
- vybrat jednu niku místo obecného automation desku
- převést opakované requesty do playbooku
- až po 2-3 placených pilotech stavět jednoduchý request portal

## Delivery workflow

1. Intake: zákazník popíše request, cílový výsledek a dostupná data.
2. Triage: AgentMint potvrdí, zda request spadá do pilot scope.
3. Agent prep: agent připraví research, návrh, workflow nebo výstup.
4. Human review: člověk zkontroluje kvalitu, rizika a citlivé informace.
5. Delivery: výstup se předá klientovi.
6. Log: výsledek se zapíše do run logu v `runs/`.
7. Learn: request se označí jako repeatable / one-off / out-of-scope.

## Guardrails

- Žádný masový outreach.
- Žádné falešné reference, fake urgency nebo revenue claimy.
- Žádné přihlašování do klientských účtů bez samostatného approvalu.
- Žádná automatizace, která posílá zprávy nebo mění externí systémy bez
  lidského potvrzení.
- Citlivá data se drží mimo Git; do run logu patří jen anonymizovaná evidence.

## Minimální assety před spuštěním

- one-page offer draft
- 10-20 ručně vybraných prospectů
- 2 outreach message varianty
- discovery call script
- intake template pro první request
- run log template

## Zdroje mechanismu

- DesignJoy official site: https://www.designjoy.co/
- The Futur, DesignJoy productized service interview: https://thefutur.com/watch/how-to-run-a-million-dollar-solo-design-agency
- AgentMint shortlist: ../shortlists/2026-05-23-first-monetization-experiments.md

## Stav spuštění

Nespouštěno. Čeká na lidské potvrzení:

1. potvrdit pilot cenu
2. potvrdit ICP pro první 20 oslovení
3. schválit outreach text
4. schválit konkrétní prospect list
