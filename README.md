# DB Ansagen Generator Pro V3 🚆📢

Ein professioneller, web-basierter Simulator für automatisierte PA-Systeme (Public Address) in Zügen und an Bahnhöfen. Dieses Tool nutzt modernste KI-Sprachsynthese (Text-to-Speech) kombiniert mit einer fortschrittlichen Web-Audio-DSP-Engine, um hochrealistische Durchsagen direkt im Browser zu generieren.

![UI Preview](https://via.placeholder.com/800x450.png?text=UI+Preview+-+DB+Ansagen+Generator)

## ✨ Features

* **KI-Sprachsynthese mit Regieanweisungen:** Steuere die Emotion, Betonung und Geschwindigkeit der KI-Stimme frei über Prompts (z.B. *"Sprich sachlich, klar und mit offizieller Betonung"*).
* **Hybrides Stimmen-System:** Auswahl zwischen realistischen KI-Profilen (Klassische Ansagerin "Blechelse", Zugchef, Leitstelle), optimiert für PA-Systeme.
* **Authentische Gong-Synthese:** In Echtzeit berechnete Gongs mittels Additiver Synthese (keine statischen Audio-Dateien).
  * Klassischer Bahnhof-Dreiklang (G-E-C) mit glasklarem Anschlag.
  * Modernes DB-Soundlogo für Züge (D-B) inkl. Intercom-Klick.
* **Dynamische Audio-Effekte (DSP):**
  * **Bahnhofshalle:** Frequenz-Tiefpass und parametrischer Raumhall (Reverb Convolution).
  * **Im Zug:** Hochpass-Intercom-Filter für typische Bordlautsprecher.
  * Stufenlose Regler für Hall-Intensität, Geschwindigkeit und Lautsprecher-Verzerrung.
* **Hintergrund-Atmo:** Zuschaltbares, prozedural generiertes Rauschen (Brown Noise) für Bahnhof- oder Zug-Ambiente.
* **High-Contrast Dark Mode:** WCAG-konformes, echtes OLED-Dark-Theme mit klarem DB-Branding (Verkehrsrot) und perfekter Tastatur-Fokussierung.

## 🛠️ Technologie-Stack

Dieses Projekt ist eine reine Frontend-Applikation (Single Page App) und kommt völlig ohne Backend aus:
* **HTML5 & Vanilla JavaScript**
* **Tailwind CSS** (via CDN für das Styling)
* **Web Audio API** (für Synthesizer, Routing und DSP-Effekte)
* **Font Awesome** (für professionelle Vektor-Icons)

## 🚀 Installation & GitHub Pages Deployment

Das Projekt besteht im Kern aus einer einzigen Datei (`index.html`) und benötigt kein Build-System (wie npm oder Webpack).

1. **Repository erstellen:** Erstelle ein neues Repository auf GitHub.
2. **Dateien hochladen:** Lade die `index.html`, diese `README.md` und die `LICENSE` in das Repository hoch.
3. **GitHub Pages aktivieren:**
   * Gehe in deinem Repository auf **Settings** -> **Pages**.
   * Wähle unter "Build and deployment" die Quelle **Deploy from a branch**.
   * Wähle den Branch `main` (oder `master`) und den Ordner `/(root)` aus.
   * Klicke auf **Save**.
4. Nach wenigen Minuten (meist < 2 Minuten) ist deine Web-App live unter `https://<dein-username>.github.io/<repo-name>/` erreichbar!

## ⚠️ Wichtiger Rechtlicher Hinweis (Disclaimer)

**Dieses Projekt ist ein inoffizielles Hobby-Projekt und steht in keinerlei rechtlicher oder geschäftlicher Verbindung zur Deutschen Bahn AG (DB) oder deren Tochtergesellschaften.**

Es handelt sich um eine technische Machbarkeitsstudie im Bereich Web-Audio-DSP und generativer KI. Logos, spezifische Bezeichnungen und das Audio-Branding der Deutschen Bahn sind markenrechtlich geschützt. Die Nutzung der generierten Audiodateien für kommerzielle Zwecke, zur vorsätzlichen Täuschung im öffentlichen Raum oder zur Verbreitung von Fehlinformationen ist strengstens untersagt und geschieht auf eigene Gefahr.
