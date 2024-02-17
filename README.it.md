# README.md
- [Deutsch](README.de.md)
- [English](README.md)
- [Spanish](README.es.md)
- [French](README.fr.md)
- [Italian](README.it.md)
- [언어](README.ko.md)
- [日本語](README.ja.md)
- [简体中文](README.zh_cn.md)
- [繁体中文](README.zh_tw.md)

# 🎠 Motrix - Cliente chatGPT nativo per macOS

Scarica [l'ultima versione da macOS appstore](https://apps.apple.com/us/app/id6447776319)

## Caratteristiche principali
- Supporto per il proxy LLM locale litellm
- È necessaria una chiave API GPT per eseguire l'app Motrix
- Collega l'API chatGPT o il servizio proxy GPT (host personalizzato)
- Supporto per le chat di gruppo
- Riprova automatica
- Selettore rapido dei modelli di prompt
- Le chat possono essere organizzate come un albero (trascinamento e rilascio)
- Interruttore rapido globale per tornare alla chat
- Nodi di chat personalizzati visualizzati nella barra dei menu
- Renderizzazione delle conversazioni in markdown
- Salva le chat e le query preferite per riferimento successivo
- Icona visibile dell'IA che indica quanti messaggi contestuali può leggere l'IA
- Ricerca delle conversazioni per parole chiave
- Incorpora 6 temi con supporto per la modalità chiara/oscura

V1.9.2  
---  
- Aggiunta la funzionalità di backup di tutti i dati e ripristino nelle preferenze
- Aggiunta la funzionalità di duplicare il messaggio in un altro nodo di chat
- Aggiunta la modalità chat memo per salvare solo qualcosa e non inviarla al server AI
- Aggiunta la funzione di invio di un messaggio temporaneo come messaggio di chat di gruppo avviando una nuova chat con il formato '@nodo1;nodo2;nodo5 newline traduci testo'
- Aggiunta la creazione rapida di una chat di gruppo dai nodi sinistri dell'albero tramite menu di scelta rapida
- Aggiunta la funzionalità di bloccare il contesto alla riga, consentendo alla conversazione di essere sempre inviata dalla riga di contesto bloccata
- Aggiunta la doppia pressione per aprire una finestra di chat pop-up per la modifica della modalità timer
- Aggiunta l'opzione di thread paralleli per le chat di gruppo nella barra laterale, utile per ridurre le richieste parallele all'API a causa di problemi di risposta del server
- Aggiunta l'opzione di modifica del timer direttamente all'interno della finestra di chat pop-up
- Aggiunta scorciatoia per aprire qualsiasi nodo di chat con finestra fluttuante
- Risolto il problema dello stile del tema della finestra rapida non corrispondente
- Risolto il problema della modalità stream che non può leggere i dati dal progetto open source litellm in modalità proxy
- [V1.9.2 Uni](https://download.marksdo.com/apps/Motrix/V1.9.2/Motrix.dmg)

V1.9.1  
---  
- Aggiunta la doppia pressione per aprire una finestra di chat pop-up per la modifica della modalità timer
- Aggiunta l'opzione di modifica del timer direttamente all'interno della finestra di chat pop-up
- Aggiunta scorciatoia per aprire qualsiasi nodo di chat con finestra fluttuante
- Risolto il problema dello stile del tema della finestra rapida non corrispondente
- [V1.9.1 Uni](https://download.marksdo.com/apps/Motrix/V1.9.1/Motrix.zip)

V1.9.0  
---  
- Aggiunto il supporto per llm/gpt proxy deploy locale (litellm) http://127.0.0.1:8000 come host per supportare la maggior parte dei server di chat llm/gpt open source
- Aggiunta la funzione di clonazione per il nodo dell'albero di chat nel menu di contesto destro
- Aggiunta la funzione di impostazione batch dei parametri del modello dei nodi (selezionare più nodi dall'albero e utilizzare il menu di contesto -> impostazione batch)
- Risolto il problema della descrizione delle istruzioni di sistema che non può essere ridotta
- [73.6 MB](https://download.marksdo.com/apps/Motrix/V1.9.0/Motrix.zip)
![image](/images/V190.webp)

V1.8.9  
---  
- Aggiunta scorciatoia per passare al nodo di chat successivo (da utilizzare in combinazione con altre app di scorciatoie di sistema)
- Aggiunta l'istantanea nel menu di contesto destro del contenuto della chat.
- La finestra popup del risultato della query AI pianificato può salvare l'immagine del risultato completo negli appunti
- La barra degli strumenti delle righe del contenuto della chat è stata rimossa. Utilizzare il menu di contesto destro come sostituzione
- Risolto un problema di layout nell'importazione di contenuti della chat in immagini
- Risolto il blocco durante l'avvio in macOS 11
- Scarica l'edizione universale [73.5 MB](https://download.marksdo.com/apps/Motrix/V1.8.9/Motrix.zip)


V1.8.7  
---   
- Aggiunta la configurazione della chiave del modello. È possibile configurare la connessione della chiave del modello quando viene rilasciato un nuovo modello.
- Aggiunta la funzionalità di eliminazione batch delle righe della chat selezionate
- Aggiunta l'opzione per disabilitare lo scorrimento automatico nella lista della chat in fondo
- Aggiunta la configurazione dell'aspetto per cambiare la dimensione del carattere dell'interfaccia utente
- Aggiunta la scorciatoia ⌘+(+-) per cambiare rapidamente la dimensione del contenuto della chat
- Aggiunta l'opzione di altezza fissa per la casella di input nella barra delle opzioni
- Il formato della barra di navigazione sinistra può essere ancora più piccolo
- Il nuovo nodo di chat utilizzerà i parametri dell'IA dell'ultimo nodo di chat selezionato
- Risolto il problema della visualizzazione della finestra popup della domanda personalizzata dell'IA quando il sistema è in standby
- Risolto il problema della disponibilità della renderizzazione markdown nelle impostazioni
- Risolto il problema dell'intento dell'app motrix delle scorciatoie

V1.8.5  
---  
- Aggiunto il supporto per il nuovo modello GPT3.5 & GPT4 16K
- Aggiunto il supporto per la larghezza predefinita della finestra di popup del timer (usata per consigli giornalieri dell'IA a lunga risposta)
- Risolto il problema di visualizzazione della modalità stream in alcuni casi
- Risolti i bug della finestra popup del timer
- Risolto il problema dello stato bloccato del nodo nuovo in macOS 11.0

V1.8.4  
---  
- Aggiunta la nuova pagina guida alla chat. È possibile selezionare un ruolo AI predefinito per iniziare la chat.
- Correzione dei bug e miglioramenti delle prestazioni.

V1.8.3  
---  
- Aggiunta la visualizzazione a griglia nel selettore dei nodi di chat di Motrix Quick service
- Aggiunta l'opzione per abilitare/disabilitare il messaggio non letto nel nodo dell'albero sinistro
- Aggiunta l'opzione per disabilitare l'autoscroll della digitazione
- Risolto il problema del clic sull'icona dell'app nella barra delle applicazioni per tornare all'app
- Risolti alcuni problemi di traduzione di lingue diverse
- Risolto il problema del crash della modalità di sintesi vocale

V1.8.2  
---  
- Aggiunto il supporto per l'app Shortcuts (macOS 13.0+). Interroga la risposta dell'IA e incorporala nel tuo flusso di lavoro automatico personale. È possibile visualizzare come utilizzarla nelle preferenze dell'app
- Il servizio rapido di Motrix ora può selezionare una finestra piccola per mostrare il contenuto della risposta dell'IA
- Risolto il problema del servizio Motrix che non può essere visualizzato nel browser o in altre app di testo

V1.8.1  
---  
- Risolto il problema della ricerca globale che a volte non elenca i dati
- Risolto il problema delle funzionalità limitate dei piani Pro
- Risolto il problema dell'altezza del corpo del messaggio che non si adatta

V1.8  
---  
- Aggiunto il timer giornaliero per interrogare automaticamente il nodo di chat AI per consigli ispirazionali o motivazionali, oppure è possibile utilizzarlo per far apparire automaticamente giornalmente consigli di codifica o esercizi linguistici (doppio tap sulla riga della domanda dell'utente)
- Il timer giornaliero può essere attivato direttamente dal menu contestuale della barra dei menu di Motrix
- Aggiunta la scorciatoia globale CMD+SHIFT+F per passare rapidamente alla ricerca globale preferiti
- Risolti i problemi di scorrimento
- Risolti i problemi dell'inserimento del testo nel selettore dei modelli rapidi
- Miglioramenti delle prestazioni in modalità streaming

Funzionalità di V1.7  
---  
- Modalità finestra fluttuante: è possibile creare una finestra di chat in un nuovo pannello galleggiante
- Supporto per il trascinamento del testo in qualsiasi area della finestra di chat per inviare un messaggio
- Aggiunta dell'interruttore di visualizzazione del layout nella barra degli strumenti principale e supporto per il ripristino personalizzato dell'icona del layout
- Aggiunta del servizio rapido di sistema Motrix, quando si seleziona del testo in un'altra app di editing, selezionando Motrix Quick verrà visualizzato il selettore dei nodi di chat e il testo selezionato verrà inviato al sistema di chat
- Aggiunta del menu di contesto del mouse destro sul messaggio per copiare rapidamente, contrassegnare come preferito, modificare
- Risolto il problema di stabilità dello scrollview
- Risolto il bug della nuova riga in markdown

Funzionalità di V1.5~1.6  
---  
- Aggiunto il supporto per la modalità di streaming per ottenere i token di risposta uno per uno
- Aggiunta la possibilità di modificare il messaggio incorporato facendo doppio clic sulla riga del messaggio
- Aggiunta della configurazione dell'aspetto nelle impostazioni per personalizzazione UI
- Aggiunti 3 nuovi temi con supporto per la modalità chiara/oscura
- Aggiunta della funzionalità di salvataggio e ripristino del layout (inclusi tema corrente, lightDark, dimensione del carattere, opzioni di auto...)
- Aggiunta dell'animazione di scrittura
- Aggiunto il servizio di testo del sistema operativo, chiama l'API di Motrix in tutti gli altri editor di testo di sistema
- Testato e verificato che Mortix è compatibile con macOS 11.0, 12.0
- Bug fix e miglioramenti delle prestazioni

Funzionalità di V1.4  
---  
- Supporto per la ricerca in tutte le conversazioni
- Supporto per la modalità selezione batch. Seleziona i messaggi di chat da condividere o esportare
- Supporto per mostrare i preferiti in tutte le conversazioni (All'interno del menu di ricerca)
- Personalizza il numero massimo di token per ogni nodo (È necessario conoscere il funzionamento di questi come il messaggio di contesto, può influenzare quanti contesti l'IA può comprendere)
- Modalità di inserimento predefinita del nodo personalizzabile
- Bug fix e miglioramenti delle prestazioni

Funzionalità di V1.1~V1.3  
---  
- Modalità di sintesi vocale: è possibile utilizzare il microfono per registrare il testo. L'app lo tradurrà in testo e manterrà la traccia audio.
- Riproduzione del contenuto vocale: fare clic singolo sull'avatar dell'utente o del bot.
- Modalità di chat di gruppo: è possibile impostare un nodo genitore e aggiungere alcuni nodi figlio (è necessario utilizzare istruzioni di sistema per inizializzare il ruolo AI e il suo ruolo), quindi inviare un messaggio nell'elemento padre. Tutti i figli risponderanno nella conversazione corrente.
- Copia automatica negli appunti: copia automaticamente il contenuto negli appunti quando viene ricevuta una risposta
- Lettura automatica: leggi automaticamente la risposta
- Maschera automatica: maschera automaticamente la risposta dell'IA. Questo è principalmente per gli utenti che vogliono esercitarsi nella dettatura di varie lingue.

Funzionalità di V1.0  
---  
- Incorpora l'editor markdown
- Gruppo di chat libero con stile ad albero (supporto per il trascinamento e rilascio)
- 3 temi con supporto per colori chiari/oscuri
- Rendering del blocco del codice
- Salva qualsiasi conversazione per la revisione o la query successiva
- La conversazione viene salvata in locale, quindi può essere visualizzata offline
- Modello di prompt personalizzato e popup rapido con "/"

Screenshot

![screenshot](images/screenshot.webp)

![screenshot1](images/screenshot1.webp)

![screenshot2](images/screenshot2.webp)

![screenshot3](images/screenshot3.webp)

![screenshot4](images/screenshot4.webp)

![screenshot5](images/screenshot5.webp)

![screenshot6](images/screenshot6.webp)

![screenshot7](images/screenshot7.webp)

![screenshot8](images/screenshot8.webp)

![screenshot9](images/screenshot9.webp)

![screenshot10](images/screenshot10.webp)

![screenshot11](images/screenshot11.webp)