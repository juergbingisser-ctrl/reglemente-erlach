Reglemente und Grundlagen der Einwohnergemeinde Erlach
Zweck
Dieses Repository enthält Reglemente, Verordnungen, Konzepte, Merkblätter und weitere Grundlagen der Einwohnergemeinde Erlach in einem strukturierten und maschinenlesbaren Format.
Die Dokumente werden primär als Markdown-Dateien geführt, um:
•	eine langfristige Archivierung sicherzustellen
•	die Durchsuchbarkeit zu verbessern
•	eine einfache Versionierung über Git zu ermöglichen
•	die Nutzung durch Large Language Models (LLMs) und Retrieval-Augmented Generation (RAG) Systeme zu unterstützen
•	rechtliche und organisatorische Zusammenhänge transparent darzustellen
________________________________________
Struktur des Repositories
reglemente-erlach/
│
├── README.md
├── references/
├── metadata/
├── 01_organisation/
├── 02_finanzen/
├── 03_bildung/
├── 04_infrastruktur_umwelt/
├── 05_sicherheit/
└── 06_soziales/
Ordnerstruktur
Ordner	Inhalt
01_organisation	Gemeindeordnung, Organisationsvorschriften, Verwaltungsorganisation
02_finanzen	Gebührenreglemente, Finanzreglemente, Spezialfinanzierungen
03_bildung	Schulreglemente und schulbezogene Dokumente
04_infrastruktur_umwelt	Wasser, Abwasser, Energie, Entsorgung, Umwelt
05_sicherheit	Feuerwehr, Bevölkerungsschutz und Sicherheit
06_soziales	Soziale Aufgaben, Kultur und Gesellschaft
references	Übergeordnete Gesetze, Verordnungen und Fachgrundlagen
metadata	Dokumenten- und Beziehungsinformationen
________________________________________
Dokumentenprinzipien
Originaltreue
Die Inhalte der Reglemente werden möglichst wortgetreu aus den rechtsgültigen Dokumenten übernommen.
Offensichtliche OCR-Fehler oder technische Formatierungsfehler können korrigiert werden. Inhaltliche Änderungen werden nicht vorgenommen.
Markdown als Primärformat
Alle Dokumente werden in Markdown gespeichert.
Vorteile:
•	menschenlesbar
•	git-freundlich
•	einfach versionierbar
•	optimal für Wissensmanagement und KI-Systeme
Metadaten
Jedes Dokument sollte einen YAML Front Matter Block enthalten.
Beispiel:
---
title: Wasserversorgungsreglement
doc_id: wasserversorgungsreglement
category: reglement
legal_level: gemeinde
status: gültig
version: 1.0
---
________________________________________
Referenzen
Übergeordnete Gesetze, Verordnungen und Fachgrundlagen werden zentral in:
references/references.md
geführt.
Beispiele:
•	Gemeindegesetz des Kantons Bern (GG)
•	Gemeindeverordnung (GV)
•	Wasserversorgungsgesetz (WVG)
•	Wasserversorgungsverordnung (WVV)
•	Gewässerschutzgesetz (KGSchG)
•	Gewässerschutzverordnung (KGV)
•	SVGW-Richtlinien
•	VSA-Richtlinien
________________________________________
Beziehungen zwischen Dokumenten
Reglemente stehen häufig in Beziehung zueinander.
Beispiele:
•	Gebührenreglement ↔ Wasserversorgungsreglement
•	Wasserversorgungsreglement ↔ Wasserversorgungsgesetz
•	Abwasserreglement ↔ Gewässerschutzgesetz
•	Gemeindeordnung ↔ Gemeindegesetz
Diese Beziehungen können künftig in strukturierten Metadatendateien dokumentiert werden.
________________________________________
Nutzung durch KI-Systeme
Das Repository ist so aufgebaut, dass es von LLMs und RAG-Systemen verarbeitet werden kann.
Empfohlene Struktur innerhalb der Dokumente:
•	klare Kapitelstruktur
•	eindeutige Artikelüberschriften
•	konsistente Terminologie
•	maschinenlesbare Metadaten
•	standardisierte Referenzen
Beispiel:
## Art. 5 Gebühren

Die Gebühren werden gemäss den Vorgaben des Wasserversorgungsgesetzes erhoben.
________________________________________
Quellen
Die rechtsgültigen Originaldokumente werden von der Einwohnergemeinde Erlach oder den zuständigen kantonalen und eidgenössischen Stellen veröffentlicht.
Dieses Repository dient der strukturierten Aufbereitung und ersetzt keine amtliche Publikation.
________________________________________
Langfristige Ziele
•	Aufbau einer konsistenten Wissensbasis der Gemeinde Erlach
•	Verbesserung der Durchsuchbarkeit und Nachvollziehbarkeit von Reglementen
•	Unterstützung zukünftiger KI-gestützter Such- und Auskunftssysteme
•	Dokumentation von rechtlichen und organisatorischen Zusammenhängen
•	Aufbau eines Knowledge Graphen für kommunale Dokumente
________________________________________
Lizenz
Sofern nicht anders vermerkt, stammen die Inhalte aus öffentlich zugänglichen Dokumenten der Einwohnergemeinde Erlach oder aus öffentlich publizierten kantonalen und eidgenössischen Rechtsgrundlagen.
