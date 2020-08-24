# Covid-19 Data - Italy

## National Trend

Official Italian Covid-19 data provided by "Dipartimento della Protezione Civile" and Italian Ministry of Health



# Metadata

## Data Source

- [Official repository](https://github.com/pcm-dpc/COVID-19) of the "Presidenza del Consiglio dei Ministri" and "Dipartimento della Protezione Civile"



## Data Update

- COVID-19 Data Italy: everyday at 18:00 (Italian Time)



## Data Format

**Directory:**  dati-andamento-nazionale<br>
**File with total data:** dpc-covid19-ita-andamento-nazionale.csv<br>



| Field name                  | Description                            | Format                       | Example             |
|-----------------------------|----------------------------------------|-------------------------------|---------------------|
| **data**                            | Date of notification                   | YYYY-MM-DD HH:MM:SS (ISO 8601) Italian Time | 2020-03-05 12:15:45 |
| **stato**                           | Country of reference                   | XYZ (ISO 3166-1 alpha-3)      | ITA                 |
| **ricoverati_con_sintomi**          | Hospitalized patients with symptoms    | Number                        | 3                   |
| **terapia_intensiva**               | Intensive Care                         | Number                        | 3                   |
| **totale_ospedalizzati**            | Total hospitalized patients            | Number                        | 3                   |
| **isolamento_domiciliare**          | Home confinement                       | Number                        | 3                   |
| **totale_positivi**                 | Total amount of current positive cases (Hospitalised patients + Home confinement)  | Number                        | 3                   |
| **variazione_totale_positivi**      | Daily variation of current positive cases (totale_positivi current day - totale_positivi previous day)  | Number                        | 3                   |
| **nuovi_positivi**                  | Daily variation of total positive cases (totale_casi current day - totale_casi previous day)  | Number                        | 3                   |
| **dimessi_guariti**                 | Recovered                              | Number                        | 3                   |
| **deceduti**                        | Deceased                                  | Number                        | 3                   |
| **casi_da_sospetto_diagnostico**    | Positive cases emerged from clinical activity                                  | Number                        | 3                   |
| **casi_da_screening**               | Positive cases emerging from surveys and tests, planned at national or regional level                                  | Number                        | 3                   |
| **totale_casi**                     | Total amount of positive cases         | Number                        | 3                   |
| **tamponi**                         | Tests performed                        | Number                        | 3                   |
| **casi_testati**                    | Total number of people tested                        | Number                        | 3                   |
| **note**                            | Notes in Italian language                       | Text                        | Lorem ipsum...                   |




### License
**License:** [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/deed.it) - [View license](https://github.com/pcm-dpc/COVID-19/blob/master/LICENSE)<br>
Schema metadata RNDT: [dati](https://geodati.gov.it/geoportale/visualizzazione-metadati/scheda-metadati/?uuid=PCM%3ACOVID-19%3A05032020%3A093000) - [aree](https://geodati.gov.it/geoportale/visualizzazione-metadati/scheda-metadati/?uuid=PCM%3A000086%3A20200306%3A110700)<br>
Theme of the dataset: [Human health and safety (Inspire)](http://inspire.ec.europa.eu/theme/hh)<br>
Category ISO 19115: Health<br>
Data Provided by Ministry of Health<br>
Data elaboration and management by "Dipartimento della Protezione Civile"