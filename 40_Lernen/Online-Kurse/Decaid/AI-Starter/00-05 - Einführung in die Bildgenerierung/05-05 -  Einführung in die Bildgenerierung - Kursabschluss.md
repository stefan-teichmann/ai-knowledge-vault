---
typ: Kurs
plattform:
  - Decaid
instruktor:
status:
  - 🔴 Nicht gestartet / 🟡 In Arbeit / 🟢 Abgeschlossen
kurs_link: https://app.decaid.academy/course/introduction-to-image-generation
tags:
  - lernen
  - weiterbildung
  - ai
  - "#ki"
erstellt: 2026-02-13
---
# 🎓 Kurs:  Einführung in die Bildgenerierung - Kursabschluss

> [!abstract] 



# 📂 Kurs-Materialien

## Wir fassen die wichtigsten Punkte zusammen und geben dir Tipps, wie du Chatbots weiter für dich nutzen kannst.
## Kursabschluss - 00:36

## Kurszusammenfassung
[[00-05-05_Kurs Zusammenfassung.pdf]]

### **Einführung in die Bildgenerierung**

#### 🚀 Ziel des Kurses

Der Kurs vermittelt praxisnahes Wissen zur KI-gestützten Bildgenerierung – von den
Grundlagen bis zur Anwendung fortgeschrittener Tools wie Midjourney, Flux oder ComfyUI.
Teilnehmende lernen, visuelle Inhalte selbstständig zu erstellen, kreative Ideen zu visualisieren
und KI effizient für Design, Marketing und Produktentwicklung zu nutzen.

#### 🧠 Grundlagen der Bild-KI
- Text-to-Image: KI übersetzt Textbeschreibungen in Bilder durch Modelle, die mit Millionen Bild-Text-Paaren trainiert wurden.
- Image-to-Image: Verwandlung oder Erweiterung bestehender Bilder.
- Diffusionsmodelle: Bilder entstehen, indem die KI aus Rauschen durch Rückwärtsberechnung ein visuelles Motiv erzeugt.
- Weitere Techniken: Inpainting, Outpainting, Style Transfer, multimodale Modelle (z. B. GPT-4o).

#### 🛠 Midjourney – Kreativtool mit Stil
- Einfache Bedienung über Weboberfläche, mit Parametern wie:
	- --ar (Aspect Ratio), --style, --cw (Character Weight), --sw (Style Weight),
	- --v (Version), --p (Personal Profiling)


- Bildsteuerung durch:
	- Image Prompts (als Input)
	- Character Reference (gleichbleibende Charaktere)
	- Style Reference (Stilkopie von Vorlagen)
	- Omni Reference (V7-exklusiv, sehr präzise Übertragung)
- Personalisierung: über Ranking-System der Plattform (mind. 200 Bildpaare), um eigenen Stil zu trainieren
- Bildbearbeitung: Inpainting, Zoom Out, Remix, Variationen, Upscaling, Formatwechsel

#### 🧪 Open-Source-Modelle & Tools

- Flux als führendes Open-Source-Modell für Text-to-Image
- Tools wie RunDiffusion, Replicate oder ComfyUI ermöglichen hohe Kontrolle und tiefen Workflow-Zugriff
- ComfyUI: visuelles Node-System zur Kombination von Modellen, LoRAs, Upscalern undPromptlogik – ideal für Fortgeschrittene
- Vorteile: flexible Nutzung, kostengünstig, lokal oder cloudbasiert

#### 🎛 Feintuning & ControlNets

- ControlNets bieten präzise Kontrolle über Struktur und Tiefe (z. B. Canny für Kanten,
- Depth für Tiefenwirkung)
- Fine-Tuning mit LoRAs: kleine Zusatzmodelle, die bestehende Modelle personalisieren (z. B. für Produktfotos oder Stilübernahme)
- Wichtig bei individuellen Marken- oder Charaktervisualisierungen

#### 🤖 Tool- & Modellvergleich

- Plattformen: Midjourney, GPT-4o, Seedream, Ideogram, Freepik, Sora
- Unterschiede in:
	- Bildqualität (z. B. Textverständnis bei Sora)
	 - Stil (z. B. künstlerisch vs. realistisch)
	- Rendergeschwindigkeit, Kostenmodell und Feature-Tiefe
- Plattformen wie Replicate und Artificial Analysis ermöglichen Blindtests & Qualitätsvergleiche

####  🔁 Automation & API-Integration

- Anbieter wie Replicate & Fall-AI bieten API-Zugänge für Bildmodelle
- Kombinierbar mit No-Code-Tools (z. B. Make, n8n)
- Beispiel-Workflow: Idee → automatisierte Bilderzeugung → Videogenerierung → Postproduktion

#### ✅ Praxisteile & Übungen


- Aufgaben mit Midjourney: Charakterdesign, Stilvariationen, Omni-Referenz
- Übungen mit ComfyUI: Workflow laden, Bild generieren, Upscaling, ControlNet  ausprobieren
- Promptvergleiche in verschiedenen Tools & Plattformen

#### 📌 Fazit

KI-Bildgenerierung ist kein Zukunftsthema mehr – sie ist praktisch, leistungsstark und zugänglich. Der Kurs vermittelt alle Werkzeuge, um eigene visuelle Ideen professionell
umzusetzen. Wichtig ist: Ausprobieren, vergleichen und den eigenen Stil entwickeln. Die Werkzeuge ändern sich – dein kreatives Verständnis bleibt zentral.

----

## Links zu allen Tools
[[00-05-05_Zusatzquellen.pdf]]
🧠 **Zusatzquellen**

**Einführung in die Bildgenerierung**


**Websites / Tools**

Sora https://sora.com
EverArt https://www.everart.ai/
RunComfy https://www.runcomfy.com/
ComfyUI (Download) https://www.comfy.org/
Midjourney https://midjourney.com/
Replicate https://replicate.com/
Fal https://fal.ai/
Freepik https://www.freepik.com
Boris Noll Post selectin

**Workflows**
Flux Base Workflow https://www.runcomfy.com/comfyui-workflows/comfyui-flux-a-new-art-image-generationRealistic Images + Upscaler
https://www.runcomfy.com/comfyui-workflows/flux-ultrarealistic-lora-v2-lifelike-ai-images

Flux + Controlnet https://www.runcomfy.com/comfyui-workflows/flux-dev-controlnet-union-pro-multi-condition

Face Swap https://www.runcomfy.com/comfyui-workflows/ace-plus-plus-face-swap

Character Consistency https://www.runcomfy.com/comfyui-workflows/ace-plus-plus-character-consistency

## Abschlussquiz 5 Fragen

Was beschreibt die Methode „Text-to-Image“ in der KI-Bildgenerierung am besten?

  Die KI übersetzt ein hochgeladenes Bild in Text
  Die KI überträgt den Stil eines Bildes auf ein anderes
  **Die KI erstellt ein Bild basierend auf einer Texteingabe**
  Die KI kombiniert mehrere Bilder zu einem GIF


Welcher Parameter in Midjourney beeinflusst, wie stilisiert oder „künstlerisch“ ein generiertes Bild aussieht?
  --ar
  **--stylize**
  --weirdness
  --cw

Was ist ein wesentlicher Vorteil von Open-Source-Modellen wie Flux oder Stable Diffusion gegenüber kommerziellen Modellen?

  Sie erzeugen ausschließlich 3D-Modelle
  Sie funktionieren nur in Kombination mit Photoshop
  **Sie bieten hohe Flexibilität und können lokal verwendet werden**
  Sie sind nur über Discord nutzbar


Was macht das ControlNet „Canny“ besonders?
  Es erkennt die Farbstimmung eines Bildes
  Es erzeugt automatisch Textbeschreibungen
  Es extrahiert die Tiefeninformationen aus dem Bild
  **Es erstellt eine Kantenzeichnung als Strukturvorlage**

Welches Modell würdest du bevorzugen, wenn du ein besonders fotorealistisches Portrait erstellen möchtest?

  Midjourney
  Seedream
  Stable Diffusion ohne LoRA
  GPT-3


## Wie fandest du diesen Kurs? - 6 Fragen


---
*Zuletzt bearbeitet: 2026-02-17*
