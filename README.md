#Progetto di analisi testuale
«Scoprendo il Paese delle Meraviglie con spaCy: analisi de Le avventure di Alice nel Paese delle Meraviglie»

Testo da analizzare
Tutti gli studenti lavoreranno sullo stesso libro:
«Le avventure di Alice nel Paese delle Meraviglie» di Lewis Carroll
(disponibile gratuitamente su Project Gutenberg)

Obiettivi
Imparare a usare strumenti NLP (spaCy) per elaborare testi reali
Scrivere codice per scoprire pattern, temi e personaggi principali
Confrontare i risultati tra studenti, visto che il testo è lo stesso

Struttura del progetto (con difficoltà crescente)

Livello 1 – Analisi di base (obbligatoria per tutti)
Usare spaCy per processare il testo.
Compiti:
Caricare e ripulire il testo (rimuovere header/footer di Project Gutenberg)
Processare il testo con spaCy 
Calcolare:
Numero totale di token (escludendo punteggiatura)
Numero di lemmi unici (escludendo stopwords)
Top 10 parole più frequenti
Visualizzare le top 10 parole con un grafico a barre

Livello 2 – Analisi intermedia (scegliere almeno due)
Analisi:
Riconoscimento di entità nominate (NER):
Estrarre le entità PERSON e contare le più frequenti
Analisi dei capitoli:
Dividere il testo in capitoli e analizzare lunghezza media o numero di token
Analisi grammaticale:
Contare frequenze dei principali POS tag (sostantivi, verbi, aggettivi)
Analisi degli aggettivi associati ai personaggi (opzionale):
Per i personaggi principali più citati, trovare gli aggettivi che hanno una relazione di dipendenza diretta (es. amod) con il nome del personaggio e visualizzare gli aggettivi più frequenti

Livello 3 – Analisi avanzata (facoltativa, per chi vuole approfondire)
Idee:
Analisi del sentiment basata su un lessico:
Utilizzare un lessico italiano di parole positive e negative (ad esempio da questo repository)
Per ogni capitolo: contare quante frasi contengono almeno una parola positiva e quante almeno una parola negativa
Visualizzare l’andamento del sentiment nei vari capitoli
Network dei personaggi:
Creare una rete che mostra quali personaggi appaiono insieme nelle stesse frasi
Keyword in context (KWIC):
Creare una funzione per mostrare il contesto in cui compaiono parole chiave definite da un utente

Domande a cui tutti dovrebbero rispondere
Quali sono le parole più usate da Carroll (dopo aver rimosso stopwords)?
Quali personaggi sono menzionati più spesso?
Qual è il capitolo più lungo?
(Se si fa l’analisi del sentiment): quale capitolo contiene più frasi positive o negative?

Cosa consegnare
Codice con commenti e grafici
Breve relazione (1–2 pagine):
Cosa avete analizzato
Metodo (come avete usato spaCy)
Principali risultati con figure
Cosa avete imparato


