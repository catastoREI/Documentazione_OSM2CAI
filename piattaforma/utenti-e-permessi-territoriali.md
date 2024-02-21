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

Qui di seguito ne vengono descritte le funzionalità principali

### Amministratore di sistema&#x20;

* Livello territoriale massimo
* Aggiunge/rimuove utenti
* Assegna/rimuove il ruolo di amministratore ad un qualsiasi utente
* Assegna/rimuove il ruolo di referente nazionale, regionale e locale ad un qualsiasi utente

### Referente nazionale

* Livello territoriale nazionale
* Visualizza la dashboard con gli elementi generali e gli elementi specifici del referente nazionale&#x20;
* Visualizza il menu con le voci generali e le voci dedicate al referente nazionale - Aggiunge utenti&#x20;
* Visualizza la lista di tutti i percorsi d’italia in una tabella con possibilità di filtrare e cercare&#x20;
* Assegna una regione ad un utente facendolo diventare così referente regionale - Assegna uno o più settori (aree, province) ad un utente facendolo diventare così referente locale&#x20;
* Esplorare aree e settori su una mappa dedicata

### Referente regionale&#x20;

* Livello territoriale regionale
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
* Visualizza la dashboard con gli elementi generali e gli elementi specifici del referente locale (relativa ai propri settori, aree e province)&#x20;
* Visualizza il menu con le voci generali e le voci dedicate al referente locale (relativa ai propri settori aree e province)&#x20;
* Visualizza la lista di tutti i percorsi (con lo stato) dei propri settori, aree e  province in una tabella con possibilità di filtrare e cercare. Dalla lista visualizza  un bottone che gli permette di andare al dettaglio del percorso da dove è possibile eseguire la validazione di un percorso&#x20;
* Scarica un foglio CSV con la lista dei percorsi dei propri settori, aree e province&#x20;
* Effettuare una ricerca in mappa per trovare un percorso specifico&#x20;
* Esplorare aree e settori su una mappa dedicata

### Utente ospite&#x20;

* Effettua il login alla piattaforma
* Accede solo in modalità consultazione in quanto non dotato di permessi territoriali

### Utente fruitore

* Non effettua il login alla piattaforma
* Accede solo alla mappa pubblica per consultare e/o scaricare le informazioni
