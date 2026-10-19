# Quellenkarte und Verifikation

## Gesetzestext

- Anbieter: Bundesministerium der Justiz und für Verbraucherschutz / Bundesamt für Justiz, Gesetze im Internet.
- [Amtliche Gesamtübersicht](https://www.gesetze-im-internet.de/prodhaftg/).
- [Abgerufenes XML-Paket](https://www.gesetze-im-internet.de/prodhaftg/xml.zip).
- Abruf: 2026-10-19T12:26:39.676094+00:00; HTTP 200.
- Konsolidierungsstand: Zuletzt geändert durch Art. 5 G v. 17.7.2017 I 2421.
- ZIP SHA-256: `76f26694b8411c1dbdabfe90918f985c773dd4b7080d28e184469ea7e330b8f2`.
- XML SHA-256: `a8df978d4c8614f4f54207496039734465353fbb51d3483fe8a63dc25ea2f172`.
- Originale im Repository: `sources/official.zip`, `sources/official.xml`; maschinenlesbare Abrufdaten in `sources/retrieval.json`.
- Parser: `audit/_parse.py`; Arbeitsformat: `audit/units.jsonl`; kanonische Ableitung: `sources/canonical.md`.
- Vorhandene Intake-Quelle: `/Volumes/LaCie/law-intake/eu/de/gesetze/gii-prodhaftg.md`. Sie wurde gelesen und nicht überschrieben. Der Änderungsstand ist unverändert; die eigene Ableitung gewährleistet eine geschlossene Prüfkette vom aktuellen Abruf zum Wortlaut. Unterschiede durch Markdown-Layout werden nicht als Gesetzesänderung ausgegeben.

## Vollständigkeit und Nachweis

Der unabhängige Zeichenvergleich gegen den gesamten XML-Inhalt jeder materiellen Einheit stimmt nach Entfernung von Layout-Leerraum vollständig überein. Erhaltung sämtlicher Paragraphen, keine Anlagen, keine weggefallenen Einheiten. Keine manuelle Rekonstruktion von Gesetzestext. [Prüfergebnis](VOLLSTAENDIGKEIT.json). Alle Quellenartefakte sind mit lokalen SHA-256-Werten in `sources/hashes.json` erfasst. Abrufzeit ist der Prüfzeitpunkt, kein Beleg für eine an diesem Tag erfolgte Gesetzesänderung.

## Amtliche Hinweise zur Stammnorm

(+++ Textnachweis ab: 1.1.1990 +++)(+++ Maßgaben aufgrund EinigVtr vgl ProdHaftG Anhang EV,     nicht mehr anzuwenden +++)

## Recherche

Die tatsächlich ausgeführten Suchansätze, erfolgreichen amtlichen Volltexte und fehlgeschlagenen Zugriffe sind in [RECHTSPRECHUNG.md](RECHTSPRECHUNG.md) beschrieben. Keine flächendeckende Rechtsprechungsauswertung; keine Aussage über das Nichtvorhandensein weiterer Entscheidungen.

## Reformstand und zeitliche Abgrenzung

Die erneute amtliche XML-Abfrage am 19.10.2026 liefert denselben Wortlaut wie die Autorenquelle. Unabhängig davon dokumentiert der [Deutsche Bundestag](https://www.bundestag.de/dokumente/textarchiv/2026/kw41-de-produkthaftungsrecht-1222456) die Annahme des Reformgesetzentwurfs am 8.10.2026. Diese parlamentarische Quelle wird als Verfahrensnachweis verwendet; sie ersetzt weder einen Verkündungsbeleg noch die Prüfung des Inkrafttretens und der Anwendungsbestimmungen einer nationalen Neuregelung.

Die [Richtlinie (EU) 2024/2853](https://eur-lex.europa.eu/eli/dir/2024/2853/oj/deu) ist davon getrennt: Artikel 2 Absatz 1 betrifft Produkte, die nach dem 9.12.2026 in Verkehr gebracht oder in Betrieb genommen werden. Artikel 21 hebt die frühere Richtlinie mit Wirkung vom 9.12.2026 auf, erhält sie aber für zuvor in Verkehr gebrachte oder in Betrieb genommene Produkte. Artikel 22 setzt den Mitgliedstaaten eine Umsetzungsfrist bis zum 9.12.2026. Aus dieser Richtlinie allein folgt keine bereits am 19.10.2026 vollzogene Erweiterung des hier zitierten deutschen § 2. Grenzfälle am Stichtag sind anhand des maßgeblichen nationalen Anwendungsrechts zu prüfen.

Gesicherte Lesetexte: [Bundestag](sources/review-bundestag-reform.md), [Richtlinie](sources/review-richtlinie-2024-2853.md). Die Zweitprüfung gibt keine vollständige Kommentierung des Reformrechts und keine umfassende Verkündungsrecherche aus.
