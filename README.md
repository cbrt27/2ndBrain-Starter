# 2ndBrain Starter

Eine einzige Datei, mit der du in Obsidian und Claude Code dein eigenes
**2ndBrain** aufbaust – ein persönliches Wissens- und Arbeitssystem, das
Claude in jeder Session kennt.

Die `CLAUDE.md` in diesem Repo ist ein **Setup-Assistent**: Claude führt dich
im Chat durch etwa fünfzehn kurze Fragen, zeigt dir einen Bauplan und legt
erst nach deinem Okay Ordner und Dateien an. Am Ende ersetzt sich die Datei
selbst durch deine persönliche `CLAUDE.md`.

## Voraussetzungen

- [Obsidian](https://obsidian.md)
- [Claude Code](https://claude.com/claude-code)

## So geht's

1. Einen leeren Ordner anlegen und in Obsidian als Vault öffnen.
2. [`CLAUDE.md`](CLAUDE.md) aus diesem Repo in den Ordner legen.
3. Im Ordner `claude` starten und „Hallo" schreiben.

Das Setup dauert etwa eine Viertelstunde. Fragen kannst du überspringen;
die Stellen sind dann mit „Noch zu ergänzen" markiert.

## Was entsteht

```
Mein Vault/
├── CLAUDE.md          deine persönliche Arbeitsanleitung für Claude
├── 00 Kontext/        Über mich, Zielgruppen, Angebot, Schreibstil, Branding
├── 01 Inbox/          Brain Dump für alles Unsortierte
├── 02 Projekte/       je Vorhaben eine Datei
├── 03 Bereiche/       dauerhafte Verantwortung, je Bereich ein Ordner
├── 04 Ressourcen/     Wissen und Referenzen, inkl. Empfehlungen
├── 05 Daily Notes/    Logbuch, eine Datei pro Tag
├── 06 Archiv/         Abgeschlossenes
└── 07 Anhänge/        Bilder, PDFs, Medien
```

Die Fragen passen sich deiner Situation an: **angestellt** (Standard),
selbstständig, in Ausbildung oder Studium, auf Jobsuche oder in Elternzeit.

Deine persönliche `CLAUDE.md` enthält erprobte Arbeitsregeln, unter anderem:
Brain-Dump-Einträge mit Datum einsortieren, Arbeitsergebnisse in der Daily
Note und den Status in der Projekt-Datei führen, Zeitleisten chronologisch
halten und „merk dir das" an die richtige Stelle ablegen.

## Datenschutz

Das Setup schreibt nur in den Vault-Ordner. Es installiert nichts, legt keine
Hooks an und ändert nichts an deiner Claude-Code-Konfiguration. Was du im
Chat erzählst, landet in den Dateien deines Vaults – überlege dir, was du dort
festhalten willst, besonders wenn du den Vault synchronisierst.

## Herkunft

Idee und Grundgerüst – geführtes Setup im Chat, PARA-Ordner 00–07,
Kontext-Profil – gehen auf das „Zweites Gehirn"-Konzept von Julian Ivanov
(YouTube) zurück. Diese Fassung ist eigenständig formuliert und um eigene
Arbeitsweisen erweitert von **cbrt27**.

## Lizenz

[CC BY-SA 4.0](LICENSE) – du darfst die Datei frei nutzen, anpassen und
weitergeben, auch kommerziell. Bedingungen: Nenne **cbrt27** als Urheberin,
verweise auf die Lizenz, mach Änderungen kenntlich und gib veränderte
Fassungen unter derselben Lizenz weiter.
