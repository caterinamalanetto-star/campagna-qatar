# Campagna anti-Qatar – dataviz Radar QN

Indice con anteprime e snippet: https://caterinamalanetto-star.github.io/campagna-qatar/

Fonte: M. O. Jones e S. Dsouza, *Manufacturing the “Great Replacement”* (2026). Dati in `data/` (CSV con `;` e virgola decimale).

- **L'Italia, da zero a 76 milioni** – `da-zero-a-76-milioni/` – Esposizioni per Paese, fase 1 contro fase 3
- **In Italia ogni annuncio arriva più lontano** – `resa-per-annuncio/` – Esposizioni medie per annuncio, Italia e Germania; il peso di YouTube
- **Solo in italiano prevale chi approva** – `commenti-per-lingua/` – Commenti favorevoli e contrari per lingua
- **Duemila contenuti, mezzo miliardo di esposizioni** – `contenuti-archiviati/` – Contenuti archiviati per piattaforma
- **Gli annunci seguono il calendario elettorale** – `calendario-elettorale/` – Le tre fasi e le scadenze elettorali
- **Dove è passata la campagna, fase per fase** – `mappa-fasi/` – Mappa interattiva: esposizioni per Paese, una fase alla volta
- **Seguire i soldi: il giro del mondo della campagna** – `seguire-i-soldi/` – Mappa interattiva a tappe con emoji: account, intermediari, indizi
- **Solo in italiano vincono i pollici in su** – `pollici/` – Cento commenti in emoji, lingua per lingua
- **Che cosa vedevano gli italiani** – `feed-italiano/` – Il copione e un anno di annunci, con emoji
- **Gli annunci, guardati da vicino** – `annunci-video/` – sei annunci video (cartella `video/`: ricodificati 360×640, senza audio)
- **Quanto ne sai? Indovina il numero** – `indovina/` – quiz con cursore (dati in `data/quiz.csv`)
- **Video con i dati** – `video/campagna-qatar-16x9.mp4`, `video/campagna-qatar-9x16.mp4` (30 s)
- **La campagna in otto tappe** – `la-storia/` – Racconto a tappe con cento pallini che si trasformano (tocca o usa le frecce)
- **Trova l'annuncio** – `trova-annuncio/` – Gioco: feed simulato, sei annunci veri e sei post inventati
- **Un centesimo per ogni schermo** – `quanto-costa/` – Calcolatore: quanta propaganda si comprava con una cifra
- **Identità usa e getta** – `usa-e-getta/` – Quanto vivevano pagine e annunci; i canali YouTube chiusi e riaperti
- **Indizi, non prove** – `indizi/` – Heatmap delle 1.231 modifiche ai video per giorno e ora, schede degli indizi
- **Le voci sotto i video** – `voci/` – Le frasi tipo dei commenti e i temi, in bolle
- **Carosello Instagram** – `social/radar-qatar-1..8.png`

## Trasformazioni
- `italia-piattaforme.csv`: «Altri annunci» = 76,2 milioni (totale Italia) − 37,5 (YouTube).
- `contenuti-archiviati`: un quadratino = 10 contenuti, arrotondato.
- `resa-annunci.csv`: valori medi dal rapporto (circa 214mila e 89mila).

- `mappa-esposizioni.csv`: coordinate dei cerchi scelte a mano (centro del Paese); Ungheria fase 1 = 0.
- `pollici`: la terza categoria (💬) è 100 meno favorevoli e contrari.
- `europa.geojson`, `mondo.geojson`: confini Natural Earth semplificati.

- `video/paesi/`: un annuncio per Paese nella mappa a fasi (Italia, Francia, Germania, Regno Unito, Stati Uniti, Libano; Ungheria: immagine). Paese attribuito in base alla lingua e al contenuto.

- Dati dal rapporto (PDF, 29 ottobre 2026): `costo.csv` (spesa registrata 5.083.373 $ / 532.615.848 esposizioni), `identita.csv` (61 identità datate: 57% in una settimana, 69% entro un mese, 12 per tre mesi o più; fasce intermedie per differenza e arrotondate), `montaggio-ore.csv` (figura 59, 1.231 eventi), `commenti-temi.csv` e `commenti-voci.csv` (sezione 12.1, frasi parafrasate), `storia-numeri.csv`.
- `trova.csv`: i post «inventati» sono creati da Radar per il gioco e dichiarati come tali.

## Pubblicazione
GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root. 
