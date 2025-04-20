# Sikkerhet: secrets, auth, mm.
En seksjon om sikkerhet samler retningslinjer for å beskytte både applikasjonen og utviklingsprosessen:

## Håndtering av secrets
Klargjør at hemmeligheter som API-nøkler, tokens, passord aldri skal committes i Git. Beskriv i stedet hvordan man bruker miljøvariabler og GitHub Secrets. F.eks.: "Lokal utvikling: legg API-nøkler i .env-fil som aldri commits. CI/CD: Secrets legges inn via GitHub repository settings og refereres i Actions-workflows." Nevn eventuelle verktøy som skanner kode for secrets (f.eks. GitHub Secret Scanning eller Husky pre-commit hooks).

## Autentisering og autorisasjon
Dokumentér hvordan appene håndterer autentisering. F.eks. "Vår app bruker OAuth 2.0 via Auth0; se docs/security/auth.md for detaljer om token-håndtering." Forklar guidelines for lagring av tokens sikkert (HTTPOnly cookies vs. AsyncStorage for mobil, osv.), og mønstre for tilgangskontroll i koden (hvilke roles finnes, hvordan sjekkes de).

## Sikker kodepraksis
List generelle beste praksiser som utviklere skal følge for å unngå sårbarheter – f.eks. input-validering for å hindre XSS/SQL injection (selv om mest frontend, kan fortsatt gjelde ved bruk av dangerouslySetInnerHTML i React, etc.), bruk av parameteriserte queries hvis appen kommuniserer med DB via backend, etc.

## Avhengighetssikkerhet
Oppfordre til jevnlig oppdatering av biblioteker for å få inn sikkerhetsfikser. Nevn bruk av Dependabot eller tilsvarende for å overvåke avhengigheter.

## Tilgangsstyring i teamet
Inkluder eventuelt regler for hvem som har tilgang til hva i utviklingsprosessen. For eksempel: "Kun admin-utviklere har tilgang til produksjonsmiljøets innstillinger. Alle PRs må godkjennes av minst én annen for å forhindre at ondsinnet kode sniker seg inn.".

<hr />
Denne seksjonen kan deles i flere filer (f.eks. `security/secrets.md`, security/auth.md, security/code-guidelines.md) eller ett samlekapittel. Formålet er å sørge for at alle skriver kode og konfigurerer systemet med sikkerhet i mente, slik at man unngår datalekkasjer eller uautoriserte tilganger i produksjon.