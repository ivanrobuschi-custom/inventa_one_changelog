---
title: "Recupero password tramite domande segrete"
date: "2026-10-07"
version: "1.0.29"
categoria: software Inventa One
---

# Recupero password tramite domande segrete

!!! note "Nota"
    Funzione già presente dalla 1.0.29 (07/10/2026), quindi anche nella 1.0.33. È riportata qui perché cambia il modo di sbloccare una password dimenticata: lo sblocco con il minuto corrente non c'è più.

[Scarica la guida in PDF](assets/resources/guida-recupero-password.pdf)

## A cosa serve

Permette a un operatore che ha dimenticato la password di recuperarla da solo, rispondendo a domande segrete scelte in precedenza. Funziona senza connessione e a qualsiasi orario. Vale sia per le password degli operatori sia per quella di «Configura parametri».

Sostituisce lo sblocco precedente (inserimento del minuto corrente e ritorno alla password predefinita), giudicato troppo semplice.

Cosa si vuole ottenere:

- recupero password sicuro, senza intervento dell'assistenza nei casi normali;
- funzionamento offline e a qualsiasi ora;
- nessun blocco per gli operatori che oggi non hanno una password.

## Come si usa

### Cosa c'è di nuovo

- Quando l'applicazione chiede una password (accesso di un operatore o ingresso in Configura parametri), sotto il campo compare la scritta **Non ricordi la password?** con il tasto **Recupera**.
- Il recupero funziona rispondendo alle domande segrete scelte in precedenza, poi si imposta subito una password nuova. Lo sblocco con il minuto corrente non c'è più.
- Le domande si impostano e il recupero si fa solo sulla cassa principale (o sulla cassa singola). Su una cassa secondaria un messaggio rimanda alla cassa principale.

### Impostare le domande segrete di un operatore

1. Dal menu aprire **Configura Operatori** e selezionare l'operatore. Deve essere già salvato: su un operatore appena inserito il riquadro compare dopo il primo Salva.
2. Nel dettaglio dell'operatore c'è il riquadro **Domande segrete** (icona a scudo). Indica la situazione attuale, per esempio «2 di 3 impostate» oppure «Nessuna domanda impostata».
3. Premere **Modifica**: si apre il foglio «Domande segrete – nome operatore», con tre righe (DOMANDA 1, 2 e 3).
4. Per ogni riga scegliere una domanda dall'elenco, oppure **Nessuna domanda**, e scrivere la risposta. Una domanda già usata in un'altra riga è segnata «già scelta». Si possono impostare da 0 a 3 domande.
5. Premere **Salva**. **Annulla** chiude senza cambiare nulla.

Domande disponibili:

- Come si chiamava il tuo primo animale domestico?
- In quale città sei nato?
- Qual è il cognome da nubile di tua madre?
- Come si chiamava la tua scuola elementare?
- Qual era il modello della tua prima auto?
- Qual è il tuo piatto preferito?

Per cambiare le domande in seguito si ripete lo stesso percorso. Le risposte già salvate non vengono mai mostrate: su una domanda già salvata il campo risposta resta vuoto con la scritta «Risposta salvata: lascia vuoto per non cambiarla». Per toglierle tutte si usa **Rimuovi domande**, che chiede conferma.

### Impostare le domande segrete per «Configura parametri»

1. Entrare in **Configura parametri**.
2. Accanto al campo «Password per accedere alla configurazione» c'è il tasto **Domande segrete**.
3. Il tasto apre lo stesso foglio degli operatori («Domande segrete – Configura parametri»), che si compila allo stesso modo.

### Recuperare una password dimenticata

1. Alla richiesta della password (dopo aver scelto l'operatore, oppure entrando in Configura parametri) premere **Recupera**, accanto a «Non ricordi la password?».
2. Si apre il foglio «Recupera la password di *nome*». In alto si legge quanti tentativi restano («Tentativi a disposizione: 5 di 5»). Sotto ci sono tutte le domande impostate, ciascuna con il suo campo risposta.
3. Rispondere a tutte le domande e premere **Verifica**.
    - Se anche una sola risposta è sbagliata compare in rosso «Risposte non corrette. Tentativi rimasti: ...». Il foglio resta aperto e si può riprovare.
    - Se le risposte sono tutte giuste si apre il foglio **Imposta la nuova password**.
4. Scrivere la password in **Nuova password** e ripeterla in **Conferma nuova password**, poi premere **Salva**.
5. Compare il messaggio **Password aggiornata**. Si torna alla richiesta della password, dove si entra con quella nuova.

## Da sapere

- Nelle risposte non contano maiuscole, spazi doppi, accenti e punteggiatura: «Fido», «fido» e «FIDO!» sono la stessa risposta.
- Se per quell'operatore (o per Configura parametri) non sono state impostate domande, premendo Recupera compare **Recupero non disponibile**: il ripristino lo fa l'assistenza.
- Dopo 5 tentativi sbagliati compare **Recupero bloccato**. Il recupero si sblocca quando si entra con la password corretta, oppure con l'intervento dell'assistenza.
- Se le anagrafiche sono gestite dal backoffice e in cassa non si possono modificare, il tasto **Modifica** del riquadro Domande segrete è disattivato.

??? info "Riferimenti"
    Stato: rilasciata in Inventa One 1.0.29 (07/10/2026).

    Epica di riferimento: IFEV-3415 – Recupero password tramite domande segrete. Sostituisce lo sblocco introdotto con IFEV-3162.
