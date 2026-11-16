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

## Trasformazioni
- `italia-piattaforme.csv`: «Altri annunci» = 76,2 milioni (totale Italia) − 37,5 (YouTube).
- `contenuti-archiviati`: un quadratino = 10 contenuti, arrotondato.
- `resa-annunci.csv`: valori medi dal rapporto (circa 214mila e 89mila).

- `mappa-esposizioni.csv`: coordinate dei cerchi scelte a mano (centro del Paese); Ungheria fase 1 = 0.
- `pollici`: la terza categoria (💬) è 100 meno favorevoli e contrari.
- `europa.geojson`, `mondo.geojson`: confini Natural Earth semplificati.

- `video/paesi/`: un annuncio per Paese nella mappa a fasi (Italia, Francia, Germania, Regno Unito, Stati Uniti, Libano; Ungheria: immagine). Paese attribuito in base alla lingua e al contenuto.

## Pubblicazione
GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root. 
