# Lechcode-Website — kurz für Michi 👋

Funktioniert wie bei **wairua**: Es ist **eine HTML-Datei**, kein Build. So bastelst du weiter.

## 👀 Nur ansehen
Datei **`index.html`** doppelklicken → öffnet im Browser. Fertig.

## ✏️ Ändern (empfohlen: wie bei wairua)
1. **Repo holen** (einmalig):
   ```
   git clone https://github.com/ComingHomeMira/lechcode.git
   cd lechcode
   ```
2. Ordner in **Claude Code** öffnen, sagen was du willst („mach die Preise-Sektion …").
   Claude ändert `index.html`. Die `CLAUDE.md` erklärt Claude den Aufbau automatisch.
3. **Prüfen:** `index.html` im Browser neu laden (Cmd/Strg + Shift + R).
4. **Hochladen / live stellen:**
   ```
   git add -A
   git commit -m "kurz was geändert wurde"
   git push
   ```
   → **GitHub Pages aktualisiert die Live-Seite automatisch (~1 Min).**

## 🌐 Live-Adresse
https://cominghomemira.github.io/lechcode/

## 🙏 Bitte beachten
- **Impressum + Datenschutz fehlen noch** → solange bleibt `noindex` im `<head>` drin. **Nicht entfernen**, bis die zwei Seiten stehen (sonst landet die unfertige Seite bei Google).
- **„Termin buchen"** (Cal.com) & das **Formular** sind Platzhalter — im Code zu finden über `PLATZHALTER-CAL` bzw. `PLATZHALTER-FORM`.
- Die **5 Demo-Karten** (Anne Robert, Vesna Pazin …) sind echte Zielkunden, die wir noch **nicht** angesprochen haben → bitte **nicht** öffentlich verlinken (bleiben „Vorschau auf Anfrage"). Nur **wairua** ist live.
- **Ton & Look:** warm, „Du", mit Seele · warm-dunkel/„Lagerfeuer" mit Gold/Bernstein — **kein Türkis**.

## 🛟 Wenn was klemmt
- Versehentlich kaputtgemacht? Nichts ist verloren — `git log` zeigt alle Versionen, `git revert`/Claude hilft zurück.
- Im Zweifel einfach **Claude Code fragen** — er kennt die `CLAUDE.md`.

Viel Spaß beim Bauen! 🔥
