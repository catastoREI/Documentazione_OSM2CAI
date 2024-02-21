# Funzionalità comuni

Queste funzionalità sono estese a tutti gli utenti, fermo restando le limitazioni imposte dai permessi territoriali

### Riepilogo nazionale

In questa sezione viene mostrato il riepilogo in tempo reale della Rete Escursionistica Italiana

<figure><img src="../.gitbook/assets/image (38).png" alt=""><figcaption><p>Riepilogo nazionale della Rete Escursionistica Italiana</p></figcaption></figure>

***

### Riepilogo nazionale

***

### Campo cerca primario

Nel campo di ricerca è possibile ricercare i seguenti elementi, se presenti nel database OSM2CAI

* **settori:** tramite \[sigla regione]\[sigla provincia]\[sigla area]\[sigla settore], per esempio "RBTC1"
* **aree:** tramite \[sigla regione]\[sigla provincia]\[sigla area], per esempio "BVRA"&#x20;
* **province:** tramite \[nome provincia], per esempio "Pisa"
* **percorsi tramite ref:REI:** il codice univoco del percorso, per esempio PAQA630D. È possibile sia COD\_REI\_OSM (ref:REI da OSM) che COD\_REI\_COMP (ref:REI calcolato)
* **percorsi tramite OpenStreetMap iD:** per esempio "9864993"
* **ref del percorso:** con indicazione del settore di appartenza, per esempio "135A"
* **sezioni e sottosezioni CAI:** tramite \[nome sezione o sottozione], per esempio "Ascoli"
* **rifugi CAI:** tramite \[nome rifugio], per esempio "Felik"
* **gruppi montuosi:** tramite \[nome gruppo montuoso], per esempio "giudicarie"

<figure><img src="../.gitbook/assets/image (46).png" alt=""><figcaption><p>esempio di ricerca tramite ref 135A</p></figcaption></figure>

***

### Sezione Percorsi Escursionistici

In questo sezione è possibile visualizzare tutti percorsi escursionistici che risultano al momento nel database.

<figure><img src="../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

La tabella ha le seguenti colonne e i campi contrassegnati con "\*" sono ordinabili; nella piattaforma i campi ordinabili hanno la seguente icona ![](<../.gitbook/assets/image (73).png>), accanto al nome.

| CAMPO                                                                 | DESCRIZIONE                                                                   |
| --------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| REGIONI                                                               | Regione di appartenenza                                                       |
| PROVINCE                                                              | Provincia di appartenenza                                                     |
| AREE                                                                  | Area di appartenenza                                                          |
| SETTORI                                                               | Settore di appartenenza                                                       |
| REF \*                                                                | Codice ref del percorso                                                       |
| COD\_REI\_OSM \*                                                      | Codice REI ricavato da OpenStreetMap                                          |
| COD\_REI\_COMP \*                                                     | Codice REI calcolato dalla piattaforma                                        |
| PERCORRIBILITÀ \*                                                     | Stato di percorribilità                                                       |
| ULTIMA RICOGNIZIONE \*                                                | Data ultima ricognizione                                                      |
| STATO \*                                                              | Stato di accatastamento                                                       |
| <img src="../.gitbook/assets/image (74).png" alt="" data-size="line"> | Permette di aggiungere o aggiornare lo stato di percorribilità di un percorso |
| <img src="../.gitbook/assets/image (75).png" alt="" data-size="line"> | Permette di accedere alla pagina di dettaglio di un percorso                  |

#### **Campo cerca secondario**

Il campo di ricerca secondario è declinato in funzione dei permessi territoriali associati all'utente, ed è possibile cercare gli stessi campi del campo di ricerca primario

#### Filtro per stato di accatastamento

Questo filtro restiutisce solo i percorsi con un dato stato di accatastamento

<figure><img src="../.gitbook/assets/image (50).png" alt=""><figcaption><p>filtro per stato di accatastamento</p></figcaption></figure>

#### Altri filtri disponibili

<figure><img src="../.gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure>

Questo filtro permette di filtrare attraverso i seguenti campi:

| CAMPO                        | DESCRIZIONE                                                                                                  |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------ |
| REGIONE                      | Regione di appartenenza                                                                                      |
| PROVINCIA                    | Provincia di appartenenza                                                                                    |
| AREA                         | Area di appartenenza                                                                                         |
| SETTORE                      | Settore di appartenenza                                                                                      |
| GEOMETRY SYNC                | Restituisce i percorsi in cui la geometria su OSM2CAI differisce da quella presente su OpenStreetMap (SI/NO) |
| DELETE ON OSM                | Restituisce i percorsi di cui è stata eliminata la corrispondente relazione su OpenStreetMap (SI/NO)         |
| REGION FAVORITE HIKING ROUTE | Restituisce i percorsi considerati tra i più significativi della Regione (SI/NO)                             |
| STATO DI PERCORRENZA         | Restituisce i percorsi con un definito stato di percorrenza                                                  |
| CORRETTEZZA GEOMETRIA        | Restituisce i percorsi con una definita correttezza geometrica  (SI/NO)                                      |

\
