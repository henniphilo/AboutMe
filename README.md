# Henrike Wiemann — Portfolio

Digitales Exposé für GitHub Pages  
(Video & Theatre Artist — live performance, moving image, code).

## Lokal ansehen

```bash
python3 -m http.server 8000
```

Dann im Browser: `http://localhost:8000`

## Dateien

| Datei / Ordner | Zweck |
| --- | --- |
| `index.html` | Seitenstruktur & Inhalte |
| `style.css` | Designsystem & Layout |
| `script.js` | optionale Interaktionen |
| `images/` | Visual Archive (`image-01.jpg` … `image-06.jpg`) |
| `README.md` | diese Anleitung |

Kein Build-Prozess, kein Framework.

## Inhalte austauschen

- Texte: direkt in `index.html` (Hero, About, Practice, Profile, Contact)
- Contact: `[CONTACT]`, `[INSTAGRAM]`, `[VIMEO]` ersetzen; GitHub ist gesetzt
- Bilder: Dateien in `images/` unter denselben Namen überschreiben; Captions in `<figcaption>`

## GitHub Pages veröffentlichen

1. Repository auf GitHub erstellen (oder bestehendes nutzen), z. B. `AboutMe`
2. Projektdateien in den Repo-Root legen (`index.html` muss im Root liegen)
3. Committen und pushen:

```bash
git add .
git commit -m "Publish portfolio site"
git push origin main
```

4. Im Repo: **Settings → Pages**
5. Source: **Deploy from a branch** → Branch `main` → Folder `/ (root)` → **Save**
6. Öffentliche URL (nach 1–2 Minuten), typischerweise:  
   `https://<username>.github.io/AboutMe/`

## Status

Meilensteine 1–8 umgesetzt (Contact-E-Mail/Instagram/Vimeo und echte Archive-Fotos noch von dir einsetzbar).
