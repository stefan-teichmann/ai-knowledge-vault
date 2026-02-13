# 🧠 AI Knowledge Base - Vault Struktur

Diese Dokumentation erklärt den Aufbau und die Logik dieses Obsidian-Vaults. Die Struktur folgt einer hybriden Logik aus PARA und thematischer Trennung.

## 📂 Ordner-Übersicht

| Ordner | Beschreibung | Git-Status |
| :--- | :--- | :--- |
| `00_Inbox` | Temporärer Speicher für neue Notizen, Web-Clippings und flüchtige Gedanken. | Tracked |
| `10_Konzepte` | Fachwissen zu KI (LLMs, RAG, Architekturen). Das "Lexikon". | Tracked |
| `20_Prompts` | Sammlung von System-Prompts, User-Prompts und Prompt-Engineering Techniken. | Tracked |
| `30_Tools` | Dokumentation zu Software, APIs und Frameworks (z.B. LangChain, OpenAI). | Tracked |
| `40_Lernen` | Strukturierte Kursnotizen, Zertifikate und Zusammenfassungen von Schulungen. | Tracked |
| `50_Ergebnisse` | Eigene Projekte, Case Studies und aufbereitete Chat-Zusammenfassungen. | Tracked |
| `80_Persoenlich` | Private Gedanken, Journaling und interne Notizen. | **Ignored** |
| `90_System` | Vorlagen (Templates), Skripte und Anhänge (Bilder/PDFs). | Tracked |

## 🛠 Nutzung von Git
- Der Vault ist als Git-Repository initialisiert.
- Der Ordner `80_Persoenlich/` ist in der `.gitignore` eingetragen, um Privatsphäre bei der Kollaboration zu gewährleisten.
- Binärdateien (PDFs, Bilder) werden in `90_System/Attachments` abgelegt.

## Obsidian-Möglichkeiten effektiv nutzen

Obsidian ist mehr als nur ein Texteditor. Um die KI-Thematik abzubilden, solltest du folgende Features nutzen:

- **Properties (YAML):** Jede Notiz sollte Metadaten haben.
    
    - `type`: (e.g., Prompt, Tool, Concept)
    - `status`: (e.g., Draft, Final, Obsolete)
    - `tags`: (e.g., #LLM, #Python, #VectorDB)
        
- **Dataview-Plugin:** Das ist ein Muss. Damit kannst du dynamische Tabellen erstellen, z. B. eine Liste aller Prompts für "Bildgenerierung", ohne sie manuell pflegen zu müssen.
    
- **Templates (Vorlagen):** Erstelle Vorlagen für Prompts (mit Feldern für "Zielgruppe", "Context", "Constraints") oder für Kursnotizen.
    
- **Canvas:** Nutze das Canvas-Feature, um komplexe KI-Workflows oder Agenten-Strukturen visuell zu skizzieren.

## Prompts und Chats festhalten

Hier schleppen viele Nutzer unnötigen Ballast mit. So machst du es besser:

- **Prompts:** Speichere sie als einzelne Markdown-Dateien im Ordner `20_Prompts`. Nutze Code-Blöcke für den eigentlichen Prompt. Dokumentiere dazu, für welches Modell der Prompt optimiert wurde (z.B. GPT-4o vs. Claude 3.5).
    
- **AI-Chats:** Kopiere keine 50-seitigen Verläufe. Erstelle eine **Zusammenfassung** des Erkenntnisgewinns. Wenn der Chat wichtig ist, nutze ein Plugin (wie _JSON to Markdown_ oder spezifische Browser-Extensions), um ihn sauber formatiert abzulegen.
    
- **Verlinkung:** Verknüpfe den Chat immer mit dem zugrunde liegenden Prompt (`[[Mein_Super_Prompt]]`).

## KI-Agenten mit dem Wissen anreichern

Wenn du später einen eigenen Agenten (z. B. einen Custom GPT oder einen lokalen RAG-Agenten) mit deinem Wissen füttern willst:

1. **Markdown-Export:** Da alles in Markdown vorliegt, können LLMs die Daten hervorragend lesen.
    
2. **Git-Integration:** Du kannst deinen Vault auf ein privates GitHub-Repository pushen. Viele Agenten-Frameworks (wie CrewAI oder AutoGPT) können direkt auf Git-Repos zugreifen.
    
3. **Vektorisierung:** Tools wie `AnythingLLM` oder `Smart Connections` (Obsidian Plugin) erlauben es dir, eine lokale Vektordatenbank über deinen Vault zu legen, um direkt in Obsidian mit deinem Wissen zu chatten.

Persönliches vs. Schulungen
Persönliche Notizen: Diese gehören in 80_Personal. Wichtig: Wenn du den Vault via Git teilst, solltest du diesen Ordner in die .gitignore-Datei aufnehmen, damit private Gedanken nicht im öffentlichen (oder Team-) Repo landen.

Schulungen:

40_Learning/Courses: Für strukturierte Kurse (z.B. Coursera, Udemy). Jede Vorlesung eine Notiz.

40_Learning/Resources: Für lose YouTube-Videos oder Artikel.

Tipp: Nutze das Plugin Media Extended, um Zeitstempel aus Videos direkt in deine Notizen zu übernehmen.

6. Was ist für effektives Wissensmanagement zu beachten?
Atomarität: Schreibe kurze Notizen zu einem Thema, statt riesige Dokumente. Verlinke sie lieber ([[Linking]]).

Die 2-Minuten-Regel: Wenn das Einordnen einer Notiz länger als 2 Minuten dauert, ist deine Struktur zu komplex.

Git-Routine: Gewöhne dir an, am Ende des Tages einen Commit zu machen. Nutze das Plugin Obsidian Git, um das automatisch im Hintergrund erledigen zu lassen.

MOCs (Map of Content): Erstelle zentrale Inhaltsverzeichnisse für große Themenbereiche (z. B. eine Notiz "KI-Agenten", die alle Unteraspekte verlinkt).

Ein kleiner Rat unter "Kollegen": Fang klein an. Der größte Fehler ist es, Wochen mit dem Bauen der perfekten Ordnerstruktur zu verbringen, anstatt tatsächlich Wissen zu kuratieren. Die Struktur wächst mit dem Inhalt.

## Erweiterungen / Plugins für Obsidian

- **Templater:** {{date}} oder {{title}} werdem beim Erstellen der Datei automatisch durch korrekte Werte ersetzt
- **Dataview-Plugin:** dynamische Tabellen
- **Media Extended:** Zeitstempel aus Videos direkt in Notizen zu übernehmen
