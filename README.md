# Academic website

Statische Jekyll-Website für GitHub Pages. Inhalte in Markdown, eigenes HTML/CSS, kein JavaScript und keine externen Schriftarten.

## Auf GitHub testen

1. Änderungen committen und pushen.
2. Im Repository **Settings → Pages → Build and deployment** öffnen.
3. **Deploy from a branch** auswählen, den gepushten Branch (aktuell `master`) und **/ (root)** einstellen.
4. Nach erfolgreichem Pages-Build ist die Seite unter https://semigroup.github.io/ erreichbar.

Es ist kein eigener GitHub-Actions-Workflow nötig. GitHub Pages baut Jekyll direkt aus dem Repository.

## Anpassen

- `_config.yml`: Name, Position, Institution, E-Mail, Beschreibung und Navigation. Nach Änderungen den lokalen Server neu starten.
- `index.md`: Startseite und Kurzbiografie.
- `research.md`, `publications.md`, `teaching.md`, `contact.md`: weitere Inhalte.
- `assets/css/style.css`: Farben, Abstände und Typografie.
- `_layouts/default.html`: gemeinsames Seitengerüst.

Alle Angaben in eckigen Klammern sowie „Your Name“, „Your University“ und die Beispiel-E-Mail ersetzen. Die englischen Texte sind Muster, keine echten Angaben zur Person.

Für den Lebenslauf `assets/cv.pdf` hinzufügen und in `contact.md` verlinken:

```liquid
[Download my CV (PDF)]({{ '/assets/cv.pdf' | relative_url }})
```

Ein Foto kannst du beispielsweise unter `assets/images/portrait.jpg` ablegen und in `index.md` einfügen:

```liquid
![Portrait of Your Name]({{ '/assets/images/portrait.jpg' | relative_url }})
```

Für Bilder bei Bedarf im CSS ergänzen: `img { max-width: 100%; height: auto; }`.

## Optional lokal ansehen

Mit installiertem Ruby und Bundler:

```bash
bundle install
bundle exec jekyll serve
```

Dann http://localhost:4000 öffnen. Der lokale Build ist für einen ersten Test über GitHub Pages nicht erforderlich.

Bei Nutzung als Projektseite statt als `username.github.io`-Repository in `_config.yml` zusätzlich `baseurl: "/repository-name"` setzen und `url` anpassen.
