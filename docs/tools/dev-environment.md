# Lokal CLI og testmiljø bruk

Her dokumenteres bruken av diverse interne verktøy og miljøer som utviklerne benytter i hverdagen

## CLI-verktøy og skript
Beskriv eventuelle kommandolinjeprogrammer som teamet har laget eller ofte bruker. For eksempel, hvis det finnes et egenutviklet CLI for å generere moduloppsett (f.eks. et script som oppretter en ny komponent med boilerplate-kode), forklar hvordan det installeres og kjøres. Eller ganske enkelt: bruk av Expo CLI (expo start, expo eject), Next.js CLI (next dev, next build), eller NPX-skript. Dokumentér de vanligste skriptene i package.json (som npm run lint, npm run test:watch).

## Lokale testmiljøer
Forklar hvordan man kjører applikasjonene lokalt og bruker testmiljøer. F.eks.: "Web: kjør npm run dev i /web-mappen for å starte Next.js dev-server på localhost. Mobil: kjør expo start i /app-mappen og bruk Expo Go på telefon eller emulator. Sanity: kjør npm run sanity for å starte Sanity Studio lokalt for innhold." Hvis det finnes en delt testserver eller staging-backend som utvikling skal peke mot, beskriv konfigurasjon for det (f.eks. egen .env.staging).

## Debugging og devtools
Gi tips om eventuelle utviklerverktøy som brukes. For eksempel: "Installer React Developer Tools i Chrome for å debugge React/React Native components." For React Native kan man nevne Flipper (debugger) eller VS Code debugger-tilkobling. Hvis spesielle devtools er satt opp (som Redux DevTools integrasjon), forklar hvordan de brukes.

## Andre interne systemer
Om teamet har en delt database dump for test, eller en mock-server verktøy, dokumenter bruken. F.eks.: "Bruk npm run seed for å fylle databasen med testdata gjennom vårt seedskript."

<hr />
Denne delen av dokumentasjonen sikrer at alle utviklere vet hvordan de praktisk utfører vanlige oppgaver. Den kan plasseres i docs/tools.md eller splittes (f.eks. tools/cli.md, tools/environments.md). Sørg for å oppdatere den når nye scripts legges til eller gamle ikke brukes lenger.
