# Versjonskontroll og branching-strategi
Beskriv teamets praksis for Git versjonskontroll og branching. Med 8 utviklere er det viktig med en enkel men effektiv workflow:

## Branching-modell
Angi om dere følger GitHub Flow, GitFlow eller Trunk-based development. Et lite team med hyppige leveranser vil ofte bruke en forenklet modell som GitHub Flow (feature branches fra main og PR inn til main for hver endring) eller trunk-based (små korte feature-branches) for høy utviklingshastighet​. Hvis dere derimot trenger separate release-løp, kan en variant av GitFlow benyttes. Dokumentet bør forklare valget: "Vi følger GitHub Flow med kontinuerlige leveranser, da dette gir raskere utvikling. main-branchen er alltid produksjonsklar."

## Navngivning av branches
Konvensjoner som at feature-branches prefix’es med type (f.eks. feature/login-flow, bugfix/issue-123), eller bruker Jira-ticket-ID dersom integrert (f.eks. PROJ-45-login-screen).

## Pull requests og merging
Beskriv krav for å opprette PR (skal alle endringer gå via PR, hvor mange approvals trengs, om squash merge brukes osv.). Oppfordre til hyppige, små PRer for å unngå store integrasjonsproblemer.

## Commit-meldinger
Hvis dere bruker en standard (som Conventional Commits eller bare enkle regler), dokumenter det. F.eks. "Commits bør ha en kortfattet beskrivelse i imperativ form, f.eks. Add caching for product images. For større endringer, legg til detaljer i beskrivelsen."

## Release tagging
Om dere tagger versjoner (f.eks. med semantisk versjonering) eller bruker GitHub Releases, beskriv prosedyren.