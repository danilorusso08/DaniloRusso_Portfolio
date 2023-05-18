# Data Science Portfolio - Danilo Russo
Questo Portfolio contiene tutti i miei progetti di Data Science e Data Analysis, svolti durante il master in Data Science di Start2Impact più altri progetti personali svolti con lo scopo di migliorare le mie capacità e conoscenze.

- **Email**: [danilo08russo@gmail.com](danilo08russo@gmail.com)
- **LinkedIn**: [linkedin.com/danilo-russo95](https://www.linkedin.com/in/danilo-russo95/)

## Progetti
<img align="left" width="250" height="150" src="Images/acquapotabile.jpg">**[Project 1: Analisi Acqua Potabile]**(https://github.com/danilorusso08/Analisi_Acqua_Potabile/blob/main/DaniloRusso_Water.ipynb)
In questo progetto, l'obiettivo sarà quello di costruire un modello predittivo per determinare la potabilità dell'acqua in base alle sue caratteristiche chimiche.<br><br>
Nell'analisi dei dati, è risultato uno sbilanciamento della classe target, per cui è stato adottato lo *stratified sampling* per mantenere la distribuzione dei dati, e una bassa correlazione tra le features e la classe target.<br>
Sono stati testati diversi modelli di classificazione per l'individuazione del migliore utilizzando due approcci, nel primo caso abbiamo utilizzato tutte le features a disposizione (Modello1), mentre nel secondo caso abbiamo utilizzato le quattro migliori features individuate tramite il chi quadro test (Modello2), dopo aver ottimizzato gli iperparametri dei modelli tramite *GridSearchCV*, il *GradientBoostingClassifier* che utilizza quattro feature è emerso come il migliore.<br>

## [Project 2: Wine](https://github.com/danilorusso08/Wine/blob/main/DaniloRussoMLP.ipynb)
Nel progetto, abbiamo costruito un modello di classificazione per prevedere il produttore di vino tra tre produttori diversi, basandoci sulle caratteristiche chimiche del vino.<br><br>
Prima di costruire il modello, abbiamo effettuato un'analisi dei dati per comprendere le caratteristiche del dataset. In particolare, abbiamo visualizzato le distribuzioni delle feature e le correlazioni tra di esse.<br>
Il modello di classificazione scelto è il RandomForestClassifier e per ottimizzarne le prestazioni, abbiamo eseguito il tuning degli iperparametri tramite la tecnica di GridSearchCV.<br><br>

Grazie all'implementazione di questo modello di classificazione, siamo stati in grado di ottenere previsioni accurate per ciascuna variante nel dataset.<br>

## [Project 3: World Happiness Report - The Human Freedom Index](https://github.com/danilorusso08/World_Happiness__Freedom/blob/main/DaniloRussoDataVis.ipynb)
In questo progetto, ci concentreremo sull'analisi dei fattori principali che influenzano il livello di felicità in uno stato, utilizzando il World Happiness Report. Inoltre, utilizzeremo i dati forniti dal Human Freedom Index per valutare il grado di libertà esistente nel mondo.<br>
Per questo, combineremo e manipoleremo i diversi dataset, al fine di identificare le correlazioni tra felicità e libertà.<br><br>
Per questo progetto, faremo uso di diverse librerie, tra cui pandas, matplotlib, seaborn e plotly.<br>

## [Project 4: File Organizer](https://github.com/danilorusso08/File_Organizer)
Script Python che iteri in ordine alfabetico sui file della cartella files e, a seconda del tipo (audio, documento, immagine), li sposti nella relativa sottocartella. Se la sottocartella non esiste, lo script dovrà crearla automaticamente.
