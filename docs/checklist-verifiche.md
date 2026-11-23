---
title: "Checklist: verifiche consigliate dopo l'aggiornamento"
date: "2026-11-23"
version: "2.0.21"
categoria: software Inventa One
---

# Checklist: verifiche consigliate dopo l'aggiornamento

Da fare in ogni locale a fine aggiornamento, nell'ordine indicato.

| Cosa controllare | Come | Perché |
| --- | --- | --- |
| Stessa versione su cassa e palmari | Su ogni palmare: Menu › Controlla aggiornamento, «Versione installata» | Con linee diverse il palmare non lavora |
| Comanda di prova da ogni palmare | Un tavolo, un piatto, invio, controllo in cucina | Conferma che il palmare parla con la cassa |
| RT | Parametri › indirizzo della RT › Test, poi uno scontrino di prova | La cassa legge matricola e firmware |
| Stampanti comande | Configura tabelle di base › Stampanti › Pannello di verifica › Stampa di prova | Verifica rete e carta di ogni centro di produzione |
| Permessi degli operatori | Configura operatori › profili | Ora sono rispettati: sconti e omaggi, apertura cassetto, annullo da «Funzioni RT», preconto dalla lista movimenti |
| «Blocca articoli avanzati» | Parametri › cerca «Blocca articoli» | Decide se sui segue già in cucina si fanno storni o solo cambi di prezzo |
| Resto sul pagamento Contanti | Configurazione dei pagamenti › Contanti | Sulle installazioni nate prima di aprile 2026 può essere spento |
| Backup | Parametri › cerca «backup» | Con «Invio del backup» su Nessuno il backup automatico non parte e la cassa lo segnala |
| Fatture elettroniche | Parametri › invio fatture › Test | Verifica dati del cedente e invio a MyCustom |
| Mail | Parametri › Mail › Test | Invio di prova con suggerimento del protocollo giusto per la porta |

## Dettaglio sui permessi degli operatori

Con la 2.0.21 i permessi dei profili sono rispettati anche in questi casi:

- Omaggio e sconto dal menu della riga chiedono il permesso degli sconti;
- SBT a vendita vuota chiede il permesso di apertura cassetto;
- l'annullo da «Funzioni RT» chiede il permesso di annullo;
- il preconto dalla lista movimenti chiede il permesso del preconto.

## Dove trovare i passi

| Verifica | Guida |
| --- | --- |
| Versione dei terminali e aggiornamento dei palmari | [Prima di aggiornare](prima-di-aggiornare.md) |
| Test della RT, della mail e delle fatture elettroniche | [Verifiche per l'installatore](verifiche-installatore.md) |
| Stampa di prova delle stampanti comande | [Stampanti comande](stampanti-comande.md) |
| Parametro «Blocca articoli avanzati» | [Segue già in cucina](segue-blocca-articoli-avanzati.md) |
| Invio del backup | [Backup e ripristino](backup-ripristino.md) |
| Ricerca nei Parametri | [Parametri](parametri.md) |

??? info "Riferimenti"
    Card di riferimento: IFEV-3717, IFEV-3720, IFEV-3719, IFEV-3829 (permessi degli operatori), FST-3160 (resto sul pagamento Contanti), IFEV-4236 (invio del backup su Nessuno).

    Fonti: Guida al changelog per i tecnici installatori (cap. 15), «Inventa One 2.0.21 – cosa cambia rispetto alla 1.0.33».
