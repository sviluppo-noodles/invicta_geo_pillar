# Invicta · Pillar GEO – Prototipo

Prototipo della pagina Pillar "Zaini da viaggio" per la strategia GEO di Invicta (topic **Viaggi**).
**Non è il sito ufficiale**: è una bozza di Noodles Comunicazione da mostrare al cliente per la revisione.

## Come vederlo

Aprire `index.html` con un doppio clic: si apre nel browser e funziona su computer e telefono.
Le foto sono incluse nel file. Il carattere Poppins si carica da Google Fonts (serve la connessione).

## Contenuto del repository

| File | Cosa contiene |
| --- | --- |
| `index.html` | Prototipo navigabile della Pillar "Zaini da viaggio" |
| `docs/presentazione/Pillar_Zaini_da_viaggio_le_mie_scelte.pdf` | Le scelte progettuali in 14 domande e risposte |
| `docs/revisione/` | Revisione critica, controllo di accessibilità, prima/dopo |
| `docs/Invicta_Pillar_Viaggi_revisione.pdf` | Prima revisione per il cliente (superata: testi non aggiornati) |

## Struttura della pagina

Segue l'"Esempio Pillar" del brief del cliente (slide 8), con tre sezioni aggiunte:

1. Apertura con foto, titolo completo, data di aggiornamento e 4 link rapidi
2. Come scegliere uno zaino da viaggio, con riquadro "In breve"
3. Quale zaino scelgo per il mio viaggio? Capienze 20 / 30 / 50 / 70 L
4. *(aggiunta)* Zaino, borsone o trolley? Tabella di confronto
5. *(aggiunta)* Misure del bagaglio per compagnia: Ryanair, easyJet, Wizz Air, Volotea
6. Zaini e borsoni Invicta a confronto: Packly, Velba, Freeway S, Maket, Freeway L, Commuter M, Commuter L
7. Cosa rende pratico uno zaino
8. Parti per un weekend? Trolley Maket + Minisac Packable
9. *(aggiunta)* Domande frequenti: i 10 prompt del brief + 2, con dati strutturati

## Cosa usare per la pagina vera (e cosa no)

**Da usare:** tutto il contenuto tra la testata e il piè di pagina (`<main>`) e i dati nel `<head>`
(titolo, descrizione, Open Graph, canonical proposto) e i blocchi JSON-LD in fondo
(FAQPage, Article, ItemList, BreadcrumbList).

**Solo d'esempio, da NON copiare:**
- **Testata** (logo, menu, icone): la mette il tema Shopify. Il menu è quello del sito al 25/11/2026;
  "Black Friday" e "Blundstone x Invicta" puntano alla home.
- **Piè di pagina**: link vuoti, newsletter finta.
- **Briciole "Home / Guide / Zaini da viaggio"**: le crea il tema; verificare che esista una sezione "Guide".
- **Tag `noindex`**: messo apposta perché il prototipo non finisca su Google. Va tolto nella pagina pubblicata.
- **Scorrimento morbido della rotella**: effetto da prototipo; sul sito vero va deciso con chi sviluppa.

## Per la pubblicazione su Shopify

- URL proposto: `/pages/zaini-da-viaggio` (già scritto nel canonical e nei dati strutturati: aggiornarlo se cambia).
- Pagina indicizzabile, fuori dal menu, inclusa nella sitemap.
- Testi come testo HTML, mai dentro immagini.
- Link alla pagina da tutte le schede dei prodotti citati.
- Inviarla a Google Search Console e a Bing Webmaster Tools.
- Il `robots.txt` non deve bloccare OAI-SearchBot (ChatGPT) e PerplexityBot.
- Prezzi: solo quelli automatici di Shopify, mai scritti nei testi.
- Immagine di anteprima (`og:image`): la foto di apertura caricata su Shopify.

## Dati verificati (25/11/2026)

- Schede su invicta.it: Freeway S (28,5 L, resistente all'acqua, PC 15,6"), Freeway L (50 x 35 x 20, 47 L, PC 15,6", spallacci a scomparsa),
  Maket (40 x 55 x 20, 33 L, 2,9 kg, TSA, ruote 360°, USB), Commuter L (70 L, fondo rinforzato, spallacci amovibili, nastro toracico, tasca laterale).
- Packly (40 x 27 x 14,5 cm, 18 L): dalle immagini della scheda Amazon.
- Regole bagaglio delle compagnie: fonti del 2026; ricontrollare ogni 3 mesi.

## Punti aperti

- Packly non è sul sito: oggi la scheda porta ad Amazon.
- "Campus M/L" del brief = Commuter M/L sul sito: da confermare.
- Le 3 guide di approfondimento (slide 7 del brief) non esistono ancora.
- Foto: le realizza Noodles (non vanno richieste al cliente).
- Le 10 domande del cliente andrebbero verificate su dati reali (Search Console, servizio clienti, Amazon).
