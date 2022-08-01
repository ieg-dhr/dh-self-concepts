# dh-self-concepts
Data and scripts for analysing self-concepts of Digital Humanities Centers

## sources | heuristic
- centerNet, https://dhcenternet.org/
- eadh, List of Digital Humanities Centres, https://eadh.org/education/digital-humanities-centres
- Wikipedia, Digital Humanities Center Category, https://en.wikipedia.org/wiki/Category:Digital_Humanities_Centers
- Web searches
  - "Digital Humanities" AND (Center OR Centre)
  - "Digital Humanities" AND (Center OR Centre) AND (goals OR values)
  - "Digital Humanities" AND (Center OR Centre) AND ("mission statement" OR "self concept" OR "charter")
- DACH+LUX:
  - Digital Humanities Course Registry, https://dhcr.clarin-dariah.eu/
  - "Digital Humanities" AND "Zentrum"

- list of all dh centers from sources: [data/dhcenter-sources.csv](data/dhcenter-sources.csv)

## data
- index of selected dh centers: [data/dhcenter-index.csv](data/dhcenter-index.csv)
- subset 1: list of statements used in Text Mining / Topic Modelling corpus: [data/dhcenter-concepts-TM-EN.csv](data/dhcenter-concepts-TM-EN.csv)
- subset 2: list of annotated statements DACHLUX (Germany, Austria, Switzerland, Luxembourg): [data/dhcenter-concepts-DACH.csv](data/dhcenter-concepts-DACH.csv)

## stats
### languages
| languages |    |       |
|----------|----|-------|
| DE       | 9  | 10,3% |
| EN       | 78 | 89,7% |
### institutions
| institutions   |    |     |
|----------------|----|-----|
| University     | 80 | 92% |
| non-university | 7  | 8%  |
### text size
| characters      |      |
|-----------------|------|
| less than 1000  | 12   |
| 1000 - 2500     | 41   |
| 2500 - 5000     | 26   |
| 5000 - 10000    | 6    |
| more than 10000 | 2    |
Median: 2107
### statement titles
| normalized_statement_names |    |     |
|----------------------------|----|-----|
| About                      | 28 | 32% |
| Mission                    | 30 | 34% |
| Values                     | 5  | 6%  |
| Vision                     | 5  | 6%  |
| Profile                    | 3  | 3%  |
| Other                      | 4  | 5%  |
| none                       | 9  | 10% |
### global distribution
| countries |    |
|-----------|----|
| USA       | 35 |
| DEU       | 14 |
| GBR       | 6  |
| CAN       | 5  |
| ITA       | 4  |
| AUT       | 3  |
| AUS       | 3  |
| RUS       | 2  |
| NLD       | 2  |
| CHE       | 2  |
| PRT       | 1  |
| POL       | 1  |
| NOR       | 1  |
| NGA       | 1  |
| LUX       | 1  |
| IND       | 1  |
| HUN       | 1  |
| FRA       | 1  |
| ESP       | 1  |
| DNK       | 1  |
| BEL       | 1  |
