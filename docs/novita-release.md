---
title: "Inventa One 2.0.21 - Novità della release"
date: "2026-11-17"
version: "2.0.21"
categoria: software Inventa One
---

# Inventa One 2.0.21 – Novità della release

**Rilasciata il 17/11/2026.**

Prima versione della linea 2.0 per i locali pilota: sostituisce la 1.0.33 e porta nuove funzioni di configurazione (configurazione guidata, pagina Parametri, tastiera, layout di stampa) e molte correzioni su vendita, tavoli e comande, scontrino, palmari e fatture.

[Scarica il changelog in PDF](assets/resources/changelog-inventa-one-2.0.21.pdf)

## Quadro d'insieme

La tabella riassume cosa cambia per chi installa e configura. Le funzioni che hanno una guida operativa sono collegate nell'ultima colonna.

| Area | Cosa cambia | Card | FST | Guida |
| --- | --- | --- | --- | --- |
| Aggiornamento dalla 1.0.33 | Alla prima apertura la cassa aggiorna da sola il database e ne tiene una copia di sicurezza. Cassa principale, casse secondarie, terminali di sala e palmari vanno aggiornati insieme: con versioni di linea diversa non si scambiano conti e comande. | IFEV-3531, IFEV-4010 | | [Prima di aggiornare](prima-di-aggiornare.md) |
| Avviso di aggiornamento dei terminali | Nuovo avviso che dice quale terminale va aggiornato, mette a confronto le due versioni e ha il pulsante «Aggiorna app». Vale per gli aggiornamenti futuri: chi aggiorna dalla 1.0.33 vede ancora l'avviso «Versione tracciato incompatibile». | IFEV-4307 | | [Prima di aggiornare](prima-di-aggiornare.md) |
| Configurazione guidata | Chiede il tipo di attività (Bar, Ristorante, Negozio o Generico) e propone 10 reparti con l'IVA e i tasti funzione adatti al locale. Gli articoli si aggiungono a mano. Prima creava solo tasti reparto generici. | IFEV-3196, IFEV-4082 | | [Configurazione guidata](configurazione-guidata.md) |
| Parametri | Pagina ridisegnata: aree a sinistra, ricerca su tutti i parametri, area «Modificati» con le modifiche non salvate. Pulsanti Test accanto all'indirizzo della RT (matricola e firmware) e alla configurazione mail (invio di prova). | IFEV-3087, IFEV-4032, IFEV-3310, IFEV-2997 | FST-3186 | [Parametri](parametri.md), [Verifiche per l'installatore](verifiche-installatore.md) |
| Stampanti comande | Nella scheda della stampante c'è il Pannello di verifica con la stampa di prova. «Ritenta la stampa» con la stampante spenta non dice più «completato» senza stampare. | IFEV-2933, IFEV-3426 | FST-3187 | [Stampanti comande](stampanti-comande.md) |
| Layout di stampa | Nuovi layout da un preset con anteprima; il valore di Totale, Coperti, Pagamenti, IVA e altri elementi si compone a blocchi (campi e testo libero). Taglio con tipo e righe di avanzamento, nomi lunghi su due righe anche in doppia larghezza. La stampa di prova non cambia più il layout della stampante. | IFEV-1568, IFEV-1669, IFEV-3431, IFEV-3599 | | [Layout di stampa](layout-di-stampa.md) |
| Configura tastiera | Selezione di più tasti con azioni di gruppo: copia su altre pagine (anche di una pagina intera), incolla su più tasti scegliendo insieme reparti o funzioni, applica stile, svuota. Selettore e «Clona» delle pagine durante la modifica, segno «già presente» su articoli, reparti e funzioni. Nuovi tasti «Gruppo reparti» e «Funzioni». | IFEV-3520, IFEV-3523, IFEV-3882, IFEV-2953, IFEV-3619, IFEV-3617, IFEV-2880 | FST-3191 | [Configura tastiera](configura-tastiera.md) |
| Tavoli, comande e segue | Il parametro «Blocca articoli avanzati» decide cosa si può fare sui piatti di un segue già in cucina: acceso, si cambia il prezzo ma non si storna; spento, lo storno è permesso ed esce l'annullo. Pressione lunga su Sospendi per non stampare le comande. Corretti comande doppie, annulli non stampati e intestazioni dei segue sbagliate. | IFEV-4045, IFEV-1112, IFEV-4291 | FST-3157, FST-3158 | [Segue già in cucina](segue-blocca-articoli-avanzati.md) |
| Vendita | Maggiorazione a valore e in percentuale, allergeni nel dettaglio dell'articolo, resto più visibile. Lo sconto di un conto cancellato non torna più sullo scontrino dopo; corretti il totale fermo e le varianti con più pezzi pagate più del dovuto. | IFEV-3937, IFEV-1227, IFEV-3075, IFEV-4094, IFEV-4125 | FST-3254 | |
| Scontrino e RT | Niente più scontrino stampato due volte se la RT smette di rispondere, né vendita sommata a uno scontrino rimasto aperto. Errori della RT con il codice al posto di «errore sconosciuto»; l'avviso di chiusura Z obbligatoria non ha più il titolo «Errore». | IFEV-4113, IFEV-4129, IFEV-4132, IFEV-4026, IFEV-4105 | | [Correzioni principali](correzioni-principali.md) |
| Palmari | Il cambio uscita di un articolo si vede subito nel riepilogo ordine. Corretti la comanda stampata due volte con la conferma in ritardo, le note dei piatti perse riaprendo il tavolo e il segue avanzato senza rete. Accesso con più di 8 operatori. | IFEV-4077, IFEV-4292, IFEV-4301, IFEV-2638 | FST-3253 | [Correzioni principali](correzioni-principali.md) |
| Fatture | Fattura differita rivista: un'emissione interrotta non finisce in una seconda fattura e «Rigenera e ristampa» mantiene sezionale e numero. Accettato il codice fiscale numerico delle società. Verso MyCustom i certificati sono dentro l'app e un problema di certificato non appare più come «Configurazione errata». | IFEV-2767, IFEV-3972, IFEV-4153, IFEV-4262 | FST-3270 | [Fattura differita](fattura-differita.md) |
| Importazione del menu da foto | I piatti nuovi non sovrascrivono gli articoli esistenti e le categorie riconosciute diventano reparti nuovi. | IFEV-3771 | FST-3260, FST-3263 | |
| Incassi e statistiche | Il venduto della dashboard torna con l'incassato, il reso RT si sottrae invece di sommarsi e una chiusura fatta fuori da «Fine giornata» non sposta più le vendite nel giorno nuovo. | IFEV-3270, IFEV-3985 | | [Correzioni principali](correzioni-principali.md) |
| Pagamenti elettronici | Pagamento con carta estera nella sua valuta (DCC) e integrazione DIS-PAY. Il test del terminale POS funziona anche con la RT non in servizio. | IFEV-2519, IFEV-2354, IFEV-2911 | | [Verifiche per l'installatore](verifiche-installatore.md) |
| Backup e licenza | Il ripristino chiede cosa fare della licenza e accetta solo backup di Inventa One; backup FTP anche in modalità attiva; con «Invio del backup» su Nessuno la cassa dice cosa configurare. L'avviso di licenza offline non si ripete ogni 3 minuti e una licenza rifiutata blocca davvero la vendita. | IFEV-3853, IFEV-3846, IFEV-4236, IFEV-3804, IFEV-4087 | | [Backup e ripristino](backup-ripristino.md) |
| Più terminali | Server di backup: se la cassa principale si guasta, un altro terminale può diventare server con una procedura guidata protetta dal codice di sblocco. | IFEV-3898 | | [Funzioni non incluse o nascoste](funzioni-non-incluse.md) |
| Lingue | Lingua scelta dai Parametri; testi in francese, spagnolo e tedesco; nuova lingua da file o con traduzione automatica. | IFEV-2673 | | |
| Inventa Backoffice | Dove c'è il backoffice: scambio di anagrafiche e manutenzioni, invio delle vendite e gestione clienti, con una coda di invio che non blocca più il pagamento. | IFEV-1251 | | [Funzioni non incluse o nascoste](funzioni-non-incluse.md) |

### Altre novità riportate nella guida per installatori

| Area | Cosa cambia |
| --- | --- |
| Altre anagrafiche | Profili operatore con «seleziona/deseleziona tutto» sui permessi; conferma prima di togliere codici e listini dalla scheda articolo; barcode personalizzati con «Prova lettura» e multipesata; anagrafica bilance Unica ETH; pannello «Strumenti DB» per l'assistenza. |
| Piattaforme e prestazioni | Aggiornamento dall'app anche su Linux; pagamento e ricezione delle vendite dagli altri terminali più rapidi. |

Il dettaglio di tutte le funzioni nuove o cambiate è nella pagina [Novità per area](novita-per-area.md).

## Da sapere

- Chi aggiorna dalla 1.0.33 vede l'avviso vecchio «Versione tracciato incompatibile» sui terminali rimasti indietro: si risolve aggiornandoli. Il nuovo avviso con «Aggiorna app» compare solo sui terminali che hanno già la 2.0.21.
- Ogni terminale scarica l'aggiornamento dal canale della propria licenza (produzione o test): prima di aggiornare un locale va verificato che la 2.0.21 sia nel canale della sua licenza.
- Restano nascosti il backup su Google Drive e la configurazione di tastiere, layout e sale dal backoffice.
- Il riepilogo completo di cosa cambia rispetto alla 1.0.33 (184 novità, 638 correzioni, verifiche consigliate) è nel documento [«Inventa One 2.0.21 – cosa cambia rispetto alla 1.0.33»](assets/resources/inventa-one-2.0.21-cosa-cambia-rispetto-1.0.33.pdf).

## Guide operative

- [Terminale con una versione diversa dalla cassa principale](prima-di-aggiornare.md) – avviso vecchio e nuovo, come aggiornare palmari e casse secondarie
- [Configurazione guidata: tipo di attività e reparti proposti](configurazione-guidata.md)
- [Parametri: la nuova pagina con aree e ricerca](parametri.md)
- [Verifiche per l'installatore: i pulsanti di test](verifiche-installatore.md) – RT, mail, stampanti comande
- [Stampanti comande: stampa di prova e comande non stampate](stampanti-comande.md)
- [Layout di stampa: preset e composizione a blocchi](layout-di-stampa.md)
- [Configura tastiera: copiare e incollare più in fretta](configura-tastiera.md)
- [Segue già in cucina: «Blocca articoli avanzati»](segue-blocca-articoli-avanzati.md)
- [Fattura differita e «Rigenera e ristampa»](fattura-differita.md)
- [Backup e ripristino della cassa](backup-ripristino.md)
