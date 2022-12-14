# dh-self-concepts
data and scripts for analysing self-concepts of Digital Humanities Centers\
dataset and documentation for DHd2023 application

## sources | heuristic
- centerNet, https://dhcenternet.org/
- EADH, List of Digital Humanities Centres, https://eadh.org/education/digital-humanities-centres
- Wikipedia, Digital Humanities Center Category, https://en.wikipedia.org/wiki/Category:Digital_Humanities_Centers
- Web search:
  - "Digital Humanities" AND (Center OR Centre)
  - "Digital Humanities" AND (Center OR Centre) AND (goals OR values)
  - "Digital Humanities" AND (Center OR Centre) AND ("mission statement" OR "self concept" OR "charter")
- Web search DACHL:
  - Digital Humanities Course Registry, https://dhcr.clarin-dariah.eu/
  - "Digital Humanities" AND "Zentrum"

## data
- list of all dh centers from sources: [data/dhcenter-sources.csv](data/dhcenter-sources.csv)
- index of selected dh centers: [data/dhcenter-index.csv](data/dhcenter-index.csv)
- subset A: list of statements used in Text Mining / Topic Modelling corpus: [data/dhcenter-concepts-TM-EN.csv](data/dhcenter-concepts-TM-EN.csv)
- subset B: list of annotated statements DACHL (Germany, Austria, Switzerland, Luxembourg): [data/dhcenter-concepts-DACHL.csv](data/dhcenter-concepts-DACHL.csv)

## analysis
- metadata | statistics: [stats.md](stats.md)
- text mining | topic modelling: [topics.md](topics.md)
