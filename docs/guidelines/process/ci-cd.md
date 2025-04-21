# CI/CD oppsett
Beskriv oppsett og bruk av Continuous Integration/Continuous Deployment (CI/CD), ettersom teamet bruker GitHub Actions for automatisering. Dokumentasjonen kan dekke:

## Bygg og test pipeline
Hvilke actions som kjøres på push/PR. For eksempel: "Alle pull requests trigges av en GitHub Actions workflow som kjører linting, bygger prosjektet og kjører alle tester." Inkluder filnavn (.github/workflows/ci.yml) og forklar struktur: jobber, steg (installer avhengigheter, kjøre npm run build, npm test osv).

## Deploy-prosess
Forklar hvordan kode går til produksjon. F.eks.: "Når kode merges til main, kjører en deploy-workflow som bygger appen og deployer til Vercel for web og kjører EAS (Expo Application Services) for å bygge mobilapp." Eller hvis dere bruker GitHub Pages for dokumentasjon (som denne dokumentasjonen selv), beskriv det.

## Miljøer og secrets
Hvordan sensitiv info brukes i CI. F.eks.: "Deployment-workflowen trekker inn API_KEY og SECRET fra GitHub Secrets for å deploye." Dette overlapper med sikkerhetsseksjonen, men her kan teknisk bruk beskrives.

## Status og varsler
Noter om CI-status vises i PR, og om teamet bruker f.eks. Slack-varsler ved feil build.

<hr />
Inkluder gjerne et konkret eksempel på workflow-konfigurasjon i dokumentet for tydelighet, men hovedsakelig bør det forklare hva utviklere trenger å vite (hvordan trigge re-run, hvordan legge til nye tester i pipeline, osv.). Filnavn som ci-cd.md under docs/process/ kan passe.