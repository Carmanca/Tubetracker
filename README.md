# Tube Tracker — GitHub Pages

Deze map is de kant-en-klare website. Geen build, database, API-sleutel of betaalde server nodig.

## Online zetten
1. Maak op GitHub een repository, bijvoorbeeld `tube-tracker`.
2. Pak deze ZIP uit. Upload alle bestanden EN de map `assets` naar de hoofdmap van je repository. `index.html` moet direct in de hoofdmap staan, niet in een extra map en niet als ZIP.
3. Open in GitHub: Settings → Pages → Build and deployment → Deploy from a branch.
4. Kies `main` en `/(root)` en klik Save.
5. Wacht tot GitHub de website heeft gepubliceerd. Het adres wordt meestal `https://JOUWNAAM.github.io/tube-tracker/` en staat bij Pages.
6. Open dat adres via HTTPS. Je kunt de site via het browsermenu aan je startscherm toevoegen.

Alle bestanden zijn relatief gekoppeld, dus ook een andere repositorynaam of een eigen domein werkt.
Het bestand `.nojekyll` hoort erbij. Browserupload toont verborgen bestanden soms niet; `index.html` en `assets` zijn de belangrijkste bestanden.

## Opslag en back-ups
Je logboek wordt lokaal op dit apparaat/in deze browser bewaard. Geen accounts en geen automatische synchronisatie.
Onder Timer → Je gegevens kun je een JSON-back-up downloaden of terugzetten.
Terugzetten vervangt de lokale gegevens. Maak regelmatig een back-up, zeker vóór het wissen van browsergegevens of wisselen van apparaat.
Privénavigatie is niet geschikt voor blijvende opslag. Bestaande gegevens op de oude gehoste site worden niet automatisch overgenomen.
De Android-app heeft eigen opslag. Met een back-up kun je gegevens tussen website en app overzetten.

## Offline en alarmen
Na het eerste succesvolle online bezoek worden de websitebestanden voor offline gebruik bewaard, zolang de browser die opslag niet wist.
Voor een website-alarm moet de pagina open en actief blijven; gesloten/slapende browsers garanderen geen tijdige melding.
De aparte Android-APK bevat de website ingebouwd en heeft geen internet nodig. Schakel daar in Timer de telefoonmeldingen en eventueel geluid in. Geef Android toestemming voor meldingen en exacte timers, en test het alarm.
Smartwatchmeldingen hangen af van de meldingsinstellingen van je telefoon en horloge.

## Aanpassen
De losse broncode staat in TubeTracker-Portable-Source.zip.
Deze download bevat alleen websitebestanden, geen logboeken, accounts of privésleutels.

## Controle
Website-build en lokale opslagtests geslaagd. APK-handtekening gecontroleerd.
Niet getest op een fysiek Android-toestel; controleer het alarm met de testknop op jouw telefoon.
