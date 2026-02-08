# GitHub Copilot Anweisungen - Vermögensstrukturen Dokumentation

## Projektübersicht

Dieses Repository enthält umfassende Dokumentation zum **Vergleich verschiedener Rechtsformen** für Vermögensverwaltung
mit Wertpapieren (Aktien, ETFs) in Deutschland. Die Dokumentation vergleicht Privatvermögen, Unternehmergesellschaft
(UG) und Familienstiftung und ist rechtskonform sowie steuerkonform gestaltet.

## Dokumentstruktur

- **README.md**: Übersicht über das Projekt, Navigation und Kernerkenntnisse
- **gruendung.md**: **Vergleich** der Gründung bei Privatvermögen, UG und Familienstiftung
- **betrieb.md**: **Vergleich** des laufenden Betriebs bei Aktienkauf/-verkauf für alle drei Formen
- **vermoegensverwaltende-ug.md**: Detailanalyse speziell für UG
- **familienstiftung.md**: Detailanalyse speziell für Familienstiftung

## Dokumentationsansatz

**Kernprinzip:** Immer eine **Gegenüberstellung der verschiedenen Rechtsformen** (Privatvermögen, UG, Familienstiftung)
vornehmen.

- Vergleichstabellen verwenden für direkte Gegenüberstellung
- Konkrete Zahlenbeispiele für jede Rechtsform
- Klare Empfehlungen: "Für wen eignet sich was?"
- Fokus auf Wertpapiergeschäfte (Aktienkauf/-verkauf)

## Code-Konventionen für Copilot

### Markdown-Stil

- **Überschriften**: Deutsche Bezeichnungen, klare Hierarchie (H1 für Haupttitel, H2 für Hauptkapitel, H3 für
Unterkapitel)
- **Listen**: Aufzählungen für einfache Listen, nummerierte Listen für Schritt-für-Schritt-Anleitungen
  - **WICHTIG**: Listen müssen immer von Leerzeilen umgeben sein (vor und nach der Liste)
  - Nummerierte Listen müssen korrekt durchnummeriert sein (1, 2, 3, nicht 1, 2, 3 oder 1, 1, 1)
  - Beispiel:

    ```markdown
    Text vor der Liste.

    - Listenpunkt 1
    - Listenpunkt 2

    Text nach der Liste.

    ```

- **Tabellen**: Für strukturierte Daten wie Kosten, Zeitpläne, Fristen
- **Checklisten**: Mit `- [ ]` für To-Do-Listen
- **Code-Blöcke (Fenced Code Blocks)**:
  - **WICHTIG**: Opening fence MUSS IMMER eine Sprache angeben (z.B. ` ```text `, ` ```bash `)
  - **WICHTIG**: Closing fence MUSS IMMER ohne Sprache sein (nur ` ``` `, NICHT ` ```text `)
  - **WICHTIG**: Müssen IMMER von Leerzeilen umgeben sein (vor und nach dem Block)
  - Verwende immer die passende Sprache: `text` für Berechnungen/Zahlen, `bash` für Befehle
- **Hervorhebungen**:
  - **Fett** für wichtige Begriffe und Beträge
  - *Kursiv* für Betonungen (sparsam verwenden)
  - `Code` für Formeln, Beispiele, technische Begriffe

### Sprache und Terminologie

- **Sprache**: Deutsch (DE)
- **Fachbegriffe**:
  - UG = Unternehmergesellschaft (haftungsbeschränkt)
  - GmbH = Gesellschaft mit beschränkter Haftung
  - HGB = Handelsgesetzbuch
  - GmbHG = GmbH-Gesetz
  - IHK = Industrie- und Handelskammer
  - HWK = Handwerkskammer
- **Ton**: Professionell, sachlich, informativ
- **Zielgruppe**: Gründer und Unternehmer mit unterschiedlichen Vorkenntnissen

### Inhaltliche Richtlinien

#### Rechtliche Aspekte

- Alle Angaben müssen auf aktuellen deutschen Gesetzen basieren
- Verweise auf relevante Paragraphen (z.B. § 43 GmbHG)
- Klare Unterscheidung zwischen Pflicht und Option
- Haftungsausschluss am Ende jedes Dokuments

#### Steuerliche Aspekte

- Aktuelle Steuersätze angeben
- Fristen und Termine präzise benennen
- Unterscheidung zwischen verschiedenen Steuerarten
- Hinweis auf Steuerberater bei komplexen Fragen

#### Praktische Informationen

- Konkrete Kostenangaben mit Spannen (z.B. ca. 100-300 Euro)
- Zeitangaben realistisch einschätzen
- Checklisten für Umsetzung bereitstellen
- Links zu offiziellen Quellen

### Wartung und Aktualisierung

#### Wenn Copilot Änderungen vorschlägt

1. **Rechtliche Änderungen**:
   - Überprüfe immer die Aktualität von Gesetzen und Verordnungen
   - Verweise auf offizielle Quellen (Gesetze-im-Internet, Bundesanzeiger)
   - Aktualisiere betroffene Paragraphen und Beträge

2. **Steuerliche Änderungen**:
   - Steuersätze ändern sich regelmäßig
   - Freibeträge werden angepasst
   - Fristen können sich ändern
   - Prüfe jährlich auf Aktualisierungen

3. **Kostenangaben**:
   - Überprüfe Gebühren für Notare, Handelsregister, Gewerbeamt
   - Passe Kostenspannen an Inflation an
   - Aktualisiere Beispielrechnungen

4. **Verweise und Links**:
   - Überprüfe alle externen Links auf Funktionsfähigkeit
   - Aktualisiere veraltete URLs
   - Ergänze neue relevante Ressourcen

#### Konsistenz zwischen Dokumenten

- **Vergleichsstruktur** in gruendung.md und betrieb.md beibehalten
- Cross-Referenzen zwischen Vergleichsdokumenten und Detailanalysen pflegen
- Terminologie durchgehend einheitlich verwenden
- Verlinkungen zwischen Dokumenten aktuell halten
- README.md als zentrale Navigation mit Kernerkenntnissen nutzen
- Vergleichstabellen konsistent formatieren
- Immer alle drei Rechtsformen berücksichtigen (Privatvermögen, UG, Familienstiftung)

### Struktur neuer Abschnitte

Wenn neue Inhalte hinzugefügt werden:

```markdown
## Hauptüberschrift

### Unterkapitel

Einführungstext mit Kontext

#### Detailaspekt

- Aufzählungspunkt 1
- Aufzählungspunkt 2

#### Beispiel oder Checkliste

- [ ] Punkt 1
- [ ] Punkt 2

#### Wichtige Hinweise

**Wichtig:** Hervorgehobene Information

### Weiterführende Informationen

Verweise auf andere Abschnitte oder externe Ressourcen

```text

### Qualitätssicherung

- **Rechtschreibung**: Deutsche Rechtschreibung (neue Rechtschreibung)
- **Grammatik**: Vollständige Sätze, klare Struktur
- **Faktencheck**: Alle Zahlen, Fristen und Beträge überprüfen
- **Lesbarkeit**: Absätze nicht zu lang, klare Gliederung
- **Verlinkungen**: Interne und externe Links testen
- **Markdown-Linting**: Alle Markdown-Dateien müssen den Linting-Regeln entsprechen
  - **WICHTIG**: Nach JEDER Änderung an Markdown-Dateien MUSS das Linting durchlaufen und bestanden werden
  - Prüfung vor dem Commit: `npx markdownlint-cli2 "**/*.md"`
  - Automatische Prüfung durch GitHub Actions CI-Workflow bei jedem Push und Pull Request
  - Linting-Tool: markdownlint-cli2
  - Konfiguration: `.markdownlint.json` im Repository-Root
  - **Wichtige Regeln:**
    - **MD026**: Keine Satzzeichen am Ende von Überschriften (z.B. kein `:` am Ende)
    - **MD032**: Listen müssen von Leerzeilen umgeben sein (davor und danach)
    - **MD029**: Nummerierte Listen müssen korrekt durchnummeriert sein (1, 2, 3...)
    - **MD013**: Zeilen dürfen maximal 120 Zeichen lang sein (außer in Code-Blöcken und Tabellen)
    - **Code-Blöcke (Fenced Code Blocks):**
      - **WICHTIG**: Opening fence MUSS IMMER eine Sprache angeben (z.B. ` ```text `, ` ```bash `, ` ```python `)
      - **WICHTIG**: Closing fence MUSS IMMER ohne Sprache sein (nur ` ``` `, NICHT ` ```text ` oder ` ```bash `)
      - **WICHTIG**: Müssen IMMER von Leerzeilen umgeben sein (eine Leerzeile vor und nach dem Block)
      - Verwende die passende Sprache: `text` für Berechnungen/Zahlen, `bash` für Kommandozeile
  - Lokale Prüfung: `npx markdownlint-cli2 "**/*.md"`
  - Automatische Korrekturen: `npx markdownlint-cli2 --fix "**/*.md"`
  - **Bei Linting-Fehlern**: Änderungen dürfen NICHT committed werden, bis alle Fehler behoben sind

### Erweiterungen

Bei Erweiterung der Dokumentation folgende Themen priorisieren:

1. **FAQ-Bereich**: Häufig gestellte Fragen
2. **Fallbeispiele**: Konkrete Szenarien mit Lösungen
3. **Vorlagen**: Muster für Verträge, Protokolle (nur Hinweise, keine vollständigen Dokumente)
4. **Glossar**: Fachbegriffe erklärt
5. **Weiterführende Ressourcen**: Bücher, Webseiten, Beratungsstellen

## Arbeiten mit GitHub Copilot

### Nützliche Prompts für dieses Projekt

- "Aktualisiere die Steuersätze für das Jahr [Jahr]"
- "Füge einen Abschnitt über [Thema] in [Dokument] hinzu"
- "Erstelle eine Checkliste für [Prozess]"
- "Überprüfe die Konsistenz der Terminologie in allen Dokumenten"
- "Füge einen Beispielfall für [Situation] hinzu"

### Kontext für Copilot

Wenn Copilot Vorschläge macht, berücksichtige:

- Deutsche Rechtslage (nicht andere Länder)
- Spezifika der UG (nicht allgemeine GmbH)
- Aktuelle Gesetzgebung (Stand 2024/2025)
- Zielgruppe: Gründer ohne Vorkenntnisse bis erfahrene Unternehmer

## Technische Anforderungen

- **Markdown-Version**: CommonMark/GitHub Flavored Markdown
- **Encoding**: UTF-8
- **Zeilenlänge**: Max. 120 Zeichen pro Zeile (für bessere Lesbarkeit im Editor)
- **Links**: Relative Links für interne Verweise, absolute für externe
- **CI/CD**: GitHub Actions Workflow für Markdown-Linting
  - Workflow-Datei: `.github/workflows/markdown-lint.yml`
  - Läuft bei jedem Push auf `main` Branch und bei allen Pull Requests
  - Verwendet: DavidAnson/markdownlint-cli2-action@v16
  - **WICHTIG**: Alle Markdown-Änderungen MÜSSEN lokal geprüft werden, BEVOR sie committed werden
  - Lokaler Test: `npx markdownlint-cli2 "**/*.md"`
- **Markdown-Linting-Regeln**: Siehe `.markdownlint.json`
  - Alle Standard-Regeln aktiviert mit wenigen Ausnahmen
  - **MD026**: Keine Satzzeichen am Ende von Überschriften (z.B. kein `:` am Ende)
  - **MD032**: Listen müssen von Leerzeilen umgeben sein
  - **MD029**: Nummerierte Listen korrekt durchnummerieren
  - **MD013**: Zeilenlänge max. 120 Zeichen (außer in Code-Blöcken und Tabellen)
  - Code-Blöcke benötigen Sprachbezeichnung
  - Leerzeilen um Code-Blöcke erforderlich
  - **Workflow**: IMMER zuerst lokal testen, dann committen

## Best Practices

1. **Aktualität wahren**: Regelmäßige Überprüfung (mindestens jährlich)
2. **Quellen angeben**: Links zu Gesetzen und Behörden
3. **Verständlichkeit**: Fachsprache erklären, Beispiele nutzen
4. **Vollständigkeit**: Alle relevanten Aspekte abdecken
5. **Praktikabilität**: Umsetzbare Anleitungen und Checklisten

## Haftungshinweis bei Änderungen

Jede Änderung sollte sicherstellen, dass der Haftungsausschluss am Ende der Dokumente erhalten bleibt und aktuell ist.
Die Dokumentation dient der Information und ersetzt keine professionelle Beratung.
