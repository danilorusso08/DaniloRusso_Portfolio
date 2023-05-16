# DaniloRusso_Portfolio

## [Project 1: Analisi Acqua Potabile](https://github.com/danilorusso08/Analisi_Acqua_Potabile/blob/main/DaniloRusso_Water.ipynb)
In questo progetto, l'obbiettivo sarà quello di costruire un modello predittivo per determinare la potabilità dell'acqua in base alle sue caratteristiche chimiche.<br><br>
Nell'analisi dei dati, è risultato uno sbilanciamento della classe target, per cui è stato adottato lo *stratified sampling* per mantenere la distribuzione dei dati, e una bassa correlazione tra le features e la classe target.<br>
Sono stati testati diversi modelli di classificazione per l'individuazione del migliore utilizzando due approcci, nel primo caso abbiamo utilizzato tutte le features a disposizione (Modello1), mentre nel secondo caso abbiamo utilizzato le quattro migliori features individuate tramite il chi quadro test (Modello2), dopo aver ottimizzato gli iperparametri dei modelli tramite *GridSearchCV*, il *GradientBoostingClassifier* che utilizza quattro feature è emerso come il migliore.

## [Project 2: Wine](https://github.com/danilorusso08/Wine)
Nel progetto, abbiamo costruito un modello di classificazione per prevedere il produttore di vino tra tre produttori diversi, basandoci sulle caratteristiche chimiche del vino.<br><br>
Prima di costruire il modello, abbiamo effettuato un'analisi dei dati per comprendere le caratteristiche del dataset. In particolare, abbiamo visualizzato le distribuzioni delle feature e le correlazioni tra di esse.<br>
Il modello di classificazione scelto è il RandomForestClassifier e per ottimizzarne le prestazioni, abbiamo eseguito il tuning degli iperparametri tramite la tecnica di GridSearchCV.<br><br>

Grazie all'implementazione di questo modello di classificazione, siamo stati in grado di ottenere previsioni accurate per ciascuna variante nel dataset.

## [Project 3: World Happiness Report - The Human Freedom Index](https://github.com/danilorusso08/World_Happiness__Freedom/blob/main/DaniloRussoDataVis.ipynb)

## [Project 4: File Organizer](https://github.com/danilorusso08/File_Organizer)

