# First monetization test checklist

Status: active checklist
Owner: jannovak
Last updated: 2026-05-23

Použij před každým experimentem, jehož cílem je ověřit první příjem nebo
kvalifikovanou poptávku pro AgentMint.

## 1. Hypotéza

- Je jasně napsané, kdo má problém.
- Je jasně napsané, za co by mohl zaplatit.
- Hypotéza jde vyvrátit během 7-14 dní.
- Není to jen "lidé chtějí AI"; je to konkrétní workflow nebo výsledek.

## 2. Nabídka

- Nabídka má jeden hlavní výsledek.
- Scope je omezený tak, aby šel dodat ručně nebo poloagentně.
- Cena nebo paid-pilot otázka je konkrétní.
- Je jasné, co není součástí nabídky.

## 3. Cílový zákazník

- ICP je popsaný konkrétněji než "SMB" nebo "founders".
- Existuje dostupný kanál, kde jde získat první signál bez placené kampaně.
- AgentMint nepotřebuje cizí zákaznická data, neveřejné databáze ani access do
  účtů třetích stran, aby test připravil.

## 4. Metrika

Experiment musí mít aspoň jednu primární metriku:

- placený pilot
- refundable deposit
- kvalifikovaný discovery call s jasnou bolestí a ochotou platit
- písemné "ano, pošli mi nabídku / fakturu"

Vanity metriky jako likes, traffic nebo pozitivní komentář nestačí.

## 5. Budget a čas

- Peněžní budget je uvedený předem.
- Časový budget founder/agent práce je uvedený předem.
- Stop date je konkrétní datum.
- Žádný placený nástroj, reklama ani SaaS subscription se nespouští bez
  lidského potvrzení.

## 6. Stop / scale rozhodnutí

Před spuštěním musí být vyplněno:

- Stop condition: co znamená, že experiment nefunguje.
- Scale condition: co znamená, že experiment stojí za další iteraci.
- Pivot note: jaký learning by vedl ke změně ICP, nabídky nebo ceny.

## 7. Bezpečnost a reputace

Experiment nesmí obsahovat:

- spam nebo masový nevyžádaný outreach
- fake engagement, falešné účty nebo stealth posting
- phishing, credential harvesting nebo klamavé claimy
- scraping proti ToS nebo obcházení rate limitů
- kopírování cizího brandu, obsahu, databáze nebo zákaznických dat

Externí akce vyžadující explicitní lidské potvrzení:

- odeslat e-mail, DM nebo formulář
- publikovat landing page nebo veřejný obsah
- utratit peníze
- použít zákaznická data
- přihlásit se do účtu třetí strany
- spustit automatizaci, která komunikuje mimo lokální workspace

## 8. Evidence

Před spuštěním existuje místo pro zápis výsledku:

- experiment spec v `specs/`
- run log v `runs/`
- odkazy na anonymizované důkazy
- rozhodnutí: stop, repeat, scale nebo pivot
