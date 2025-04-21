# Testing strategi
Forklar teamets teststrategi og verktøy for kvalitetssikring (enhet, integrasjon, E2E)

## Enhetstester
Beskriv at små isolerte tester (f.eks. med Jest) skal dekke funksjoner og komponenter. Forklar konvensjoner for testfiler (f.eks. *.test.tsx i samme mappe som koden eller under en __tests__/ mappe).

## Integrasjonstester
Beskriv tester som kjører flere moduler sammen, f.eks. render av en React-komponent med tilhørende context eller state, kanskje bruk av React Testing Library for å simulere brukerinteraksjon uten et fullstendig ende-til-ende miljø.

## End-to-end-tester (E2E)
Forklar hvordan dere tester hele brukerflyter. For web kan dette være med Cypress eller Playwright som automatiserer en nettleser. For mobil Expo/RN kan man bruke Detox eller End-to-end manuelt via testflight etc. Beskriv hvilke kritiske brukerhistorier som dekkes.

## Testdekning og prioritering
Understrek pyramideprinsippet: man bør ha flest enhetstester, færre integrasjonstester, og et utvalg E2E for kritiske stier. Dette fordi enhetstester er enklest og raskest å skrive, mens E2E er komplekse og tidskrevende – de brukes der de gir mest verdi.

## Testprinsipper
Oppmuntre til TDD der det passer, eller i det minste at hver feature kommer med tilhørende tester. Notér om code coverage brukes aktivt (f.eks. minst X% dekning).

## Testdata og miljø
Forklar om tester kjøres mot mock data, eller om det finnes et dedikert test-API eller test-database. For eksempel: "Integrasjonstester bruker en lokal mock server for API (se mocks/-mappen) for å unngå å treffe produksjonsdata."

<hr />
Dokumentasjonen kan deles i underfiler som testing/unit-testing.md, testing/e2e-testing.md, eller en samlet testing.md med underoverskrifter. Den skal gjøre det klart hvordan man kjører testene lokalt (npm test, npm run cypress etc.), og hvordan testene er integrert i CI. På den måten vet nye utviklere nøyaktig hvordan de skal verifisere at endringer ikke introduserer regresjoner.