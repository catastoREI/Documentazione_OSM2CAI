---
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Utenti e Permessi territoriali

La gerarchia degli utenti della piattaforma OSM2CAI rispecchia la suddivisione territoriale della SOSEC (Direttivo, Gruppi Regionali, Gruppi sezionali)

Vengono identificati i diversi livelli di accesso con permessi territoriali differenti; è possibile associare una qualsiasi area di competenza (settore, area, provincia o regione) ad un utente.&#x20;

Gli Amministrari, i Referenti Nazionali e i Referenti Regionali possono modificare i metadati relativi ad altri utenti e effettuare l'assegnazione territoriale, per abilitarli ad operare sulla piattaforma.\
Fare riferimento alla sezione apposita: [Utenti](../interfaccia-utente/resources/utenti.md)

Qui di seguito ne vengono descritte le funzionalità principali

### Amministratore di sistema&#x20;

* Livello territoriale massimo
* Aggiunge/rimuove utenti
* Assegna/rimuove il ruolo di amministratore ad un qualsiasi utente
* Assegna/rimuove il ruolo di referente nazionale, regionale e locale ad un qualsiasi utente

### Referente nazionale

* Livello territoriale nazionale
* Validazione dei percorsi su tutto il territorio nazionale
* Visualizza la dashboard con gli elementi generali e gli elementi specifici del referente nazionale&#x20;
* Visualizza il menu con le voci generali e le voci dedicate al referente nazionale - Aggiunge utenti&#x20;
* Visualizza la lista di tutti i percorsi d’italia in una tabella con possibilità di filtrare e cercare&#x20;
* Assegna una regione ad un utente facendolo diventare così referente regionale - Assegna uno o più settori (aree, province) ad un utente facendolo diventare così referente locale&#x20;
* Esplorare aree e settori su una mappa dedicata

### Referente regionale&#x20;

* Livello territoriale regionale
* Validazione dei percorsi su tutto il territorio regionale
* Visualizza la dashboard con gli elementi generali e gli elementi specifici del referente regionale
* Visualizza il menu con le voci generali e le voci dedicate al referente regionale&#x20;
* Assegna uno o più settori (aree, province) della propria regione ad un utente facendolo diventare così referente locale&#x20;
* Visualizza la lista di tutti i percorsi della propria regione in una tabella con possibilità di filtrare e cercare&#x20;
* Scarica un foglio CSV con la lista dei percorsi di tutta la regione (il file viene generato ogni giorno)
* Scarica un file shape con la suddivisione in Settori della propria Regione
* Scarica un file .geojson con i percorsi della sua Regione (il file viene generato ogni giorno)
* Effettua una ricerca in mappa per trovare un percorso specifico&#x20;
* Esplorare aree e settori su una mappa dedicata

### Referente locale&#x20;

* Livello territoriale provincia, area e settore
* Validazione dei percorsi su tutto il territorio associato
* Visualizza la dashboard con gli elementi generali e gli elementi specifici del referente locale (relativa ai propri settori, aree e province)&#x20;
* Visualizza il menu con le voci generali e le voci dedicate al referente locale (relativa ai propri settori aree e province)&#x20;
* Visualizza la lista di tutti i percorsi (con lo stato) dei propri settori, aree e  province in una tabella con possibilità di filtrare e cercare. Dalla lista visualizza  un bottone che gli permette di andare al dettaglio del percorso da dove è possibile eseguire la validazione di un percorso&#x20;
* Scarica un foglio CSV con la lista dei percorsi dei propri settori, aree e province&#x20;
* Effettuare una ricerca in mappa per trovare un percorso specifico&#x20;
* Esplorare aree e settori su una mappa dedicata

### Referente sezionale

* Livello territoriale Sezione
* Validazione dei percorsi dei percorsi monitorati dalla Sezione
* Visualizza la dashboard con gli elementi generali e gli elementi specifici del referente locale (relativa alla propria Sezione)&#x20;
* Visualizza il menu con le voci generali e le voci dedicate al referente sezionale
* Visualizza la lista di tutti i percorsi (con lo stato) della propria Sezione in una tabella con possibilità di filtrare e cercare. Dalla lista visualizza  un bottone che gli permette di andare al dettaglio del percorso da dove è possibile eseguire la validazione di un percorso&#x20;
* Scarica un foglio CSV con la lista dei percorsi della propria sezione
* Effettuare una ricerca in mappa per trovare un percorso specifico&#x20;
* Esplorare aree e settori su una mappa dedicata

### Utente validatore

* Accede alla lista specifica dei rilievi effettuati sul campo da altri utenti (Acquasorgente, Segni dell'uomo, Aree Archeologiche, Siti Archeologici, Siti Geologici), in base ai permessi di validazione assegnati
* Modifica i metadati dei rilievi
* Validazione dei rilievi: un rilievo validato non può più essere modificato dall'autore del rilievo stesso

### Utente ospite&#x20;

* Effettua il login alla piattaforma
* Accede solo in modalità consultazione in quanto non dotato di permessi territoriali
* Visualizza gli elementi (punti di interesse, rilievo percorso e immagini) acquisiti sul campo tramite le APP del Club Alpino Italiano, collegate alla piattaforma: APP del Sentierista, APP Sentiero Italia CAI e APP Acquasorgente
* Gestione (creazione, modifica ed eliminazione) dei dati acquisiti
* Effettuare una ricerca in mappa per trovare un percorso specifico&#x20;
* Esplorare aree e settori su una mappa dedicata

### Utente fruitore

* Non effettua il login alla piattaforma
* Accede solo alla mappa pubblica per consultare e/o scaricare le informazioni
