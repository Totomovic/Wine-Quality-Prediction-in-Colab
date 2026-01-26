    Obiettivo del progetto
L’obiettivo del progetto è analizzare un dataset sulla qualità del vino rosso e sviluppare un modello di machine learning in grado di classificare un vino come di buona o bassa qualità sulla base delle sue caratteristiche chimiche.

    Dataset utilizzato
Il dataset contiene diverse variabili chimico-fisiche del vino, tra cui:
-  acidità fissa e volatile
-  acido citrico
-  contenuto di zuccheri residui
-  pH 
-  gradazione alcolica
La variabile target è quality, che rappresenta la qualità del vino valutata su una scala discreta.

    Analisi esplorativa dei dati (EDA)
È stata inizialmente condotta un’analisi esplorativa per comprendere la struttura e il comportamento dei dati:
-  analisi statistica descrittiva delle variabili,
-  studio della distribuzione della qualità del vino,
-  analisi della relazione tra alcune variabili chimiche e la qualità,
-  costruzione di una matrice di correlazione per individuare le variabili più influenti.
Questa fase ha permesso di evidenziare le relazioni tra le caratteristiche del vino e la qualità finale.

    Pre-processing dei dati
Per semplificare il problema di classificazione:
-  la variabile quality è stata trasformata in una variabile binaria,
-  i vini con qualità ≥ 7 sono stati classificati come buona qualità,
-  i vini con qualità < 7 come bassa qualità.
Successivamente il dataset è stato suddiviso in:
-  training set (80%)
-  test set (20%)

    Modello di Machine Learning
È stato utilizzato un Random Forest Classifier, un algoritmo basato su un insieme di alberi decisionali, particolarmente efficace nel gestire dataset con molte variabili.
Il modello è stato addestrato sul training set e valutato sul test set utilizzando come metrica l’accuracy.

    Risultati
Il modello ha ottenuto una buona accuratezza nella classificazione dei vini sul test set, dimostrando la capacità di distinguere tra vini di buona e bassa qualità sulla base delle caratteristiche chimiche.

    Applicazione del modello
Infine, il modello è stato utilizzato per effettuare una predizione su un nuovo campione di vino:
-  inserendo manualmente i valori delle variabili chimiche,
-  ottenendo come output la classificazione della qualità del vino.
Questo dimostra una possibile applicazione pratica del modello in ambito enologico.

    Conclusioni
Il progetto mostra come tecniche di data analysis e machine learning possano supportare la valutazione della qualità del vino, offrendo uno strumento predittivo basato su dati oggettivi.
