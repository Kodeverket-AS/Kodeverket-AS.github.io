# Bruk av AI-verktøy
Utviklingsteamet bør ha retningslinjer for bruk av AI-verktøy som ChatGPT og GitHub Copilot, da disse stadig oftere brukes i kodedagen

## Tillatt bruk og formål
Angi i hvilke situasjoner AI-verktøy er greit å bruke. F.eks.: "ChatGPT kan brukes for å få forslag til algoritmer, forklare kode eller generere dokumentasjonseksempler. Copilot kan benyttes for autofullføring av kode og forslag til implementasjoner." Poenget er at AI er et hjelpemiddel, ikke en erstatning for egen forståelse.

## Personvern og konfidensialitet
En viktig regel er at man ikke skal dele lukket/kode eller sensitiv informasjon med offentlige AI-tjenester uten tillatelse. Kode som legges inn i ChatGPTs gratisversjon kan bli en del av treningsdata. Presiser at selskapssensitiv logikk eller nøkler aldri må skrives inn. (Hvis bedriften har tilgang til en privat ChatGPT-løsning eller self-hosted LLM, kan man nevne det som alternativ).

## Kvalitetskontroll
Gjør det klart at AI-generert kode må gjennomgås kritisk. Utvikleren er ansvarlig for resultatet – man må teste og verifisere at forslaget er korrekt, sikkert og følger teamets standarder. F.eks.: "Copilot kan foreslå kode som ikke er optimalt eller oppdatert; bruk det som utgangspunkt, men refaktorer til å oppfylle våre kodestandarder."

## Lisens og kildekode
Det har vært diskusjoner rundt Copilot som kan gjengi kode fra open source-prosjekter. Teamet bør være oppmerksom på dette. Retningslinjer kan være: "Unngå å akseptere større kodeblokker fra Copilot uten å forstå opphavet. Hvis du mistenker at forslaget er kopiert fra et identifiserbart prosjekt med uforenlig lisens, omskriv koden." Dette for å overholde Open Source-policyen.

## Dokumentasjonshjelp
AI kan også brukes til å generere tekst som dokumentasjon, kommentarer osv. Her gjelder samme kvalitetskontroll – teamets tone og stil skal opprettholdes.

<hr />
Skriv disse retningslinjene i klartekst (f.eks. ai-tools.md). Målet er å oppmuntre til produktiv bruk av AI samtidig som man unngår fallgruver som lekkasje av sensitiv info eller innføring av bugget/uegnet kode. Siden AI-verktøy er relativt nye og i rask utvikling, bør denne seksjonen revideres jevnlig basert på erfaringer og evt. selskapets offisielle politikk.