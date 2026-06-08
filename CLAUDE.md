# Lechcode — Agentur-Website (Kontext für Claude Code)

Die Single-File-Website der Web-Agentur **Lechcode** aus Landsberg am Lech.
Eine Datei, **kein Build** (kein npm/Vite). Einfach `index.html` im Browser öffnen.

## Dateien
- **`index.html`** — die komplette Seite (HTML + CSS + JS, alles inline).
- **`assets/team.jpg`** — Teamfoto (Lenny · Marie · Michael).
- **Hosting:** GitHub Pages. `git push` auf `main` → Seite ist in ~1 Min live unter
  `https://cominghomemira.github.io/lechcode/`.

## Marke, Ton & Look (bitte einhalten)
- **Tagline:** „Code mit Seele." · **Ton:** warm, auf Augenhöhe, Wert zuerst, kein Druck. Anrede durchgehend **Du**.
- **Look „Lagerfeuer":** warm-dunkel (Braun-/Schwarztöne, `--night #16130c`) + **Bernstein/Gold** als Akzent, dazu warme Creme-/Sand-„Lichtungen" für helle Sektionen. **Kein kaltes Türkis.**
- **Fonts:** Space Grotesk (Headlines), Inter (Fließtext), JetBrains Mono (nur Logo/„code").
- **Logo-Zeichen:** Lech-Welle im Kreis (Gold) — in Nav & Footer; Favicon ist dieselbe Welle.
- **Lokale Wahrzeichen (Heimat):** Bayertor als leises Hintergrund-Motiv im „Über uns"; Footer-Skyline (Bayertor · Schmalzturm · Mutterturm); sanft **fließende Lech-Welle** als Sektions-Trenner.
- Voll responsive, sanfte/„atmende" Animationen, **`prefers-reduced-motion` respektieren**.

## ⚠ Vor echtem Go-Live erledigen
1. **Cal.com-Link** einsetzen — Suche `PLATZHALTER-CAL` (Buttons „Termin buchen").
2. **Web3Forms-Key** einsetzen — Suche `PLATZHALTER-FORM` (Kontaktformular).
3. **Impressum + Datenschutz** anlegen & im Footer verlinken — **und DANN** `<meta name="robots" content="noindex">` im `<head>` **entfernen** (erst dann darf Google die Seite indexieren).

## Wichtig zum Portfolio („Arbeiten")
Die 5 Demo-Karten (Anne Robert, Vesna Pazin, Hofladen Dürr …) sind **echte, noch nicht angesprochene Zielkunden**. Sie sind bewusst **nicht** öffentlich verlinkt (zeigen „Vorschau auf Anfrage"). Nur **wairua** ist live verlinkt. Bitte **nicht** öffentlich auf deren Demos verlinken.

## Arbeitsweise
- Änderungen direkt in `index.html`. Nach dem Speichern im Browser neu laden (Cmd/Strg+Shift+R).
- Akquise-Haltung der Agentur: **kein Kalt-E-Mail** (§7 UWG). Die Seite ist Schaufenster + Buchung, kein aggressives Verkaufen.
