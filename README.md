# 📘 Kodeverkets Utviklerdokumentasjon

Dette repositoriet inneholder all dokumentasjon for utviklingsteamet vårt. Her samler vi retningslinjer, beste praksis, tekniske beskrivelser og rutiner som skal gjøre det enklere å utvikle, samarbeide og onboarde nye teammedlemmer. Målet er å ha en **levende og søkbar dokumentasjonsplattform** som er utviklervennlig og lett å navigere i.

## 🚀 Hva finner du her?

Dokumentasjonen er delt inn i flere hovedområder:

| Tema                            | Beskrivelse |
|---------------------------------|-------------|
| 📐 **Kodestandarder**           | Regler for formatering, navngivning, komponentstruktur og beste praksis |
| 📚 **Domenekunnskap**           | Forklaringer av forretningsbegreper og design-/UX-samarbeid |
| ⚙️ **Prosesser og rutiner**     | Hvordan man setter opp prosjekter, bruker Git, jobber med CI/CD og tester |
| 🔐 **Retningslinjer**           | Sikkerhet, tilgjengelighet, etikk og ansvarlig utvikling |
| 🛠 **Verktøy og hjelpemidler**  | CLI-verktøy, testmiljøer og intern verktøybruk |
| 🧠 **Onboarding**               | Veiledning for nye utviklere som skal inn i teamet |

## 🌐 Tilgjengelig som nettside

Vi publiserer denne dokumentasjonen som en søkbar og brukervennlig nettside via vår [GitHub Pages](https://kodeverket-as.github.io).

## 📂 Mappestruktur

```plaintext
docs/
├── standards/         → Kodestandarder og beste praksis
├── domain/            → Domenespråk og design-samarbeid
├── process/           → Prosessbeskrivelser og rutiner
├── policies/          → Etikk, sikkerhet og prinsipper
├── tools/             → CLI-verktøy og utviklingsmiljøer
└── onboarding.md      → Onboarding-guide for nye utviklere
```

## 🧑‍💻 Bidra til dokumentasjonen
Alle i teamet kan og bør bidra til dokumentasjonen. Gjør endringer via en Pull Request og be om en gjennomgang som ved vanlig kodeendring. Husk:
- Hold språket klart og konsist
- Bruk norsk i tekst, engelsk i kode
- Hold struktur og stil konsistent med resten av repoet

Hvis du ønsker å få live previews mens du skriver dokumentasjon kan du kjøre `mkdocs-material` lokalt. Dette krever at du har python 3.4 eller høyere og har installert `mkdocs-material` med følgende cli
```console
pip install mkdocs-material
```
Etterpå har du mulighet til å kjøre serveren med følgende kommando
```console
mkdocs serve
```

## 📢 Kontakt
Har du forslag eller spørsmål til strukturen? Ta kontakt med @kunkristoffer eller @Andreastak86 i Discord eller bruk vårt [diskusjons forum](https://github.com/orgs/Kodeverket-AS/discussions).