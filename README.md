# Joomla Sprachpaket: Obersorbisch (hsb-DE)

Frontend (Website)-Sprachpaket für Joomla! 6.x, Sprachcode `hsb-DE`.

## Installation

1. In Joomla Backend: **System → Erweiterungen installieren**
2. `hsb-DE_6.1.3.zip` hochladen und installieren
3. Unter **System → Website → Sprachen** eine neue Inhaltssprache anlegen (oder die bestehende „Obersorbisch" bearbeiten):
   - Sprach-Tag: `hsb-DE`
   - Bild: `hsb_de`

## Flagge manuell hochladen (einmalig, per FTP)

**Wichtig:** Die Flaggen-Datei wird bewusst NICHT automatisch durch das Paket installiert (siehe Hinweis in `install.xml`) — Joomla würde sonst bei jeder Aktualisierung dieses Pakets den kompletten, von allen Sprachen gemeinsam genutzten Flaggen-Ordner leeren.

Datei `hsb_de.gif` per FTP hochladen nach:
```
media/mod_languages/images/hsb_de.gif
```

## Automatische Update-Benachrichtigung

Dieses Paket registriert bei der Installation automatisch einen Update-Server (`update.xml` in diesem Repository). Sobald hier eine neue Version veröffentlicht wird, zeigt Joomla im Backend unter **System → Aktualisieren → Erweiterungen** automatisch „Update verfügbar" an.

## Hinweis zum Inhalt

Die Textinhalte sind aktuell noch deutschsprachige Platzhalter aus einer früheren Vorlage und müssen noch ins Obersorbische übertragen werden.
