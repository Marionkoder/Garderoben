# Garderoben

En liten app for å bygge og se garderoben din med egne bilder.

## Legg ut på GitHub Pages

1. Pakk ut zip-filen på datamaskinen.
2. Lag et nytt repo på GitHub, for eksempel `garderoben`.
3. Åpne repoet, velg **Add file, Upload files**, og dra **alle filene i mappen** (ikke selve zip-filen) inn i vinduet på én gang. Trykk **Commit changes**.
   `index.html` må ligge i roten av repoet.
4. Gå til **Settings, Pages**. Velg **Deploy from a branch**, branch `main` og mappen `/ (root)`, og trykk Save.
5. Etter et minutt eller to ligger appen på `https://brukernavn.github.io/garderoben/`.

## Bilder og data

Plagg og bilder lagres kun i nettleseren (IndexedDB) på enheten du bruker appen på. De ligger **ikke** i repoet, så de er ikke offentlige.

- Åpne appen i Safari eller Chrome og velg **Legg til på Hjem-skjerm**. Da behandles den som en egen app, og lagringen er tryggere.
- Data følger ikke med mellom enheter eller mellom ulike nettadresser.
- Nederst i fanen **Plagg** finner du **Sikkerhetskopi**. «Lagre sikkerhetskopi» lager én fil med alle plagg, bilder, antrekk og farger. «Last inn sikkerhetskopi» henter dem tilbake, enten ved å slå sammen med det som er i appen eller ved å erstatte alt. Det er slik du flytter alt fra claude.ai-versjonen til GitHub-adressen, eller til en ny telefon.
