---
title: "Inventa One 2.0.21 - Funzioni non incluse o nascoste"
date: "2026-11-23"
version: "2.0.21"
categoria: software Inventa One
---

# Funzioni non incluse o nascoste

## Cosa non fa parte della 2.0.21

- **Configurazione dal backoffice** (tastiere, layout di stampa e mappa delle sale gestiti da Inventa Backoffice): nella 2.0 è nascosta e arriva con la 3.0. Dal backoffice restano lo scambio di anagrafiche e manutenzioni, l'invio delle vendite e la gestione clienti.
- **Comanda con stampante spenta o senza carta durante la stampa**: la correzione non è nel ramo del pilota.
- **Avviso di aggiornamento**: nella 2.0.21 arriva quello nuovo, ma lo mostrano solo i terminali già aggiornati. Durante il passaggio dalla 1.0.33 i palmari rimasti indietro mostrano ancora la finestra vecchia.
- **Fuori dal collaudo del pilota**: seconda cassa e terminale di sala, server di backup, backoffice, bilance, pagamento DCC e DIS-PAY sono presenti ma non fanno parte delle prove fatte per i locali pilota.
- **Backup su Google Drive**: resta nascosto come nella 1.0.33, perché non è ancora pronto.

!!! warning "Attenzione"
    Se un cliente vede il backup su Google Drive, è un errore da segnalare.

!!! warning "Attenzione"
    La correzione per la comanda con stampante spenta o senza carta durante la stampa non è nel ramo del pilota: se un locale la segnala, non è ancora coperta dalla 2.0.21. Vedi [Stampanti comande](stampanti-comande.md).

## Server di backup (presente, non collaudato)

Se la cassa principale si guasta, un altro terminale può diventare server con una procedura guidata, protetta dal codice di sblocco. Può farlo anche un terminale di sala o un palmare senza RT. Gli altri terminali si collegano da soli al nuovo server, e quando il vecchio server torna si evita il doppio server.

## Inventa Backoffice

Dove c'è il backoffice restano lo scambio di anagrafiche e manutenzioni, l'invio delle vendite e la gestione clienti, con una coda di invio che non blocca più il pagamento. Lo scambio dati ha ricevuto circa 110 correzioni.

??? info "Riferimenti"
    Card di riferimento: IFEV-3545 (configurazione dal backoffice), IFEV-3818 (comanda con stampante spenta o senza carta), IFEV-3903, IFEV-3904, IFEV-3905, IFEV-3917, IFEV-3952 (server di backup).

    Fonti: Guida al changelog per i tecnici installatori (cap. 14), «Inventa One 2.0.21 – cosa cambia rispetto alla 1.0.33».
