---
title: "Inventa One 2.0.21 - Guida al changelog per i tecnici installatori"
date: "2026-11-23"
version: "2.0.21"
categoria: software Inventa One
---

# Inventa One 2.0.21 – Guida al changelog per i tecnici installatori

Cosa cambia rispetto alla 1.0.33, come si configurano le novità e cosa verificare dopo l'aggiornamento. Con le schermate della versione 2.0.20 e 2.0.21.

| | |
| --- | --- |
| **Versione software** | 2.0.21 – prima versione della linea 2.0, locali pilota |
| **Data di rilascio** | 17 novembre 2026 |
| **Sostituisce** | 1.0.33 – in produzione dal 30/10/2026 |
| **Documento del** | 23/11/2026 |

!!! warning "Guida riservata"
    Guida riservata ai tecnici installatori. Non distribuire agli esercenti.

## In breve: cosa porta la 2.0.21

La 2.0.21 è la prima versione della linea 2.0 di Inventa One, rilasciata il 17/11/2026 per i locali pilota. Prende il posto della 1.0.33 e porta circa cinque mesi di sviluppo: **184 novità e migliorie** e **638 correzioni**.

Le novità che cambiano il modo di lavorare dell'installatore riguardano soprattutto la configurazione: configurazione guidata con il tipo di attività, pagina Parametri ridisegnata con ricerca, pulsanti di test per RT, mail e stampanti comande, layout di stampa con preset e composizione a blocchi, tastiera con selezione multipla dei tasti. Le correzioni toccano vendita, tavoli e comande, scontrino e RT, palmari e fatture.

### I tre punti da tenere a mente

- **Linea nuova.** Si passa dalla linea 1.0 alla linea 2.0. Cassa principale, casse secondarie, terminali di sala e palmari devono avere la stessa linea: con linee diverse non si scambiano conti e comande.
- **Database.** Alla prima apertura la cassa aggiorna da sola il database e ne tiene una copia di sicurezza. Il passaggio è stato provato su database della 1.0 con mesi di vendite, senza perdita di dati.
- **Verifiche a fine lavoro.** La 2.0.21 ha pulsanti di test che permettono di controllare RT, mail e stampanti comande senza fare una vendita: conviene usarli sempre dopo l'aggiornamento (vedi la [checklist](checklist-verifiche.md)).

## Come è organizzato il portale

!!! note "Nota"
    Le schermate di questa guida vengono dalla 2.0.20 e dalle prove sulla versione di test; nella 2.0.21 l'aspetto è lo stesso. Il portale è pensato per essere letto per area: ogni pagina è autonoma.

### Aggiornamento

| Pagina | Cosa contiene |
| --- | --- |
| [Prima di aggiornare](prima-di-aggiornare.md) | Cassa, palmari e canale della licenza: procedura, avvisi di aggiornamento dei terminali, ritorno alla 1.0 |
| [Checklist dopo l'aggiornamento](checklist-verifiche.md) | Le verifiche consigliate da fare in ogni locale a fine aggiornamento |

### Novità e correzioni

| Pagina | Cosa contiene |
| --- | --- |
| [Novità della release](novita-release.md) | Quadro d'insieme: cosa cambia area per area, con card e FST di riferimento |
| [Novità per area](novita-per-area.md) | Elenco di dettaglio delle funzioni nuove o cambiate |
| [Correzioni principali](correzioni-principali.md) | Esempi delle 638 correzioni e richieste dei locali (FST) risolte |
| [Funzioni non incluse o nascoste](funzioni-non-incluse.md) | Cosa non fa parte del pilota e il server di backup |

### Guide operative

| Guida | Cosa spiega |
| --- | --- |
| [Configurazione guidata](configurazione-guidata.md) | Tipi di locale, reparti e IVA proposti, tasti generati |
| [Parametri](parametri.md) | Aree, ricerca, area «Modificati» e salvataggio |
| [Verifiche per l'installatore](verifiche-installatore.md) | Test della RT, della mail, delle stampanti comande e degli altri controlli |
| [Configura tastiera](configura-tastiera.md) | Selezione di più tasti, copia su altre pagine, incolla su più tasti, Clona pagina, segno «già presente», nuovi tasti |
| [Stampanti comande](stampanti-comande.md) | Pannello di verifica, stampanti in errore e Riconnetti, comande in coda, «Ritenta la stampa» per le comande dei palmari |
| [Layout di stampa](layout-di-stampa.md) | Preset con anteprima, valore composto a blocchi, taglio |
| [Segue già in cucina](segue-blocca-articoli-avanzati.md) | Cosa si può cambiare sui piatti già in cucina, con il parametro «Blocca articoli avanzati» acceso o spento |
| [Fattura differita](fattura-differita.md) | Emissione della fattura differita (TD24) e ristampa con lo stesso sezionale e numero |
| [Backup e ripristino](backup-ripristino.md) | Configurazione, backup manuale, avvisi e ripristino con la scelta della licenza |
| [Recupero password](recupero-password.md) | Recupero tramite domande segrete (già dalla 1.0.29) |

## Documenti scaricabili

- [Guida al changelog per i tecnici installatori (PDF completo)](assets/resources/inventa-one-2.0.21-guida-changelog-installatori.pdf)
- [Changelog Inventa One 2.0.21 – Novità della release (PDF)](assets/resources/changelog-inventa-one-2.0.21.pdf)
- [Inventa One 2.0.21 – cosa cambia rispetto alla 1.0.33 (PDF)](assets/resources/inventa-one-2.0.21-cosa-cambia-rispetto-1.0.33.pdf)

Tutti i documenti, comprese le singole guide operative, sono nella pagina [Download](download.md).
