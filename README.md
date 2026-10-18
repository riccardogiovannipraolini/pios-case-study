# PIOS · case study

> **English summary.** PIOS (Personal Intentional Operating System) is the personal operating system I designed and run in Notion: a single intake, a plan that only review decisions can authorise, weekly sprints and monthly reviews that correct the system itself. It evolved from personal planning systems I have kept for about three years; the current Notion version dates from February 2026. Single user, with an AI assistant for context and rituals. The case below shows the system correcting itself on evidence: a broken time model in June 2026, a restart in July, 11 completed reviews by 20 September 2026.

**PIOS** (Personal Intentional Operating System) è il sistema operativo personale che ho progettato e costruito in Notion, e che uso ogni settimana: trasforma stimoli e decisioni in lavoro pianificato, e usa le review per correggersi.

Questo repository contiene il case study, non il sistema. Il workspace reale contiene dati personali e resta privato.

| | |
|---|---|
| **Ruolo** | Progettista e unico utente |
| **Periodo** | sistema personale di pianificazione in evoluzione da circa tre anni (le versioni precedenti non sono conservate); primi elementi oggi presenti in Notion: marzo 2025; versione attuale: da febbraio 2026, in corso |
| **Strumenti** | Notion (database relazionati), assistente AI per i rituali |
| **Stato** | in uso; sistema a utente singolo |

## Il problema

Il problema non era fare più cose, ma decidere senza perdersi. Studio, lavoro, salute e finanze vivevano in posti separati, le decisioni venivano riaperte di continuo e il calendario non conservava il perché delle scelte.

Il prodotto necessario: un solo ingresso, autorità esplicite, lavoro autorizzato prima di essere eseguito, e review capaci di trasformare dati e frizioni in decisioni.

## Il sistema

Tre motori, un solo ciclo:

1. **Direzione**: le aree della vita, ognuna con mandato e metriche, decidono che cosa conta.
2. **Piano**: un unico registro di progetti e task autorizza e ordina il lavoro.
3. **Esecuzione**: sprint settimanali consegnano e misurano.

Un ingresso unico raccoglie ogni stimolo. La regola cardine è che l'ingresso non alimenta automaticamente il piano: solo una decisione presa in review autorizza nuovo lavoro. Sprint Review settimanali e Monthly Review mensili riportano l'apprendimento verso l'alto. Le regole operative vivono in un database di articoli, che è l'unica fonte di verità.

Un assistente AI recupera il contesto e aiuta nell'esecuzione dei rituali. Direzione e decisioni restano mie.

## Il ciclo completo: il restart di luglio

Il caso che mostra meglio il sistema che si corregge sull'evidenza:

1. **Evidenza.** Giugno 2026: oltre quattro settimane senza Sprint Review, con la Monthly di giugno rimasta incompleta, in un mese occupato da tesi, esami e preparazione dello stage.
2. **Interpretazione.** Al restart, con lo stage appena iniziato (1 luglio), il modello di allocazione delle ore risultava impossibile: era stato pensato prima dello stage, e 40 ore di lavoro più il tragitto non ci stavano.
3. **Decisione.** Riallineare la capacità invece di aumentare la pressione sull'esecuzione. Cancellare le review vecchie e far ripartire il ciclo da zero, invece di trascinarsi dietro un registro sporco.
4. **Modifica.** Una nuova categoria di tempo per il lavoro dipendente, contato dall'uscita di casa al rientro. Il modello precedente assumeva per i progetti personali circa quattro volte le ore davvero disponibili.
5. **Nuovo esito.** Al 20 settembre 2026, dal restart del 4 luglio: 11 review completate, 9 Sprint Review settimanali e 2 Monthly. Dalla prima Sprint Review del nuovo ciclo, il 19 luglio, era saltata una sola settimana.

## Altre decisioni di prodotto

- **Non riscrivere tutto.** Ho valutato di migrare il sistema su un runtime locale, con file aperti e un'interfaccia su misura. L'ho rinviato: la migrazione era lunga, le relazioni andavano ricostruite e l'assistente AI avrebbe avuto meno contesto. Ho scelto di restare su Notion, con un export in Markdown e git come copertura. La migrazione non è mai partita e l'export non è ancora verificato.
- **Maturità per sottrazione.** Le revisioni di settembre hanno tolto più di quanto hanno aggiunto: un solo registro per progetti e task, un ingresso smaltito in due passaggi (settimanale e mensile), metriche che nascono all'avvio di un progetto e vengono chiuse alla fine. Le regole operative ora stanno negli articoli, senza più una sintesi separata da tenere allineata. Già ad agosto erano stati eliminati i controlli periodici che costavano più di quanto rendevano.
- **Uscire dal sistema.** Lo stesso metodo mi serve oggi per organizzare il lavoro di stage, in un sistema separato.

## Cronologia

| Data | Passaggio |
|---|---|
| circa 2023 – 2025 | versioni precedenti del sistema personale, non conservate |
| marzo 2025 | primi elementi oggi presenti in Notion |
| 12 febbraio 2026 | nasce la radice della versione attuale |
| 11 marzo 2026 | prima specifica tecnica |
| 13–18 aprile | primo avvio completo |
| 22 maggio | arriva l'assistente AI |
| giugno | oltre quattro settimane senza review |
| 4 luglio | restart e riallineamento della capacità |
| 19 luglio | prima Sprint Review del nuovo ciclo |
| 24 agosto | decisione di restare su Notion |
| settembre | revisioni di semplificazione |

## Perché è product management

| Competenza | Come si vede in PIOS |
|---|---|
| Discovery | osservazione del comportamento e delle frizioni, registrata in review e decisioni |
| Strategia | gerarchia di fini, aree e focus del mese |
| Prioritizzazione | l'ingresso non alimenta il piano senza una decisione presa in review |
| Execution | roadmap, dipendenze, sprint, criteri di accettazione |
| Misura | metriche scelte all'avvio di ogni progetto |
| Sistemi AI | instradamento del contesto, memoria, competenze e permessi dell'assistente |

## Limiti

- **Un solo utente, nessuna adozione esterna.** Il sistema prova di sapersi correggere sull'evidenza, non una validazione di mercato.
- **Il registro prima del restart è parziale:** le quattro Sprint Review di aprile e maggio sono state cancellate; restano le Monthly.
- **La serie non è continua:** la settimana dal 31 agosto al 6 settembre non ha avuto review. I dati del nuovo esito sono fermi al 20 settembre 2026.
- **Rischio strutturale:** l'eccesso di struttura. Ogni pezzo deve giustificare il proprio costo di manutenzione.
