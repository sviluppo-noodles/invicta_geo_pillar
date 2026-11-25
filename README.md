# Invicta · Pillar GEO – Prototipo

Prototipo delle pagine Pillar per la strategia GEO di Invicta (topic **Viaggi**).
**Non è il sito ufficiale**: è una bozza da mostrare al cliente per la revisione.

## Come vederlo

Aprire `index.html` con un doppio clic: si apre nel browser e funziona su desktop e mobile.
Le foto sono incluse nel file. Il font Poppins si carica da Google Fonts (serve la connessione).

## Contenuto

| File | Cosa contiene |
| --- | --- |
| `index.html` | Prototipo navigabile della Pillar "Zaini da viaggio" |
| `docs/Invicta_Pillar_Viaggi_revisione.pdf` | Testi per la revisione del cliente, con le domande aperte |

## Struttura della pagina

Segue l'"Esempio Pillar" del brief del cliente (slide 8):

1. Apertura con foto, titolo e 4 link rapidi alle guide
2. Come scegliere uno zaino da viaggio
3. Quale zaino scelgo per il mio viaggio? Schede 20 / 30 / 50 / 70 L
4. Gli zaini e i borsoni Invicta a confronto: Velba, Freeway S, Commuter M, Commuter L (+ Freeway L, Maket, Packly)
5. Le caratteristiche che rendono pratico uno zaino
6. Combo Maket + Minisac Packable
7. Domande frequenti: 12 FAQ che coprono i prompt del brief (con dati strutturati FAQPage)

## Punti aperti

- Packly non è presente sul sito: servono foto e dati.
- "Campus M" e "Campus L" del brief corrispondono, dalle foto, ai borsoni Commuter M e L: da confermare.
- Le guide collegate non esistono ancora: i link rapidi per ora portano alle sezioni della pagina.
- Prezzi di listino al 25/11/2026: nella pagina reale vanno collegati al catalogo Shopify.
- Foto ambientate per l'apertura da ricevere dal cliente.

## Per lo sviluppo su Shopify

- Pagina pubblicata e indicizzabile, fuori dal menu, inclusa nella sitemap.
- URL proposto: `/pages/zaini-da-viaggio-guida`.
- Il prototipo ha `noindex`: va tolto nella pagina reale.
- Mantenere i testi come testo HTML (mai dentro immagini) e i dati strutturati FAQPage e BreadcrumbList.
