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

## data
- list of all dh centers from sources: [data/dhcenter-sources.csv](data/dhcenter-sources.csv)
- index of selected dh centers: [data/dhcenter-index.csv](data/dhcenter-index.csv)
- subset 1: list of statements used in Text Mining / Topic Modelling corpus: [data/dhcenter-concepts-TM-EN.csv](data/dhcenter-concepts-TM-EN.csv)
- subset 2: list of annotated statements DACHLUX (Germany, Austria, Switzerland, Luxembourg): [data/dhcenter-concepts-DACH.csv](data/dhcenter-concepts-DACH.csv)

## analysis
- statistics: [stats.md](stats.md)
- topic modelling: [topics.md](topics.md)
