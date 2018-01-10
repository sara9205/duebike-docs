# Analisi tecnica di massima

## Tecnologie utilizzate
### Firebase
Firebase è una piattaforma integrata per lo sviluppo di Applicazioni Mobile e Web. L'infrastruttura è gestita ed erogata da Google. Non ci sono limitazioni nella richiesta di risorse come spazio di archiviazione, memoria, numero di richieste contemporanee e potenza computazinonale. L'infrastruttura, quindi, è scalabile in ogni momento e indipendentemente dall'applicazione in corso. Inoltre, gli oneri di manutenzione ordinaria e straordinaria (software, hardware), di eventuale potenziamento della rete elettrica per ospitare l'infrastruttura, di impianti di climatizzazione ed in generale di un progetto per ospitare una infrastruttura in loco, non sono da considerare.

- Autenticazione/Registrazione utenti
    - Google Account
    - Facebook
    - Twitter
- Database
- Hosting per Landing page - ?
- Storage per archiviazione media
- Elaborazione dati e Logica applicativa
    - Utilizzando Node JS
- Notifiche verso Applicazione Mobile
- Metriche tecniche Applicazione Mobile
	- Segnalazione arresti anomali (crash)
	- Monitoraggio delle performance
- Metriche di distribuzione Applicazione Mobile
- Backup giornalieri

### Applicazione Mobile
NativeScript è un Framework open source che permette lo sviluppo di Applicazioni Mobile totalmente native mediante l'utilizzo di Angular JS, TypeScript o Javascript. La scelta di questo Framework ha come vantaggio di sviluppare l'applicazione una sola volta e distribuirla per Android e iOS.
- Android e iOS utilizzando NativeScript
- Multilingua

### Applicazione Backoffice
- Aggiunta/Modifica Circuiti
- Gestione dei Partner
- Grafici Small Data e Big Data?
- Impostazioni generiche della Piattaforma
- Multilingua

### Stripe
- Piattaforma per pagamenti online

## Oggetti dell'Applicazione
### Piattaforma
La piattaforma è il proprietario del sistema. Ha il controllo completo su tutti gli oggetti dell'applicazione.

### Utenti
- Partners
- Turisti

### Equipment
Identifica il mezzo sportivo (Bici, Rollerblade, Kitesurf, Canoa)

### Tipologie di Equipments
Identifica la categoria di Equipments (Cicli, Pattini, Imbarcazioni)

### Turisti
- Dati anagrafici
- Altri metadati

### Partner
Il Partner rappresenta l'attività commerciale collegata alla Piattaforma
- Noleggiante
- Coordinate geografiche
- Commissione da applicare sul pagamento online (in percentuale)
- Altri metadati

### Circuiti
- Partono da un Partner abilitato al noleggio
- Finiscono ad un Partner abilitato al noleggio
- Insieme di coordinate geografiche

### Punti di Interesse
- Coordinate geografiche

### Fughe dal Circuito
Identifica la deviazione da un Circuito per raggiungere un Partner o un Punto di Interesse
- Circuito
- Partner o Punto di Interesse
- Insieme di coordinate geografiche per raggiungere il Checkpoint

### Offerta
Identifica un'offerta di un servizio erogato da un Partner.
- Partner
- Fissa o Temporizzata

### Planning
- Turista
- Calendario integrato con il medesimo sullo smartphone
- Offerta o Circuito

### Messaggistica Mobile
- Tra Parner e Turista
- Tra Partner e Piattaforma

### Interazioni Social
Il Turista potrà condividere I contenuti della Applicazione Mobile sui Social da lui collegati.

### Pagamenti
Il Partner avrà la possibilità di inoltrare i pagamenti verso i Turisti. Mediante Stripe, il Turista sarà in grado di pagare direttamente con la sua Carta di Credito/Debito/Pre-pagata senza necessitare di nessuno servizio di terze parti.
Stripe ha una commissione fissa per ogni transazione effettuata.

### Relazioni tra gli oggetti
![Circuito Tour](https://github.com/DueBiKe/duebike-docs/blob/master/images/1.jpg)
![Offerte](https://github.com/DueBiKe/duebike-docs/blob/master/images/2.jpg)
![Planning](https://github.com/DueBiKe/duebike-docs/blob/master/images/3.jpg)

## Raccolta Dati
