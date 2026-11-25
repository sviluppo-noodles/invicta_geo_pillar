# Controllo accessibilità (WCAG 2.2 AA): prototipo Pillar "Zaini da viaggio"

Metodo: scansione automatica axe-core con Chrome; contrasto del titolo sulla foto misurato sui pixel; revisione manuale del codice (tastiera, struttura, lettori di schermo).

| # | Problema | Criterio | Livello | Gravità | Correzione |
|---|---|---|---|---|---|
| 1 | Titolo bianco sulla foto: contrasto circa 1,7:1 nei punti chiari (serve 3:1) | 1.4.3 | AA | Alta | Velatura scura uniforme, contrasto ≥ 4,5:1 |
| 2 | Testo grigio #8A8A8A su bianco 3,45:1 (sottotitoli link rapidi, "dati da fornire" #999) | 1.4.3 | AA | Alta | Grigio #666 (5,7:1) |
| 3 | Manca il link "Vai al contenuto" | 2.4.1 | A | Alta | Skip link come primo elemento |
| 4 | Icone della testata (ricerca, preferiti, account, carrello, menu) senza nome accessibile né aria-hidden | 1.1.1 / 4.1.2 | A | Moderata | Pulsanti/link con aria-label; SVG con aria-hidden |
| 5 | Titoli del piè di pagina in h4 dopo h2 (salto di livello) | 1.3.1 | A | Moderata | h2 con stile invariato |
| 6 | Newsletter: finto campo (div) senza input né etichetta | 1.3.1 / 4.1.2 | A | Moderata | input type="email" con label e pulsante "Iscriviti" |
| 7 | Barra "PROTOTIPO" fuori dai landmark | best practice | – | Bassa | Dentro un elemento aside con aria-label |
| 8 | Link rapidi con attributo title (non letto in modo affidabile) e stessa destinazione | 2.4.4 | A | Moderata | Destinazioni distinte, niente title |
| 9 | Icone dei riquadri capienza senza aria-hidden | 1.1.1 | A | Bassa | aria-hidden="true" |
| 10 | Immagini ripetute nei riquadri e nella griglia prodotti annunciate due volte | best practice | – | Bassa | alt descrittivo una sola volta; nei riquadri alt col modello reale |

Già corretti: lang="it", un solo h1, landmark header/nav/main/footer, focus visibile, FAQ con details/summary (tastiera nativa), prefers-reduced-motion rispettato, nessun contenuto a trascinamento.
