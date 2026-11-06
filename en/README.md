# Work After AI 2026, machine edition (English)

The Great Misconception About the AI Job Killer: The annual assessment of how artificial intelligence is transforming work. Version 1.3 of November 6, 2026.

This machine edition is the report in the form that language models and agents read: as plain text (Markdown) with stable identifiers and as data files (JSON). It contains the same text as the PDF edition, only without layout and without the figures, which stand in the text as placeholders. It is the English edition of the report; the German original has a machine edition of its own with the same identifiers, so WAAI-2026-K03 is key finding 3 in both languages.

## Files

- report.md: the full report as Markdown, with one anchor per chapter, key finding, prediction, external benchmark and source (for example report.md#WAAI-2026-K03) and the version history at the end.
- key-findings.json: the 11 key findings, each with identifier, title, text, cited source numbers and a citation template.
- predictions.json: the 9 predictions with target year, test criterion (field "test") and sources; they are graded publicly in the 2027 edition.
- benchmarks.json: the external benchmarks, that is dated predictions by others with source, target year, self-interest and status.
- sources.json: the list of sources with 205 entries, number, text and addresses. The numbers are stable within an edition; new sources are appended.
- chapters.json: the table of contents with identifiers, line ranges, word counts and the sources cited per chapter.
- index.json: metadata of the version (version, date, DOI, license, citation, checksums of all files, version history).
- llms.txt: short description for language models with pointers to the files.
- skill/work-after-ai-en: the skill for agents (SKILL.md plus references and data), also as a zip file next to it.

## Identifiers

Every statement has a fixed identifier: WAAI-2026-C05 is the chapter "Three forces", WAAI-2026-K03 the third key finding, WAAI-2026-P04 the fourth prediction, WAAI-2026-V02 the second external benchmark, WAAI-2026-Q017 source 17. Chapter identifiers are assigned once, since version 1.3, and stay: a new chapter receives the next free number regardless of its place in the text; the place is given in chapters.json as the position. Key findings and predictions carry the printed number of the respective version; when a key finding is added, the following numbers shift, and the mapping to the prior version is in index.json under "concordance" and in the section Concordance below. Source numbers are stable within the edition. The identifiers are identical in the German and the English edition; what has changed in substance is set out in the version history.

## Concordance to prior versions

Version 1.2: chapters C11 becomes C12; C12 becomes C13; C13 becomes C14; C14 becomes C15; C15 becomes C16; C16 becomes C17; C17 becomes C18; C18 becomes C19; C19 becomes C20. Key findings K07 becomes K08; K08 becomes K09; K09 becomes dropped; K10 becomes K11.

Version 1.3: chapters unchanged. Key findings unchanged.

## Citing

Recommended form: Kürner, Gerhard (2026): Work After AI 2026. The Great Misconception About the AI Job Killer. Work After AI, 2026 edition, version 1.3. Wels: Kuerner Group GmbH. DOI 10.5281/zenodo.22868155.

For a single statement: name the version, the identifier and the DOI, for example "version 1.3, key finding 3 (WAAI-2026-K03)". The work DOI 10.5281/zenodo.22868155 always resolves to the latest version; the DOI of this version is 10.5281/zenodo.23997629.

## Currency

The current version is at https://www.workafterai.org/p/work-after-ai-report-2026-en. Within an edition, versions appear at intervals of roughly one quarter, each with its own version number and DOI; predictions remain unchanged within an edition. Between versions, analyses appear on https://www.workafterai.org, each naming the key finding it touches. What exists and how to load it is described on the page "Der Report für Maschinen" (in German) at https://www.workafterai.org/p/der-report-fur-maschinen.

## License

The text of the report (report.md) is, like the PDF edition, licensed under Creative Commons Attribution 4.0 International (CC BY 4.0). For the structured data set (the JSON files) and the skill package: Free to use, quote and share with attribution (Gerhard Kürner, Work After AI, version and DOI). Commercial embedding of the data set or the skill package in third-party products, services or platforms requires an agreement with the publisher. Details in LICENSE.md.

## Contact and errors

Errors, missing sources and questions to gerhard@kuerner.at. Corrections appear with the next version and are listed in the version history.

---

## Deutsche Kurzfassung

Dies ist die Maschinenfassung der englischen Ausgabe von Work After AI 2026, dem jährlichen Report von Gerhard Kürner über künstliche Intelligenz und Arbeitswelt mit europäischem und DACH-Schwerpunkt. Sie enthält den vollständigen englischen Text als Markdown mit stabilen Kennungen (Kapitel C, Kernbefunde K, Prognosen P, Vergleichsmarken V, Quellen Q, Präfix WAAI-2026, gleich mit der deutschen Ausgabe), dazu JSON-Dateien für Kernbefunde, Prognosen, Vergleichsmarken, Quellen und Gliederung, eine index.json mit Metadaten und Prüfsummen, eine llms.txt und ein Skill-Paket für Agenten. Zitiert wird: Kürner, Gerhard (2026): Work After AI 2026. The Great Misconception About the AI Job Killer. Work After AI, 2026 edition, version 1.3. Wels: Kuerner Group GmbH. DOI 10.5281/zenodo.22868155.. Der Werk-DOI 10.5281/zenodo.22868155 zeigt immer auf die neueste Fassung. Der Text steht unter der Lizenz Creative Commons Attribution 4.0 International (CC BY 4.0); der Datenbestand und das Skill-Paket sind mit Namensnennung frei nutzbar, die gewerbliche Einbindung in Produkte oder Dienste Dritter bedarf einer Vereinbarung mit dem Herausgeber.
