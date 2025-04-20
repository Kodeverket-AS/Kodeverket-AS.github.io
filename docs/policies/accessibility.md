# Tilgjengelighet og universell utforming
Dokumentasjonen bør inkludere klare retningslinjer for tilgjengelighet (accessibility) og universell utforming. Dette er både et etisk ansvar og i mange tilfeller et lovkrav i Norge (f.eks. offentlige rettede nett- og mobil-løsninger skal oppfylle WCAG 2.1 nivå AA):

## WCAG-sjekkpunkter
Beskriv de viktigste prinsippene utviklerne må følge, som tekstalternativer for bilder (alt-tekster), korrekt semantisk HTML (bruk av `<button>` for knapper, `<label>` med inputs osv.), undertekster/transkripsjoner for multimedia, tilstrekkelig fargekontrast, og at løsningen kan brukes med kun tastatur.

## Rammeverk og verktøy
Hvis dere bruker komponentbiblioteker eller designsystem, påpeke at disse skal være i tråd med tilgjengelighet (f.eks. Material-UI eller Chakra UI som har mange innebygde tilpasninger). Nevn eventuelle verktøy som axe-core (for automatisk test av tilgjengelighet i tester) eller browser-utvidelser.

## Testing av tilgjengelighet
Oppmuntre til å teste applikasjonen med skjermleser (f.eks. NVDA/VoiceOver) og tastaturnavigasjon. Dette kan inngå som en del av teststrategien: integrasjonstester kan f.eks. sjekke at komponenter har riktige aria-tags.

## Universell utforming som del av designprosessen
Presiser at utviklere bør samarbeide med designere for å sikre universell utforming fra starten av. Referer gjerne til UU-lovverket kort, og interne mål: "Vi tilstreber AA-nivå på alle nye funksjoner."

<hr />
Tilgjengelighet handler om at alle brukere, uansett forutsetninger, kan bruke løsningen. Ved å ha dette eksplisitt i dokumentasjonen signaliseres det at teamet tar det på alvor. Innholdet kan legges i docs/accessibility.md. Inkluder gjerne lenker til eksterne ressurser som UU-tilsynets sjekklister eller W3Cs WCAG-dokumentasjon for utdypning.