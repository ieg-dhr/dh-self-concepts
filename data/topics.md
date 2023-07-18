# dataset Digital Humanities Centers Self-Concepts
data and scripts for analysing the public self-concepts of selected digital humanities centres

## topic modelling
![Topics in self-concepts](/figures/dh-centers-topics.png)

- Words in Topics: [data/words_in_topics.txt](data/words_in_topics.txt)
- Topics in Self-Concepts: [data/dhcenter-concepts-topics.csv](data/dhcenter-concepts-topics.csv)

## text mining
### Top 40 words in corpus
| word                   | pct   |
|------------------------|-------|
| research               | 92,31 |
| project                | 80,77 |
| humanity               | 79,49 |
| digital                | 78,21 |
| center                 | 67,95 |
| university             | 65,38 |
| support                | 62,82 |
| work                   | 61,54 |
| technology             | 61,54 |
| student                | 58,97 |
| new                    | 56,41 |
| method                 | 56,41 |
| science                | 56,41 |
| collaboration          | 52,56 |
| mission                | 51,28 |
| community              | 50,00 |
| faculty                | 48,72 |
| development            | 48,72 |
| study                  | 46,15 |
| tool                   | 46,15 |
| researcher             | 44,87 |
| history                | 44,87 |
| social                 | 44,87 |
| include                | 43,59 |
| cultural               | 43,59 |
| scholarship            | 43,59 |
| provide                | 42,31 |
| innovative             | 42,31 |
| develop                | 42,31 |
| art                    | 41,03 |
| create                 | 41,03 |

### keywords in texts
**appearance**
| topic         | keywords                                     | pct   |
|---------------|----------------------------------------------|-------|
| collaboration | ['collaborat', 'interdisciplin', 'together'] | 82.05 |
| openness      | ['open', 'public', 'access']                 | 66.67 |
| experiment    | ['experiment', 'fail', 'explor']             | 41.03 |
| diversity     | ['divers', 'inclusi', 'equal']               | 38.46 |
| collegiality  | ['collegial', 'welcom', 'credit']            | 19.23 |                                                                                               

**texts**
| topic         | texts                                                                                                                                                                                                                                                      |
|---------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| collaboration | {1, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 17, 20, 21, 22, 23, 24, 25, 26, 28, 29, 30, 31, 33, 34, 35, 36, 38, 39, 40, 41, 42, 43, 44, 48, 49, 50, 52, 53, 54, 56, 57, 58, 60, 61, 62, 63, 65, 67, 68, 72, 73, 74, 75, 76, 77, 78, 79, 81, 83, 84, 85, 86, 88} |
| openness      | {1, 6, 7, 8, 9, 10, 11, 12, 13, 14, 21, 22, 23, 24, 26, 27, 28, 29, 32, 33, 34, 35, 36, 39, 40, 41, 43, 44, 46, 48, 49, 50, 53, 60, 61, 62, 63, 64, 65, 67, 68, 70, 71, 72, 73, 75, 76, 79, 83, 84, 85, 88}                                                |
| experiment    | {1, 7, 8, 10, 14, 17, 19, 24, 27, 29, 31, 33, 34, 35, 37, 38, 39, 43, 44, 48, 49, 50, 54, 60, 65, 66, 67, 72, 74, 75, 78, 84}                                                                                                                              |
| diversity     | {7, 9, 10, 13, 14, 17, 22, 23, 26, 29, 32, 33, 34, 39, 40, 41, 43, 44, 46, 47, 48, 54, 70, 71, 72, 75, 76, 78, 84, 85}                                                                                                                                     |
| collegiality  | {33, 34, 67, 39, 7, 42, 75, 76, 43, 14, 44, 49, 21, 25, 29}                                                                                                                                                                                             |
