# Sezioni

In questa sezione viene mostrato l'elenco riepilogativo di tutte le Sezioni CAI Italiane, con i seguenti dati:

| CAMPO         | DESCRIZIONE                                                                       |
| ------------- | --------------------------------------------------------------------------------- |
| NOME \*       | nome della Sezione o Sottosezione                                                 |
| CODICE CAI \* | codice interno CAI della Sezione o Sottosezione                                   |
| REGIONE       | Regione di appartenenza della Sezione o Sottosezione                              |
| SDA1          | numero percorsi in stato di accatastamento 1 gestiti dalla Sezione o Sottosezione |
| SDA2          | numero percorsi in stato di accatastamento 2 gestiti dalla Sezione o Sottosezione |
| SDA3          | numero percorsi in stato di accatastamento 3 gestiti dalla Sezione o Sottosezione |
| SDA4          | numero percorsi in stato di accatastamento 4 gestiti dalla Sezione o Sottosezione |
| TOT           | numero percorsi totali gestiti dalla Sezione o Sottosezione                       |
| SPS           | numero percorsi in stato di percorribilità sconosciuto                            |
| SPP           | numero percorsi in stato di percorribilità percorribile                           |
| SPPP          | numero percorsi in stato di percorribilità parzialmente percorribile              |
| SPNP          | numero percorsi in stato di percorribilità non percorribile                       |

I campi contrassegnati con "\*" sono ordinabili; nella piattaforma i campi ordinabili hanno la seguente icona ![](<../../../.gitbook/assets/image (79).png>), accanto al nome.

<figure><img src="../../../.gitbook/assets/image (40).png" alt=""><figcaption><p>Lista delle Sezioni CAI</p></figcaption></figure>

### Filtro

È disponibile un filtro su base regionale

<figure><img src="../../../.gitbook/assets/image (21).png" alt=""><figcaption><p>Filtro per Regione</p></figcaption></figure>

## Pagina Sezione

Per ogni Sezione è disponibile una pagina riepilogativa dove vengono mostrati i dati relativi alla Sezione, gli utenti associati alla Sezione e i percorsi gestiti

### Riepilogo dati

<figure><img src="../../../.gitbook/assets/image (120).png" alt=""><figcaption><p>Riepilogo Sezione</p></figcaption></figure>

In questa sezione vengono mostrati:\
\- numero percorsi nei diversi stati di accatastamento\
\- stato avanzamento lavori (SAL) sullo [stato di percorribilità](../../../piattaforma/definizioni/stato-di-percorribilita.md)\
\- stato avanzamento lavori (SAL) sullo [stato di accatastamento](../../../piattaforma/definizioni/stato-di-accatastamento.md)\
\- numero totale dei percorsi monitorati dalla Sezione\
\- numero totale dei chilometri dei percorsi monitorati dalla Sezione

### Download dati

<figure><img src="../../../.gitbook/assets/image (110).png" alt=""><figcaption></figcaption></figure>

In questa sezione è possibile effettuare scaricare i seguenti dati:\
\- file .geojson dei percorsi\
\- file .csv con l'elenco dei percorsi

### Referente Sezionale della **Sentieristica**

{% hint style="warning" %}
Le condizioni per poter assegnare i ruoli ad un utente sono:\
\- l'utente deve avere il MyCAI attivo ([https://soci.cai.it/](https://soci.cai.it/));\
\- l'utente deve aver fatto almeno un login sulla piattaforma OSM2CAI ([https://osm2cai.cai.it/](https://osm2cai.cai.it/))
{% endhint %}

I Referenti Regionali possono assegnare il ruolo di **Referente Sezionale della Sentieristica**, ad un qualunque utente che abbia fatto l'accesso alla piattaforma, tramite la Action \<Assegna responsabile sezione>.

<figure><img src="../../../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

Una volta selzionata la action, sarà disponibile un campo cerca per selezionare l'utente desiderato

<figure><img src="../../../.gitbook/assets/image (134).png" alt=""><figcaption><p>menu per la ricerca dell'utente</p></figcaption></figure>

{% hint style="info" %}
Gli Admin, i Referenti Nazionali e i Referenti Regionali possono modificare il ruolo di Referente Sezionale andando a modificare l'informazione nel profilo dell'utente.

Fare riferimento al seguente paragrafo: [Modifica profilo utente](https://catastorei.gitbook.io/documentazione-osm2cai/interfaccia-utente/resources/utenti#modifica-profilo-utente)
{% endhint %}

### Lista membri Gruppo Sentieri

{% hint style="warning" %}
Le condizioni per poter assegnare i ruoli ad un utente sono:\
\- l'utente deve avere il MyCAI attivo ([https://soci.cai.it/](https://soci.cai.it/));\
\- l'utente deve aver fatto almeno un login sulla piattaforma OSM2CAI ([https://osm2cai.cai.it/](https://osm2cai.cai.it/))
{% endhint %}

Il Referente Sezionale della **Sentieristica** possono assegnare il ruolo di **Membro del Gruppo Sentieri**, ad un qualunque utente che abbia fatto l'accesso alla piattaforma, tramite la Action \<Aggiungi membri alla sezione>

<figure><img src="../../../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

Una volta selezionata la action, sarà disponibile un campo cerca per selezionare l'utente desiderato

<figure><img src="../../../.gitbook/assets/image (136).png" alt=""><figcaption><p>menu per la ricerca dell'utente</p></figcaption></figure>

### Lista percorsi

{% hint style="warning" %}
**ATTENZIONE:** per far comparire i percorsi nella lista dei percorsi della Sezione è necessario inserire il codice Sezione su OpenStreetMap, ed attendere o forzare la sincronizzazione
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (94).png" alt=""><figcaption><p>Elenco percorsi associati alla Sezione</p></figcaption></figure>

Sono disponibili i seguenti filtri:

| CAMPO                   | DESCRIZIONE                                                           |
| ----------------------- | --------------------------------------------------------------------- |
| REGIONE                 | Regione di appartenenza del percorso                                  |
| PROVINCIA               | Provincia di appartenenza del percorso                                |
| AREA                    | Area di appartenenza del percorso                                     |
| SETTORE                 | Settore di appartenenza del percorso                                  |
| GEOMETRIA SINCRONIZZATA | Sincronizzazione della geometria tra OpenStreetMap e OSM2CAI  (SI/NO) |
| ELIMINATO SU OSM        | Percorso eliminato su OpenStreetMap (SI/NO)                           |
| REGIONE PREFERITA       | Percorso considerato tra i più significativi della Regione (SI/NO)    |
| STATO DI PERCORRENZA    | Stato di percorribilità dei percorsi                                  |
| CORRETTEZZA GEOMETRIA   | Corretta della geometria dei percorsi                                 |
| RIFUGI                  | Presenza in un buffer di un chilometro di Rifugi                      |
| SDA                     | Stato di accatastamento                                               |

