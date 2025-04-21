# Prosjektopprettelse og -forvaltning

Ha en guide for prosjektopprettelse og forvaltning som beskriver hvordan man starter et nytt prosjekt eller modul i stacken, og hvordan man administrerer et prosjekt gjennom livssyklusen. Denne dokumentasjonen fungerer som en oppskrift for konsistente prosjekter. Innhold kan inkludere:

## Opprettelse av nytt prosjekt

Hvordan bruke boilerplate eller maler (f.eks. create-next-app for Next.js, eller Expo CLI for React Native) med teamets preferanser. Beskriv eventuelle interne verktøy eller templates som skal benyttes for å få riktig konfigurasjon (lint, testoppsett, etc.) fra start.

## Konfigurasjon og miljøer

Hvordan sette opp utviklingsmiljøet lokalt (Node-versjon, pakkehåndtering, miljøvariabler). Hvis teamet har en standard for .env-filer eller config, dokumentér dette. Inkluder stegene for å koble mot nødvendige tjenester (f.eks. Sanity databasen, API-endepunkter) i et nytt prosjekt.

## Deploy og miljøhåndtering

Retningslinjer for opprettelse av staging- og produksjonsmiljøer, hvordan prosjektet deployeres via CI/CD (beskrevet i egen seksjon), og rutiner for vedlikehold. Forvaltning kan også inkludere hvordan man oppgraderer avhengigheter jevnlig, overvåker ytelse, logger feil, osv.

## Prosjektmal og struktur

Referer til avsnittet om prosjektstruktur – nye prosjekter bør følge samme mappeoppsett, naming og modulinndeling for gjenkjennelighet.

<hr />
Denne guiden kan samles i en markdown-fil (f.eks. project-setup.md). Den sørger for at alle starter nye prosjekter på samme måte, noe som sparer tid og reduserer konfigurasjonsfeil.
