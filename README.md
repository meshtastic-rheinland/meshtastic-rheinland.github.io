## Meshtastic Rheinland – GitHub Pages

Statische, filebasierte Seite für die Rheinland‑Community rund um Meshtastic.

### Struktur

- `index.md` – Übersicht, Schnellstart, Links
- `setup.md` – Setup & empfohlene DE/EU‑Settings (mit Doku‑Verweisen)
- `community.md` – WhatsApp‑Gruppe (per `_config.yml`), Forum/Discord
- `_config.yml` – Titel, Theme, Links, Variablen
- `assets/` – Logo etc.

### Theme

Jekyll „Just the Docs“ via `remote_theme` – hübsch, leicht zu pflegen, Markdown‑basiert.

### Deployment (GitHub Pages)

1. Repository auf GitHub pushen.
2. In den Repo‑Settings → Pages:
   - Source: „Deploy from a branch“
   - Branch: `main` (oder `master`) / Root
3. Warten bis GitHub Pages baut, dann oben angezeigte URL öffnen.

Kein lokaler Build nötig (GitHub Pages baut Jekyll + Remote Theme automatisch).

### Anpassen

- `_config.yml`: `whatsapp_invite_url` eintragen.
- Inhalte in `index.md`, `setup.md`, `community.md` ergänzen.

### Hinweise

- Bitte lokale Funkregeln beachten (EU868 in DE, Duty Cycle etc.).
- Verweise auf die offizielle Doku bleiben Quelle der Wahrheit.

