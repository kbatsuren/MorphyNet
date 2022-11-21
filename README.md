# MorphyNet

MorphyNet is a large-scale, high-quality multilingual database of derivational and inflectional morphology. Currently, MorphyNet contains 13.5M inflectional and 696K derivational instances of 15 languages. Most importantly, we have morpheme segmentations.   

## Inflectional morphology:

|language| lemma |	inflected form |  morphological features | morpheme segmentation|
| --- | --- |	--- | --- | --- |
|hun|holmi| holmikat| N \| PL \| ACC	| holmi \| k \| at |
|rus|оборвать| оборвались | V;PFV \| IND;PST;FIN \| PL \| MID | оборвать \| л \| и \| сь |
|cat|ossificar|ossificaven| V \| IND;PST;IPFV \| 3;PL | ossificar \| ava \| en|
|spa|abrir|abrámonos| V \| IMP;POS;1;PL \| ACC;PRO;1;PL	| abrir \| amos \| nos|

## Derivational morphology:

| Language | source word | target word | source POS | target POS | morpheme | type   |
|----------|-------------|-------------|------------|------------|-------|--------|
| eng      | slow        | slowly      | J          | R          | ly    | suffix |
| eng      | describe    | misdescribe | V          | V          | mis   | prefix |
| mon      | сурах       | сурагч      | V          | N          | гч    | suffix |


## Statistics:

|    |                |  infl.  |    infl.   |   infl.   |  deri.  |   deri. |   deri.   |            |
|----|----------------|:-------:|:----------:|:---------:|:-------:|--------:|:---------:|-----------:|
|    | Languages      |  words  |    forms   | morphemes |  words  |  forms  | morphemes |    total   |
| 1  | Finnish        |    81,729 |  3,708,296 |     1,139 |  18,142 |  36,843 |       446 |  3,745,139 |
| 2  | Serbo-Croatian |    68,757 |  1,760,095 |       263 |   8,553 |   4,916 |       429 |  1,765,011 |
| 3  | Italian        |    89,763 |    712,021 |       100 |  18,650 |  58,848 |       749 |    770,869 |
| 4  | Hungarian      |    38,067 |  1,016,819 |       428 |  14,566 |  28,177 |       832 |  1,044,996 |
| 5  | Russian        |    36,387 |  1,321,024 |       215 |  11,922 |  93,039 |       575 |  1,414,063 |
| 6  | Spanish        |    65,565 |  1,289,324 |        66 |   9,159 |  25,080 |       490 |  1,314,404 |
| 7  | French         |    52,711 |    453,229 |       118 |  12,473 |  72,952 |       636 |    526,181 |
| 8  | Portuguese     |    39,029 |    376,341 |       158 |   6,076 |  11,774 |       387 |    388,115 |
| 9  | Polish         |    36,940 |    663,545 |       251 |   6,518 |  58,711 |       405 |    722,256 |
| 10 | German         |    39,275 |    490,331 |       244 |   8,070 |  29,381 |       465 |    519,712 |
| 11 | Czech          |    33,348 |    816,956 |        92 |   4,875 |  32,336 |       318 |    849,292 |
| 12 | English        |   396,772 |    649,594 |         8 |  67,412 | 225,131 |     2,445 |    874,725 |
| 13 | Catalan        |    14,979 |    158,922 |        58 |   3,244 |   8,018 |       220 |    166,940 |
| 14 | Swedish        |    12,508 |    131,599 |        29 |   2,190 |   9,244 |       217 |    140,843 |
| 15 | Mongolian      |     2,085 |     14,592 |        35 |   1,410 |   1,629 |       229 |     16,221 |
|    |                | 1,007,915 | 13,562,688 |     3,204 | 193,260 | 696,079 |     8,843 | 14,258,767 |
## Source:
English Wiktionary <br />
French Wiktionary <br />
Russian Wiktionary <br />
Czech Wiktionary <br />
Hungarian Wiktionary <br />
Polish Wiktionary <br />
German Wiktioanry <br />
Italian Wiktioanry <br />
Catalan Wiktionary <br />
Finnish Wiktionary <br />
Portuguese Wiktionary <br />
Spanish Wiktionary <br />
Swedish Wiktionary <br />


## License: 
https://creativecommons.org/licenses/by-sa/3.0/



## Reference
Khuyagbaatar Batsuren, Gábor Bella, and Fausto Giunchiglia - MorphyNet: a Large Multilingual Database of Derivational and Inflectional Morphology
https://aclanthology.org/2021.sigmorphon-1.5/
