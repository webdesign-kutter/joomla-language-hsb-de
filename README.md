# Joomla Sprachpaket: Obersorbisch (hsb-DE)

Frontend (Website)-Sprachpaket für Joomla! 6.x, Sprachcode `hsb-DE`.

## Installation

1. In Joomla Backend: **System → Erweiterungen installieren**
2. `hsb-DE_6.2.0.2.zip` hochladen und installieren
3. Unter **System → Website → Sprachen** eine neue Inhaltssprache anlegen (oder die bestehende „Obersorbisch" bearbeiten):
   - Sprach-Tag: `hsb-DE`
   - Bild: `hsb_de`

## Flagge

Die Flagge `hsb_de.gif` wird bei der Installation automatisch nach `media/mod_languages/images/` kopiert. Danach unter **System → Sprachen** beim Eintrag „Obersorbisch" im Feld „Bild" `hsb_de` wählen.

**Achtung beim Deinstallieren:** Joomla löscht dabei den gesamten Ordner `media/mod_languages/images/` (alle Flaggen aller Sprachen), nicht nur `hsb_de.gif`. Vor dem Deinstallieren dieses Pakets den Ordner sichern. Die Flagge liegt zusätzlich im Ordner `flagge/` dieses Repos.

## Automatische Update-Benachrichtigung

Dieses Paket registriert bei der Installation automatisch einen Update-Server (`update.xml` in diesem Repository). Sobald hier eine neue Version veröffentlicht wird, zeigt Joomla im Backend unter **System → Aktualisieren → Erweiterungen** automatisch „Update verfügbar" an.

## Hinweis zum Inhalt

Die Textinhalte sind aktuell noch deutschsprachige Platzhalter aus einer früheren Vorlage und müssen noch ins Obersorbische übertragen werden.
