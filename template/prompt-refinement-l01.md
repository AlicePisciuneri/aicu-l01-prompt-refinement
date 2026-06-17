# Prompt Refinement L01

## Prompt Di Partenza

Incolla qui il prompt scelto.

Aggiungi un messaggio carino quando non ci sono ticket aperti.

## Diagnosi Operativa

- Informazioni mancanti:
- Ambiguita':
- Rischio di scope troppo largo:
- Output non verificabile:
- Strategia iniziale: zero-shot / few-shot / non chiara
- Servono esempi? Si / No, perche':

## Diagnosi Operativa Alice

* Informazioni mancanti:

  * Non è specificato cosa si intenda per "carino".
  * Non è indicato il tipo di applicazione o il contesto in cui compare il messaggio.
  * Non è specificato dove debba essere visualizzato il messaggio.
  * Non è chiaro se si richiede solo un testo o anche elementi grafici.
  * Non sono definiti tono, lunghezza o obiettivo della comunicazione.

* Ambiguità:

  * Il termine "carino" è soggettivo e può essere interpretato in modi diversi.
  * Il termine "messaggio" può riferirsi a diverse tipologie di contenuto.
  * Non è chiaro quale stile comunicativo debba essere utilizzato.

* Rischio di scope troppo largo:

  * L'AI potrebbe proporre modifiche all'interfaccia oltre al semplice messaggio.
  * Potrebbe suggerire immagini, icone, animazioni o altri elementi non richiesti.
  * Potrebbe introdurre cambiamenti che non rispettano il tono generale dell'applicazione.
  * Potrebbe produrre contenuti troppo lunghi, troppo brevi, troppo informali o troppo professionali.

* Output non verificabile:

  * Non esiste un criterio oggettivo per stabilire se il messaggio sia davvero "carino".
  * Non sono definiti requisiti minimi per valutare il risultato.
  * Non è possibile verificare facilmente se l'output rispetta le aspettative del team.

* Strategia iniziale:

  * Zero-shot

* Servono esempi?:

  * No, perché il problema principale non riguarda il formato dell'output ma la mancanza di contesto, vincoli e criteri di verifica. Istruzioni più precise sono sufficienti per rendere il prompt controllabile.





## Prompt Usato Per Migliorare

```txt
Aiutami a migliorare questo prompt.
Non risolvere il task.
Dimmi prima quali informazioni mancano.
Indica se basta una versione zero-shot o se servono 1-2 esempi few-shot.
Non mostrare chain-of-thought estesa: elenca solo assunzioni, criterio e verifica proposta.
Poi proponi una versione migliore.
```





## Strategia Del Prompt Finale

- Zero-shot o few-shot:
- Motivo della scelta:
- Se few-shot, cosa dimostrano gli esempi:
- Evidenze richieste all'AI: assunzioni / criterio / verifica


Zero-shot o few-shot: Zero-shot
Motivo della scelta: il formato dell'output è semplice e non richiede esempi; il miglioramento dipende soprattutto da contesto, confini e criteri di verifica
Evidenze richieste all'AI: assunzioni, criterio utilizzato e verifica proposta




## Prompt Migliorato

Stiamo lavorando a una piccola applicazione didattica di gestione ticket.

Quando la lista dei ticket aperti è vuota, proponi un messaggio di solo testo da mostrare all'utente nell'empty state.

Confini:

* Non modificare il layout dell'interfaccia.
* Non proporre immagini, icone o altri elementi grafici.
* Non introdurre nuove funzionalità.
* Non produrre codice, patch o pull request.

Output richiesto:

* Proponi un singolo messaggio.
* Fornisci una breve spiegazione del criterio utilizzato.

Verifica:

* Il messaggio deve comunicare chiaramente che non sono presenti ticket aperti.
* Deve mantenere un tono professionale e coerente con un'applicazione di gestione ticket.
* Deve essere composto da massimo 5 parole.

Evidenze:

* Elenca eventuali assunzioni effettuate.
* Indica il criterio utilizzato.
* Spiega come verificheresti che il risultato sia adeguato.


## Controllo Qualita'

- Contesto presente:
- Confini espliciti:
- Output atteso:
- Prova di controllo:
- Cosa chiede all'AI di non fare:
- Esempi necessari e proporzionati:
- Evita chain-of-thought estesa:
- E' piu' specifico perche':
- Limita meglio il lavoro perche':
- Produce un output piu' verificabile perche':
- Lo classificherei come: Vago / Utilizzabile / Controllabile / Consegnabile


## Controllo Qualità

* Contesto presente:

  * Sì, viene specificato che si tratta di una piccola applicazione didattica di gestione ticket.

* Confini espliciti:

  * Sì, viene indicato di non modificare il layout, non introdurre nuove funzionalità e non produrre codice.

* Output atteso:

  * Sì, viene richiesto un singolo messaggio accompagnato da una breve spiegazione del criterio utilizzato.

* Prova di controllo:

  * Sì, il messaggio deve comunicare chiaramente l'assenza di ticket aperti, mantenere un tono professionale e avere una lunghezza massima di 5 parole.

* Cosa chiede all'AI di non fare:

  * Non modificare l'interfaccia, non proporre elementi grafici, non introdurre nuove funzionalità e non produrre codice.

* Esempi necessari e proporzionati:

  * No, il prompt utilizza una strategia zero-shot perché il formato dell'output è semplice e non richiede esempi.

* Evita chain-of-thought estesa:

  * Sì, richiede solo assunzioni, criterio utilizzato e verifica proposta.

* È più specifico perché:

  * Definisce contesto, obiettivo, limiti e criteri di valutazione.

* Limita meglio il lavoro perché:

  * Riduce le possibilità di interpretazioni arbitrarie e impedisce modifiche fuori scope.

* Produce un output più verificabile perché:

  * Stabilisce requisiti chiari e misurabili per valutare il risultato.

* Lo classificherei come:

  * Controllabile
