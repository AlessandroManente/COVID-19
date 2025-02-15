# Changelog

Tutte le modifiche al progetto, nuove funzionalità e informazioni sono documentate in questo file

## Prossimi aggiornamenti

- Bonifica dati pregressi con codici NUTS
- Note di analisi di data quality
- Aggiornamento dati giorni precedenti in base alle note di ricalcoli da parte delle Regioni
- Dopo il 6 gennaio 2021 gli agiornamenti delle nuove aree con le misura di contenimento verranno effettuati solo sul file generalizzato

## 2021-03-07

- Modifica: aggiornati csv e json file delle metriche sulle visualizzazioni delle dashboard desktop e mobile
- 
## 2021-03-01

- Modifica: aggiornati shape e geojson file generalizzati con le nuove misure di contenimento a livello regionale (aree rosse, arancioni, gialle e bianche) con relativi metadata. Per le aree bianche, nell'attributo LegSpecRif è stato introdotto il nuovo valore "art.1 comma 11", sempre con riferimento alle disposizioni del DPCM 14 gennaio 2021.

## 2021-02-21

- Modifica: aggiornati shape e geojson file generalizzati con le nuove misure di contenimento a livello regionale (aree rosse, arancioni e gialle) con relativi metadata.

## 2021-02-14

- Modifica: aggiornati shape e geojson file generalizzati con le nuove misure di contenimento a livello regionale (aree rosse, arancioni e gialle) con relativi metadata.

## 2021-02-11

- Modifica: aggiornati shape e geojson file generalizzati con le nuove misure di contenimento a livello regionale (aree rosse, arancioni e gialle) con relativi metadata.

## 2021-02-08

- Modifica: aggiornati shape e geojson file generalizzati con le nuove misure di contenimento a livello regionale (aree rosse, arancioni e gialle) con relativi metadata.

## 2021-02-01

- Modifica: aggiornati shape e geojson file generalizzati con le nuove misure di contenimento a livello regionale (aree rosse, arancioni e gialle) con relativi metadata.

## 2021-01-24

- Modifica: aggiornati shape e geojson file generalizzati con le nuove misure di contenimento a livello regionale (aree rosse, arancioni e gialle) con relativi metadata.

## 2021-01-18

- Aggiunta informazioni "codice_nuts_1" e "codice_nuts_2" sul dataset regioni e "codice_nuts_1", "codice_nuts_2" e " codice_nuts_3" sul dataset province
- Aggiunta informazioni "totale_positivi_test_molecolare", "totale_positivi_test_antigenico_rapido", "tamponi_test_molecolare" e "tamponi_test_antigenico_rapido" sui dataset regioni e andamento nazionale

## 2021-01-17

- Modifica: aggiornati shape e geojson file generalizzati con le nuove misure di contenimento a livello regionale (aree rosse, arancioni e gialle) con relativi metadata.

## 2021-01-11

- Modifica: aggiornati shape e geojson file generalizzati con le nuove misure di contenimento a livello regionale (aree rosse, arancioni e gialle) con relativi metadata.

## 2021-01-07

- Modifica: aggiornati shape e geojson file generalizzati con le nuove misure di contenimento a livello nazionale (aree rosse, arancioni e gialle) con relativi metadata.

## 2020-12-29

- Modifica: aggiunta anche una versione generalizzata (-g) del dataset relativo alle nuove aree con le misure di contenimento a livello nazionale (aree rosse, arancioni e gialle).

## 2020-12-24

- Modifica: aggiornato shape file con le nuove misure di contenimento a livello nazionale (aree rosse, arancioni e gialle) con relativi metadata.

## 2020-12-20

- Modifica: aggiornato shape file con le nuove misure di contenimento a livello nazionale (aree rosse, arancioni e gialle) con relativi metadata.

## 2020-12-13

- Modifica: aggiornato shape file con le nuove misure di contenimento a livello nazionale (aree rosse, arancioni e gialle) con relativi metadata.

## 2020-12-09
- Aggiunta: "Ingressi in terapia intensiva"

## 2020-12-06

- Modifica: aggiornato shape file con le nuove misure di contenimento a livello nazionale (aree rosse, arancioni e gialle) con relativi metadata.

## 2020-12-03

- I dati caso da sospetto diagnostico e casi da screening non più erogati

## 2020-12-01

- Aggiunta: nuovo shape file con le nuove misure di contenimento a livello nazionale (aree rosse, arancioni e gialle) con relativi metadata.

## 2020-06-29

- Modifica: nuovo dataset che aggiunge i dati "casi_da_sospetto_diagnostico" e "casi_da_screening", i campi note_it e note_en vengono rimossi includendo un solo campo "note", in dati Province aggiunto il valore "Fuori Regione / Provincia Autonoma", tutti i dati storici sono stati allineati e fino al 31/07 viene tenuto un repository legacy con i vecchi dataset nella directory "legacy"

## 2020-05-18

- Aggiunta: aggiornamento al 18/5/2020 shape file e relativi metadati con misure di contenimento a livello nazionale a seguito del DPCM 17/5/2020.

## 2020-05-16

- Cambio codice_regione P.A. Bolzano e P.A. Trento: da 04 a 21 per P.A. Bolzano e da 04 a 22 per P.A. Trento (codice provincia)

## 2020-05-06

- Aggiunta: aggiornamento al 03/05/2020 shape file e relativi metadata con misure di contenimento a livello subregionale (province, comuni e frazioni).

## 2020-05-04

- Aggiunta: aggiornamento al 4/5/2020 shape file e relativi metadati con misure di contenimento a livello nazionale a seguito del DPCM 26/4/2020.

## 2020-04-27

- Aggiunta: aggiornamento al 26/4/2020 shape file e relativi metadata con misure di contenimento a livello subregionale (province, comuni e frazioni).

## 2020-04-23

- Aggiunta: metadati del nuovo dataset contratti dpc forniture (contratti e pagamenti) in formato DCAT-AP-IT
- Integrato README con specifiche per il data model dei dataset aree (nazionali e subregionali)

## 2020-04-21

- Aggiunta: nuovo shape file con misure di contenimento a livello subregionale (province, comuni e frazioni) con relativi metadata.

## 2020-04-20

- Aggiunta: "casi_testati", totale dei soggetti sottoposti al test dal 19/04/2020

## 2020-03-30

- Modifica: "totale_attualmente_positivi" rinominato in "totale_positivi" (ricoverati_con_sintomi + terapia_intensiva + isolamento domiciliare) in "dati_regioni" e "dati_andamento_nazionale"
- Modifica: "nuovi_attualmente_positivi" rinominato in "variazione_totale_positivi" (totale_attualmente positivi giorno corrente - totale_attualmente positivi giorno precedente) in "dati_regioni" e "dati_andamento_nazionale"
- Aggiunta: "nuovi_positivi" (totale_casi giorno corrente - totale_casi giorno precedente) in "dati_regioni" e "dati_andamento_nazionale"
- Modifica: Regione "Emilia Romagna" rinominato in "Emilia-Romagna" in "dati-regioni" e "dati-province" ("denominazione_regione")

## 2020-03-25

- Data nel formato ISO8601 UTC
- Aggiunta: "Note" in "dati-regioni", "dati-province" e "dati-andamento-nazionale"
- Aggiunta: dataset "note"

## 2020-03-19

- Aggiunti ultimi dati (latest) csv, nelle rispettive directory, per andamento nazionale (dpc-covid19-ita-andamento-nazionale-latest.csv), regioni (dpc-covid19-ita-regioni-latest.csv) e province (dpc-covid19-ita-province-latest.csv)
- Aggiunti ultimi dati (latest) json, nella directory dati-json, per andamento nazionale (dpc-covid19-ita-andamento-nazionale-latest.json), regioni (dpc-covid19-ita-regioni-latest.json) e province (dpc-covid19-ita-province-latest.json)

## 2020-03-12

- Aggiunto: Codice di Condotta in italiano (CODE_OF_CONDUCT.md) e in inglese (CODE_OF_CONDUCT_EN.md)
- Aggiunto: Changelog in italiano (CHANGELOG.md) e in inglese (CHANGELOG_EN.md)
- Aggiornate le Aree secondo il nuovo DPCM 11 Marzo 2020

## 2020-03-11

- Modifica: "Bolzano" e "Trento" rinominati in "P.A. Bolzano" e "P.A. Trento" in "dati-regioni e "dati-province" ("denominazione_regione")
- Modifica: Friuli V. G. rinominata in "dati-regioni e "dati-province" ("denominazione_regione") in "Friuli Venezia Giulia"

## 2020-03-10

- Aggiornate le Aree secondo il nuovo DPCM 9 Marzo 2020

## 2020-03-08

- Modifica: "dati-andamento-nazionale" riportando i totali dei dati delle Regioni
- Rimossa: directory "shape-aree-contenimento" e creata "aree" con "shp" e "geojson"
