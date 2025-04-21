# Kodegjennomgang retningslinjer

Dokumentér prosessen for kodegjennomgang (code review), slik at alle vet hvordan endringer blir evaluert før de merges

## Formål med code review

Klargjør at hensikten er kvalitetssikring og kunnskapsdeling, ikke kritikk av personen. Code review skal sikre at endringer forbedrer kodebasens helse over tid​ google.github.io, ved å fange opp potensielle feil, opprettholde standarder og spre forståelse av koden i teamet.

## Prosedyre

Beskriv hvordan code reviews foregår i praksis. F.eks.: "Alle PR-er må gjennomgås av minst én kollega (helst to). Bruk GitHubs review-funksjon til kommentarer. Godkjenn PR (“Approve”) når den er klar, eller be om endringer (“Request changes”) hvis noe må fikses." Nevn forventet responstid (f.eks. prøv å se gjennom en PR innen en arbeidsdag).

## Hva man ser etter

Lag en sjekkliste for kodereviewere: Overholdes kodestandarder? Er det tester for ny funksjonalitet? Kan koden forenkles eller forbedres (uten at man krever perfeksjon)? Sikkerhetshull eller feil? Performance-problemer? Dokumenter disse punktene slik at både forfatter og reviewer vet fokusområdene. (Man kan trekke inn elementer fra f.eks. Googles "Hva se etter i code review").

## Ton og kultur

Presiser at tilbakemeldinger skal være konstruktive og konkrete. Gjerne påminn om å bruke “Nit: …” for småpirk som ikke er kritisk​
google.github.io
, og å gi ros når noe er bra. Målet er en trygg kodegjennomgangskultur der folk tør å få koden sin vurdert.

## Automatisering

Nevn om noe av reviewprosessen er automatisert: "ESLint og testene kjører automatisk på PR, så reviewer trenger i utgangspunktet kun fokusere på logikk og struktur." Også kan man referere til Code Owners fil hvis dere bruker det for å auto-requeste riktige reviewers.

<hr />
En code review-guide kan ligge som code-review.md. Denne hjelper nye utviklere å vite hvordan de får koden sin integrert, og minner erfarne om beste praksis i review. Over tid er godt gjennomførte code reviews med på å heve kodekvaliteten kontinuerlig.
