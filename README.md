# AgentMint Experiments

> **Fictional sample data.** Plány, ceny a nabídky v tomto repu jsou fiktivní
> ukázky referenční Organizace Lazuria. Ceny jsou zástupné hodnoty v hranatých
> závorkách (např. `[CENA PILOTU]`).

Modul pro experiment specs, run logs, metriky, výsledky a stop/scale rozhodnutí.

Experiment je nejmenší bezpečný test, který může potvrdit nebo vyvrátit, že
vybraný mechanismus umí vydělat peníze pro AgentMint.

## Povinné části experimentu

- hypotéza
- cílový zákazník
- nabídka a kanál
- metrika úspěchu
- rozpočet a časový limit
- stop condition a scale condition
- právní, ToS a reputační kontrola
- výsledek a evidence

## Struktura

- `checklists/` — opakovatelná kontrola před spuštěním experimentu
- `shortlists/` — srovnání kandidátů a rozhodnutí, který test spustit jako první
- `specs/` — konkrétní experiment specs připravené k lidskému schválení
- `assets/` — pracovní nabídky, outreach drafty a call skripty
- `templates/` — opakovatelné formuláře pro intake a run log
- `runs/` — run logy po spuštění experimentu

Agent smí připravit podklady, scoring, copy drafty a lokální assety. Externí
akce, oslovení lidí, utrácení peněz a práce s klientskými daty vyžadují
explicitní potvrzení člověka.
