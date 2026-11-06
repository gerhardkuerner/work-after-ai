# Work After AI 2026, Maschinenfassung

Der große Irrtum vom Jobkiller KI: Die jährliche Standortbestimmung zur Transformation der Arbeitswelt durch künstliche Intelligenz. Fassung 1.3 vom 6. November 2026.

Diese Maschinenfassung ist der Report in der Form, die Sprachmodelle und Agenten lesen: als reiner Text (Markdown) mit stabilen Kennungen und als Datendateien (JSON). Sie enthält denselben Text wie die PDF-Fassung, nur ohne Gestaltung und ohne die Abbildungen, die im Text als Platzhalter stehen.

## Dateien

- report.md: der vollständige Report als Markdown, mit einem Anker je Kapitel, Kernbefund, Prognose, Vergleichsmarke und Quelle (etwa report.md#WAAI-2026-K03) und dem Versionsverlauf am Ende.
- kernbefunde.json: die 11 Kernbefunde, je Eintrag Kennung, Titel, Text, zitierte Quellennummern und Zitatvorlage.
- prognosen.json: die 9 Prognosen mit Zieljahr, Messgröße (Feld „pruefung") und Quellen; sie werden in der Ausgabe 2027 öffentlich benotet.
- vergleichsmarken.json: die externen Vergleichsmarken, also fremde datierte Prognosen mit Absender, Zieljahr, Eigeninteresse und Stand.
- quellen.json: das Quellenverzeichnis mit 205 Einträgen, Nummer, Text und Adressen. Die Nummern sind innerhalb der Ausgabe stabil, neue Quellen werden angehängt.
- kapitel.json: die Gliederung mit Kennungen, Zeilenbereichen, Wortzahl und den je Kapitel zitierten Quellen.
- index.json: Metadaten der Fassung (Version, Datum, DOI, Lizenz, Zitierempfehlung, Prüfsummen aller Dateien, Versionsverlauf).
- llms.txt: Kurzbeschreibung für Sprachmodelle mit Verweisen auf die Dateien.
- skill/work-after-ai: der Skill für Agenten (SKILL.md plus Beilagen), auch als Zip-Datei daneben.

## Kennungen

Jede Aussage hat eine feste Kennung: WAAI-2026-C05 ist das Kapitel „Drei Kräfte", WAAI-2026-K03 der dritte Kernbefund, WAAI-2026-P04 die vierte Prognose, WAAI-2026-V02 die zweite Vergleichsmarke, WAAI-2026-Q017 die Quelle 17. Kapitelkennungen sind seit der Fassung 1.3 einmal vergeben und bleiben: Ein neues Kapitel bekommt die nächste freie Nummer, unabhängig von seiner Stelle im Text; die Stelle steht in kapitel.json als Position. Kernbefunde und Prognosen tragen die gedruckte Nummer der jeweiligen Fassung; wenn ein Kernbefund hinzukommt, verschieben sich die folgenden Nummern, und die Zuordnung zur Vorfassung steht in index.json unter „konkordanz" und im Abschnitt Konkordanz unten. Quellennummern sind innerhalb der Ausgabe stabil. Was sich inhaltlich geändert hat, steht im Versionsverlauf.

## Konkordanz zu den Vorfassungen

Fassung 1.2: Kapitel C11 wird C12; C12 wird C13; C13 wird C14; C14 wird C15; C15 wird C16; C16 wird C17; C17 wird C18; C18 wird C19; C19 wird C20. Kernbefunde K07 wird K08; K08 wird K09; K09 wird entfällt; K10 wird K11.

Fassung 1.3: Kapitel unverändert. Kernbefunde unverändert.

## Zitieren

Empfohlene Form: Kürner, Gerhard (2026): Work After AI 2026. Der große Irrtum vom Jobkiller KI. Work After AI, Ausgabe 2026, Fassung 1.3. Wels: Kuerner Group GmbH. DOI 10.5281/zenodo.22862384.

Für eine einzelne Aussage: Fassung, Kennung und DOI nennen, etwa „Fassung 1.3, Kernbefund 3 (WAAI-2026-K03)". Der Werk-DOI 10.5281/zenodo.22862384 zeigt immer auf die neueste Fassung; der DOI dieser Fassung ist 10.5281/zenodo.23997620.

## Aktualität

Die jeweils aktuelle Fassung liegt unter https://www.workafterai.org/p/report-2026-als-pdf. Innerhalb einer Ausgabe erscheinen Fassungen im Abstand von etwa einem Quartal, jede mit eigener Versionsnummer und eigenem DOI; Prognosen bleiben innerhalb einer Ausgabe unverändert. Zwischen den Fassungen erscheinen Analysen auf https://www.workafterai.org, die jeweils den Kernbefund nennen, den sie berühren.

## Lizenz

Der Text des Reports (report.md) steht wie die PDF-Fassung unter der Lizenz Creative Commons Namensnennung 4.0 International (CC BY 4.0). Für den strukturierten Datenbestand (die JSON-Dateien) und das Skill-Paket gilt: Frei für Nutzung, Zitat und Weitergabe mit Namensnennung (Gerhard Kürner, Work After AI, Fassung und DOI). Die gewerbliche Einbindung des Datenbestands oder des Skill-Pakets in Produkte, Dienste oder Plattformen Dritter bedarf einer Vereinbarung mit dem Herausgeber. Einzelheiten in LICENSE.md.

## Kontakt und Fehler

Fehler, fehlende Quellen und Rückfragen an gerhard@kuerner.at. Berichtigungen erscheinen mit der nächsten Fassung und werden im Versionsverlauf ausgewiesen.

---

## English summary

This is the machine-readable edition of Work After AI 2026, the annual report by Gerhard Kürner on how artificial intelligence changes work, with a European and DACH focus. It contains the full text as Markdown with stable anchors (chapters C, key findings K, forecasts P, external benchmarks V, sources Q, prefix WAAI-2026), plus JSON files for key findings, forecasts, external benchmarks, sources and the table of contents, an index.json with metadata and checksums, an llms.txt, and an agent skill package. Cite as: Kürner, Gerhard (2026): Work After AI 2026. Der große Irrtum vom Jobkiller KI. Work After AI, Ausgabe 2026, Fassung 1.3. Wels: Kuerner Group GmbH. DOI 10.5281/zenodo.22862384.. The work DOI 10.5281/zenodo.22862384 always resolves to the latest version. The text is licensed under Creative Commons Namensnennung 4.0 International (CC BY 4.0); the structured data and the skill package are free to use with attribution, while commercial embedding in third-party products or services requires an agreement with the publisher.
