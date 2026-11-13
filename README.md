# espresso.signal – öffentliche OAuth-Informationsseiten

Dieses **öffentliche, eigenständige** Repository enthält ausschließlich statische Informationsseiten für die private Google-Drive-OAuth-Anwendung `espresso.signal`.

Es enthält **keinen** Produktquellcode, keine rclone-Konfiguration, keine Google-Drive-Dateien, keine Tokens, keine Diagnoseprotokolle und keine Gerätesteuerung.

## GitHub Pages einrichten

1. Nach Review den Pull Request in `main` übernehmen.
2. In **Settings → Pages** unter **Build and deployment** `Deploy from a branch` auswählen.
3. Branch **main**, Ordner **/(root)** wählen und speichern.
4. Prüfen, dass die folgenden URLs tatsächlich erreichbar sind:
   - Startseite: `https://oxfrd1337.github.io/espresso-signal-oauth-pages/`
   - Datenschutz: `https://oxfrd1337.github.io/espresso-signal-oauth-pages/privacy.html`

**Die URLs sind erst nach erfolgreichem Pages-Deployment als veröffentlicht anzusehen.** Die Akzeptanz der Domain durch die Google Auth Platform muss gesondert geprüft werden. Falls Google `github.io` ablehnt, sind ein anderer Webhost oder eine selbst kontrollierte Domain erforderlich.

## Sicherheit

Keine Geheimnisse oder Projekt-/Hardwaredaten in dieses öffentliche Repository schreiben. Änderungen erfolgen über Branch und Pull Request. Die Website selbst enthält keine Login-Funktion und verändert die OAuth-Konfiguration nicht.

Die Datenschutzhinweise beschreiben den vorgesehenen Eigenbetrieb. Vor einer wesentlich anderen oder öffentlichen Nutzung müssen Betreiberangaben, tatsächliche Berechtigungen und Datenflüsse erneut geprüft werden.
