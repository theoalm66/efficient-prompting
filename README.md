# Eefizientes Prompting

Willkommen im Repository für strukturiertes und effizientes Prompting! Dieses Projekt bietet praxisnahe Lernmaterialien, Use Cases und Vorlagen, um generative KI im Arbeitsalltag zielgerichtet, sicher und reproduzierbar einzusetzen. 

Das Herzstück bilden interaktive One-Pager, die direkt im Browser genutzt werden können, um Prompt-Vorlagen zu kopieren und die Logik dahinter zu verstehen.

---

## 🗂 Inhalt des Repositories

Die Navigation erfolgt zentral über die `index.html` im Hauptverzeichnis. Das Repository gliedert sich in drei Hauptbereiche:

### 1. Grundlagen – Strukturiertes Prompting
*(Datei: `Grundlage/001_prompting_onepager_v01.html`)*

Ein interaktiver Guide, der die Basis für sauberes Prompt-Design (u. a. mit Markdown, XML-Tags und Tabellen) vermittelt.
* **Theorie:** Was ist strukturiertes Prompting, wo liegen die Vor- und Nachteile?
* **Praxis:** 8 direkt anwendbare Top Use Cases aus dem Arbeitsalltag:
  1. Zusammenfassung von Meetings & Protokollen
  2. Wissenschaftliche Publikationen extrahieren
  3. Experteninput adressatengerecht aufbereiten
  4. Antwortschreiben & Anfragen formulieren
  5. Texte in allgemeinverständliche Sprache (Bürgeranfragen) übersetzen
  6. Arbeitsanweisungen / Prozessdefinitionen erstellen
  7. Bewertung nach standardisierten Kriterien
  8. Abgleich mit Leitlinien/DIN (Gap-Analyse)

### 2. Vertiefung – Advanced: R-Code, CustomGPT & Python
*(Datei: `Vertiefung/002_prompting_onepager_vertiefung_v01.html`)*

Der Expertenteil für fortgeschrittene Anwender, die ganze Prozesse automatisieren wollen.
* **Track A (R-Code):** Prompt-Spezifikation für robuste und reproduzierbare statistische Auswertungen in R.
* **Track B (CustomGPT Architektur):** Aufbau eines eigenen GPTs zur Vorprüfung von Dokumenten. Zeigt die Trennung von Systemprompt (Instructions), Wissensbasis (Knowledge-Dateien wie Guidelines & Mapping) und strukturiertem User-Prompt.
* **Track C (Python & Execution):** End-to-End Datenanalyse am Beispiel fiktiver E-Commerce-Sales-Daten, bei der die KI (z. B. via Advanced Data Analysis) angewiesen wird, den Code nicht nur zu schreiben, sondern direkt auszuführen.

### 3. Lokaler Prompt Generator
*(Datei: `Promptgenerator/generator.html`)*

Ein interaktives Tool, das lokal im Browser läuft. Es hilft dabei, eigene Arbeitsaufträge in eine saubere Markdown-Struktur (Aufgabe, Kontext, Input, Regeln, Ausgabeformat) zu gießen, um sie anschließend direkt in ein KI-Tool der Wahl zu kopieren.

---

## 🚀 Erste Schritte (Nutzung)

Um die Lernmaterialien und Tools zu nutzen, wird kein Server oder Backend benötigt. Alles läuft lokal im Browser.

1. **Repository klonen** oder als `.zip` herunterladen:
   ```bash
   git clone [https://github.com/DeinNutzername/DeinRepository.git](https://github.com/DeinNutzername/DeinRepository.git)
