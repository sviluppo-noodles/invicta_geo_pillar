# Revisione critica: prototipo Pillar "Zaini da viaggio"

Contesto: utente da ricerca AI o Google, primo accesso, domanda del tipo "che zaino per un weekend in aereo". Obiettivo: capire la capienza giusta e arrivare al prodotto. Vincoli: stile invicta.it, struttura dell'"Esempio Pillar" del cliente (slide 8).

Test dei 5 secondi: si capisce l'argomento (titolo chiaro). L'azione principale non è chiara: nessun prodotto né invito all'azione nella prima schermata; i 4 link rapidi non sembrano cliccabili.

| # | Problema | Principio | Gravità | Correzione |
|---|---|---|---|---|
| 1 | Titolo bianco sopra la parte alta chiara della foto: si legge male | Gerarchia visiva, contrasto | 3 | Velatura scura uniforme sotto il testo |
| 2 | I 4 link rapidi portano tutti allo stesso punto (#capienza) | H4 Coerenza: l'etichetta promette un contenuto diverso | 3 | Ogni link porta alla sezione che risponde davvero (FAQ bagaglio a mano, combo weekend, capienza) |
| 3 | I link rapidi non hanno aspetto cliccabile | Affordance, Krug "è ovvio cosa si clicca?" | 2 | Freccia a chevron e sottolineatura al passaggio |
| 4 | Riquadro "20 L" mostra il Velba da 25 L, "30 L" il Freeway S da 28,5 L | H4 Coerenza, H2 corrispondenza col mondo reale | 2 | Didascalia con modello e litri reali sotto ogni immagine |
| 5 | Riquadri capienza a 2 colonne su telefono: righe di 2-3 parole | Leggibilità, Prägnanz | 2 | 1 colonna sotto i 600 px, immagine a sinistra e testo a destra |
| 6 | Nessuna risposta breve in apertura (In breve) | Strategia GEO: risposta prima, poi dettaglio | 2 | Riquadro "In breve" di 2 righe nella sezione "Come scegliere" |
| 7 | Nessuna briciola di pane visibile (c'è solo nei dati strutturati) | Krug "dove sono?", orientamento | 2 | Home / Guide / Zaini da viaggio sotto la testata |
| 8 | Pulsante "Scegli la tua combo!" porta solo al Maket | H4: etichetta e destinazione non coincidono | 2 | Pulsante sul Maket + link testuale al Minisac Packable |
| 9 | Schede prodotto senza invito esplicito | Krug "satisficing" | 1 | Testo "Scopri" sotto le misure, come link della scheda |
| 10 | Etichette "Foto provvisoria" sopra le foto si confondono col contenuto | H8 Minimalismo | 1 | Stile uniforme giallo prototipo, lo stesso della barra in alto |

Punti di forza: struttura identica all'esempio del cliente; titoli con il punto finale e angoli vivi come sul sito; FAQ a fisarmonica con la prima aperta; testi in HTML, non in immagine.
