# Onboarding av nye utviklere
Lag en egen onboarding-guide for nyansatte utviklere. Dette er ofte det første en ny utvikler leser, og bør gi et steg-for-steg opplegg for å komme i gang:

## Tilgang og verktøy
Beskriv hvordan nye utviklere får tilgang til GitHub-repositorier, Slack-kanaler, Jira/Notion (prosjektstyringsverktøy), og eventuelle andre nødvendige kontoer. Inkluder kontaktperson for tilgang om relevant.

## Utviklingsmiljø oppsett
Steg for steg for å sette opp maskinen sin. For eksempel: installer Node.js (angi versjon), Yarn/NPM, Expo CLI, Android Studio/Xcode for mobil, osv. Deretter: klone repo, kjøre npm install, kopiere .env.example til .env og fylle inn nødvendige keys (som de må få fra en kollega eller vault). Denne delen kan hentes fra "Prosjektopprettelse" men spesifikt vinklet til en person som kommer ny inn.

## Lesing av dokumentasjon
Henvis den nyansatte til de øvrige dokumentene i repositoryet. F.eks.: "Les gjennom kodestandarder og beste praksis først, så domenebegreper for å forstå forretningen. Sett deg inn i branching-strategien før du lager din første commit."

## Første oppgave
Ofte kan man inkludere en “Hello World”-oppgave: f.eks. "Start utviklerserveren for webappen (npm run dev) og last den i nettleser. Gjør en liten endring (f.eks. legg til deg selv som bidragsyter i Om oss-siden) og opprett en pull request i henhold til rutinene." Dette lar den nye gjennomføre hele syklusen (kode -> commit -> PR -> merge) i liten skala.

## Mentor og møter
Hvis teamet har en fadder/mentorordning, noter det i dokumentet. Også eventuelle onboarding-møter (f.eks. arkitekturgjennomgang med tech lead, intro til domene med produkteier) kan listes slik at nyansatt vet hva som kommer.

<hr />
Onboarding-guiden (f.eks. ONBOARDING.md) fungerer som en sjekkliste. Den bør være skriftlig i docs-repo slik at den lett kan oppdateres når prosesser endrer seg, og nye ansatte alltid får oppdatert info. God onboarding-dokumentasjon reduserer ramp-up tid dramatisk​ og forhindrer at feil (pga. misforståelser) skjer i startfasen.