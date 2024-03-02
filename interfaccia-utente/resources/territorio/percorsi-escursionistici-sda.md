# Percorsi escursionistici (SDA\*)

### Elenco percorsi

<figure><img src="../../../.gitbook/assets/image (36).png" alt=""><figcaption></figcaption></figure>

In questa sezione viene mostrato l'elenco dei percorsi escursionistici presenti nel catasto; i campi mostrati sono i seguenti:

| CAMPO                                                                       | DESCRIZIONE                                                                        |
| --------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- |
| REGIONI                                                                     | regione di appartenenza del percorso                                               |
| PROVINCE                                                                    | provincia di appartenenza del percorso                                             |
| AREE                                                                        | aree di appartenenza del percorso                                                  |
| SETTORI                                                                     | settori di appartenenza del percorso                                               |
| REF \*                                                                      | numero del percorso                                                                |
| COD\_REI\_OSM \*                                                            | codice REI presente su OpenStreetMap                                               |
| COD\_REI\_COMP \*                                                           | codice REI calcolato dalla piattaforma, sulla base della suddivisione territoriale |
| PERCORRIBILITÀ \*                                                           | stato di percorribilità del percorso                                               |
| ULTIMA RICOGNIZIONE \*                                                      | data ultima ricognizione del percorso                                              |
| STATO                                                                       | stato di accatastamento del percorso                                               |
| <img src="../../../.gitbook/assets/image (77).png" alt="" data-size="line"> | Permette di aggiungere o aggiornare lo stato di percorribilità di un percorso      |
| <img src="../../../.gitbook/assets/image (76).png" alt="" data-size="line"> | Permette di accedere alla pagina di dettaglio di un percorso                       |

I campi contrassegnati con "\*" sono ordinabili; nella piattaforma i campi ordinabili hanno la seguente icona ![](<../../../.gitbook/assets/image (73).png>), accanto al nome.

### Filtri

#### **Filtro SDA**

Questo filtro permette di visualizzare solo i percorsi con uno specifico stato di accatastamento.

<figure><img src="../../../.gitbook/assets/image (28).png" alt=""><figcaption><p>Esempio filtro per Stato di accatastamento</p></figcaption></figure>

#### **Altri filtri disponibili**

sono implementati i seguenti filtri per migliorare la ricerca dei percorsi

<figure><img src="../../../.gitbook/assets/image (29).png" alt=""><figcaption><p>F<strong>iltri disponibili</strong></p></figcaption></figure>

| CAMPO                               | DESCRIZIONE                                                                   |
| ----------------------------------- | ----------------------------------------------------------------------------- |
| REGIONE                             | filtro per regione di appartenenza del percorso                               |
| PROVINCIA                           | filtro per provincia di appartenenza del percorso                             |
| AREA                                | filtro per area di appartenenza del percorso                                  |
| SETTORE                             | filtro per settore di appartenenza del percorso                               |
| GEOMETRY SYNC FILTER                | filtro per sincronizzazione della geometria (SI/NO)                           |
| DELETE ON OSM FILTER                | filtro per corretta della geometria (SI/NO)                                   |
| REGION FAVORITE HIKING ROUTE FILTER | filtro per percorsi considerati tra i più significativi della Regione (SI/NO) |
| STATO DI PERCORRENZA                | filtro per stato di percorribilità dei percorsi                               |
| CORRETTEZZA GEOMETRIA               | filtro per corretta della geometria dei percorsi                              |

### Dettaglio percorso

Per ogni percorso è disponibile una pagina riepilogativa dove vengono mostrati i dati relativi presenti nel database OSM2CAI, e dove è possibile procedere alla verifica dei dati e successivamente alla validazione per percorso

#### Sezione codice REI e stato di validazione

<figure><img src="../../../.gitbook/assets/image (71).png" alt=""><figcaption></figcaption></figure>

In questa parte è possibile visualizzare le seguenti informazioni:

| CAMPO                   | DESCRIZIONE                                                                                                                                                                                        |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| REF                     | numero del percorso                                                                                                                                                                                |
| CODICE REI              | se disponibile viene visualizzato  il codice REI inserito su OpenStreetMap. Mentre viene sempre visualizzato il codice REI calcolato sulla base del REF del percorso e del settore di appartenenza |
| SETTORI                 | vengono indicati i settori su cui insiste il percorso, con relative percentuali. Il sistema assegna in automatico quello con percentuale maggiore                                                  |
| OpenStreetMap           | mostra l'id **OpenStreetMap** del percorso, rimandando direttamente alla piattaforma per eventuali aggiornamenti                                                                                   |
| Waymarkedtrails         | rimanda al percorso sulla piattaforma **waymarkedtrails.org**                                                                                                                                      |
| OSM Relation analyzer   | rimanda all'analisi del percorso sulla piattaforma **OSM Relation Analyzer**                                                                                                                       |
| OSM2CAI                 | rimanda alla mappa del percorso sulla piattaforma OSM2CAI                                                                                                                                          |
| INFOMONT                | rimanda alla mappa del percorso sulla piattaforma INFOMONT                                                                                                                                         |
| STATO DI ACCATASTAMENTO | mostra lo stato di accatastamento del percorso                                                                                                                                                     |
| DATA DI VALIDAZIONE     | mostra la data di validazione del percorso                                                                                                                                                         |
| VALIDATORE              | mostra l'utente che ha validato il percorso                                                                                                                                                        |

#### Sezione Mappa e validazione

<figure><img src="../../../.gitbook/assets/image (64).png" alt=""><figcaption><p>Mappa percorso</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (89).png" alt=""><figcaption><p>Esempio di mappa con due tracce:<br>Linea blu: percorso OSM2CAI/OSM<br>Linea rossa: percorso caricato dall'utente</p></figcaption></figure>

In questa parte è possibile visualizzare le seguenti informazioni:

| CAMPO                 | DESCRIZIONE                                                                                                                                                                                                                                                                                                                    |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Percorribilità        | mostra lo stato di percorribilità del percorso                                                                                                                                                                                                                                                                                 |
| Legenda               | <p>mostra la legenda della mappa:</p><ul><li>Linea blu: percorso OSM2CAI/OSM</li><li>Linea rossa: percorso caricato dall'utente</li></ul>                                                                                                                                                                                      |
| Mappa                 | viene mostrata la mappa del percorso, con la possibilità di visualizzarla a tutto schermo                                                                                                                                                                                                                                      |
| Correttezza geometria | <p>mostra o meno la correttezza della geometria del percorso: </p><p>-<img src="../../../.gitbook/assets/image (68).png" alt=""> geometria corretta<br>-<img src="../../../.gitbook/assets/image (69).png" alt=""> geometria non corretta</p>                                                                                  |
| Coerenza ref REI      | <p>mostra o meno la coerenza del codice REI, tra quello calcolato e quello presente su OpenStreetMap</p><p>-<img src="../../../.gitbook/assets/image (68).png" alt=""> codice REI coerente<br>-<img src="../../../.gitbook/assets/image (69).png" alt=""> codice REI non coerente</p>                                          |
| Geometry Sync         | <p>mostra o meno la sincronizzazione della geometria del percorso, tra quella presente su OpenStreetMap e quella nel database OSM2CAI</p><p>-<img src="../../../.gitbook/assets/image (68).png" alt=""> geometria sincronizzata<br>-<img src="../../../.gitbook/assets/image (69).png" alt=""> geometria non sincronizzata</p> |

### Azioni disponibili

In questa parte è possibile svolgere le seguenti azioni:

<figure><img src="../../../.gitbook/assets/image (8).png" alt=""><figcaption><p>Azioni disponibili</p></figcaption></figure>

| CAMPO                         | DESCRIZIONE                                                                                                                                                                                 |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| UPLOAD GPX/KML/GEOJSON        | permette il caricamento di una traccia ricavata da un rilievo fatto sul percorso                                                                                                            |
| VALIDATE                      | permette di validare un percorso                                                                                                                                                            |
| SYNC WITH OSM DATA            | permette di forzare la sincronizzazione dei dati OM2CAI <> OpenStreetMap, senza attendere il normale tempo di sincronizzazione (48 ore)                                                     |
| REVERT VALIDATION             | permette di riportare in stato di accatastamento 3 un percorso validato, per permettere di poterlo aggiornare e rivalidarlo successivamente                                                 |
| ELIMINA                       | permette di eliminare un percorso dal database di OSM2CAI.                                                                                                                                  |
| REFATTORIZZAZIONE SETTORI     | permette di rigenerare la lista dei settori, nel caso di modiche effettuate dagli amministratori                                                                                            |
| PERCORSO FAVORITO             | permette di inserire il percorso tra i favoriti e aggiunge una descrizione e un'immagine. Fare riferimento alla sezione apposita: [Percorsi favoriti](../../dashboard/percorsi-favoriti.md) |
| DATA PUBBLICAZIONE LOSCARPONE | permette di programma la data di pubblicazione sullo Scarpone                                                                                                                               |
| PERCORRIBILITÀ                | permette di aggiornare lo stato di percorribilità del percorso                                                                                                                              |

#### Caricamento traccia di confronto

Tramite la action \<UPLOAD GPX/KML/GEOJSON> è possibile carica una traccia di confronto, ricavata da un rilievo sul campo

<figure><img src="../../../.gitbook/assets/image (108).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Il file che verrà caricato servirà esclusivamente per essere confrontato con la traccia presente nel Catasto/OpenStreetMap; in caso di validazione sarà la traccia del Catasto/OpenStreetMap (in mappa di colore blu) ad essere validata.
{% endhint %}

#### Validazione

Tramite la action \<VALIDATE> è possibile validare un percorso

<figure><img src="../../../.gitbook/assets/image (109).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Un percorso può essere validato solo se è in [stato di accatastamento ](../../../piattaforma/definizioni/stato-di-accatastamento.md)uguale a 3; ed è necessario caricare un traccia del rilievo per il confronto
{% endhint %}

#### Forzare la sincronizzazione con OpenStreetMap

Tramite la action \<SYNC WITH OSM DATA> è possibile forzare la sincronizzazione&#x20;

<figure><img src="../../../.gitbook/assets/image (110).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
La sincronizzazione ha validità fino alla mezzanotte del giorno in cui è stata effetuata; per motivi tecnici dopo tale orario la sincronizzazione automatica sovrascriverà con le informazioni non aggiornate
{% endhint %}

#### Revertare lo stato di accatastamento

Tramite la action \<REVERT VALIDATION> permette di riportare lo stato di accatastamento di un percorso da 4 a 3.

<figure><img src="../../../.gitbook/assets/image (112).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
È possibile revertare lo [stato di accatastamento](../../../piattaforma/definizioni/stato-di-accatastamento.md) da 4 a 3, azione necessaria per permettere al sistema di sincronizzare le modifiche effetuate succesivamente alla validazione
{% endhint %}

#### Elimina percorso

Tramite la action \<ELIMINA> è possibile eliminare un percorso da OSM2CAI

<figure><img src="../../../.gitbook/assets/image (111).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Un percorso può essere eliminato da OSM2CAI solo se è stata eliminata la corrispondente relazione su OpenStreetMap
{% endhint %}

#### Percorsi favoriti

Tramite la action \<PERCORSO FAVORITO> è inserire il percorso tra i favoriti, aggiunge una descrizione e un'immagine.

<figure><img src="../../../.gitbook/assets/image (1) (1) (1).png" alt=""><figcaption><p>Interfaccia di inserimento</p></figcaption></figure>

#### Percorribilità

Tramite la action \<PERCORRIBILITÀ> è possibile aggiornare lo [stato di percorribilità](../../../piattaforma/definizioni/stato-di-percorribilita.md) di un percorso

<figure><img src="../../../.gitbook/assets/image (113).png" alt=""><figcaption></figcaption></figure>

### Sezione metadata

<figure><img src="../../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

In questa parte è possibile visualizzare le seguenti informazioni:

{% tabs %}
{% tab title="Main" %}
| CAMPO              | DESCRIZIONE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Source             | <p>vengono mostrati i campi relativi al tag &#x3C;source> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>                                                                                                                                                                                                                                                                                                        |
| Data ricognizione  | <p>vengono mostrati i campi relativi al tag &#x3C;survey:date> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>                                                                                                                                                                                                                                                                                                   |
| Codice Sezione CAI | <p>vengono mostrati i campi relativi al tag &#x3C;source:ref> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore><br><strong>CODICE SEZIONE</strong>: &#x3C;valore> , rimanda alla pagina della Sezione<br><br><strong>ATTENZIONE:</strong> per far comparire i percorsi nella lista dei percorsi della Sezione è necessario inserire il codice Sezione su OpenStreetMap, ed attendere o forzare la sincronizzazione</p> |
| REF precedente     | <p>vengono mostrati i campi relativi al tag &#x3C;old_ref> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>                                                                                                                                                                                                                                                                                                       |
| REF rei            | <p>vengono mostrati i campi relativi al tag &#x3C;ref:REI> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>                                                                                                                                                                                                                                                                                                       |
| REF regionale      | <p>vengono mostrati i campi relativi al tag &#x3C;reg_ref> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>                                                                                                                                                                                                                                                                                                       |
{% endtab %}

{% tab title="General" %}
| CAMPO                        | DESCRIZIONE                                                                                                                                                                                              |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Località di partenza         | <p>vengono mostrati i campi relativi al tag &#x3C;from> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>         |
| Località di arrivo           | <p>vengono mostrati i campi relativi al tag &#x3C;to> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>           |
| Nome del percorso            | <p>vengono mostrati i campi relativi al tag &#x3C;name> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>         |
| Tipo di rete escursionistica | <p>vengono mostrati i campi relativi al tag &#x3C;network> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>      |
| Codice OSM segnalietica      | <p>vengono mostrati i campi relativi al tag &#x3C;osmc:symbol> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>  |
| Segnaletica descr. (EN)      | <p>vengono mostrati i campi relativi al tag &#x3C;symbol> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>       |
| Segnaletica descr. (IT)      | <p>vengono mostrati i campi relativi al tag &#x3C;symbol:it> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>    |
| Percorso ad anello           | <p>vengono mostrati i campi relativi al tag &#x3C;roundtrip> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>    |
| Nome rete escursionistica    | <p>vengono mostrati i campi relativi al tag &#x3C;network:name> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p> |


{% endtab %}

{% tab title="Tech" %}
| CAMPO                        | DESCRIZIONE                                                                                                                                                                                                                                                                                         |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Lunghezza in Km              | <p>vengono mostrati i campi relativi al tag &#x3C;distance> sia nel database OSM2CAI sia OpenStreetMap e sia quello calcolato dalla piattaforma<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore><br><strong>CALCOLATO</strong>: &#x3C;valore></p>          |
| Diff. CAI                    | <p>vengono mostrati i campi relativi al tag &#x3C;cai_scale> sia nel database OSM2CAI sia OpenStreetMap e sia quello calcolato dalla piattaforma<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore><br><strong>CALCOLATO</strong>: &#x3C;valore></p>         |
| Dislivello positivo in metri | <p>vengono mostrati i campi relativi al tag &#x3C;ascent> sia nel database OSM2CAI sia OpenStreetMap e sia quello calcolato dalla piattaforma<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore><br><strong>CALCOLATO</strong>: &#x3C;valore></p>            |
| Dislivello negativo in metri | <p>vengono mostrati i campi relativi al tag &#x3C;descent> sia nel database OSM2CAI sia OpenStreetMap e sia quello calcolato dalla piattaforma<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore><br><strong>CALCOLATO</strong>: &#x3C;valore></p>           |
| Durata (P->A)                | <p>vengono mostrati i campi relativi al tag &#x3C;duration:forward> sia nel database OSM2CAI sia OpenStreetMap e sia quello calcolato dalla piattaforma<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore><br><strong>CALCOLATO</strong>: &#x3C;valore></p>  |
| Durata (A->P)                | <p>vengono mostrati i campi relativi al tag &#x3C;duration:backward> sia nel database OSM2CAI sia OpenStreetMap e sia quello calcolato dalla piattaforma<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore><br><strong>CALCOLATO</strong>: &#x3C;valore></p> |
| Quota massima                | <p>vengono mostrati i campi relativi al tag &#x3C;ele:max> sia nel database OSM2CAI sia OpenStreetMap e sia quello calcolato dalla piattaforma<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore><br><strong>CALCOLATO</strong>: &#x3C;valore></p>           |
| Quota minima                 | <p>vengono mostrati i campi relativi al tag &#x3C;ele:min> sia nel database OSM2CAI sia OpenStreetMap e sia quello calcolato dalla piattaforma<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore><br><strong>CALCOLATO</strong>: &#x3C;valore></p>           |
| Quota punto di partenza      | <p>vengono mostrati i campi relativi al tag &#x3C;ele:from> sia nel database OSM2CAI sia OpenStreetMap e sia quello calcolato dalla piattaforma<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore><br><strong>CALCOLATO</strong>: &#x3C;valore></p>          |
| Quota punto di arrivo        | <p>vengono mostrati i campi relativi al tag &#x3C;ele:to> sia nel database OSM2CAI sia OpenStreetMap e sia quello calcolato dalla piattaforma<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore><br><strong>CALCOLATO</strong>: &#x3C;valore></p>            |


{% endtab %}

{% tab title="Other" %}
| CAMPO                 | DESCRIZIONE                                                                                                                                                                                                   |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Descrizione (EN)      | <p>vengono mostrati i campi relativi al tag &#x3C;description> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>       |
| Descrizione (IT)      | <p>vengono mostrati i campi relativi al tag &#x3C;description:it> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>    |
| Manutenzione (EN)     | <p>vengono mostrati i campi relativi al tag &#x3C;maintenance> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>       |
| Manutenzione (IT)     | <p>vengono mostrati i campi relativi al tag &#x3C;maintenance:it> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>    |
| Note (EN)             | <p>vengono mostrati i campi relativi al tag &#x3C;from> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>              |
| Note (IT)             | <p>vengono mostrati i campi relativi al tag &#x3C;note> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>              |
| Note di progetto      | <p>vengono mostrati i campi relativi al tag &#x3C;note:it> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>           |
| Operator              | <p>vengono mostrati i campi relativi al tag &#x3C;operator> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>          |
| Stato del percorso    | <p>vengono mostrati i campi relativi al tag &#x3C;state> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>             |
| Indirizzo web         | <p>vengono mostrati i campi relativi al tag &#x3C;website> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p>           |
| Immagine su wikimedia | <p>vengono mostrati i campi relativi al tag &#x3C;wikimedia_commons> sia nel database OSM2CAI sia OpenStreetMap<br><br><strong>INFOMONT</strong>: &#x3C;valore></p><p><strong>OSM</strong>: &#x3C;valore></p> |


{% endtab %}

{% tab title="Content" %}
| CAMPO                                 | DESCRIZIONE                                                                                                                                                                                                                                                                   |
| ------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Automatic Name (computed for TDH)     | mostra il campo generato automaticamente relativo al nome del percorso                                                                                                                                                                                                        |
| Automatic Abstract (computed for TDH) | mostra il campo generato automaticamente relativo alla descrizione del percorso                                                                                                                                                                                               |
| Feature Image                         | mostra la presenza o meno dell'immagine associata al percorso                                                                                                                                                                                                                 |
| Description CAI IT                    | mostra la descrizione del percorso inserita dall'utente                                                                                                                                                                                                                       |
| Region Favorite                       | <p>mostra la presenza o meno della selezione <br>percorso favorito</p><p>-<img src="../../../.gitbook/assets/image (68).png" alt=""> percorso segnalato come favorito<br>-<img src="../../../.gitbook/assets/image (69).png" alt=""> percorso non segnalato come favorito</p> |


{% endtab %}

{% tab title="Issues" %}
| CAMPO                     | DESCRIZIONE                                                              |
| ------------------------- | ------------------------------------------------------------------------ |
| Issue Status              | mostra lo stato di percorribilità del percorso                           |
| Issue Description         | mostra la descrizione relativa alla percorribilità del percorso          |
| Issue Date                | mostra la data di segnalazione relativa alla percorribilità del percorso |
| Issue Author              | mostra l'utente che ha effettuato la segnalazione                        |
| Cronologia Percorribilitá | mostra la cronologia delle segnalazioni                                  |


{% endtab %}

{% tab title="POI" %}
In questa sezione vengono mostrati i POI presenti del database di OSM2CAI, in un buffer di un chilometro (1 Km) dal percorso

<figure><img src="../../../.gitbook/assets/image (107).png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Huts" %}
In questa sezione vengono mostrati i Rifugi o Bivacchi presenti del database di OSM2CAI, in un buffer di un chilometro (1 Km) dal percorso

<figure><img src="../../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Natural Springs" %}
In questa sezione vengono mostrati i dati del progetto Acqua Sorgente presenti del database di OSM2CAI, in un buffer di un chilometro (1 Km) dal percorso
{% endtab %}
{% endtabs %}
