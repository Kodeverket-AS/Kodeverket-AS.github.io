# Tredjepartsavhengigheter og rammeverk

Her listes og forklares de viktigste tredjepartsavhengighetene og rammeverkene teamet bruker. Dette fungerer som en teknologistakk-dokumentasjon som hjelper både nye og eksisterende utviklere å se helheten:

    Oversikt over teknologistakken: En tabell eller liste over språk, rammeverk, biblioteker og verktøy som inngår i systemet (f.eks. TypeScript, React, Next.js, React Native (Expo), Sanity, Jest for testing, React Testing Library, Cypress for E2E, osv.). Inkluder også byggverktøy (Webpack/Vite) eller state management (Redux, React Context) hvis relevant.

    Bruk og versjoner: For hver nevnte teknologi, skriv et kort avsnitt om hva den brukes til i våre prosjekter og eventuelle retningslinjer. F.eks.: "Sanity brukes som headless CMS for innholdsadministrasjon. Vi bruker Sanity vX, og strukturer innholdet slik..." Eller: "For nettverkskall bruker vi Axios vY i stedet for fetch API, hovedsakelig for bedre interceptors – se kodeeksempel i best practices."

    Godkjente biblioteker: Om teamet har preferanser (eller forbud) – som at man skal bruke Date-fns for datoer fremfor Moment, eller at UI-komponentbibliotek X er standard. Dette hjelper med å unngå duplikate løsninger.

    Hvordan håndtere nye avhengigheter: Beskriv prosessen for å innføre en ny tredjepartsavhengighet. Bør det gjennomgås i kodegjennomgang? Sjekk av lisens (f.eks. unngå GPL-lisenser i proprietær kode) – dette kan også lenke til Open Source-policy.

Dette kan samles i en dependencies.md eller tech-stack.md. Det gir utviklere en rask forståelse av landskapet og hvor de kan finne mer info (f.eks. lenker til dokumentasjon for hvert rammeverk).

# ???
Dokumentér den logiske prosjektstrukturen og mappestrukturen som teamet følger. For både web (Next.js/React) og mobil (React Native/Expo) prosjekter, vis en oversikt over filinndelingen:

## Top-nivå struktur
Beskriv viktige mapper i rot av repo: src/ eller app/, components/, pages/ (for Next.js), utils/, assets/, osv. Forklar hva som hører hvor. For eksempel: "components/ inneholder gjenbrukbare React-komponenter. pages/ (Next.js) definerer side-ruter. lib/ kan inneholde domene-spesifikk logikk som ikke er React-spesifikk."

## Modulstruktur
Hvis prosjektet er delt inn i funksjonelle moduler eller feature-folders, beskriv det. F.eks. en React Native app kan ha mapper som features/ShoppingCart/, features/Profile/ med egne sub-strukturer.

## Navnekonvensjoner
Hvordan navngis filer og mapper? (kebab-case, PascalCase for komponentfiler, etc.) Skal komponentfiler ha .tsx-ending og styles i samme mappe (CSS modules eller styled-components)? Dokumentér eventuelle patterns som presentational vs container components struktur, osv.

## Eksempel strukturdiagram
Det er ofte nyttig å vise et lite eksempel av trestrukturen i dokumentasjonen for klarhet.

<hr />
Ved å standardisere mappestrukturen blir det lettere for utviklere å navigere kodebasen, spesielt på tvers av prosjekter. Denne dokumentasjonen kan lages per type applikasjon dersom web- og mobilprosjekter er svært ulike (f.eks. project-structure-web.md og project-structure-mobile.md), eller et samlet dokument med underseksjoner. Filene kan ligge under docs/architecture/ sammen med evt. systemarkitekturdiagrammer.