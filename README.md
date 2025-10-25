# jn-technologies-website

Dies ist der Quellcode der statischen Website für **JN Technologies**. Die Seite ist responsiv, auf Deutsch verfasst und nutzt ein dezentes Farbkonzept in Kobaltblau und Violett. Sie stellt unser Start‑up vor, listet Produkte auf, erklärt unsere Vision und bietet ein Kontaktformular sowie eine Vorschau auf den geplanten Website‑Agenten.

## Aufbau

- **index.html** – Startseite mit Hero‑Abschnitt, Mission und Feature‑Überblick
- **produkte.html** – Platzhalterseite für Präsentationen, Templates und andere Downloads
- **about.html** – Unternehmensprofil mit Vision und Roadmap
- **kontakt.html** – Kontaktformular und eine Demo‑UI für den künftigen Agent‑Chat
- **impressum.html** und **datenschutz.html** – Rechtliche Seiten mit Platzhaltern, bitte mit euren echten Daten füllen
- **style.css** – Zentrales Stylesheet für Layout, Farben und Typografie
- **manifest.json**, **robots.txt**, **sitemap.xml** – Dateien zur Konfiguration als Web App und für Suchmaschinen
- **assets/logo.svg** – Einfaches Logo (zwei überlagerte Quadrate)

## Lokale Entwicklung

Die Website ist komplett statisch. Um sie lokal zu testen, klonen Sie dieses Repository und öffnen Sie `index.html` in Ihrem Browser oder bedienen Sie einen einfachen HTTP‑Server:

```bash
python3 -m http.server 8000
# anschließend im Browser http://localhost:8000/ aufrufen
```

## Deployment mit GitHub Pages

Um die Seite öffentlich erreichbar zu machen, können Sie GitHub Pages nutzen:

1. Öffnen Sie die Repository‑Einstellungen (Settings).
2. Wählen Sie im Abschnitt **Pages** die Quelle **Deploy from a branch** und den Branch `main` aus. Der Ordner kann auf `/root` stehen bleiben.
3. Nach dem Speichern ist die Website wenige Minuten später unter `https://<username>.github.io/jn-technologies-website/` erreichbar.

## Anpassung

Ersetzen Sie die Platzhalter im Impressum und der Datenschutzerklärung durch Ihre tatsächlichen Unternehmensdaten. Sie können außerdem neue Unterseiten hinzufügen, Inhalte ergänzen oder das Design über die CSS‑Variablen (`--primary`, `--secondary`, `--background`) anpassen.

Viel Spaß beim Einsatz unseres AI‑Co‑Piloten!