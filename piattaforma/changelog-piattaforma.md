# Changelog piattaforma

### 233.30.3 (2024-06-21)

#### Bug Fixes

* flow rate calculated only when water flow rate is validated

### 233.30.2 (2024-06-21)

#### Bug Fixes

* fixed volume and time calculation for source surveys

### 233.30.1 (2024-06-19)

#### Bug Fixes

* bug fix in edit mode source survey

### 233.30.0 (2024-06-13)

#### Features

* added has\_photo boolean column to ugc\_pois table&#x20;
* added has\_photo boolean column to ugc\_pois table&#x20;

#### Bug Fixes

* fixed source survey edit nova&#x20;
* fixed source survey edit nova&#x20;

#### Miscellaneous Chores

* enhanced computing source surveys data process
* enhanced computing source surveys data process
* mitur abruzzo api enhancement&#x20;
* mitur abruzzo api enhancement&#x20;
* updated authorizations for source surveys nova resource&#x20;
* updated authorizations for source surveys nova resource

### 233.29.0 (2024-06-07)

#### Features

* added source survey nova resource oc:3431&#x20;
* added source survey nova resource oc:3431&#x20;

#### Bug Fixes

* abstract mitur abruzzo api&#x20;
* added geometry and validation to overlay geojson&#x20;
* added geometry and validation to overlay geojson&#x20;

#### Miscellaneous Chores

* enhanced mitur abruzzo apis&#x20;
* enhanced mitur abruzzo apis&#x20;

### 233.28.0 (2024-06-06)

#### Features

* added source survey nova resource oc:3431

### 233.27.0 (2024-06-03)

#### Features

* api mitur abruzzo enhancement
* updated mitur abruzzo apis

#### Bug Fixes

* fixed abstract in abruzzo api&#x20;
* fixed mitur abruzzo apis

### 233.26.0 (2024-05-07)

#### Features

* updated export apis for ec pois user association

### 233.25.0 (2024-05-02)

#### Features

* added check user no match command to ugc poi

### 233.24.3 (2024-05-02)

#### Bug Fixes

* fixed user no match in ugc import from geohub&#x20;

### 233.24.2 (2024-04-30)

#### Bug Fixes

* mock opening hours in mitur huts api

### 233.24.1 (2024-04-30)

#### Bug Fixes

* fixed hr id on huts api (was relation id before, now is taking osm2cai id)
* fixed mitur abruzzo apis&#x20;
* fixed section ids key to mitur abruzzo apis

#### Miscellaneous Chores

* enhanced mitur abruzzo huts api documentation

### 233.24.0 (2024-04-18)

#### Features

* updated export api&#x20;

### 233.23.0 (2024-04-18)

#### Features

* implemented areas export api
* implemented ec pois export api
* implemented export api for hiking\_routes list and single feature
* implemented huts export api&#x20;
* implemented itineraries export api
* implemented mountain groups export api&#x20;
* implemented natural springs export api&#x20;
* implemented sections export api&#x20;
* implemented sectors export api
* implemented ugc media export api&#x20;
* implemented ugc pois export api
* implemented ugc track export api
* implemented users export api&#x20;

### 233.22.2 (2024-04-17)

#### Bug Fixes

* fixed natural springs sync command

### 233.22.1 (2024-04-17)

#### Bug Fixes

* fixed poi api caching

### 233.22.0 (2024-04-17)

#### Features

* improved poi mitur api performance

### 233.21.1 (2024-04-16)

#### Bug Fixes

* fixed calculate intersections command

### 233.21.0 (2024-04-16)

#### Features

* improved api performance for mountain groups. Added intersections columns to mountain groups table and created nova action and command to calculate intersections&#x20;

### 233.20.1 (2024-04-16)

#### Bug Fixes

* improved mitur hiking routes api examples&#x20;

### 233.20.0 (2024-04-16)

#### Features

* updated api doc
* updated api docs



### 233.19.2 (2024-04-10)

#### Bug Fixes

* fixed import ugc

### 233.19.1 (2024-04-03)

#### Bug Fixes

* fixed ec pois xlsx

### 233.19.0 (2024-04-02)

#### Features

* implemented form\_id update on creating new ugc poi

### 233.18.0 (2024-04-02)

#### Features

* added fields for api to sections table and updated section sync to overpass command
* created tags mapping config variable
* created trait for tags mapping&#x20;
* implemented apis
* implemented cai huts mitur abruzzo api
* mitur abruzzo sections api updated&#x20;
* updated poi apis for mitur abruzzo&#x20;

#### Bug Fixes

* ecpois wiki fields clickable in xls file download&#x20;
* fix score update command
* fixed hiking routes count in mitur abruzzo dashboard
* fixed lat and lon in ugc poi csv download&#x20;
* fixed lista percorsi in itinerary details&#x20;
* fixed mitur dashboard values&#x20;
* fixed sync command&#x20;

### 233.17.0 (2024-03-21)

#### Features

* added count card and trend for acqua sorgente dashboard
* added nova action to csv download mountain groups
* added region filter to mountain groups
* added ugc download csv action

### 233.16.3 (2024-03-20)

#### Bug Fixes

* deactivated mountain groups table in mitur abruzzo dashboard

### 233.16.2 (2024-03-19)

#### Bug Fixes

* fixed mountain groups issue

### 233.16.1 (2024-03-12)

#### Bug Fixes

* added $route\_cai->is\_syncing = true;
* added $route\_cai->is\_syncing = true; to all
* fixed relation table for mountain groups and regions

### 233.16.0 (2024-03-04)

#### Features

* added mitur abruzzo apis for mountain groups
* added mitur abruzzo hiking routes apis&#x20;
* added mitur single region api&#x20;
* added swagger documentation for mitur region list&#x20;
* api endpoints for mitur abruzzo and controller&#x20;
* created geoIntersect trait
* implemented api for mitur huts regions and sections
* region\_list api implemented
* tests for mitur abruzzo api&#x20;
* updated timestamp documentation in swagger

#### Bug Fixes

* fixed hiking route api

### 233.15.1 (2024-02-27)

#### Bug Fixes

* fixed osm\_id update command

### 233.15.0 (2024-02-27)

#### Features

* added filters to ecpois
* added region favorite to content tab in metadata field in hiking route detail&#x20;
* created command to update pois with missing osm type
* limited value length on regione field on hiking routes section

#### Bug Fixes

* bug fix on osm type
* bug fix on stato di accatastamento card in hiking route details
* command fix
* fix zip download on ugc tracks
* fixed
* hut sync sleep
* sync huts attemps and sleep&#x20;

### 233.14.0 (2024-02-21)

#### Features

* add cai huts tab to hiking routes&#x20;
* add natural spring tab to hiking routes
* added caihuts
* added fillables to hiking routes
* added logs to natural spring sync command
* added migrations
* added postgis to workflow git
* added postgres service to workflow
* create sync command for huts&#x20;
* deploy\_dev\_workflow&#x20;
* installed laravel prompts&#x20;
* ordered results by favorite routes count in descending order&#x20;
* updated associate command to associate huts&#x20;
* updated mitur abruzzo page and sync tool in nova&#x20;

#### Bug Fixes

* added role to psql git workflow&#x20;
* fixed region api
* improved associate to region command&#x20;
* workflow dev deploy fix 1&#x20;

#### Miscellaneous Chores

* removed laravel prompts&#x20;

### 233.13.1 (2024-02-13)

#### Bug Fixes

* fix on sync mountain groups command

### 233.13.0 (2024-02-13)

#### Features

* added action Percorso favorito
* added reg\_ref to sync with osm data&#x20;
* added region field in ecpoi nova
* added regions field to mountain groups nova&#x20;
* added script to associate mountain groups to regions based on geometric data
* added sync ecpoi and mountaingroup tool for admins&#x20;
* added ugcTrack download geojson zip&#x20;
* dashboard percorsi favoriti&#x20;

#### Bug Fixes

* fixed issues\_description in action percorribilità&#x20;

### v233.12.0 (2024-01-31)

#### Features

* added SAL dashboard table
* added swagger docs for ecpois api&#x20;
* api for ecPois&#x20;
* enhanced default user overpass query
* enhanced styles in sal table&#x20;
* modified default query in cerca punti di interesse action&#x20;

#### Bug Fixes

* fixed mitur abruzzo url&#x20;
* fixed osm sync action&#x20;
* fixed SAL mitur-abruzzo&#x20;
* fixed swagger documentation for ecpoi apis&#x20;
* fixed table name&#x20;
* increased max length of default overpass query&#x20;
* problem with sync osm data action in hiking route

#### Miscellaneous Chores

* enhanced swagger api description

### v233.11.0 (2024-01-30)

#### Features

* added poi table (1km buffer) to hiking routes&#x20;
* default overpass query added to user&#x20;
* itinerari default 50&#x20;
* poi relazionati

#### Bug Fixes

* poi name import fixed

### v233.10.0 (2024-01-29)

#### Features

* added osm\_type to ecPoi table and enhanced nova to show type and osm url&#x20;

### v233.9.0 (2024-01-27)

#### Features

* updated colors for section sal

#### Bug Fixes

* fixed code column in natural spring table to be nullable&#x20;
* fixed geometries for pois mountain groups and natural springs
* fixed import poi command&#x20;
* fixed redirect path in associa utente action&#x20;
* fixed sections geojson and csv file names

### v233.8.1 (2024-01-23)

#### Bug Fixes

* fixed associa utente action&#x20;

### v233.8.0 (2024-01-20)

#### Features

* added associa utente action in user index
* added dark mode toggle
* colors updated for percorribilità dashboard

#### Bug Fixes

* fixed import poi policies
* fixewd download geojson action in section index

### v233.7.1 (2024-01-17)

#### Features

* action import poi from osm\_id implemented in hr&#x20;

#### Bug Fixes

* fix on import poi command&#x20;

### v233.7.0 (2024-01-17)

#### Features

* added action assign moderator to sectors&#x20;
* added action download to sectioons&#x20;
* added card stato-avanzamento-percorribilitá to dashboard-regional&#x20;
* added dashboard percorribilità&#x20;
* added dashboard percorribilità to local user&#x20;
* added download csv percorsi for referente locale
* added filtering to ugc for regional and local users
* added geometry check to hiking routes detail&#x20;
* added indicazione download&#x20;
* added metric for sda 3 hiking routes issue status&#x20;
* added metric for sda 4 hiking routes issue status
* added metrics to section details
* Added scheduled task to import UGC from Geohub
* improved performance caching dashboard results&#x20;
* improved query performance for hr&#x20;
* improved users dashboard&#x20;
* improved users dashboard
* updated no permission message
* user nova resource improvement

#### Bug Fixes

* error fixed in ugcmedia&#x20;
* fixed area n in regional dashboard&#x20;
* permission ecpoi user&#x20;
* SectionController imports error
* typo
* user\_permission delete hr&#x20;

### v233.5.3 (2023-12-29)

#### Bug Fixes

* fixed referente regionale issue&#x20;
* fixed revert validate for regional referent&#x20;
* refactoring code&#x20;

### v233.5.2 (2023-12-29)

#### Bug Fixes

* fixed permission for osm sync action&#x20;
* permissions fixes on hiking routes actions

### v233.5.1 (2023-12-29)

#### Bug Fixes

* fixed permissions on hiking routes actions

### v233.5.0 (2023-12-28)

#### Features

* add filter user page&#x20;
* add view user&#x20;
* added 'documentazione OSM2CAI' link in nova tools sidebar menu
* added asHtml() to ugc media url&#x20;
* added osm2cai and infomont map links to hr
* added url oms2cai and infomont map to hr&#x20;
* added user filters&#x20;
* added wm embed maps field to nova ugc resources&#x20;
* clean hr index colums
* enhanced nova interface for ugc resources
* hiking\_route\_details\_action\_upload\_gpx\_policy
* hiking\_route\_details\_sync\_withOSM\_policy
* hr areas and sectors columns resized&#x20;
* hr feature image added helper&#x20;
* improved province, aree,settori list in hr nova index
* map multi linestring component updated&#x20;
* ucg sync&#x20;
* update pagina sezione&#x20;
* user nova indexquery for regional referent&#x20;

#### Bug Fixes

* added more error handling to import ugc
* better error handling in ugc import
* changed relation id to osm2cai id in hr cards links&#x20;
* fix import ugc
* fixed DBAL database error not recognize geometry type in database&#x20;
* fixed download users csv action&#x20;
* fixed error in geojsonable trait
* fixed relationships ugc&#x20;
* typo
* ugc media relative url import
* user relationship with ugc&#x20;

### v233.4.1 (2023-12-21)

**Bug Fixes**

* fixed nova global search

### v233.4.0 (2023-12-20)

#### Features

* added automatic versioning workflow
* added codice sezione and nome sezione to regional csv export
* added dashboard to section detail nova
* added default value for issue\_description in percorribilitá popup for hiking routes nova resource&#x20;
* added index query for regional users on hr. Now they can only see hiking routes for their region&#x20;
* added issues chronology to hiking routes&#x20;
* added osm2cai OSM import itinerary action&#x20;
* added punti di interesse
* added ref\_reg and ref\_reg\_osm to hr nova
* added rilievi section to side menu
* added ugc models
* associate hr to itinerary reworked&#x20;
* improved nova dashboard
* prevent detach hr from sections

#### Bug Fixes

* Add ST\_srid check for geometry in HikingRoutesRegionControllerV2
* fixed api v2 hiking-routes-collection bounding box
* fixed hr upload file text&#x20;
* fixed reg\_ref&#x20;
* fixed restore user when emulate
* moved cai\_scale to tech tab in nova hikingroute resource
* policies for attach hr to sections&#x20;
* restored dashboard&#x20;
* sections can now be created only from admin&#x20;
* typo on update release date script&#x20;
* Update HikingRoutesRegionControllerV2 and app version
* updated confirm text in validate hr action

### v233.3.2

* Implementazione prima versione sezione \<itinerari>

### v233.3.1

* aggiornamenti propedeutici per implementazioni di nuove caratteristiche

### v233.3.0

* aggiornamento campi dati dei file esportati geojson e csv
* implementata sincronizzazione con OSM dei campi elevazione

### v233.2.2

* Implementazione pagina Sezioni
* implemento \<stato percorribilità>: percorribile, parzialmente percorribile, non percorribile, sconosciuto

### v233.1.1

* \[Referenti nazionali/Referenti regionali] Implementazione Percorsi favoriti&#x20;
* \[Percorso/dettaglio] Implementazione Stato di percorribilità

### v224.3.3&#x20;

* \[Percorso/dettaglio] hotfix SYNC WITH DATA OSM&#x20;
* \[Dashboard/regionale] hotfix download file percorsi .csv&#x20;
* \[Dashboard/locale] hotfix download file percorsi .csv

### v224.3.2&#x20;

* \[Percorso/dettaglio] possibilità di portare un percorso da SDA4 a SDA3&#x20;
* \[Referente nazionale e admin] possibilità di eliminare un percorso da OSM2CAI solo se non più presente la corrispondente relazione su OSM&#x20;
* \[Settori/dettaglio] attraverso la action “Associa moderatore”/ Responsabile permette di cercare tra i referenti/utenti che hanno già un account su osm2cai&#x20;
* \[Settori/dettaglio] hotfix modifica full\_code settore (solo admin)\
  \[Percorso/dettaglio] implementato il campo “Geometry Sync” che verifica le eventuali modifiche apportate su OSM rispetto ai dati su OSM2CAI&#x20;
* \[Percorso/dettaglio] aggiunta la condizione della correttezza della geometria per la validazione&#x20;
* \[Percorsi/lista] implementato campi COD\_REI\_OSM (ref:REI da OSM) e COD\_REI\_COMP (ref:REI calcolato)&#x20;
* \[Percorsi/dettaglio] adesso la action SYNC WITH DATA OSM se il percorso è in SDA4, forza la sincronizzazione con OSM e riporta il percorso in SDA3. È necessario procedere a nuova validazione&#x20;
* \[Percorsi/dettaglio] implementata RIFATTORIZZAZIONE SETTORE, nel caso di modifica apportata al settore di appartenenza del percorso&#x20;
* \[Percorsi/dettaglio] adesso la action SYNC WITH DATA OSM, lancia anche lo script per il calcolo di OSM2CAI\_STATUS&#x20;
* \[Cerca] la funzione cerca permette di trovare i percorsi attraverso il COD\_REI\_COMP (ref:REI calcolato)&#x20;
* \[Province/dettaglio] implementato report&#x20;
* \[Aree/dettaglio] implementato report&#x20;
* \[Header] implementato numero versione e data rilascio&#x20;
* \[Utenti/lista] hotfix elenco utenti&#x20;
* \[Utenti/lista] implementato export .csv utenti (solo admin)&#x20;
* \[API] implementazione di nuove API

### v224.3.1

* \[Percorsi/lista] migliorata interfaccia bottone filtro , con il label
* \[Dettaglio/percorso] migliorata l’interfaccia relativa ai campi di un percorso, specificando quelli presenti in INFOMONT, quelli di OpenStreetMap, quelli calcolati
* \[Dashboard Regionale] implementata data di sincronizzazione con OpenStreetMap
* \[Dashboard Locale] implementata data di sincronizzazione con OpenStreetMap
* \[Dettaglio/percorso] migliorata la funzione
* \[Settori/lista] hotfix modifica geometrie settori

### v224.3

* \[Dashboard nazionale] implementata cella con chilometri totali per sda3+sda4 e cella con chilometri totali in sda4
* \[Settori/lista] implementata colonna Responsabili relativa agli utenti associati ai settori
* \[Settore/dettaglio] implementata la possibilità di modificare i campi "code" e "fullcode" per i Referenti Nazionali e Regionali
* \[Dettaglio percorso] implementato check del ref:REI su base geografica
* \[Dettaglio percorso] implementato check della geometria del percorso
* \[Utenti/lista] hotfix lista utenti solo per account minimo di livello Regionale
* \[Database] aggiornate geometrie confini amministrativi al 1° gennaio 2022
* \[API] implementate nuove API

### v224.2

* \[Dettaglio percorso] implementata Action “SYNC WITH DATA OSM”, per sincronizzare immediatamente i dati di OSM con OSM2CAI
* \[Dettaglio percorso] implementato icona in mappa per visualizzare la mappa del percorso a schermo intero
* \[Dettaglio percorso] implementato icona in mappa per centrare la mappa sulla geometria del percorso
* \[Dettaglio percorso] implementato scala in mappa percorso
* \[Dettaglio settore] implementata possibilità di fare il download della lista dei percorsi di quel settore in formato .csv
* \[Dettaglio percorso] hotfix, eliminato pulsante validazione duplicato
* \[Dettaglio percorso] implementato ref:REI nella tabella metadati
* \[Dettaglio percorso] implementato link per analisi della relazione
* \[Lista percorsi] implementato ordinamento percorsi tramite campo o ref:REI
* \[Dashboard regionale] hotfix, allineamento colori SDA nel riepilogo nazionale
* \[Dashboard regionale] aggiunto SAL nel riepilogo nazionale
* \[Dashboard regionale] hotfix, adesso SDA e SAL corrispondono alle aree e province corrette
* \[Dashboard regionale] hotfix, lista province, aree, settori solo della propria Regione
* \[Dashboard regionale] hotfix, risolto errore visualizzazione pagina dettaglio Aree e Province
* \[Dashboard locale] hotfix, lista province, aree, settori solo quelli assegnati
* \[Dashboard locale] hotfix, SDA e SAL corrispondono alle aree e province corrette
* \[Dashboard main menu] implementata (rimanda a questa guida)

### v224.1.1

* \[Dettaglio percorso] implementato link a waymarkedtrails.org
* \[Dettaglio validazione] implementato codice ref e codice ref:REI nella finestra di validazione
* \[Dashboard main menu] implementata
* \[Dashboard main menu] implementata : percorsi stato di accatastamento 1,2,3 e 4
* \[Dashboard main menu] implementata : solo percorsi validati, cioè in stato di accatastamento 4

### v224.1

* \[hotfix] profilo account regionale e locale
* \[hotfix] lista utenti per account admin
* \[Cerca] implementati i risultati human-readable
* \[Dashboard referente regionale] implementato avviso sull’aggiornamento dei dati disponibili al download
* \[Dashboard referente regionale] implementato SAL Province
* \[Dashboard referente regionale] implementato filtro SAL Province SDA1, SDA2, SDA3 e SDA4
* \[Dashboard referente regionale] implementato SAL Settori
* \[Dashboard referente regionale] implementato filtro SAL Settori SDA1, SDA2, SDA3 e SDA4
* \[Dashboard referente regionale] “Dashboard” rinominata in “Dashboard Regionale”
* \[Dashboard referente locale] implementata dashboard Referente Locale “Dashboard Locale”
* \[Dettaglio percorso] implementata data di validazione (Stato di accatastamento 4)
* \[Dettaglio percorso] implemento nome del validatore
* \[Dettaglio percorso] implementata legenda relativa alla mappa

### v223.1.1

* \[hotfix] caricamento gpx, geojson o kml

### v223.1

* primo rilascio
