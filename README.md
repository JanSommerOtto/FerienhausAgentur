# FerienhausAgentur

Arbeitsbereich für die Vermarktung und Verwaltung von Ferienhäusern und Ferienwohnungen: Objektbeschreibungen, Marketing-Kampagnen, Gästekommunikation und Auswertungen an einem Ort.

> **Hinweis:** Diese README ist ein Beispiel. Ersetze die Platzhalter in `<spitzen Klammern>` durch eure echten Angaben.

## Inhalt

- [Überblick](#überblick)
- [Ordnerstruktur](#ordnerstruktur)
- [Erste Schritte](#erste-schritte)
- [Arbeitsabläufe](#arbeitsabläufe)
- [Konventionen](#konventionen)
- [Kontakt](#kontakt)

## Überblick

| Bereich            | Beschreibung                                                        |
| ------------------ | ------------------------------------------------------------------- |
| **Objekte**        | Stammdaten, Beschreibungstexte und Fotos aller Ferienunterkünfte    |
| **Marketing**      | Anzeigen (Google, Meta), Social-Media-Posts, Newsletter             |
| **Gäste**          | Vorlagen für Buchungsbestätigung, Anreiseinfos, Bewertungsanfragen  |
| **Auswertungen**   | Belegung, Umsatz, Kampagnen-Performance                             |

## Ordnerstruktur

```
FerienhausAgentur/
├── objekte/
│   └── <objektname>/
│       ├── steckbrief.md        # Lage, Größe, Ausstattung, Preise
│       ├── beschreibung.md      # Texte für Portale und Website
│       └── fotos/
├── marketing/
│   ├── kampagnen/               # Anzeigentexte und Kampagnenpläne
│   ├── social-media/            # Redaktionsplan und Posts
│   └── newsletter/
├── gaeste/
│   └── vorlagen/                # E-Mail-Vorlagen für die Gästekommunikation
├── auswertungen/                # Monats- und Saisonberichte
└── README.md
```

## Erste Schritte

1. Repository klonen:
   ```bash
   git clone <repo-url>
   cd FerienhausAgentur
   ```
2. Für ein neues Objekt den Ordner `objekte/_vorlage/` kopieren und umbenennen.
3. `steckbrief.md` ausfüllen. Daraus werden später Beschreibungstexte und Anzeigen erstellt.

## Arbeitsabläufe

### Neues Objekt aufnehmen

1. Steckbrief anlegen (siehe oben)
2. Fotos in `fotos/` ablegen, sprechend benennen (z. B. `wohnzimmer-01.jpg`)
3. Beschreibungstexte für Website und Buchungsportale erstellen
4. Objekt in den Kampagnenplan aufnehmen

### Saisonkampagne starten

1. Zielzeitraum und Budget in `marketing/kampagnen/<saison>.md` festlegen
2. Anzeigentexte erstellen und freigeben lassen
3. Kampagnen pausiert anlegen und erst nach Freigabe aktivieren
4. Nach 2 Wochen Performance prüfen und in `auswertungen/` dokumentieren

## Konventionen

- **Sprache:** Deutsch, Gäste werden gesiezt
- **Dateinamen:** Kleinbuchstaben, Bindestriche statt Leerzeichen, keine Umlaute (`ferienhaus-am-wasser.md`)
- **Preise:** immer inkl. MwSt. und mit Angabe, ob die Endreinigung enthalten ist
- **Commits:** kurze, beschreibende Nachricht, z. B. `Objekt "Haus Möwe" angelegt`

## Kontakt

<Agenturname>
<Straße Hausnummer>, <PLZ Ort>
E-Mail: <kontakt@beispiel.de>
Web: <https://www.beispiel.de>
