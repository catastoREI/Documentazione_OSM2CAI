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

I campi contrassegnati con "\*" sono ordinabili; nella piattaforma i campi ordinabili hanno la seguente icona ![](<../../../.gitbook/assets/image (73).png>), accanto al nome.

<figure><img src="../../../.gitbook/assets/image (34).png" alt=""><figcaption><p>Lista delle Sezioni CAI</p></figcaption></figure>

### Filtro

È disponibile un filtro su base regionale

<figure><img src="../../../.gitbook/assets/image (15).png" alt=""><figcaption><p>Filtro per Regione</p></figcaption></figure>

### Pagina Sezione

Per ogni Sezione è disponibile una pagina riepilogativa dove vengono mostrati i dati relativi alla Sezione, gli utenti associati alla Sezione e i percorsi gestiti

#### Riepilogo dati

<figure><img src="../../../.gitbook/assets/image (114).png" alt=""><figcaption><p>Riepilogo Sezione</p></figcaption></figure>

In questa sezione vengono mostrati:\
\- numero percorsi nei diversi stati di accatastamento\
\- stato avanzamento lavori (SAL) sullo [stato di percorribilità](../../../piattaforma/definizioni/stato-di-percorribilita.md)\
\- stato avanzamento lavori (SAL) sullo [stato di accatastamento](../../../piattaforma/definizioni/stato-di-accatastamento.md)\
\- numero totale dei percorsi monitorati dalla Sezione\
\- numero totale dei chilometri dei percorsi monitorati dalla Sezione

#### Download dati

<figure><img src="../../../.gitbook/assets/image (104).png" alt=""><figcaption></figcaption></figure>

In questa sezione è possibile effettuare scaricare i seguenti dati:\
\- file .geojson dei percorsi\
\- file .csv con l'elenco dei percorsi

#### Lista Utenti

<figure><img src="../../../.gitbook/assets/image (87).png" alt=""><figcaption><p>Elenco utenti associati alla Sezione</p></figcaption></figure>

#### Lista percorsi

{% hint style="warning" %}
**ATTENZIONE:** per far comparire i percorsi nella lista dei percorsi della Sezione è necessario inserire il codice Sezione su OpenStreetMap, ed attendere o forzare la sincronizzazione
{% endhint %}

<figure><img src="../../../.gitbook/assets/image (88).png" alt=""><figcaption><p>Elenco percorsi associati alla Sezione</p></figcaption></figure>

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

