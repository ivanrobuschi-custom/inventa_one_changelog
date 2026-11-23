---
title: "Inventa One 2.0.21 - Correzioni principali per area"
date: "2026-11-23"
version: "2.0.21"
categoria: software Inventa One
---

# Correzioni principali per area

Le 638 correzioni toccano tutte le aree. Qui ci sono gli esempi più rilevanti per chi assiste i locali. Alcune correggono difetti nati durante lo sviluppo della 2.0, che i locali non hanno mai visto.

## Esempi per area

| Area | Cosa è stato corretto (esempi) |
| --- | --- |
| Scontrino e RT | Scontrino stampato due volte se la RT smette di rispondere (IFEV-4113); scontrino rimasto aperto nella RT sommato o annullato dalla vendita dopo (IFEV-4129); vendita senza numero di scontrino dopo un errore della RT (IFEV-4132); «Carta terminata» con la carta presente (IFEV-3473); sconti con un centesimo in meno (IFEV-3947); annulli e resi su RT che non arrivano alla cassa principale (IFEV-4175). |
| Vendita | Totale a video fermo dopo codice a barre, Ricerca articoli o reso (IFEV-3646, IFEV-4062, IFEV-4074); varianti con quantità maggiore di 1 pagate più del dovuto (IFEV-4125); cambio prezzo di riga che azzerava gli sconti delle altre righe (IFEV-3380); IVA al 10% inventata se il codice IVA dell'articolo manca (IFEV-3208); lo sconto di un conto cancellato non torna più sullo scontrino dopo (si azzera anche per convenzioni e ricariche). |
| Tavoli e comande | Tavolo che restava «in corso» dopo Dividi conto o conto alla romana (IFEV-3588); articoli spariti spostandoli fra tavoli (IFEV-3692); «Ritenta la stampa» che diceva «completato» con la stampante spenta (IFEV-3426); piatto tolto da un segue già in cucina senza annullo (IFEV-4296); numero d'asporto ripetuto (IFEV-3471). |
| Palmari | Comanda stampata due volte se la conferma della cassa arriva in ritardo (IFEV-4292); note dei piatti cancellate riaprendo il tavolo (IFEV-4301); segue avanzato senza rete che non arrivava in cucina (IFEV-4297); «Apri Tavolo» col numero che apriva un tavolo diverso (IFEV-3601); pagamenti doppi dopo un timeout (IFEV-4205). |
| Incassi e statistiche | Venduto della dashboard più basso dell'incassato (IFEV-3277); reso RT sommato come vendita (IFEV-3278); chiusura fatta fuori da «Fine giornata» che lasciava le vendite nel giorno nuovo (IFEV-4080); filtro «Data» della lista movimenti sulla giornata lavorativa (IFEV-3827). |
| Fatture | Fattura differita che includeva vendite annullate (IFEV-3971); codice fiscale numerico di società rifiutato (IFEV-4153); numero della fattura elettronica oltre 20 caratteri con sezionali lunghi (IFEV-3742); «Ritenta invio» che mandava anche le fatture annullate (IFEV-3965). |
| Configurazione | Annulla incompleto in Configura tastiera (IFEV-3337); configurazione guidata rifatta su un archivio in uso che rinominava i reparti (IFEV-3863); stampante eliminata senza avviso anche se usata da un terminale (IFEV-4016); prezzo che perdeva il terzo decimale (IFEV-3734); virgola non accettata nelle finestre degli importi (IFEV-3782). |
| Licenze e backup | Licenza rifiutata che tornava a vendere riavviando (IFEV-4088); backup FTP dato per riuscito senza farlo (IFEV-3846); ripristino interrotto che faceva perdere il database (IFEV-3847); chiusura giornaliera bloccata se l'esportazione dei log non riesce (IFEV-3794). |
| Offerte | Happy Hour di un gruppo di clienti applicata a tutti e listino dell'offerta rimasto dopo la fascia oraria (IFEV-3785, IFEV-3787). |
| Permessi operatori | Ora sono rispettati: Omaggio e sconto dal menu della riga chiedono il permesso degli sconti, SBT a vendita vuota quello di apertura cassetto, l'annullo da «Funzioni RT» quello di annullo, il preconto dalla lista movimenti quello del preconto (IFEV-3717, IFEV-3720, IFEV-3719, IFEV-3829). |
| Backoffice | Circa 110 correzioni allo scambio dati: vendite inviate una sola volta e con i totali giusti, coda che non blocca il pagamento se il backoffice è lento, variazioni che non si perdono. |
| Assistenza | Le richieste di log arrivano anche ai palmari; gli errori di comande e comunicazione finiscono nei log consultabili (IFEV-4148, IFEV-3822). |

## Richieste dei locali risolte nella 2.0.21

Undici FST hanno la soluzione nella 2.0.21 e non nella 1.0.33. FST-3155, FST-3241, FST-3244 e FST-3246 erano già risolte nella 1.0.33.

| FST | Card | Area | Problema segnalato | Nella 2.0.21 |
| --- | --- | --- | --- | --- |
| FST-3157 | IFEV-4049 | Tavoli e segue | Non si può cambiare il prezzo di un piatto di un segue già avanzato | Con «Blocca articoli avanzati» acceso il prezzo si cambia, perché non va in comanda |
| FST-3158 | IFEV-4049 | Tavoli e segue | Non si può stornare un piatto già stampato in un segue | Con il parametro spento lo storno è permesso ed esce l'annullo in cucina; con il parametro acceso resta bloccato |
| FST-3160 | IFEV-4053 | Pagamenti | Resto non abilitato sul pagamento Contanti | Nessuna modifica: il resto è già attivo sui database nuovi; sulle installazioni vecchie va acceso a mano |
| FST-3186 | IFEV-3310 | Configurazione | Manca un test rapido della RT | Pulsante Test accanto all'indirizzo della RT nei Parametri |
| FST-3187 | IFEV-2933 | Stampanti | Manca un test della stampante termica | Pannello di verifica con stampa di prova nella configurazione delle stampanti |
| FST-3191 | IFEV-3619 | Tastiera | Non si vede cosa è già sulla tastiera | Segno «già presente» su articoli, reparti e funzioni in Configura tastiera |
| FST-3253 | IFEV-4078 | Palmare | Il cambio uscita di un articolo non si vede nel riepilogo ordine | Il riepilogo si aggiorna subito |
| FST-3254 | IFEV-4095 | Vendita | Lo sconto di un conto cancellato torna sullo scontrino dopo | Lo sconto si azzera quando si svuota la vendita, anche per convenzioni e ricariche (IFEV-4103) |
| FST-3260 | IFEV-3772 | Importazione menu | Alla seconda importazione da foto i nuovi piatti sovrascrivono quelli esistenti | I piatti nuovi non toccano gli articoli esistenti |
| FST-3263 | IFEV-3772 | Importazione menu | Le categorie riconosciute non diventano reparti | Le categorie nuove diventano reparti nuovi |
| FST-3270 | IFEV-4263 | Fatture | «Errore di configurazione» nell'invio a MyCustom | Certificati dentro l'app e messaggio chiaro se il problema è il certificato |

Guide collegate: [Segue già in cucina](segue-blocca-articoli-avanzati.md), [Verifiche per l'installatore](verifiche-installatore.md), [Stampanti comande](stampanti-comande.md), [Configura tastiera](configura-tastiera.md), [Fattura differita](fattura-differita.md).

??? info "Riferimenti"
    Fonti: Guida al changelog per i tecnici installatori (cap. 13), «Inventa One 2.0.21 – cosa cambia rispetto alla 1.0.33» (sezioni «Correzioni principali per area» e «FST collegate»).
