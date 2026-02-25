# Studio Commerciale · Dott. Salvatore Scrascia
### Circolare Interattiva — Iper-Ammortamento 4.0 · Legge di Bilancio 2026

Applicazione web **self-contained** (singolo file HTML, zero dipendenze esterne) per la comunicazione professionale ai clienti dello studio in materia di agevolazioni fiscali sugli investimenti in beni strumentali 4.0.

---

## Contenuto

La circolare copre integralmente la disciplina introdotta dall'**art. 1, co. 427–436, L. 30.12.2025 n. 199** (Legge di Bilancio 2026):

- **Panoramica** — tabella riepilogativa dell'agevolazione e differenze rispetto alle misure precedenti (bonus 4.0 ex L. 178/2020 e Transizione 5.0)
- **Soggetti** — beneficiari, esclusi e condizioni di spettanza
- **Beni agevolabili** — Allegato IV (beni materiali) e Allegato V (beni immateriali) con accordion interattivi
- **Misura** — scaglioni di maggiorazione (180% / 100% / 50%) e calcolo della deduzione extracontabile
- **Simulatore** — calcolo interattivo con piano di ammortamento pluriennale e stima del risparmio IRES/IRPEF
- **Adempimenti** — timeline operativa e checklist documentale

---

## Caratteristiche tecniche

| Caratteristica | Dettaglio |
|---|---|
| Tipo file | Singolo `index.html` |
| Dimensione | ~50 KB |
| Dipendenze esterne | **Nessuna** |
| Font | Georgia, Trebuchet MS (system fonts) |
| Framework | Vanilla HTML/CSS/JS |
| Compatibilità | Tutti i browser moderni, mobile-friendly |

---

## Deploy

### Netlify Drop (consigliato — 30 secondi)
1. Aprire [drop.netlify.com](https://drop.netlify.com)
2. Trascinare `index.html` nel riquadro
3. Copiare il link generato (es. `https://studio-scrascia.netlify.app`)
4. Inviare il link ai clienti via email

### GitHub Pages
```bash
git clone https://github.com/tuo-utente/studio-scrascia.git
cd studio-scrascia
# assicurarsi che il file si chiami index.html
git add .
git commit -m "Prima release — circolare iper-ammortamento 2026"
git push origin main
```
Abilitare **GitHub Pages** da *Settings → Pages → Branch: main → / (root)*.
Il sito sarà disponibile su `https://tuo-utente.github.io/studio-scrascia`.

---

## Aggiornamenti

Per aggiornare i contenuti (nuove circolari, modifiche normative):
1. Modificare il file `index.html`
2. Ricaricare su Netlify Drop — il link rimane invariato se si usa lo stesso sito
3. Oppure fare `git push` se si usa GitHub Pages

---

## Riferimenti normativi

- L. 30.12.2025 n. 199, art. 1 co. 427–436 (Legge di Bilancio 2026)
- Allegato IV — Beni materiali funzionali alla trasformazione tecnologica e digitale
- Allegato V — Beni immateriali funzionali alla trasformazione digitale
- Circ. Agenzia delle Entrate 30.3.2017 n. 4 (prassi di riferimento)
- Guida Eutekne, aggiornata al 23.02.2026

---

## Disclaimer

Il presente documento ha finalità **esclusivamente informativa** e non costituisce parere professionale. Per consulenza personalizzata contattare lo Studio.

---

*Studio Commerciale · Dott. Salvatore Scrascia — aggiornato al 25/02/2026*
