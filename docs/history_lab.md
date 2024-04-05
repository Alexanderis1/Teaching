## Analisi delle Battaglie Antiche Attraverso la Tecnologia

### Introduzione
Il confine tra il passato e il presente si assottiglia quando applichiamo gli strumenti della tecnologia moderna all'esplorazione della storia decifrando gli eventi delle battaglie antiche con l'aiuto della programmazione e del machine learning.

Inizieremo esplorando le battaglie selezionate per il nostro "training set" (approfondiremo il significato di questa parola più in là), che includono:

- **Battaglia di Alalia (540 a.C.)**
- **Battaglia di Sardi (547 a.C.)**
- **Battaglia di Thymbra (547 a.C.)**
- **Battaglia di Pteria (547 a.C.)**

E la battaglia avvolta nel mistero da analizzare:

- **Battaglia dell'Eclissi (585 a.C.)**

Dovrete raccogliere dati storici accurati, utilizzando fonti come:

- Database accademici: JSTOR, Project MUSE
- Google Scholar per articoli e pubblicazioni
- "The Cambridge Ancient History" e "The Oxford Classical Dictionary"
- Perseus Digital Library e Internet Ancient History Sourcebook
- Livius.org per articoli di storia antica

### Come utilizzare i Dati

Una volta ottenuti i dati di nostro interesse possiamo utilizzarli per far imparare ad un nostro "robottino" vitruale come determinati fattori hanno prodotto determinati risultati in un contesto specifico. Questa tecnologia è definita Machine Learning e [Questo](https://www.youtube.com/watch?v=R9OHn5ZF4Uo&ab_channel=CGPGrey) breve video è una spiegazione semplice ed intuitiva.

Per creare il nostro robottino utilizzeremo il noto linguaggio di programmazione *Python*, non è necessario conoscere a fondo fondamenti di programmazione, perchè grazie a poche piccole istruzioni è possibile ottenere grandi risultati grazie a dati organizzati e precisi.

Senza la necessità di scaricare software esterni è possibile programmare in Python e salvare il proprio codice su Google Drive grazie a [Google Colab](https://colab.google/) con cui vi consiglio di prendere familiarità giocandoci e vedendo [Questo](https://www.youtube.com/watch?v=mFzbw-5cUKg&ab_channel=Informathicamente) breve video.

Parlando di codice, professionalmente parlando, quello che noi stiamo cercando di risolvere è un problema di Regressione Lineare basata su quello che viene chiamato "Supervised Learning", ovvero ci occupiamo noi di insegnare alla macchina i concetti che gli servono dandogli solo i dati che ci interessano e utilizzeremo la Libreria di Python Scikit, e Tensorflow che contengono al loro interno codice preconfezionato per creare e far allenare le nostre macchine, per chi vuole approfondire il nostro problema consiglio [Questa](https://scikit-learn.org/stable/modules/linear_model.html) Documentazione (un po' avanzata..).

### Introduzione alla Regressione Lineare su Colab

[Questo](https://colab.research.google.com/github/google/eng-edu/blob/main/ml/cc/exercises/linear_regression_with_synthetic_data.ipynb) è un "notebook" già scritto dai sviluppatori di colab e tensorflow per introdurre gli studenti alla regressione lineare! Vi consiglio una lettura approfondita passo passo, che vi spiegerà le grandi potenzialità del modello.


### Scrivere il codice

Come esempio vi affido un problema simile al nostro:

Date una serie di giornate con determinate condizioni climatiche, il nostro amico immaginario Paolo ha deciso di andare o non andare a giocare a tennis.

Ad esempio:
- Lunedì ha piovuto, facevano 12 gradi e c'era nebbia. Paolo non è andato a giocare
- Martedi ha piovuto, facevano 18 gradi e non c'era nebbia. Paolo è andato a giocare
- Mercoledì c'era il sole, facevano 23 gradi e non c'era nebbia. Paolo è andato a giocare
- Giovedì era nuvolo, facevano 20 gradi e c'era nebbia. Paolo non è andato a giocare
- Venerdì c'era il sole, facevano 15 gradi e c'era nebbia. Paolo è andato a giocare
- Sabato era nuvolo, facevano 19 gradi e non c'era nebbia. Paolo è andato a giocare
- Domenica era nuvolo, facevano 10 gradi e non c'era nebbia. Paolo non è andato a giocare

Sapendo che stamani è ipoteticamente il lunedì dopo la domenica in questione, sappiamo che è nuvolo, fanno 28 gradi e c'è nebbia, paolo giocherà?

[Questo](https://colab.research.google.com/drive/18_pb0G0rq7ug_LvDs7_WUm95gAOq1B8c?usp=sharing) Notebook di colab fatto da me in precedenza vi illustrerà il problema di paolo e la sua risoluzione.

### Esposizione dei dati ottenuti

Una volta ottenute le nostre previsioni sulla battaglia dell'eclissi seguendo il metodo del problema di Paolo dobbiamo interpretare i dati per poter ricostruire la storia, anche lasciandoci guidare dalla nostra immaginazione, unendo i dati attendibili e quelli predetti (specificato quali sono quelli predetti) per immaginare come la battaglia si è svolta veramente.

Potete utilizzare qualunque software di presentazione per preparare una lezione su quanto ricostruito per la notte del 19 Aprile.
