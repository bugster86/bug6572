Descrizione Role
=========

Ricerca tutti i file di tipo 
/usr/java/<JDK>/jre/lib/content-types.properties

Si assicura che all'interno di questi sia presente la sezione:

audio/mpeg: \
        description=Mpeg Audio;\
        file_extensions=.mp3;\
        icon=mp3


Questa sezione permette di mappare il content type per i file di tipo .mp3

Se il file è modificato e se sul server gira il processo vxmlua --> Il processo vxmlua viene riavviato

In modalità esecuzione viene chiesto all'operatore di digitare yes per confermare l'esecuzione (C'è la possibilità che il processo vxmlua venga riavviato in produzione... chi sta facendo questo lavoro deve esserne cosciente).

Requisiti
------------
Nessuno

Variabili
--------------

Nessuna passata esplicitamente da riga di comando
Se invocato dagli automatic_bugs_7042.yml è settata una variabile auto=true che fa skippare la conferma per la partenza del playbook

Dipendenze
------------

Nessuna

Esempio di chiamata
----------------

ansible-playbook /home/playbook/bugs/6572/main.yml

Informazioni Autore
------------------

Martino.Viganò
Martino.Vigano@enghouse.com
