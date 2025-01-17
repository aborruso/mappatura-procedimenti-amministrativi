# Architettura dello schema per descrivere i metadati minimi che identificano un procedimento amministrativo
Di seguito viene proposto uno schema di metadati minimi per identificare un procedimento amministrativo. Lo schema vuole avere l'obiettivo di orientare il personale della Pubblica Amministrazione, soprattutto dell'ente comunale, nell'attività di assegnare proprietà quanto più dettagliate e specifiche al procedimento amministrativo.

I metadati individuati sono 30 e sono applicabili a qualsiasi procedimento amministrativo.

| **==Denominazione dei metadati per descrivere le informazioni relative al procedimento amministrativo==** | **==Risposte==** | **==Note che si ritengono utili inserire per illustrare al meglio le informazioni sul procedimento amministrativo==** |
|:-----|:-----|:-----|
| individuare la denominazione per ogni metadato per il quale si richiede al compilatore di inserire informazioni | dare al compilatore questo campo per descrivere le informazioni relative al metadato associato (colonna precedente) | dare al compilatore questo campo per inserire eventuali informazioni ad approfondimento del precedente campo “Risposte” |

Si tratta di uno schema semplice per la compilazione, alla portata di tutti in una pubblica amministrazione. 

E' essenziale fornire uno schema semplice da compilare, piuttosto che uno schema "professionale" per mappare e modellare/ottimizzare i processi, in quanto uno schema complesso comporta la conoscenza completa dello stesso da parte di tutti i soggetti che nella PA sono coinvolti nella gestione delle fasi del peocedimento amministrativo.

Uno schema tabellare semplice come quello proposto, ha visto al Comune di Palermo, la partecipazione di tutte le UO responsabili di procedimenti amministrativi e non è stato incontrato alcun problema di rilievo nella compilazione delle schede.


## Esempio di schema di metadati per identificare un procedimento amministrativo di un ente comunale
Quello che segue è un esempio di schema, abbastanza semplice ma allo stesso tempo esaustivo per la comprensione del procedimento ai fini della digitalizzazione.

| ==ID metadato== | ==**METADATI per descrivere le informazioni relative al procedimento amministrativo**== | 
|---------|----------------|
| 1 | Nome del procedimento amministrativo |
| 2 | Descrizione del procedimento amministrativo |
| 3 | Nome dell'Area comunale competente |
| 4 | Nome Settore comunale competente e del Servizio. (Se non è previsto il Settore scrivere il nome del Servizio di appartenenza) |
| 5 | Nome dell'Unità Organizzativa responsabile dell'istruttoria |
| 6 | Responsabile del procedimento (nome, cognome) |
| 7 | Email del responsabile del procedimento |
| 8 | Indirizzo di posta dell'Ufficio al quale rivolgersi per ricevere informazioni sul procedimento su appuntamento o secondo giorni di ricevimento |
| 9 | Email alla quale rivolgersi per informazioni sul procedimento (in caso di più email usare il carattere trattino - di separazione)
| 10 | Telefono/i al/i quale/i rivolgersi per informazioni sul procedimento (in caso di più telefoni usare il carattere trattino - di separazione) |
| 11 | Ufficio/Servizio/Settore competente all'adozione del provvedimento finale (se previsto ed è diverso dall'Ufficio responsabile dell'avvio dell'istruttoria). Se non è previsto scrivere: "Lo stesso ufficio che avvia l'istruttoria" | 
| 12 | Modalità di accesso al procedimento. (Esempio: richiesta via email o tramite applicativo informatico alla U.O. competente) |
| 13 | Termine di conclusione del procedimento in giorni (previsto per legge) |
| 14 | Il provvedimento può essere sostituito da dichiarazione dell'interessato, ovvero il procedimento può concludersi con il silenzio assenso dell'amministrazione? (si,no) |
| 15 | Link di accesso al servizio on line per l'avvio del procedimento (se ad oggi è previsto il relativo servizio online) |
| 16 | Modalità per l'effettuazione dei pagamenti se sono previsti pagamenti (Esempio: iban, c/c postale, PagoPA, bancomat,..). Se non è previsto pagamento scrivere: "Non è previsto pagamento" |
| 17 | Se è previsto pagamento indicare estremi iban, c/c postale, PagoPA, bancomat, ... |
| 18 | Potere sostitutivo da attivare in caso di inerzia. Titolare del potere sostitutivo in caso di inerzia è (scrivere nome e cognome o funzione) |
| 19 | Il procedimento amministrativo è correlato ad un servizio pubblico da erogare al cittadino/azienda (si,no) |
| 20 | Se il procedimento amministrativo è correlato ad un servizio pubblico da erogare al cittadino/azienda, scrivere il nome del servizio da erogare all'utenza. In caso negativo scrivere: "non è correlato ad un servizio pubblico da erogare" |
| 21 | Se esiste modulistica da utilizzare per la gestione del procedimento amministrativo, digitare il link della pagina web del sito istituzionale dove è scaricabile. Se la modulistica è solo su Intracom scrivere: "Intracom" |
| 22 | Elenco delle norme che regolamentano la gestione del procedimento amministrativo (separate dal carattere trattino -). Ad es.: Decreto legislativo 33/2013 - Decreto legislativo 50/2016 - e così via |
| 23 | Scrivere il nome dell'applicativo gestionale (se esiste) per gestire le fasi del processo relativo al procedimento in esame. Se non esiste scrivi "non esiste applicativo" |
| 24 | E' prevista la firma digitale del dirigente in qualche atto da produrre (es. determinazione, nota) per gestire il procedimento amministrativo? (si,no) |
| 25 | E'  prevista la firma digitale della P.O. (o RUP o l'altra figura competente) che ha avuto l'apposita delega? (si,no) |
| 26 | E'  prevista l'assegnazione all'interno della U.O. a diversi operatori? (si,no). Se si nel campo note descrivere le informazioni |
| 27 | E'  prevista la compilazione del provvedimento su una modulistica standardizzata, che possa essere successivamente controllata e firmata dal/dai responsabili incaricati? (si,no) |
| 28 | E' prevista la consultazione di banche dati per la gestione del procedimento? (si,no) |
| 29 | Se è prevista la consultazione di banche dati dell'amministrazione (o di altri enti pubblici) per la gestione del procedimento, descrivere il nome della banca dati. Se sono più banche dati da consultare usare il trattino - di separazione |
| 30 | Il procedimento può essere gestito anche in modalità di lavoro agile, perché, ad esempio, non è necessario consultare atti cartacei che si trovano in ufficio o per altri motivi che non rendono necessaria la presenza quotidiana in ufficio? (si,no) |

!!! Nota "Importante"
    Più sarà accurata la compilazione e la tipologia di metadati, più sarà facile costruire una piattaforma informatica di gestione dei vari procedimenti amministrativi che, sebbene diversi tra di loro, avranno comunque e sempre un metodo di gestione univoco che non disorienterà il cittadino, ma anzi lo rassicurerà perché nella presentazione di un’istanza, ad esempio, costui si troverà sempre davanti alla stessa struttura del procedimento che ha seguito per ottenere l’erogazione di un altro servizio.

Metadatando dettagliatamente ogni singolo procedimento amministrativo è possibile costruire un catalogo da condividere all’interno dell’ente, e pubblicare anche sul sito web istituzionale per facilitare l’accesso dei cittadini ai servizi pubblici e la relativa comprensione. 

## Metadatazione necessaria per la costruzione e implementazione del software gestionale 
Il catalogo con l'elenco dei procedimenti e le schede dettagliate contenente la metadatazione, possono costituire un allegato tecnico al capitolato speciale di appalto che una pubblica amministrazione può (e deve) rendere alle Aziende interessate alla fornitura di programmi applicativi in grado di gestire in modalità esclusivamente digitale la gestione dei procedimenti amministrativi dell'ente richiedente. 

In questo caso le aziende avranno del materiale tecnico preziosissimo per comprendere la metadatazione dei procedimenti (con le proprietà specifiche) utile a realizzare l'interoperabilità tra applicativi informatici diversi che necesitano di essere in diretta relazione per la gestione del procedimento stesso (es: accesso ad altre banche dati dello stesso ente per verifiche - interazione con altri appplicativi informatici necessaria al processamento di attività necessarie alla gestione del procedimento).

Un requisito fondamentale del software individuato per gestire i procedimenti in modalità digitale è rappresentato dal fatto che l'utilizzatore (ente pubblico), nella figura del Responsable del sistema di gestione documentale, deve poter arricchire la sezione dei metadati dei procedimenti, in autonomia dall'Azienda fornitrice.  In pratica il software, attraverso l'utilizzo di policy prestabilite, deve consentire di aumentare la classe dei metadati nel tempo, ciò in considerazione del fatto che nuove norme possono prevedere cambiamenti nella gestione di procedimenti - e servizi pubblici correlati - già consolidati nel tempo. Le pubbliche amministrazioni devono poter gestire in autonomia l'implementazione delle classi di metadati all'interno degli applicativi gestionali in uso. La tecnologia disponibile al 2021 consente ai software di poter intervenire nell'implementazione delle classi dei metadati degli applicativi gestionali, senza fare ricorso alla software house che ha sviluppato il programma.

