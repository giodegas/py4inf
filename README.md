Python for Informatics: Esplorare le Informazioni
=============================================

Questo è il codice sorgente di "Python for Informatics: Exploring Information"
il sito di questo libro è http://www.pythonlearn.com/

File LaTeX
-----------

Il file sorgente del libro è *book.tex* - questo file  include i file 
per capitoli *00-cover.tex* fino a  *AD-copyright.tex*

Flusso di lavoro
-----------

Quando hai una adeguata installazione di LaTeX e HeVeA il flusso di
lavoro è semplice.

Per produrre la versione PDF del libro scrivi in console:

    bash book.sh

Questo produce il risultato su *book.pdf* e se hai un Mac o Linux, cerca
anche di aprire il visualizzatore PDF del tuo sistema.

Per produrre la versione HTML del libro scrivi in console:

    bash html.sh

Questo produce i file nella cartella *html* . In questa cartella trovi
il libro, i capitoli in HTML e le immagini per il libro.

Per ottenere i file nei formati EPUB e MOBI utilizzo il software
Calibre. I passi da intraprendere in Calibre sono disponibili qui:

* [Importare HTML in Calibre](CALIBRE.md)

Ho anche un server che rigenera l'ultima versione dal repository a questo URL:

* http://do1.dr-chuck.com/py4inf/IT-it/ (* non ancora attivato - 6 Gennaio 2016*)

Non ho ancora i file che mi permettono di fare il check in automatico
perchè risulta alquanto macchinoso. Se vuoi mettere su il tuo proprio
server per la rigenerazione - il check in lo faccio io.

Installazione del software - Macintosh
--------------------------------------

Eseguire lo script per produrre il PDF sul Mac è molto semplice e conveniente.
Semplicemente installa questo pacchetto:

* https://tug.org/mactex/

Assicurati di installare anche gli extras. Se hai un Mac recente **non
puoi** scaricare una versione binaria di *hevea* che ti funziona in
quanto è compilato come binario PowerPC.

Se vuoi anche generare la versione HTML, hai bisogno di una variante di Linux.

Installazione del Software - Ubuntu
-----------------------------------

Questo sono i passaggi che ho usato in Ubuntu:

    sudo apt-get install texlive-latex-base
    sudo apt-get install texlive-latex-recommended
    sudo apt-get install texlive-fonts-recommended 
    sudo apt-get install texlive-latex-extra
    sudo apt-get install hevea
    sudo apt-get install imagemagick
    sudo apt-get install texlive-fonts-extra

    sudo apt-get install texlive-lang-spanish texlive-doc-es 

Potresti metterli tutti in un unico e lungo comando apt-get, ma voglio
vedere se fuziona :)

Quando questo è fatto, gli script *book.sh* e *html.sh* dovrebbero
funzionare senza problemi. Per mia salute mentale utilizzo Parallels con
una immagine Ubuntu per generare l'HTML. Era più semplice che mantenere
un MacBook di 4 anni fa che faccia girare Rosetta.

Tradurre Questo Libro
---------------------

Questo libro è disponibile con una licenza Creative Commons
ttribution-NonCommercial-ShareAlike 3.0 Unported. Quindi a meno che tu
non intendi ottenere profitto dalla traduzione, non è necessario avere
nessuna autorizzazione per tradurlo e pubblicarlo. Se vuoi vendere il
risultato finale del libro tradotto commercialmente, per cortesia leggi
l'Appendice sul Copyright e contattami.

Le traduzione in lavorazione sono le seguenti:

* Korean - [Libro Formattato](http://do1.dr-chuck.com/py4inf/KO-ko/book.pdf) | [Sorgenti del Libro](https://github.com/statkclee/py4inf-kor) (Lead: Victor KC Lee)
* Italian - [Google Doc](https://docs.google.com/document/d/1ZyxzXGe2qGgsc-Dbqs-pXvQFPKbpJfLs1cq2gUFkxqw/edit?usp=sharing) (Lead: Mauro Toselli)
* Italian - [GitHub Repository](https://github.com/giodegas/py4inf/tree/ita) (Lead: Giovanni De Gasperis)
* Spanish - [Libro Formattato](http://do1.dr-chuck.com/py4inf/ES-es/) | [Book Source](https://github.com/hedemarrie/py4inf-esp) (Lead: Hedemarrie Dussan)

Mandami pure un collegamento (oppure forka ed edita questa pagina e mandami un Pull Request).

Puoi usare la tecnologia che più ti aggrada tra LaTeX, Google Docs, WikiBook or altro che preferisci.

Se conosci e puoi utilizzare LaTeX, la via più semplice per tradurre il
libro è fare un fork del mio repo su GitHub e iniziare a tradurre nel
tuo repo personale. In questo modo sarà più semplice rimanere aggiornati
con i cambiamenti che faccio sulla versione Inglese del libro.

Se inizi a tradurre in github, per cortesia contattami in modo che io possa aggiungerti 
al processo automatico di generazione del libro:

* http://do1.dr-chuck.com/py4inf/

In questo modo il tuo lavoro aggiornato può essere facilmente trovato dagli studenti dal mio sito
appena inizia la traduzione.

DA FARE
-------

Ho bisogno di documentare e di fare il check in del codice per eseguire
il server di build. Sarebbe un ottima alternativa per gli utenti MacBook
che non hanno HeVea per sviluppare. Edita localmente, controllare il PDF
e poi fai il check in delle modifiche, aspetti un attimo e la versione
HTML è pronta sul server.

Non ho idea coem funzioni LaTeX su Windows. Sarei ben felice di avere
maggiori info a proposito.

Chuck Severance - 
Mon Aug 18 22:20:12 EDT 2014




