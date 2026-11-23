---
title: "Curriculum für Certified Professional for Software Architecture (CPSA)® Advanced Level SWARC4AI – Softwarearchitektur für KI-Systeme"
publisher: "iSAQB e. V."
language: "de"
version: "2026.1-rev0"
date: "2026-11-23"
pdf: "curriculum-swarc4ai-de.pdf"
license: "Die Nutzung unterliegt den Bedingungen im Abschnitt 'Lizenz und Copyright'."
generated: "Aus den AsciiDoc-Quellen des Lehrplans generiert. Inhaltlich identisch mit der PDF- und HTML-Version."
---

# Curriculum für Certified Professional for Software Architecture (CPSA)® Advanced Level **SWARC4AI** *– Softwarearchitektur für KI-Systeme*

## Lizenz und Copyright

**© (Copyright), International Software Architecture Qualification Board e. V. (iSAQB® e. V.) 2026**

Die Nutzung des Lehrplans ist nur unter den nachfolgenden Voraussetzungen erlaubt:

1. Sie möchten das Zertifikat zum CPSA Certified Professional for Software Architecture Foundation Level® oder CPSA Certified Professional for Software Architecture Advanced Level® erwerben. Für den Erwerb des Zertifikats ist es gestattet, die Text-Dokumente und/oder Lehrpläne zu nutzen, indem eine Arbeitskopie für den eigenen Rechner erstellt wird. Soll eine darüber hinausgehende Nutzung der Dokumente und/oder Lehrpläne erfolgen, zum Beispiel zur Weiterverbreitung an Dritte, Werbung etc., bitte unter [info@isaqb.org](mailto:info@isaqb.org) nachfragen. Es müsste dann ein eigener Lizenzvertrag geschlossen werden.
2. Sind Sie Trainer oder Trainingsprovider, ist die Nutzung der Dokumente und/oder Lehrpläne nach Erwerb einer Nutzungslizenz möglich. Hierzu bitte unter [info@isaqb.org](mailto:info@isaqb.org) nachfragen. Lizenzverträge, die alles umfassend regeln, sind vorhanden.
3. Falls Sie weder unter die Kategorie 1. noch unter die Kategorie 2. fallen, aber dennoch die Dokumente und/oder Lehrpläne nutzen möchten, nehmen Sie bitte ebenfalls Kontakt unter [info@isaqb.org](mailto:info@isaqb.org) zum iSAQB e. V. auf. Sie werden dort über die Möglichkeit des Erwerbs entsprechender Lizenzen im Rahmen der vorhandenen Lizenzverträge informiert und können die gewünschten Nutzungsgenehmigungen erhalten.

> **Wichtiger Hinweis**
>
> **Grundsätzlich weisen wir darauf hin, dass dieser Lehrplan urheberrechtlich geschützt ist. Alle Rechte an diesen Copyrights stehen ausschließlich dem International Software Architecture Qualification Board e. V. (iSAQB® e. V.) zu.**

Die Abkürzung "e. V." ist Teil des offiziellen Namens des iSAQB und steht für "eingetragener Verein", der seinen Status als juristische Person nach deutschem Recht beschreibt. Der Einfachheit halber wird iSAQB e. V. im Folgenden ohne die Verwendung dieser Abkürzung als iSAQB bezeichnet.

## Lernziele im Überblick

- LZ 1-1: Künstliche Intelligenz und Machine Learning, Data Science, Deep Learning, Generative KI einordnen können
- LZ 1-2: KI-Anwendungsfälle identifizieren, fachlich einordnen, priorisieren und bewerten
- LZ 1-3: Stärken, Grenzen und typische Risiken von KI einordnen
- LZ 1-4: Unterschiede zwischen KI-Systemen und traditioneller Software verstehen, erklären und die geeignete Lösungsart entscheiden
- LZ 1-5: Rollen und deren Aufgaben sowie ihre Zusammenarbeit im Kontext von KI kennen
- LZ 1-6 [OPTIONAL]: Das Konzept der Productivity J-Curve erläutern und seine Bedeutung für die Einführung von KI in Organisationen einordnen
- LZ 2-1: Einfluss der Datenschutzgesetze auf die Implementierung und Nutzung von KI kennen
- LZ 2-2: Die Anforderungen des EU AI Act analysieren und daraus architekturrelevante Maßnahmen für Datenflüsse, Logging, technische Dokumentation, Human Oversight, Robustheit und Deployment ableiten.
- LZ 2-3: Klassifikation von KI-Systemen nach EU AI Act Risikolevel durchführen
- LZ 2-4: Urheberrecht, Offenheitsgrade und Lizenzbedingungen von KI-Modellen und KI-generierten Inhalten bewerten
- LZ 2-5: Strategien zur Einhaltung regulatorischer Anforderungen bewerten und geeignete Nachweis- und Dokumentationsartefakte für Modelle, Datensätze und Betriebsprozesse festlegen
- LZ 2-6: Fallstricke hinsichtlich Security sowie Angriffsarten auf ML-Modelle kennen und geeignete Sicherheitsmaßnahmen gegen Angriffe auf KI-Systeme auswählen
- LZ 2-7: Strategien zur KI-Risikominimierung kennen und anwenden
- LZ 2-8: Grundproblematik und Facetten von AI-Safety verstehen
- LZ 2-9: Ethikleitlinien und Prinzipien von AI Governance in Organisations-, Entwicklungs- und Architekturentscheidungen übersetzen
- LZ 3-1: Life-Cycle eines Machine-Learning- bzw. Data-Science-Projekts verstehen
- LZ 3-2: Datenarten und Anforderungen an Daten sowie typische ML-Problemstellungen und deren Anforderungen verstehen
- LZ 3-3: Geeignete Architektur- und Design-Patterns für KI-Systeme auswählen, gegeneinander abwägen und anhand von Qualitätsanforderungen begründen.
- LZ 3-4: Metriken zur Messung der Performance von ML-Modellen kennen
- LZ 3-5: KI-Komponenten über geeignete Integrationsmuster, Schnittstellen und Entkopplungsmechanismen in bestehende Systeme und Domänenarchitekturen integrieren.
- LZ 3-6: Benutzerinteraktionen für KI-Systeme so gestalten, dass Unsicherheit, Erklärbarkeit, Freigaben und Human-in-the-Loop angemessen berücksichtigt werden.
- LZ 3-7: Leistung und Skalierbarkeit von KI-Systemen analysieren und gestalten
- LZ 3-8: Robustheit in KI-Systemen verstehen und Strategien zur Erhöhung der Robustheit anwenden
- LZ 3-9: Zuverlässigkeit und Verfügbarkeit von KI-Systemen einordnen
- LZ 3-10: Maßnahmen für Reproduzierbarkeit, Auditierbarkeit und Nachvollziehbarkeit von Modellen, Datenständen, Prompts, Konfigurationen und Ergebnissen festlegen.
- LZ 3-11: Erklärbarkeit und Interpretierbarkeit in KI-Systemen einordnen
- LZ 3-12: Fehlertoleranz in KI-Systemen erläutern
- LZ 3-13: Architekturentscheidungen für KI-Systeme dokumentieren.
- LZ 4-1: Daten akquirieren und labeln
- LZ 4-2: Quellen und Eignung öffentlich verfügbarer Datensätze hinsichtlich Qualität, Lizenz, Repräsentativität und Risiken bewerten.
- LZ 4-3: Datenpipelines und Datenarchitekturen für KI-Systeme so entwerfen, dass Qualität, Nachvollziehbarkeit, Skalierbarkeit, Governance und Wiederverwendbarkeit unterstützt werden.
- LZ 4-4: Strategien für Datenaggregation, -bereinigung, -transformation, -anreicherung und -augmentierung kennen
- LZ 4-5: Möglichkeiten zur Speicherung der Daten kennen
- LZ 4-6: Data Products, Data Contracts und Verantwortlichkeiten in Datenarchitekturen für KI-Systeme einordnen und für robuste Schnittstellen zwischen Fachlichkeit, Datenplattform und KI-Komponenten nutzen.
- LZ 5-1: (Hardware)-Anforderungen an Training und Inferenz kennen
- LZ 5-2: Trade-Offs verschiedener Modellarchitekturen bezüglich der Qualitätsmerkmale kennen
- LZ 5-3: Verschiedene Qualitätsmerkmale eines ML-Modells abstimmen
- LZ 5-4: Kosten, Stromverbrauch und nachhaltige Nutzung von KI (Green IT) verstehen
- LZ 5-5: MLOps für die Automatisierung des Life-Cycles eines Data-Science-Projekts überblicken
- LZ 5-6: Modelltraining, Parameter, Metriken und Ergebnisse tracken
- LZ 5-7: Modellevaluation, Systemevaluation und fachliche Nutzenbewertung unterscheiden und geeignete Evaluationsansätze für KI-Systeme auswählen.
- LZ 5-8: Arten von Drift sowie mögliche Ursachen und Lösungsansätze dafür kennen
- LZ 5-9: CI/CD-Pipelines, Modellmanagement und Deployment-Strategien für KI-Modelle überblicken
- LZ 5-10: Vor- und Nachteile von SaaS und Self-Hosting nennen sowie Make-or-Buy-Entscheidungen anhand von Qualitätsanforderungen treffen
- LZ 5-11: Monitoring und Observability für KI-Systeme konzipieren, insbesondere für Drift, Qualitätsverlust, Kosten, Latenz, Sicherheitsereignisse und Governance-relevante Nachweise.
- LZ 5-12: Nutzer-Feedback sowie Methoden und Werkzeuge zur Sammlung von Nutzer-Feedback verstehen
- LZ 5-13: [OPTIONAL] Klassen von MLOps-Werkzeugen und Plattformen sowie wesentliche Auswahlkriterien für ihren Einsatz kennen.
- LZ 6-1: Integrationsebenen von KI überblicken
- LZ 6-2: KI-Systeme in die Gesamtarchitektur einer IT-Landschaft integrieren
- LZ 6-3: Generative KI und ihre Funktionsweise grundlegend verstehen
- LZ 6-4: Architekturmuster für den Einsatz von LLMs kennen und deren Einsatzgrenzen, Risiken und Trade-offs bewerten, insbesondere bei RAG, Function Calling, Fine-Tuning, Assistenzsystemen und Agenten.
- LZ 6-5: Use-Cases für RAG (Retrieval-Augmented Generation) sowie ausgewählte RAG-Techniken kennen und verstehen
- LZ 6-6: Arten von Prompt Engineering kennen
- LZ 6-7: Agentic Workflows hinsichtlich Planung, Werkzeugnutzung, Reflexion, Zustandsmanagement, Kontrollmechanismen und Multi-Agenten-Kollaboration analysieren und architektonisch einordnen.
- LZ 6-8: Eine Auswahl von Design Patterns für Generative KI-Systeme kennen
- LZ 6-9: Techniken zur Evaluation von LLM-Anwendungen auswählen und auf Antwortqualität, Retrieval-Qualität, Halluzinationen, Sicherheit, Kosten und Nutzermehrwert anwenden.
- LZ 6-10: Bekannte LLMs und Auswahlkriterien überblicken
- LZ 6-11: Bedeutung von Cost Management für GenAI Applikationen verstehen
- LZ 6-12: Klassen von Bibliotheken, Schnittstellen und Werkzeugen für LLM-Anwendungen sowie deren Einsatzkontexte und Auswahlkriterien kennen.
- LZ 6-13: [OPTIONAL] Agentic-AI-Architekturen, zentrale Architekturkomponenten, Sicherheits- und Governance-Grenzen sowie typische Einsatzmuster und Grenzen von Agentensystemen kennen und bewerten.
- LZ 6-14: Agenten-Laufzeitsysteme für LLM- und Agentensysteme architektonisch einordnen und anwenden
- LZ 7-1: Anhand einer durchgehenden Fallstudie oder eines Praxisprojekts Architekturentscheidungen für ein KI-System treffen, dokumentieren, begründen und im Hinblick auf Qualität, Compliance, Betrieb und Integration bewerten.

## Einführung: Allgemeines zum iSAQB Advanced Level

### Was vermittelt ein Advanced Level Modul?

Das Modul kann unabhängig von einer CPSA-F-Zertifizierung besucht werden.

- Der iSAQB Advanced Level bietet eine modulare Ausbildung in drei Kompetenzbereichen mit flexibel gestaltbaren Ausbildungswegen. Er berücksichtigt individuelle Neigungen und Schwerpunkte.
- Die Zertifizierung erfolgt als Hausarbeit. Die Bewertung und mündliche Prüfung wird durch vom iSAQB benannte Expert:innen vorgenommen.

### Was können Absolventen des Advanced Level (CPSA-A)?

CPSA-A-Absolventen können:

- eigenständig und methodisch fundiert mittlere bis große IT-Systeme entwerfen
- in IT-Systemen mittlerer bis hoher Kritikalität technische und inhaltliche Verantwortung übernehmen
- Maßnahmen zur Erreichung von Qualitätsanforderungen konzeptionieren, entwerfen und dokumentieren sowie Entwicklungsteams bei der Umsetzung dieser Maßnahmen begleiten
- architekturrelevante Kommunikation in mittleren bis großen Entwicklungsteams steuern und durchführen

### Voraussetzungen zur CPSA-A-Zertifizierung

- erfolgreiche Ausbildung und Zertifizierung zum Certified Professional for Software Architecture, Foundation Level® (CPSA-F)
- mindestens drei Jahre Vollzeit-Berufserfahrung in der IT-Branche; dabei Mitarbeit an Entwurf und Entwicklung von mindestens zwei unterschiedlichen IT-Systemen

  - Ausnahmen sind auf Antrag zulässig (etwa: Mitarbeit in Open-Source-Projekten)
- Aus- und Weiterbildung im Rahmen von iSAQB-Advanced-Level-Schulungen im Umfang von mindestens 70 Credit Points aus mindestens drei unterschiedlichen Kompetenzbereichen
- erfolgreiche Bearbeitung der CPSA-A-Zertifizierungsprüfung

  
  

![Certified Professional for Software Architecture® Advanced Level (CPSA-A)](images/00-preamble/cpsa-a-logo.png)

## Grundlegendes

### Was vermittelt das Modul „SWARC4AI“?

Das Modul präsentiert den Teilnehmer:innen moderne Softwarearchitektur-Konzepte für KI-Systeme als Mittel, um leistungsfähige, skalierbare und integrierbare KI- Lösungen zu gestalten. Am Ende des Moduls kennen die Teilnehmer:innen die wesentlichen Prinzipien der Softwarearchitektur für KI-Systeme und können diese bei Entwurf und Implementierung von Machine Learning und Generative KI- Systemen anwenden. Mit Hilfe der vermittelten Modellierungstechniken und Architekturwerkzeuge können sie KI-Komponenten nahtlos in bestehende Softwaresysteme integrieren. Die Schulung umfasst sowohl Machine Learning Systeme als auch Generative KI und vermittelt, wie diese mit klassischen Softwaresystemen kombiniert werden können. Die Teilnehmer:innen lernen, wie die Architektur für solche hybriden Systeme aussehen muss, um Skalierbarkeit, Wartbarkeit und Erweiterbarkeit zu gewährleisten.

### Struktur des Lehrplans und empfohlene zeitliche Aufteilung

| Inhalt | Empfohlene Mindestdauer (min) |
| --- | ---: |
| Einführung in softwarearchitekturrelevante Konzepte für Künstliche Intelligenz | 120 |
| Compliance, Security, Alignment | 120 |
| Entwurf und Entwicklung von KI-Systemen | 320 |
| Datenmanagement und Datenverarbeitung für KI-Systeme | 90 |
| Wichtige Qualitätsmerkmale für den Betrieb von KI-Systemen | 160 |
| Systemarchitekturen- und Plattformen für Generative KI-Systeme | 160 |
| Fallstudien und Praxisprojekte | 110 |
| Gesamt | 1080 |

### Dauer, Didaktik und weitere Details

Die Dauer einer Schulung zum Modul SWARC4AI sollte mindestens 3 Tage betragen, kann aber länger sein. Anbieter können sich durch Dauer, Didaktik, Art und Aufbau der Übungen sowie der detaillierten Kursgliederung voneinander unterscheiden. Insbesondere die Art der Beispiele und Übungen lässt der Lehrplan komplett offen. Lizenzierte Schulungen zu SWARC4AI tragen zur Zulassung zur abschließenden Advanced-Level-Zertifizierungsprüfung folgende Credit Points) bei:

|  |  |
| --- | --- |
| Methodische Kompetenz: | 10 Punkte |
| Technische Kompetenz: | 20 Punkte |
| Kommunikative Kompetenz: | 0 Punkte |

### Voraussetzungen

Teilnehmer:innen **sollten** folgende Kenntnisse und/oder Erfahrung mitbringen:

- Ein grundlegendes Verständnis von Künstlicher Intelligenz, Machine Learning und Data Science
- Ein grundlegendes Verständnis für Softwarearchitektur, DevOps und den Entwurf von Softwaresystemen sowie APIs
- Ein grundlegendes Wissen über die Programmiersprache Python und ihre Nutzung für KI-Probleme
- Überblick über gängige Bibliotheken wie scikit-learn, TensorFlow und PyTorch

Wissen in folgenden Bereichen können **hilfreich** für das Verständnis einiger Konzepte sein:

- Erfahrung mit der Kommandozeile auf Linux-Systemen
- Wissen aus der iSAQB CPSA Foundation-Level Schulung für ein allgemeines Verständnis für Softwarearchitektur, Entwurfsmuster und Methodiken

### Gliederung des Lehrplans

Die einzelnen Abschnitte des Lehrplans sind gemäß folgender Gliederung beschrieben:

- **Begriffe/Konzepte**: Wesentliche Kernbegriffe dieses Themas.
- **Unterrichts-/Übungszeit**: Legt die Unterrichts- und Übungszeit fest, die für dieses Thema bzw. dessen Übung in einer akkreditierten Schulung mindestens aufgewendet werden muss.
- **Lernziele**: Beschreibt die zu vermittelnden Inhalte inklusive ihrer Kernbegriffe und -konzepte.

Dieser Abschnitt skizziert damit auch die zu erwerbenden Kenntnisse in entsprechenden Schulungen.

### Ergänzende Informationen, Begriffe, Übersetzungen

Soweit für das Verständnis des Lehrplans erforderlich, haben wir Fachbegriffe ins [iSAQB-Glossar](https://github.com/isaqb-org/glossary) aufgenommen, definiert und bei Bedarf durch die Übersetzungen der Originalliteratur ergänzt.

## 1. Einführung in softwarearchitekturrelevante Konzepte für Künstliche Intelligenz

|  |  |
| --- | --- |
| Dauer: 120 Min. | Übungszeit: 0 Min. |

### 1.1. Begriffe und Konzepte

KI, Generative KI, Machine Learning, Symbolische KI, Evolutionäre Algorithmen, Statistical Learning, Deep Learning, LLMs, Halluzination, Bias, Jagged Technological Frontier, Data Preparation, Model Training, Model Evaluation, Feature Engineering, Data Science, Data Engineering

### 1.2. Lernziele

#### LZ 1-1: Künstliche Intelligenz und Machine Learning, Data Science, Deep Learning, Generative KI einordnen können

Die Teilnehmer:innen können die Begriffe Künstliche Intelligenz, Machine Learning, Data Science, Deep Learning und Generative KI erläutern, voneinander abgrenzen und ihre Zusammenhänge einordnen.

#### LZ 1-2: KI-Anwendungsfälle identifizieren, fachlich einordnen, priorisieren und bewerten

Die Teilnehmer:innen können typische KI-Anwendungsfälle identifizieren und fachlich beschreiben. Sie können deren Eignung anhand fachlicher Ziele, Datenverfügbarkeit und -qualität, technischer Umsetzbarkeit, erwartbarem Mehrwert, Risiken, Integrationsaufwand und Auswirkungen auf die Softwarearchitektur bewerten und eine begründete Priorisierung vornehmen.

Typische Anwendungsfälle umfassen beispielsweise Bilderkennung und Bildgenerierung, Sprachverarbeitung, Vorhersagemodelle, Personalisierung, Anomalieerkennung, Chatbots, Empfehlungssysteme und intelligente Assistenzsysteme.

#### LZ 1-3: Stärken, Grenzen und typische Risiken von KI einordnen

Die Teilnehmer:innen können Stärken und Grenzen von KI-Technologien in unterschiedlichen Anwendungskontexten einordnen und erklären, warum die Eignung von KI stark von der jeweiligen Aufgabe abhängt.

Sie können typische technische und gesellschaftliche Risiken identifizieren, beispielsweise

- Halluzinationen,
- Bias,
- Unfairness
- Deepfakes,
- KI-gestützte Cyberangriffe,
- Sicherheitsrisiken in kritischen Systemen,
- Soziale Manipulation,
- Verletzungen geistiger Eigentumsrechte

Die Teilnehmer:innen kennen die „Jagged Technological Frontier“ bzgl. der aufgabebezogenen Eignung von KI.

#### LZ 1-4: Unterschiede zwischen KI-Systemen und traditioneller Software verstehen, erklären und die geeignete Lösungsart entscheiden

Die Teilnehmer:innen verstehen die Unterschiede von KI-Systemen zu traditioneller Software:

- Datengetrieben (bei ML) – Daten-zentrierte statt Code-zentrierte Entwicklung
- Probabilistische Ergebnisse (Non-deterministic behavior)
- Statistische Validierung
- Experimentelles Design: Unterstützung für schnelle Iteration und Testen von Modellen.
- Modellkomplexität und Interpretierbarkeit: ML-Modelle, insbesondere Deep-Learning-Modelle, können äußerst komplex sein. Der „Black-Box“-Charakter erschwert die Interpretierbarkeit und Erklärbarkeit.
- Debugging und Tests sind aufgrund des Nichtdeterminismus komplexer.
- Model Decay: Continuous monitoring und Retraining sind notwendig, um die Leistung der Modelle aufrechtzuerhalten.
- KI-spezifische Regulatorik von Branchen und auf EU-Ebene müssen berücksichtigt werden.
- Interoperabilität: Nahtlose Integration in bestehende Systeme und Technologiestacks.

Teilnehmer:innen können entscheiden und erklären, ob und warum ein Problem mittels KI oder klassischer SW-Entwicklung zu lösen ist.

#### LZ 1-5: Rollen und deren Aufgaben sowie ihre Zusammenarbeit im Kontext von KI kennen

Die Teilnehmer:innen kennen typische Rollen und deren Aufgaben in diesen Kontexten. Die Rollen umfassen insbesondere:

Data Scientist, Data Analyst, Data Engineer, Machine Learning Engineer, MLOps Engineer, AI Architect, Data Architect, Business Intelligence (BI) Developer, Data Governance Specialist und ML-Researcher.

Die Teilnehmer:innen wissen darüber hinaus, wie diese Rollen im Team zusammenarbeiten könnten (Team Topologies für ML-Teams).

#### LZ 1-6 [OPTIONAL]: Das Konzept der Productivity J-Curve erläutern und seine Bedeutung für die Einführung von KI in Organisationen einordnen

Dieses Phänomen hilft zu verstehen, warum Unternehmen bei der Implementierung von KI zunächst einen Produktivitätsrückgang verzeichnen können, dem bei der weiteren Entwicklung aber Produktivitätsgewinne folgen können.

### 1.3. Referenzen

[Agrawal et al.], [Bahree 2024], [Brynjolfsson et al.], [Burkov 2019], [Chong et al.], [Dell’Acqua 2026], [Géron 2022], [Gharbi et al. 2026], [Hall et al. 2023], [Harvard et al. 2024], [Huyen 2022], [Kelleher 2015], [Roser 2022], [Tan et al.], [Vaughan 2020], [Visengeriyeva, JTF], [Wang et al. 2024]

## 2. Compliance, Security, Alignment

|  |  |
| --- | --- |
| Dauer: 120 Min. | Übungszeit: 30 Min. |

### 2.1. Begriffe und Konzepte

EU AI Act, Datenschutz, Urheberrecht, Lizenz, Open (Source), AI Security, Jailbreak,Adversarial Attack, Data Poisoning, Model Inversion & Extraction, AI Safety, AI Ethics, AI Alignment, Model und Data Dokumentation, Transparenzpflicht, Human Oversight, Data Governance, AI Governance, KI-Systeme nach Risikostufen (unannehmbares Risiko, hohes Risiko, begrenztes Risiko, minimales Risiko)

### 2.2. Lernziele

#### LZ 2-1: Einfluss der Datenschutzgesetze auf die Implementierung und Nutzung von KI kennen

Die Teilnehmer:innen kennen die Datenschutzgesetze wie die DSGVO und wissen, wie diese die Sammlung, Verarbeitung und Speicherung von Daten durch KI-Systeme beeinflussen.

#### LZ 2-2: Die Anforderungen des EU AI Act analysieren und daraus architekturrelevante Maßnahmen für Datenflüsse, Logging, technische Dokumentation, Human Oversight, Robustheit und Deployment ableiten.

Die Teilnehmer:innen können die Ziele und Regelungen des EU AI Act erläutern und deren Einfluss auf die Entwicklung und den Einsatz von KI-Systemen analysieren. Außerdem können sie die Anforderungen des EU AI Act (Trustworthy AI) hinsichtlich ihrer Auswirkungen auf den Entwicklungsprozess und die Architektur des Softwaresystems analysieren und daraus architekturrelevante Maßnahmen ableiten. Insbesondere können sie die Auswirkungen auf einige der folgenden Aspekte analysieren und entsprechende Maßnahmen ableiten:

- Risikomanagementsystem (Risikominimierung)
- Datenqualität und Daten-Governance (Qualitätsmanagementsystem)
- Erstellung und Pflege einer umfassenden technischen Dokumentation des KI-Systems
- Automatische Aufzeichnung/Logging von Events im KI-System.
- Bereitstellung klarer und verständlicher Informationen für Nutzer
- Implementierung der Maßnahmen zur menschlichen Aufsicht
- Gewährleistung eines angemessenen Maßes an Genauigkeit/Accuracy und Robustheit
- Implementierung von Maßnahmen zur Cybersicherheit

#### LZ 2-3: Klassifikation von KI-Systemen nach EU AI Act Risikolevel durchführen

Die Teilnehmer:innen können KI-Systeme anhand konkreter Anwendungsfälle den Risikostufen des EU AI Act (unannehmbares Risiko, hohes Risiko, begrenztes Risiko, minimales Risiko) zuordnen und die jeweils geltenden regulatorischen Anforderungen bestimmen.

#### LZ 2-4: Urheberrecht, Offenheitsgrade und Lizenzbedingungen von KI-Modellen und KI-generierten Inhalten bewerten

Die Teilnehmer:innen können urheberrechtliche Fragestellungen bei Trainingsdaten und KI-generierten Inhalten einordnen und deren Auswirkungen auf Entwicklung, Bereitstellung und Nutzung von KI-Systemen erläutern.

Sie können unterschiedliche Grade der Offenheit von ML-Modellen, beispielsweise hinsichtlich Trainingsdaten, Quellcode, Modellarchitektur und Modellparametern, unterscheiden sowie Lizenzbedingungen und daraus resultierende Einschränkungen für ein KI-System bewerten.

#### LZ 2-5: Strategien zur Einhaltung regulatorischer Anforderungen bewerten und geeignete Nachweis- und Dokumentationsartefakte für Modelle, Datensätze und Betriebsprozesse festlegen

Die Teilnehmer:innen verstehen die Grundaussagen des EU AI Acts (insbesondere Transparenzpflichten) und kennen Strategien für deren Einhaltung sowie mögliche Herausforderungen dabei.

Sie können insbesondere Dokumentationsartefakte für Modelle, Datensätze, Prompts, Evaluationsverfahren, Änderungen und Betriebsprozesse auswählen und erklären, wie diese Nachvollziehbarkeit, Transparenz und Auditierbarkeit unterstützen.

Die Teilnehmer:innen können Regulatory Sandboxes als Instrument zur kontrollierten Erprobung innovativer KI-Systeme einordnen und deren Möglichkeiten, Grenzen und Konsequenzen bei Nichteinhaltung des EU AI Acts erläutern.

#### LZ 2-6: Fallstricke hinsichtlich Security sowie Angriffsarten auf ML-Modelle kennen und geeignete Sicherheitsmaßnahmen gegen Angriffe auf KI-Systeme auswählen

Die Teilnehmer:innen kennen mögliche Fallstricke hinsichtlich Security sowie typische Angriffsarten auf ML-Modelle. Dies betrifft beispielsweise:

- LLM-Jailbreaks durch Prompt-Engineering
- Adversarial Attacks
- Data Poisoning
- Model Inversion & Extraction.

Die Teilnehmer:innen können die mit diesen Angriffsarten verbundenen Sicherheitsrisiken für KI-Systeme bewerten und geeignete Sicherheitsmaßnahmen zur Absicherung gegen Angriffe (AI Security) auswählen und ihre Auswahl begründen. Insbesondere können sie Möglichkeiten zur Integration von Sicherheitsstandards und Schutzmechanismen in Architektur, Schnittstellen und Betriebsmodell hinsichtlich ihrer Eignung bewerten und geeignete Maßnahmen auswählen.

#### LZ 2-7: Strategien zur KI-Risikominimierung kennen und anwenden

Die Teilnehmer:innen können erläutern, wie Strategien zur KI-Risikominimierung entwickelt werden, und diese auf konkrete KI-Systeme anwenden. Insbesondere können sie die folgenden Strategien situationsgerecht einsetzen:

- Stärkung der Robustheit durch umfangreiche Tests
- Fehlertolerante KI-Systeme
- Transparente Entwicklung
- Erklärbare KI (explainable AI)

#### LZ 2-8: Grundproblematik und Facetten von AI-Safety verstehen

Die Teilnehmer:innen verstehen die Grundproblematik von AI-Safety und kennen die verschiedenen Facetten dazu. Insbesondere kennen die Teilnehmer:innen spezifische Probleme wie beispielsweise "AI model risks by poisoning" und "Bias".

Die Teilnehmer:innen wissen, wie Bias in Daten und Modellen erkannt und reduziert werden können, um Fairness und Gleichbehandlung in KI-Anwendungen sicherzustellen.

#### LZ 2-9: Ethikleitlinien und Prinzipien von AI Governance in Organisations-, Entwicklungs- und Architekturentscheidungen übersetzen

Die Teilnehmer:innen können ethische Problemstellungen, die beim Einsatz von KI-Systemen entstehen können, erkennen und geeignete Ansätze zum Umgang mit diesen Problemen auf konkrete Anwendungsfälle übertragen, beispielsweise bei der Erstellung von KI-Richtlinien. Dazu können die Teilnehmer:innen wichtige Ethik-Leitlinien wie die „EU-Ethik-Leitlinien für vertrauenswürdige KI“ heranziehen und deren Prinzipien in konkrete Organisations-, Entwicklungs- und Architekturentscheidungen übersetzen.

Optional können die Teilnehmer:innen wichtige Dokumente und Frameworks zu AI Governance anwenden, um die Kernprinzipien von AI Governance und Responsible AI in konkrete Vorgaben für das Unternehmen zu übertragen, z.B.:

- OECD AI Principles, [https://oecd.ai/en/ai-principles](https://oecd.ai/en/ai-principles)
- The Asilomar AI Principles, [https://futureoflife.org/open-letter/ai-principles/](https://futureoflife.org/open-letter/ai-principles/)
- The IEEE Ethically Aligned Design framework, [https://standards.ieee.org/wp-content/uploads/import/documents/other/ead_v2.pdf](https://standards.ieee.org/wp-content/uploads/import/documents/other/ead_v2.pdf)

### 2.3. Referenzen

[ATLAS], [Bhajaria 2022], [Chen et al. 2022], [CSIRO et al. 2023], [EU AI Act], [Gharbi et al. 2026], [Hall et al. 2023], [Hotz, Best Practices], [Jarmul 2023], [Masood et al. 2023], [Molnar 2024], [Nist], [Pruksachatkun et al. 2023], [Visengeriyeva, Ethics]

## 3. Entwurf und Entwicklung von KI-Systemen

|  |  |
| --- | --- |
| Dauer: 320 Min. | Übungszeit: 45 Min. |

### 3.1. Begriffe und Konzepte

CI/CD, MLOps, CRISP-ML(Q), AI-Application, AI-Engineering, ML-Modellentwicklung, ML-Infrastruktur, Performance, Robustheit, Zuverlässigkeit, Fehlertoleranz, Model-as-Service, Model-as-Dependency, Precompute, Model-on-Demand, Hybrid-Serving, Multi-Agent System (MAS)

### 3.2. Lernziele

#### LZ 3-1: Life-Cycle eines Machine-Learning- bzw. Data-Science-Projekts verstehen

Die Teilnehmer:innen haben ein Verständnis für den Life-Cycle eines Machine-Learning- bzw. Data-Science-Projekts. Dabei kennen sie insbesondere die folgenden Phasen:

- Exploratory Data Analysis
- Data Cleansing und Aufbereitung
- Feature Engineering
- Modell Training und Auswahl
- POC
- Deployment
- Maintenance

Die Teilnehmer:innen kennen typische Vorgehensmodelle für die Softwareentwicklung von KI-Systemen. Dies sind beispielsweise

- CRISP-ML(Q)
- Team Data Science Process
- GenAI Life Cycle.

#### LZ 3-2: Datenarten und Anforderungen an Daten sowie typische ML-Problemstellungen und deren Anforderungen verstehen

Die Teilnehmer:innen kennen verschiedene Arten von Daten sowie typische ML-Probleme und Anwendungsfälle für die Nutzung der Daten aus den Bereichen:

- Supervised Learning
- Unsupervised Learning
- Reinforcement Learning

und verstehen, welche Anforderungen diese haben können, z.B.:

- Vorhandensein von korrekten Labels verschiedener Art
- Datenumfang und -diversität
- Zeitliche oder semantische Abhängigkeiten in Datenmerkmalen
- Kodierung der Eingabedaten von ML-Modellen, z.B.:
- One-Hot-Encodings
- Label Encodings
- Embeddings

Insbesondere haben die Teilnehmer:innen ein gutes Verständnis für die Notwendigkeit von Validierung und Kenntnis der typischen Datenaufteilung in Trainings-, Validierungs- und Testdaten.

#### LZ 3-3: Geeignete Architektur- und Design-Patterns für KI-Systeme auswählen, gegeneinander abwägen und anhand von Qualitätsanforderungen begründen.

Die Teilnehmer:innen können geeignete Design Patterns für KI-Systeme anhand von Qualitätsanforderungen auswählen, gegeneinander abwägen und ihre Auswahl begründen. Das betrifft die folgenden Design Patterns:

- ML Systems Topology Patterns
- Pipeline Architecture Patterns
- Model Training Pattern
- Model Serving Patterns
- Model Deployment Patterns

Insbesondere kennen die Teilnehmer:innen Transfer-Learning bzw. Fine-Tuning als Möglichkeit, um die vortrainierten Basismodelle auf bestehende Anwendungsfälle zu adoptieren.

#### LZ 3-4: Metriken zur Messung der Performance von ML-Modellen kennen

Die Teilnehmer:innen kennen verschiedene Metriken zur Messung der Performance von ML-Modellen wie beispielsweise:

- Precision, Recall
- F1-Score
- Accuracy

und wissen, wie man Bewertungskriterien zur Leistungsbeurteilung festlegt.

#### LZ 3-5: KI-Komponenten über geeignete Integrationsmuster, Schnittstellen und Entkopplungsmechanismen in bestehende Systeme und Domänenarchitekturen integrieren.

Die Teilnehmer:innen verstehen, wie ML-Modelle in bestehende Systeme integriert werden können, und kennen die entsprechenden Schnittstellen und Integrationspunkte. Sie können geeignete Integrationsmuster, Schnittstellen und Entkopplungsmechanismen anwenden, um KI-Komponenten in bestehende Systeme und Domänenarchitekturen zu integrieren.

#### LZ 3-6: Benutzerinteraktionen für KI-Systeme so gestalten, dass Unsicherheit, Erklärbarkeit, Freigaben und Human-in-the-Loop angemessen berücksichtigt werden.

Die Teilnehmer:innen können Benutzerinteraktionen und Benutzeroberflächen für KI-Systeme so gestalten, dass effektive Interaktionen mit dem ML-System ermöglicht und die Benutzererfahrung optimiert werden. Dabei können sie Konzepte entwickeln, die Unsicherheit, Erklärbarkeit, Freigaben und Human-in-the-Loop angemessen berücksichtigen.

#### LZ 3-7: Leistung und Skalierbarkeit von KI-Systemen analysieren und gestalten

Die Teilnehmer:innen verstehen die Bedeutung von Leistungskennzahlen wie Latenz, Durchsatz und Resourcenauslastung in KI-Systemen für Training sowie Inferenz und verstehen, wie diese optimiert werden können.

Sie können Ursachen von Leistungs- und Skalierungsproblemen analysieren und geeignete Maßnahmen auswählen, damit KI-Systeme steigende Datenmengen, Nutzerzahlen und Anfragevolumen verarbeiten können. Darauf aufbauend können sie Konzepte zur Leistungsoptimierung und Skalierung von KI-Systemen entwerfen.

#### LZ 3-8: Robustheit in KI-Systemen verstehen und Strategien zur Erhöhung der Robustheit anwenden

Die Teilnehmer:innen haben ein Verständnis davon, was Robustheit in KI-Systemen bedeutet, und können Strategien zur Erhöhung der Robustheit in verschiedenen Anwendungskontexten anwenden.

#### LZ 3-9: Zuverlässigkeit und Verfügbarkeit von KI-Systemen einordnen

Die Teilnehmer:innen verstehen die Konzepte der Zuverlässigkeit und Verfügbarkeit und wissen, wie sie KI-Systeme bauen, die stabil und konstant verfügbar sind.

#### LZ 3-10: Maßnahmen für Reproduzierbarkeit, Auditierbarkeit und Nachvollziehbarkeit von Modellen, Datenständen, Prompts, Konfigurationen und Ergebnissen festlegen.

Die Teilnehmer:innen verstehen die Bedeutung reproduzierbarer und prüfbarer KI-Ergebnisse und kennen Methoden zur Sicherstellung dieser Eigenschaften. Sie können geeignete Maßnahmen zur Gewährleistung der Reproduzierbarkeit, Auditierbarkeit und Nachvollziehbarkeit von Modellen, Datenständen, Prompts, Konfigurationen und Ergebnissen anhand konkreter Anforderungen bewerten, auswählen und festlegen.

#### LZ 3-11: Erklärbarkeit und Interpretierbarkeit in KI-Systemen einordnen

Die Teilnehmer:innen verstehen die Bedeutung von Erklärbarkeit und Interpretierbarkeit in KI-Systemen und wissen, wie man diese sicherstellen kann, um Vertrauen und Transparenz zu fördern.

#### LZ 3-12: Fehlertoleranz in KI-Systemen erläutern

Die Teilnehmer:innen kennen die Konzepte der Fehlertoleranz und können erläutern, wie KI-Systeme trotz Fehlern oder Störungen funktionsfähig bleiben.

#### LZ 3-13: Architekturentscheidungen für KI-Systeme dokumentieren.

Die Teilnehmer:innen wissen, wie man die Anwendungsfälle bzw. Aufgaben eines ML-Modells definiert und dokumentiert, wie beispielsweise die Klassifikation von Bildern oder die Erkennung von Betrug, insbesondere Trade-offs zu:

- RAG versus Fine-Tuning
- SaaS versus Self-Hosting
- Batch versus Realtime
- Zentralem versus domänenspezifischem KI-Service.

### 3.3. Referenzen

[Bornstein et al.], [Cdteliot], [Crowe et al. 2024], [Gharbi et al. 2026], [Heiland et al. 2023], [Hotz, Life Cycle], [Hotz, TDSP], [Koc], [Lakshmanan et al.], [ML software architecture], [Nahar et al.], [Saltz], [Savarese], [Serban], [Studer et al.], [tdcox], [TU Berlin], [Visengeriyeva, AI Agents], [Zaharia et al.]

## 4. Datenmanagement und Datenverarbeitung für KI-Systeme

|  |  |
| --- | --- |
| Dauer: 90 Min. | Übungszeit: 0 Min. |

### 4.1. Begriffe und Konzepte

Datenakquise, Labelling, Daten-Pipeline, ETL-Prozesse, Datenaggregation, Datenbereinigung, Transformation, Augmentierung, Dateien, RDBMS, NoSQL, Dokumentbasierte Datenbanken, Data Products, Data Contracts, Data Architectures: Data Warehouse, Data Lake, Data Mesh

### 4.2. Lernziele

#### LZ 4-1: Daten akquirieren und labeln

Die Teilnehmer:innen überblicken verschiedene Methoden, um Daten zu akquirieren und Daten zu labeln, und können geeignete Methoden zur Datenakquise und zum Datenlabeling auf konkrete Anwendungsfälle anwenden.

Die Teilnehmer:innen kennen relevante Werkzeuge fürs Daten-Labeln wie beispielsweise CVAT, Label Studio oder Amazon Mechanical Turk.

#### LZ 4-2: Quellen und Eignung öffentlich verfügbarer Datensätze hinsichtlich Qualität, Lizenz, Repräsentativität und Risiken bewerten.

Die Teilnehmer:innen können gängige Plattformen für öffentlich zugängliche Daten nennen und die Eignung der dort verfügbaren Datensätze für konkrete Anwendungsfälle anhand von Kriterien wie Qualität, Lizenzbedingungen, Repräsentativität und Risiken bewerten und ihre Bewertung begründen.

#### LZ 4-3: Datenpipelines und Datenarchitekturen für KI-Systeme so entwerfen, dass Qualität, Nachvollziehbarkeit, Skalierbarkeit, Governance und Wiederverwendbarkeit unterstützt werden.

Die Teilnehmer:innen haben ein Verständnis für die Gestaltung effizienter Datenpipelines und -architekturen, die Betrachtung von Datenqualität sowie für Speicherlösungen und deren Management. Sie können darauf aufbauend Datenpipelines und Datenarchitekturen für KI-Systeme entwerfen, die Anforderungen an Qualität, Nachvollziehbarkeit, Skalierbarkeit, Governance und Wiederverwendbarkeit berücksichtigen. Dazu kennen die Teilnehmer:innen:

- Architekturmuster für Data-Engineering-Pipelines und ETL-Prozesse
- Wie eine effektive Datenverwaltung die Qualität und Sicherheit von Daten in KI-Anwendungen sicherstellt

Die Teilnehmer:innen überblicken relevante Werkzeuge für Data Engineering Pipelines wie beispielsweise Apache Spark und Flink.

#### LZ 4-4: Strategien für Datenaggregation, -bereinigung, -transformation, -anreicherung und -augmentierung kennen

Die Teilnehmer:innen kennen Strategien für Datenaggregation, -bereinigung, -transformation, -anreicherung und -augmentierung.

#### LZ 4-5: Möglichkeiten zur Speicherung der Daten kennen

Die Teilnehmer:innen kennen verschiedene Möglichkeiten zur Speicherung der Daten sowie deren Vor- und Nachteile. Zu den Möglichkeiten gehören die folgenden Technologien:

- CSV-Dateien
- Spaltenorientierte Dateien
- Relationale und Dokumentbasierte Datenbanken
- Data Warehouses
- Data Lakes
- Vektordatenbanken
- Graphdatenbanken

#### LZ 4-6: Data Products, Data Contracts und Verantwortlichkeiten in Datenarchitekturen für KI-Systeme einordnen und für robuste Schnittstellen zwischen Fachlichkeit, Datenplattform und KI-Komponenten nutzen.

Die Teilnehmer:innen kennen grundlegende Konzepte moderner Datenarchitekturen für KI-Systeme und verstehen die Rolle von Data Products, Data Contracts sowie fachlicher und technischer Verantwortlichkeiten für stabile und skalierbare Datenflüsse. Sie können diese Konzepte auf konkrete Anwendungsfälle übertragen und Data Products, Data Contracts sowie die Zuordnung von Verantwortlichkeiten nutzen, um robuste Schnittstellen zwischen Fachlichkeit, Datenplattform und KI-Komponenten zu gestalten.

### 4.3. Referenzen

[Bhajaria 2022], [Bornstein et al.], [Dehghani], [Ford et al.], [Gharbi et al. 2026], [Jones], [Reis et al.], [Sanderson et al.], [Sarkis], [Serra]

## 5. Wichtige Qualitätsmerkmale für den Betrieb von KI-Systemen

|  |  |
| --- | --- |
| Dauer: 160 Min. | Übungszeit: 30 Min. |

### 5.1. Begriffe und Konzepte

Qualitätsmerkmale, Skalierbarkeit, Leistungsoptimierung, Monitoring, Logging, Feedback, FinOps für KI-Plattformen

### 5.2. Lernziele

#### LZ 5-1: (Hardware)-Anforderungen an Training und Inferenz kennen

Die Teilnehmer:innen kennen unterschiedliche (Hardware)-Anforderungen für beispielsweise TPU, NPU, LPU, GPU oder CPU an Training und Inferenz.

#### LZ 5-2: Trade-Offs verschiedener Modellarchitekturen bezüglich der Qualitätsmerkmale kennen

Die Teilnehmer:innen können beispielhaft Trade-Offs verschiedener Modellarchitekturen bezüglich der Qualitätsmerkmale nennen. Insbesondere für Skalierung, Effizienz und Speicherlast sollten die Teilnehmer:innen die Trade-Offs sowie die Vor- und Nachteile von wichtigen Architekturen wie beispielsweise RNNs und Transformern kennen.

#### LZ 5-3: Verschiedene Qualitätsmerkmale eines ML-Modells abstimmen

Die Teilnehmer:innen kennen Möglichkeiten, um verschiedene Qualitätsmerkmale wie Genauigkeit, Effizienz und Speicherlast eines ML-Modells abzustimmen und gegeneinander einzutauschen. Sie können geeignete Techniken anwenden, um diese Qualitätsmerkmale anhand konkreter Anforderungen gegeneinander abzuwägen und abzustimmen. Insbesondere können die Teilnehmer:innen die folgenden Techniken situationsgerecht einsetzen:

- Quantisierung
- Pruning
- Destillierung
- LoRA

#### LZ 5-4: Kosten, Stromverbrauch und nachhaltige Nutzung von KI (Green IT) verstehen

Die Teilnehmer:innen erlangen ein Verständnis für Kosten, Stromverbrauch und nachhaltige Nutzung von KI (Green IT). Insbesondere wissen die Teilnehmer:innen, wie man KI-Modelle und -Systeme entwickelt, die ressourcenschonend arbeiten, indem sie Speicher, Rechenleistung und Speicherplatz effizient nutzen.

#### LZ 5-5: MLOps für die Automatisierung des Life-Cycles eines Data-Science-Projekts überblicken

Die Teilnehmer:innen kennen den Begriff MLOps für die Automatisierung des Life-Cycles eines Data-Science-Projekts sowie den Zusammenhang mit DevOps.

Die Teilnehmer:innen verstehen anhand eines Praxisbeispiels, wie eine MLOps-Pipeline aussehen kann und welche Einsichten diese auf die Parameter, Metriken usw. bietet.

#### LZ 5-6: Modelltraining, Parameter, Metriken und Ergebnisse tracken

Die Teilnehmer:innen haben ein Verständnis vom Tracking im Modelltraining, Parametern, Metriken und Ergebnissen. Sie können geeignete Tracking-Methoden anwenden, um Trainingsläufe, Parameter, Metriken und Ergebnisse systematisch zu erfassen und nachzuverfolgen.

#### LZ 5-7: Modellevaluation, Systemevaluation und fachliche Nutzenbewertung unterscheiden und geeignete Evaluationsansätze für KI-Systeme auswählen.

Die Teilnehmer:innen überblicken Ansätze zur Evaluation von ML-Modellen und darauf aufbauenden KI-Systemen. Sie können zwischen Modellevaluation, Systemevaluation und fachlicher Nutzenbewertung unterscheiden, geeignete Evaluationsansätze für konkrete KI-Systeme anhand relevanter Anforderungen und Qualitätskriterien bewerten, auswählen und ihre Auswahl begründen.

#### LZ 5-8: Arten von Drift sowie mögliche Ursachen und Lösungsansätze dafür kennen

Die Teilnehmer:innen kennen verschiedene Arten von Drift, wie beispielsweise Daten-Drift oder Modell-Drift, sowie mögliche Ursachen und Lösungsansätze dafür.

#### LZ 5-9: CI/CD-Pipelines, Modellmanagement und Deployment-Strategien für KI-Modelle überblicken

Die Teilnehmer:innen haben ein Verständnis von CI/CD-Pipelines, Modellmanagement und Deployment-Strategien für KI-Modelle.

Die Teilnehmer:innen kennen eine Auswahl verschiedener Deployment-Möglichkeiten von KI-Modellen:

- API Deployment
- Embedded Deployment
- Batch Prediction
- Streaming
- Containerization
- Serverless Deployment
- Cloud Services

Die Teilnehmer:innen kennen gängige Plattformen und Werkzeuge für die Modellbereitstellung sowie Erstellung von POCs und verstehen die konzeptionelle Funktionsweise.

#### LZ 5-10: Vor- und Nachteile von SaaS und Self-Hosting nennen sowie Make-or-Buy-Entscheidungen anhand von Qualitätsanforderungen treffen

Die Teilnehmer:innen kennen die Vor- und Nachteile von SaaS und Self-Hosting und können dazwischen abwägen.

Die Teilnehmer:innen sind in der Lage, Make-or-Buy Entscheidungen für MLOps- und KI-Plattform Systemen/Komponenten anhand von Qualitätsanforderungen, Kosten, Risiko, Compliance und Integrationsaufwand zu treffen.

Die Teilnehmer:innen überblicken bekannte SaaS-KI-Lösungen, wie beispielsweise Azure OpenAI Services.

#### LZ 5-11: Monitoring und Observability für KI-Systeme konzipieren, insbesondere für Drift, Qualitätsverlust, Kosten, Latenz, Sicherheitsereignisse und Governance-relevante Nachweise.

Die Teilnehmer:innen verstehen die Notwendigkeit für Monitoring, auch im Hinblick auf KI-spezifische Anforderungen wie das Tracking von Drift. Sie können darauf aufbauend Monitoring- und Observability-Konzepte für KI-Systeme entwerfen, die insbesondere Drift, Qualitätsverlust, Kosten, Latenz, Sicherheitsereignisse und Governance-relevante Nachweise berücksichtigen.

Die Teilnehmer:innen kennen relevante Metriken wie beispielsweise Accuracy, Precision, Recall, F1-Score, MAE, MSE, Perplexity, Latenz, Durchsatz und Ressourcenauslastung und verstehen, warum diese für das Monitoring relevant sind.

Die Teilnehmer:innen kennen Beispiel-Werkzeuge für Monitoring. Dies betrifft sowohl allgemeine Werkzeuge, wie beispielsweise Prometheus & Grafana, als auch ML-spezifische wie beispielsweise MLflow.

#### LZ 5-12: Nutzer-Feedback sowie Methoden und Werkzeuge zur Sammlung von Nutzer-Feedback verstehen

Die Teilnehmer:innen verstehen den Nutzen von Nutzer-Feedback für das weitere Modelltraining. Darüber hinaus kennen die Teilnehmer:innen verschiedene Methoden und Werkzeuge zur Sammlung von Nutzer-Feedback, wie beispielsweise die Auswahl zwischen mehreren Antworten oder Flagging in Gradio.

Die Teilnehmer:innen kennen weitere Methoden zur Gewinnung von Nutzer-Feedback, wie beispielsweise RLHF, RLAIF und DPO.

#### LZ 5-13: [OPTIONAL] Klassen von MLOps-Werkzeugen und Plattformen sowie wesentliche Auswahlkriterien für ihren Einsatz kennen.

Die Teilnehmer:innen kennen bekannte MLOps-Werkzeuge und End-to-End Plattformen,wie beispielsweise:

- Domino Data Lab, h2o.ai, DVC, activeloop, aporia, argo, arize, bentoML, comet ML, DagsHub, Databricks MLOps Stacks, Feast, Kedro, Metaflow, MLflow, MLRun, prefect, PrimeHub, Weights & Biases, WhyLabs, zenML, KNIME, RapidMiner, NVIDIA AI Enterprise, watsonx.ai
- OpenSource: MLFlow, Kubeflow, ClearML
- PaaS: AWS SageMaker, Azure ML, Google Vertex AI

### 5.3. Referenzen

[Chen et al. 2022], [Gharbi et al. 2026], [Haviv et al. 2023], [Kumara et al.], [Osipov 2022], [Salama et al.], [Tan Wei Hao et al. 2024], [Treveil et al. 2020], [Wilson 2022]

## 6. Systemarchitekturen und Plattformen für Generative KI-Systeme

|  |  |
| --- | --- |
| Dauer: 160 Min. | Übungszeit: 30 Min. |

### 6.1. Begriffe und Konzepte

Generative KI, LLMs, MLflow, Managed MLflow, Azure Machine Learning, Metaflow, Generative KI, LLM, (Stable) Diffusion, Vektor-DB, Embedding, RNN, Transformer, RAG, Agentic Workflows etc.

### 6.2. Lernziele

#### LZ 6-1: Integrationsebenen von KI überblicken

Die Teilnehmer:innen können verschiedene Integrationsebenen von KI unterscheiden und ihre jeweiligen Funktionen und Einsatzbereiche erläutern. Dazu gehören die folgenden Ebenen:

- Anwendungen (z. B. Coding Assistenten)
- AI-Engineering (z. B. Prompt Engineering)
- ML-Modellentwicklung (z. B. pytorch)
- ML-Infrastruktur (z. B. Vektor-DBs).

Die Teilnehmer:innen kennen einige Beispiele von verbreiteten Bibliotheken, Schnittstellen und Tools zur Integration von KI-Modellen.

#### LZ 6-2: KI-Systeme in die Gesamtarchitektur einer IT-Landschaft integrieren

Die Teilnehmer:innen kennen Möglichkeiten, KI-Systeme in IT-Landschaften auf strategischer Ebene zu integrieren. Beispielsweise können sie das strategische Design von DDD (insbesondere Context Maps) einsetzen, um die Art und den Grad der Integration von KI-Systemen zu bestimmen und zu dokumentieren.

Die Teilnehmer:innen üben anhand eines Fallbeispiels mit einer ausgedachten Fachlichkeit, geeignete Integrationsmöglichkeiten für KI in einer bestehenden Software-Landschaft anzuwenden, und diskutieren die Umsetzung.

#### LZ 6-3: Generative KI und ihre Funktionsweise grundlegend verstehen

Die Teilnehmer:innen haben ein grundlegendes Verständnis von generativer KI wie beispielsweise LLMs und Diffusionmodelle.

Die Teilnehmer:innen verstehen die Funktionsweise von LLMs und können die zugehörige Begriffswelteinordnen: Token, Embedding, RNN, Transformer, Attention.

#### LZ 6-4: Architekturmuster für den Einsatz von LLMs kennen und deren Einsatzgrenzen, Risiken und Trade-offs bewerten, insbesondere bei RAG, Function Calling, Fine-Tuning, Assistenzsystemen und Agenten.

Die Teilnehmer:innen kennen bekannte Patterns bei der Nutzung von LLMs und können deren Einsatzgrenzen, Risiken und Trade-offs anhand konkreter Anforderungen und Anwendungsszenarien bewerten. Dies umfasst die folgenden Patterns:

- RAG und Retrieval-Strategien
- Function Calling
- Finetuning
- Assistenten
- Agenten

#### LZ 6-5: Use-Cases für RAG (Retrieval-Augmented Generation) sowie ausgewählte RAG-Techniken kennen und verstehen

Die Teilnehmer:innen können typische Use-Cases für RAG wie beispielsweise „Talk to your documents/database/API“ erläutern.

Insbesondere können die Teilnehmer:innen die grundlegende Funktionsweise einer Auswahl gängiger RAG-Techniken erklären und diese voneinander unterscheiden, beispielsweise:

- Reguläres RAG, GraphRAG, CAG, Agentic RAG and Multi-Agent RAG
- Context Enrichment Techniques
- Fusion Retrieval
- Intelligent Reranking
- Query Transformations
- Adaptive Retrieval
- Iterative Retrieval
- Ensemble Retrieval
- Knowledge Graph Integration

#### LZ 6-6: Arten von Prompt Engineering kennen

Die Teilnehmer:innen kennen verschiedene Arten von Prompt Engineering, wie beispielsweise

- Few-Shot-Learning
- Chain-of-Thought
- Role-Playing

sowie allgemeine Best Practices für das Prompting.

#### LZ 6-7: Agentic Workflows hinsichtlich Planung, Werkzeugnutzung, Reflexion, Zustandsmanagement, Kontrollmechanismen und Multi-Agenten-Kollaboration analysieren und architektonisch einordnen.

Die Teilnehmer:innen wissen, was Agentic Workflows sind, und kennen die Begriffe Reflexion, Werkzeugnutzung, Planung und Multi-Agenten-Kollaboration. Sie können Agentic Workflows hinsichtlich Planung, Werkzeugnutzung, Reflexion, Zustandsmanagement, Kontrollmechanismen und Multi-Agenten-Kollaboration analysieren, die Zusammenhänge dieser Komponenten untersuchen und deren Bedeutung für die Architektur von KI-Systemen einordnen.

#### LZ 6-8: Eine Auswahl von Design Patterns für Generative KI-Systeme kennen

Die Teilnehmer:innen wissen welche Design Patterns für Generative KI-Systeme existieren. Sie kennen eine Auswahl der folgenden Patterns:

- AI Query Router (Simple Router; Ranking-based Router; Learning-based Router)
- Layered Caching Strategy Leading to Fine-Tuning
- Multiplexing AI Agents
- Fine-Tuning LLMs for Multiple Tasks
- Blending Rules-Based and Generative Approaches
- Utilizing Knowledge Graphs with LLMs
- Swarm of Generative AI Agents
- Modular Monolith LLM Approach with Composability
- Memory Cognition for LLMs
- Red and Blue Team Dual-Model Evaluation

#### LZ 6-9: Techniken zur Evaluation von LLM-Anwendungen auswählen und auf Antwortqualität, Retrieval-Qualität, Halluzinationen, Sicherheit, Kosten und Nutzermehrwert anwenden.

Die Teilnehmer:innen kennen mehrere Techniken zur Evaluation von LLM-Anwendungen. Sie können diese hinsichtlich ihrer Eignung für konkrete Evaluationsziele bewerten, geeignete Techniken auswählen und zur Beurteilung von Antwortqualität, Retrieval-Qualität, Halluzinationen, Sicherheit, Kosten und Nutzermehrwert anwenden. Dies können beispielsweise die folgenden Techniken sein:

- Scoring
- Human Feedback
- Comparative Evaluation
- Model Based Evaluation

Die Teilnehmer:innen kennen gängige Evaluations-Frameworks wie beispielsweise LangSmith oder LangFuse, um mit Unbestimmtheit und Fehlern in KI-Systemen umzugehen.

#### LZ 6-10: Bekannte LLMs und Auswahlkriterien überblicken

Die Teilnehmer:innen kennen bekannte LLMs wie beispielsweise GPT, Claude, Gemini, Llama, Mistral oder Luminous und können deren wesentliche Unterschiede sowie relevante Auswahlkriterien für ein geeignetes LLM erläutern.

#### LZ 6-11: Bedeutung von Cost Management für GenAI Applikationen verstehen

Die Teilnehmer:innen verstehen die Bedeutung von Cost Management für GenAI Applikationen.

#### LZ 6-12: Klassen von Bibliotheken, Schnittstellen und Werkzeugen für LLM-Anwendungen sowie deren Einsatzkontexte und Auswahlkriterien kennen.

Die Teilnehmer:innen kennen einige Beispiele von verbreiteten Bibliotheken, Schnittstellen und Tools im Zusammenhang mit LLM-Anwendungen wie beispielsweise OpenAI-API oder LangChain.

#### LZ 6-13: [OPTIONAL] Agentic-AI-Architekturen, zentrale Architekturkomponenten, Sicherheits- und Governance-Grenzen sowie typische Einsatzmuster und Grenzen von Agentensystemen kennen und bewerten.

Die Teilnehmer:innen kennen Agentic AI Software Architekturen, AI Agent Architekturkomponenten und Typen von AI Agentarchitekturen. Sie können unterschiedliche Agentic-AI-Architekturen hinsichtlich ihrer zentralen Architekturkomponenten, typischen Einsatzmuster, Einsatzgrenzen sowie Sicherheits- und Governance-Anforderungen bewerten und ihre Einschätzung anhand konkreter Anwendungsszenarien begründen.

#### LZ 6-14: Agenten-Laufzeitsysteme für LLM- und Agentensysteme architektonisch einordnen und anwenden

Die Teilnehmer:innen verstehen Agenten-Laufzeitsysteme als architektonische Kontroll- und Integrationsschicht für probabilistische KI-Komponenten wie LLMs und Agenten. Sie können Harness-Ansätze mit klassischen Architekturkonzepten wie Kapselung, Schnittstellenkontrolle, Invarianten, Betriebsgrenzen, Observability, Policy Enforcement, Fehlerisolierung, kontrollierter Änderung, Governance und Auditierbarkeit beschreiben und beim Entwurf produktionsfähiger KI-Systeme anwenden. Sie können insbesondere ableiten, wie ein Agenten-Laufzeitsystem:

- die Autonomie einer KI-Komponente durch klare Schnittstellen, erlaubte Aktionen und Betriebsgrenzen begrenzt,
- Eingaben, Kontext, Toolzugriffe, Zustände und Ausgaben kontrolliert,
- Systeminvarianten und Policies durchsetzt,
- Fehler und unsichere Modelloutputs isoliert,
- Beobachtbarkeit, Nachvollziehbarkeit und Auditierbarkeit sicherstellt,
- kontrollierte Änderungen an Prompts, Modellen, Retrieval-Komponenten und Tools ermöglicht,
- Sicheren Betrieb sowie die sichere Weiterentwicklung von KI-Systemen unterstützt.

### 6.3. Referenzen

[Bahree 2024], [bornstein-radovanic], [Dibia 2025], [Foster 2023], [Gharbi et al. 2026], [Gradient Flow], [Koc], [Parnin], [Spirin et al.]

## 7. Fallstudien und Praxisprojekte

|  |  |
| --- | --- |
| Dauer: 110 Min. | Übungszeit: 110 Min. |

### 7.1. Lernziele

#### LZ 7-1: Anhand einer durchgehenden Fallstudie oder eines Praxisprojekts Architekturentscheidungen für ein KI-System treffen, dokumentieren, begründen und im Hinblick auf Qualität, Compliance, Betrieb und Integration bewerten.

Die Teilnehmer:innen können anhand einer durchgehenden Fallstudie oder eines Praxisprojekts eigenständig Architekturentscheidungen für ein KI-System treffen, dokumentieren und begründen. Dabei können sie die getroffenen Entscheidungen hinsichtlich relevanter Qualitätsanforderungen, regulatorischer Anforderungen (Compliance), betrieblicher Aspekte und der Integration in bestehende IT-Systeme bewerten.

### 7.2. Referenzen

[Gharbi et al. 2026]

## Referenzen

Dieser Abschnitt enthält Quellenangaben, die ganz oder teilweise im Curriculum referenziert werden.

**A**

- [Agrawal et al.] A. Agrawal, J. Gans, A. Goldfarb:  Prediction Machines: The Simple Economics of Artificial Intelligence [https://www.predictionmachines.ai/](https://www.predictionmachines.ai/)
- [ATLAS] ATLAS - Adversarial Threat Landscape for Artificial-Intelligence Systems. [https://github.com/mitre/advmlthreatmatrix](https://github.com/mitre/advmlthreatmatrix)

**B**

- [Bahree 2024] Bahree, A.: Generative AI in Action [https://www.manning.com/books/generative-ai-in-action](https://www.manning.com/books/generative-ai-in-action)
- [Bhajaria 2022] N. Bhajaria: Data Privacy - A runbook for engineers [https://www.manning.com/books/data-privacy](https://www.manning.com/books/data-privacy)
- [Bornstein et al.] M. Bornstein, J. Li, M. Casado: Emerging Architectures for Modern Data Infrastructure [https://a16z.com/emerging-architectures-for-modern-data-infrastructure/](https://a16z.com/emerging-architectures-for-modern-data-infrastructure/)
- [bornstein-radovanic] M. Bornstein and R. Radovanovic: Emerging Architectures for LLM Applications [https://a16z.com/emerging-architectures-for-llm-applications/](https://a16z.com/emerging-architectures-for-llm-applications/)
- [Brynjolfsson et al.] Brynjolfsson, E.: The Productivity J-Curve: How Intangibles complement General Purpose Technologies [https://www.nber.org/system/files/working_papers/w25148/w25148.pdf](https://www.nber.org/system/files/working_papers/w25148/w25148.pdf)
- [Burkov 2019] Burkov, A.: The Hundred-Page Machine Learning Book [https://themlbook.com/](https://themlbook.com/)

**C**

- [Cdteliot] AI Agents: Understanding Their Impact and Functions [https://www.perplexity.ai/page/ai-agents-understanding-their-bL1Mg8FeStyUB4o9u3HT5Q](https://www.perplexity.ai/page/ai-agents-understanding-their-bL1Mg8FeStyUB4o9u3HT5Q)
- [Chen et al. 2022] C. Chen, N. R. Murphy, K. Parisa, D. Sculley, T. Underwood: Reliable Machine Learning [https://www.oreilly.com/library/view/reliable-machine-learning/9781098106218/](https://www.oreilly.com/library/view/reliable-machine-learning/9781098106218/)
- [Chong et al.] J. Chong, Y. C. Chang: How to Lead in Data Science [https://www.manning.com/books/how-to-lead-in-data-science](https://www.manning.com/books/how-to-lead-in-data-science)
- [Crowe et al. 2024] R. Crowe, H. Hapke, E. Caveness, D. Zhu: Machine Learning Production Systems [https://learning.oreilly.com/library/view/machine-learning-production/9781098156008/](https://learning.oreilly.com/library/view/machine-learning-production/9781098156008/)
- [CSIRO et al. 2023] CSIRO, Q. Lu, J. Wittle, X. Xu, L. Xhu: Responsible AI: Best Practices for Creating Trustworthy AI Systems [https://www.oreilly.com/library/view/responsible-ai-best/9780138073947/](https://www.oreilly.com/library/view/responsible-ai-best/9780138073947/)

**D**

- [Dehghani] Z. Dehghani: Data Mesh [https://learning.oreilly.com/library/view/data-mesh/9781492092384/](https://learning.oreilly.com/library/view/data-mesh/9781492092384/)
- [Dell’Acqua 2026] Fabrizio Dell’Acqua et al.: Paper: "Navigating the Jagged Technological Frontier: Field Experimental Evidence of the Effects of AI on Knowledge Worker Productivity and Quality" [https://doi.org/10.1287/orsc.2025.21838](https://doi.org/10.1287/orsc.2025.21838)
- [Dibia 2025] V. Dibia with C. Wang: Multi-Agent Systems with AutoGen [https://www.manning.com/books/multi-agent-systems-with-autogen](https://www.manning.com/books/multi-agent-systems-with-autogen)

**E**

- [EU AI Act] EU AI Act [https://artificialintelligenceact.eu/de/ai-act-explorer/](https://artificialintelligenceact.eu/de/ai-act-explorer/)

**F**

- [Ford et al.] N. Ford, M. Richards, P. Sadalage, Z. Dehghani Software Architecture: The Hard Parts. [https://learning.oreilly.com/library/view/software-architecture-the/9781492086888/](https://learning.oreilly.com/library/view/software-architecture-the/9781492086888/)
- [Foster 2023] D. Foster: Generative Deep Learning, 2nd Edition [https://www.oreilly.com/library/view/generative-deep-learning/9781098134174/](https://www.oreilly.com/library/view/generative-deep-learning/9781098134174/)

**G**

- [Gharbi et al. 2026] M. Gharbi, H. Klus, H. Tiemeyer, M. Zhang: Praxiswissen Softwarearchitektur für KI-Systeme: Grundlagen, Konzepte, Techniken und Plattformen. Aus- und Weiterbildung zum Certified Professional for Software Architecture – Advanced Level – Modul SWARC4AI nach iSAQB®-Standard. dpunkt.verlag, 2026.
- [Géron 2022] Aurélien Géron: Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow [https://learning.oreilly.com/library/view/hands-on-machine-learning/9781098125967/](https://learning.oreilly.com/library/view/hands-on-machine-learning/9781098125967/)
- [Gradient Flow] LLM Routers Unpacked [https://gradientflow.com/llm-routers-unpacked/](https://gradientflow.com/llm-routers-unpacked/)

**H**

- [Hall et al. 2023] P. Hall, J. Curtis, P. Pandey: Machine Learning for High-Risk Applications [https://www.oreilly.com/library/view/machine-learning-for/9781098102425/](https://www.oreilly.com/library/view/machine-learning-for/9781098102425/)
- [Harvard et al. 2024] Harvard Business Review, E. Mollick, D. De Cremer, T. Neeley, P. Sinha: Generative AI: The Insights You Need. (Generative AI Use Cases) [https://learning.oreilly.com/library/view/generative-ai-the/9781647826406/](https://learning.oreilly.com/library/view/generative-ai-the/9781647826406/)
- [Haviv et al. 2023] Y. Haviv, N. Gift: Implementing MLOps in the Enterprise [https://www.oreilly.com/library/view/implementing-mlops-in/9781098136574/](https://www.oreilly.com/library/view/implementing-mlops-in/9781098136574/)
- [Heiland et al. 2023] L. Heiland, M. Hauser, J. Bogner: Design Patterns for AI-based Systems: A Multivocal Literature Review and Pattern Repository. 2023 IEEE/ACM 2nd International Conference on AI Engineering–Software Engineering for AI (CAIN). IEEE, 2023.
- [Hotz, Best Practices] N. Hotz: 15 Data Science Documentation Best Practices [https://www.datascience-pm.com/documentation-best-practices/](https://www.datascience-pm.com/documentation-best-practices/)
- [Hotz, Life Cycle] N. Hotz: What is a Data Science Life Cycle? [https://www.datascience-pm.com/data-science-life-cycle/](https://www.datascience-pm.com/data-science-life-cycle/)
- [Hotz, TDSP] N. Hotz: What is TDSP [https://www.datascience-pm.com/tdsp/](https://www.datascience-pm.com/tdsp/)
- [Huyen 2022] C. Huyen: Designing Machine Learning Systems [https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/)

**J**

- [Jarmul 2023] K. Jarmul: Practical Data Privacy [https://www.oreilly.com/library/view/practical-data-privacy/9781098129453/](https://www.oreilly.com/library/view/practical-data-privacy/9781098129453/)
- [Jones] A. Jones: Driving Data Quality with Data Contracts [https://learning.oreilly.com/library/view/driving-data-quality/9781837635009/](https://learning.oreilly.com/library/view/driving-data-quality/9781837635009/)

**K**

- [Kelleher 2015] John D. Kelleher, Brian Mac Namee, and Aoife D’Arcy: Fundamentals of Machine Learning for Predictive Data Analytics [https://mitpress.mit.edu/9780262029445/fundamentals-of-machine-learning-for-predictive-data-analytics](https://mitpress.mit.edu/9780262029445/fundamentals-of-machine-learning-for-predictive-data-analytics)
- [Koc] V. Koc: Generative AI Design Patterns: A Comprehensive Guide [https://towardsdatascience.com/generative-ai-design-patterns-a-comprehensive-guide-41425a40d7d0](https://towardsdatascience.com/generative-ai-design-patterns-a-comprehensive-guide-41425a40d7d0)
- [Kumara et al.] I. Kumara, R., D. Di Nucci, W. J. Van Den Heuvel, D. A. Tamburri: Requirements and Reference Architecture for MLOps:Insights from Industry [https://www.techrxiv.org/doi/full/10.36227/techrxiv.21397413.v1](https://www.techrxiv.org/doi/full/10.36227/techrxiv.21397413.v1)

**L**

- [Lakshmanan et al.] V. Lakshmanan, S Robinson, M. Munn: Machine Learning Design Patterns [https://learning.oreilly.com/library/view/machine-learning-design/9781098115777/](https://learning.oreilly.com/library/view/machine-learning-design/9781098115777/)

**M**

- [Masood et al. 2023] A. Masood, H. Dawe: Responsible AI in the Enterprise [https://www.oreilly.com/library/view/responsible-ai-in/9781803230528/](https://www.oreilly.com/library/view/responsible-ai-in/9781803230528/)
- [ML software architecture] ML software architecture [https://appliedaiinitiative.notion.site/ML-software-architecture-790b9f5fcfcf408884287acb82f4d75e](https://appliedaiinitiative.notion.site/ML-software-architecture-790b9f5fcfcf408884287acb82f4d75e)
- [Molnar 2024] C. Molnar: Interpretable Machine Learning, 2nd ed. [https://christophm.github.io/interpretable-ml-book/](https://christophm.github.io/interpretable-ml-book/)

**N**

- [Nahar et al.] N. Nahar, et al.: A meta-summary of challenges in building products with ml components–collecting experiences from 4758+ practitioners. 2023 IEEE/ACM 2nd International Conference on AI Engineering–Software Engineering for AI (CAIN). IEEE, 2023.
- [NirDiamant] RAG Techniques [https://github.com/NirDiamant/RAG_Techniques](https://github.com/NirDiamant/RAG_Techniques)
- [Nist] NIST AI Risk Management Framework. [https://www.nist.gov/itl/ai-risk-management-framework](https://www.nist.gov/itl/ai-risk-management-framework)

**O**

- [Osipov 2022] C. Osipov: MLOps Engineering at Scale [https://www.manning.com/books/mlops-engineering-at-scale](https://www.manning.com/books/mlops-engineering-at-scale)

**P**

- [Parnin] Building Your Own Product Copilot: Challenges, Opportunities, and Needs [https://arxiv.org/pdf/2312.14231v1](https://arxiv.org/pdf/2312.14231v1)
- [Pruksachatkun et al. 2023] Y. Pruksachatkun, M. Mcateer, S. Majudmar: Practicing Trustworthy Machine Learning [https://www.oreilly.com/library/view/practicing-trustworthy-machine/9781098120269/](https://www.oreilly.com/library/view/practicing-trustworthy-machine/9781098120269/)

**R**

- [Reis et al.] J. Reis, M. Housley: Fundamentals of Data Engineering [https://learning.oreilly.com/library/view/fundamentals-of-data/9781098108298/](https://learning.oreilly.com/library/view/fundamentals-of-data/9781098108298/)
- [Roser 2022] Roser, Max: Brief History of AI: [https://ourworldindata.org/brief-history-of-ai](https://ourworldindata.org/brief-history-of-ai)

**S**

- [Salama et al.] K. Salama, J. Kazmierczak, D. Schut: Practitioners guide to MLOps: A framework for continuous delivery and automation of machine learning. [https://services.google.com/fh/files/misc/practitioners_guide_to_mlops_whitepaper.pdf](https://services.google.com/fh/files/misc/practitioners_guide_to_mlops_whitepaper.pdf)
- [Saltz] J. Saltz: The GenAI Life Cycle [https://www.datascience-pm.com/the-genai-life-cycle/](https://www.datascience-pm.com/the-genai-life-cycle/)
- [Sanderson et al.] C. Sanderson, M. Freeman: Data Contracts [https://learning.oreilly.com/library/view/data-contracts/9781098157623/](https://learning.oreilly.com/library/view/data-contracts/9781098157623/)
- [Sarkis] A. Sarkis: Training Data for Machine Learning [https://learning.oreilly.com/library/view/training-data-for/9781492094517/](https://learning.oreilly.com/library/view/training-data-for/9781492094517/)
- [Savarese] S. Savarese: How AI Agents Will Revolutionize the AI Enterprise [https://www.salesforce.com/blog/how-ai-agents-will-revolutionize-the-ai-enterprise/](https://www.salesforce.com/blog/how-ai-agents-will-revolutionize-the-ai-enterprise/)
- [Serban] A. Serban, J. Visser: "Adapting software architectures to machine learning challenges." 2022 IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER). IEEE, 2022.
- [Serra] J. Serra: Deciphering Data Architectures [https://learning.oreilly.com/library/view/deciphering-data-architectures/9781098150754/](https://learning.oreilly.com/library/view/deciphering-data-architectures/9781098150754/)
- [Spirin et al.] N. Spirin, M. Balint: Mastering LLM Techniques: LLMOps [https://developer.nvidia.com/blog/mastering-llm-techniques-llmops/](https://developer.nvidia.com/blog/mastering-llm-techniques-llmops/)
- [Studer et al.] S. Studer et al.: Towards CRISP-ML(Q): A Machine Learning Process Model with Quality Assurance Methodology [https://arxiv.org/abs/2003.05155](https://arxiv.org/abs/2003.05155)

**T**

- [Tan et al.] D. Tan, A. Leung, D. Colls: Effective Machine Learning Teams [https://learning.oreilly.com/library/view/effective-machine-learning/9781098144623/](https://learning.oreilly.com/library/view/effective-machine-learning/9781098144623/)
- [Tan Wei Hao et al. 2024] B. Tan Wei Hao, S. Padmanabhan, V. Mallya: Design a Machine Learning System (From Scratch) [https://www.manning.com/books/design-a-machine-learning-system-design-from-scratch](https://www.manning.com/books/design-a-machine-learning-system-design-from-scratch)
- [tdcox] MLOps Roadmap 2024 - DRAFT [https://github.com/cdfoundation/sig-mlops/blob/main/roadmap/2024/MLOpsRoadmap2024.md](https://github.com/cdfoundation/sig-mlops/blob/main/roadmap/2024/MLOpsRoadmap2024.md)
- [Treveil et al. 2020] M. Treveil, N. Omont, C. Stenac, K. Lefevre, D. Phan, J. Zentici, A. Lavoillotte, M. Miyazaki, L. Heidmann: Introducing MLOps [https://www.oreilly.com/library/view/introducing-mlops/9781492083283/](https://www.oreilly.com/library/view/introducing-mlops/9781492083283/)
- [TU Berlin] Architecture of Machine Learning Systems (TU Berlin, SS 2024): [https://mboehm7.github.io/teaching/ss24_amls/index.htm](https://mboehm7.github.io/teaching/ss24_amls/index.htm)

**V**

- [Vaughan 2020] Vaughan, D.: Analytical Skills for AI and Data Science (AI Use Cases) [https://learning.oreilly.com/library/view/analytical-skills-for/9781492060932/](https://learning.oreilly.com/library/view/analytical-skills-for/9781492060932/)
- [Visengeriyeva, JTF] Visengeriyeva, L.: Defining Jagged Technological Frontier: [https://www.perplexity.ai/page/defining-jagged-technological-iF8sDPVFQEKSdd2oyytztA](https://www.perplexity.ai/page/defining-jagged-technological-iF8sDPVFQEKSdd2oyytztA)
- [Visengeriyeva, AI Agents] Visengeriyeva, L.: AI Agents vs. Traditional Models [https://www.perplexity.ai/page/ai-agents-vs-traditional-model-JFf4gKT0RySW_Ehvbxho2g](https://www.perplexity.ai/page/ai-agents-vs-traditional-model-JFf4gKT0RySW_Ehvbxho2g)
- [Visengeriyeva, Ethics] Model Governance, Ethics, Responsible AI (Linksammlung) [https://github.com/visenger/Awesome-ML-Model-Governance](https://github.com/visenger/Awesome-ML-Model-Governance)

**W**

- [Wang et al. 2024] C. Wang et al.: Quality Assurance for Artificial Intelligence: A Study of Industrial Concerns, Challenges and Best Practices [https://arxiv.org/pdf/2402.16391](https://arxiv.org/pdf/2402.16391)
- [Wilson 2022] B. Wilson: Machine Learning Engineering in Action [https://www.manning.com/books/machine-learning-engineering-in-action](https://www.manning.com/books/machine-learning-engineering-in-action)

**Z**

- [Zaharia et al.] M. Zaharia et al.: The Shift from Models to Compound AI Systems [https://bair.berkeley.edu/blog/2024/02/18/compound-ai-systems/](https://bair.berkeley.edu/blog/2024/02/18/compound-ai-systems/)
