---
title: "Inventa One 2.0.21 - Novità per area"
date: "2026-11-16"
version: "2.0.21"
categoria: software Inventa One
---

# Novità per area

Qui ci sono le funzioni nuove o cambiate che l'esercente o l'installatore vede rispetto alla 1.0.33. Le correzioni sono nella pagina [Correzioni principali](correzioni-principali.md).

La 2.0.21 prende il posto della 1.0.33, in produzione dal 30/10. Rispetto alla 1.0.33 porta circa cinque mesi di sviluppo: 184 novità e migliorie e 638 correzioni. Rispetto alla 2.0.20 aggiunge il nuovo avviso di aggiornamento per palmari e terminali (IFEV-4307), un'evolutiva che vale per gli aggiornamenti futuri.

[Scarica il documento «cosa cambia rispetto alla 1.0.33» in PDF](assets/resources/inventa-one-2.0.21-cosa-cambia-rispetto-1.0.33.pdf)

## Vendita e cassa

- **Tasto «Gruppo reparti»**: apre i reparti del gruppo e poi i loro articoli (IFEV-3617). Vedi [Configura tastiera](configura-tastiera.md).
- **Tasto «Funzioni»** che raccoglie più funzioni in un solo tasto della tastiera (IFEV-2880).
- **Maggiorazione** a valore e in percentuale, accanto agli sconti (IFEV-3937).
- **Resto più visibile**: la dimensione del testo del resto si imposta in «Configurazione header» (IFEV-3075).
- **Allergeni**: nel dettaglio dell'articolo un pulsante info mostra gli allergeni collegati (IFEV-1227).
- **Messaggi della RT più chiari**: per un errore non riconosciuto compare il codice restituito dalla stampante, e l'avviso di chiusura Z obbligatoria non ha più il titolo «Errore» (IFEV-4026, IFEV-4105).
- **Pulsanti dei popup** più grandi e più facili da toccare (IFEV-3586).
- **Pagamenti elettronici**: pagamento con carta estera nella valuta della carta (DCC) e integrazione DIS-PAY (IFEV-2519, IFEV-2354). Il test dei terminali POS funziona anche con la RT non in servizio: fa una chiusura POS (IFEV-2911).
- **Cassetto automatico**: svuotamento a fondo cassa e azzeramento del contatore delle banconote (IFEV-3656, IFEV-3657).

## Tavoli, comande e segue

- **Flag «Blocca articoli avanzati»**: decide se sui piatti di un segue già mandato in cucina si possono cambiare prezzo e fare storni (FST-3157, FST-3158 → IFEV-4049). Vedi [Segue già in cucina](segue-blocca-articoli-avanzati.md).
- **Pressione lunga su «Sospendi»**: sospende il conto senza stampare le comande, dopo una domanda di conferma (IFEV-1112).
- **«Coperti obbligatori»** su una sala senza articoli di tipo coperto: la cassa propone di crearne uno (IFEV-3989).
- **Layout di stampa**: valore degli elementi composto a blocchi (campi e testo libero da riordinare), taglio con tipo e righe di avanzamento, nomi lunghi su due righe anche in doppia larghezza. La stampa di prova non cambia più il layout della stampante (IFEV-1568, IFEV-1669, IFEV-3431). I preset Tallon ci sono anche senza modulo Horeca (IFEV-3599). Vedi [Layout di stampa](layout-di-stampa.md).
- **Stampanti comande**: pannello di verifica con stampa di prova dalla configurazione (FST-3187 → IFEV-2933). Vedi [Stampanti comande](stampanti-comande.md).

## Palmari e più terminali

- **Avviso di aggiornamento più chiaro** (novità della 2.0.21): quando un palmare, una cassa secondaria o un terminale di sala ha una versione diversa dalla cassa principale, l'avviso dice quale terminale va aggiornato, mette a confronto le due versioni, spiega il perché in una riga e ha il pulsante «Aggiorna app» che apre la pagina degli aggiornamenti (IFEV-4307). È un'evolutiva per gli aggiornamenti futuri: lo mostra solo un terminale che ha già la 2.0.21, quindi chi aggiorna dalla 1.0.33 vede ancora l'avviso vecchio. Vedi [Prima di aggiornare](prima-di-aggiornare.md).
- **Server di backup**: se la cassa principale si guasta, un altro terminale può diventare server con una procedura guidata, protetta dal codice di sblocco. Può farlo anche un terminale di sala o un palmare senza RT. Gli altri terminali si collegano da soli al nuovo server, e quando il vecchio server torna si evita il doppio server (IFEV-3903, IFEV-3904, IFEV-3905, IFEV-3917, IFEV-3952). Nel pilota non è previsto, ma è presente.
- **Accesso al palmare con più di 8 operatori** (IFEV-2638).

## Configurazione

- **Nuova pagina Parametri**: sezioni nella barra laterale, ricerca su tutti i parametri, conteggio dei parametri modificati e pulsanti Test accanto all'indirizzo della RT e alla configurazione mail (IFEV-3087, IFEV-4032, FST-3186 → IFEV-3310, IFEV-2997). Vedi [Parametri](parametri.md) e [Verifiche per l'installatore](verifiche-installatore.md).
- **Configura tastiera**: selezione di più tasti con azioni di gruppo (copia su altre pagine, anche di una pagina intera; incolla su più tasti scegliendo insieme reparti o funzioni; applica stile; svuota), copia del tasto con tutte le proprietà già spuntate, «Clona» e selettore della pagina durante la modifica, segno «già presente in tastiera» su articoli, reparti e funzioni (IFEV-3523, IFEV-3881, IFEV-3882, IFEV-2953, IFEV-2955, FST-3191 → IFEV-3619). Vedi [Configura tastiera](configura-tastiera.md).
- **Configurazione guidata**: si sceglie il tipo di attività (Bar, Ristorante, Negozio o Generico) e la cassa propone 10 reparti con l'IVA e i tasti funzione adatti al locale; gli articoli si aggiungono a mano (IFEV-3196, IFEV-4082). Vedi [Configurazione guidata](configurazione-guidata.md).
- **Vecchie pagine di configurazione tolte**: 19 pagine sostituite dalle nuove anagrafiche (IFEV-3685).
- **Profili operatore**: «seleziona/deseleziona tutto» sull'elenco dei permessi (IFEV-3073).
- **Scheda articolo**: conferma prima di togliere codici, listini e altre righe (IFEV-3669).
- **Barcode personalizzati**: «Prova lettura», barcode multipesata, struttura creata dalla scansione di un barcode esistente (IFEV-2479, IFEV-2480, IFEV-2481).
- **Bilance Unica ETH**: anagrafica bilance e invio degli articoli (IFEV-2373).
- **Lingue**: lingua scelta dai Parametri, file in francese, spagnolo e tedesco, nuova lingua da file o con traduzione automatica in «Configura testi in lingua» (IFEV-2677, IFEV-2682, IFEV-2685).
- **Pannello «Strumenti DB»** per l'assistenza (IFEV-2198).

## Fatture e documenti

- **Fattura differita rivista**: l'emissione interrotta non finisce in una seconda fattura, «Rigenera e ristampa» mantiene sezionale e numero (IFEV-2767, IFEV-3972, IFEV-3974). Vedi [Fattura differita](fattura-differita.md).
- **MyCustom**: i certificati necessari sono dentro l'app, e un problema di certificato non compare più come «Configurazione errata» (FST-3270 → IFEV-4263).
- **Scontrini dematerializzati**: pagina per consultarli e reinviarli (IFEV-2873).

## Backup, licenze e assistenza

- **Backup e ripristino**: al ripristino da file o da FTP la cassa chiede cosa fare della licenza e accetta solo backup di Inventa One; il backup FTP si può fare anche in modalità attiva; con «Invio del backup» su Nessuno il backup automatico non parte e la cassa dice cosa configurare (IFEV-3853, IFEV-3846, IFEV-4236). Vedi [Backup e ripristino](backup-ripristino.md).
- **Licenze**: l'avviso «licenza offline» non si ripresenta ogni 3 minuti, una licenza rifiutata blocca davvero la vendita, «Carica licenza» funziona dalla finestra di blocco (IFEV-3805, IFEV-4088, IFEV-3809).
- **Log per l'assistenza**: le richieste di log arrivano anche ai palmari, e gli errori di comande e comunicazione finiscono nei log consultabili (IFEV-4148, IFEV-3822).

## Altre piattaforme e prestazioni

- Aggiornamento dall'app anche su Linux (IFEV-1237).
- Pagamento e ricezione delle vendite dagli altri terminali più rapidi (IFEV-2692, IFEV-2701).
- Interrogazioni AI delle vendite: dal grafico si apre il dettaglio dell'elemento toccato (IFEV-2656).
