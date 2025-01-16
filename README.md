# Multi-CAST Cypriot Greek

## How to cite

If you use these data please cite
- the original source
  > Hadjidas, Harris & Vollmer, Maria. 2021. Multi-CAST Cypriot Greek. In Haig, Geoffrey & Schnell, Stefan (eds.), Multi-CAST: Multilingual corpus of annotated spoken texts. Version 2101. Bamberg: University of Bamberg. (multicast.aspra.uni-bamberg.de/#cypgreek) (date accessed)
- the derived dataset using the DOI of the [particular released version](../../releases/) you were using

![](cldf/media/image.jpg)

## Description


**Cypriot Greek** ([cypr1249](https://glottolog.org/resource/languoid/id/cypr1249)) is the variety of Greek spoken in Cyprus. The three texts in this corpus, all of which are traditional narratives, were originally recorded in the 1960s, and later compiled and published by Konstantinos Giangoullis as part of a book of traditional Cypriot tales ([Giangoullis 2009](Source#cldf:giangoullis2009)). The author of the text collection, Konstantinos Giangoullis, has kindly given his permission for the three texts in this corpus to be made freely available as part of Multi-CAST.

While unfortunately no audio recordings are available for this corpus, the texts appear to have been only minimally edited and reflect reasonably faithfully the spoken language used in traditional narratives. The texts were initially transliterated into the Roman alphabet and translated into English by a native speaker, Harris Hadjidas, who also conducted the first round of syntactic annotation. A second round of annotation was completed by Maria Vollmer under the supervision of Geoffrey Haig.

This dataset is licensed under a CC-BY-4.0 license

Available online at https://multicast.aspra.uni-bamberg.de/#cypgreek


```geojson
{
    "type": "FeatureCollection",
    "features": [
        {
            "type": "Feature",
            "geometry": {
                "type": "Point",
                "coordinates": [
                    32.978113,
                    34.924591
                ]
            }
        },
        {
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            27.978113,
                            39.924591
                        ],
                        [
                            37.978113,
                            39.924591
                        ],
                        [
                            37.978113,
                            29.924591
                        ],
                        [
                            27.978113,
                            29.924591
                        ],
                        [
                            27.978113,
                            39.924591
                        ]
                    ]
                ]
            }
        }
    ]
}
```



## Corpus counts

Only a small number of basic GRAID symbols are counted:

*Function symbols*
- ⟨0⟩ zero
- ⟨pro⟩ definite pronoun
- ⟨np⟩ full noun phrase
- ⟨other⟩ form not further specified

*Person/Animacy symbols*
- ⟨.1⟩ first person
- ⟨.2⟩ second person
- ⟨.h⟩ third person, human
- ⟨.d⟩ third person, anthropomorphic
- ø third person, non-human

*Function symbols*
- ⟨:s⟩ subject of an intransitive clause
- ⟨:a⟩ subject of a transitive clause
- ⟨:ncs⟩ non-canonical subject
- ⟨:p⟩ direct object
- ⟨:obl⟩ oblique argument
- ⟨:g⟩ goal argument
- ⟨:l⟩ locational argument
- ⟨:pred⟩ predicate
- ⟨:poss⟩ possessive
- ⟨:other⟩ function not further specified

Only basic categories are listed; categories represented by complex symbols with additional
specifiers (e.g. ⟨dem_pro⟩ ‘demonstrative pronoun’) have been subsumed under the more basic
category (e.g. ⟨pro⟩ ‘definite pronoun’). Please refer to the annotation notes for this corpus for
information on all annotated categories, including those not listed here.

| GRAID | ⟨:s⟩ | ⟨:a⟩ | ⟨:ncs⟩ | ⟨:p⟩ | ⟨:obl⟩ | ⟨:g⟩ | ⟨:l⟩ | ⟨:pred⟩ | ⟨:poss⟩ | ⟨:other⟩ | totals |
|:--------------|-------:|-------:|---------:|-------:|---------:|-------:|-------:|----------:|----------:|-----------:|---------:|
| **⟨0.1⟩** | 55 | 116 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 172 |
| **⟨0.2⟩** | 75 | 116 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 192 |
| **⟨0.h⟩** | 173 | 182 | 0 | 5 | 0 | 0 | 0 | 0 | 0 | 1 | 361 |
| **⟨0.d⟩** | 6 | 7 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 14 |
| **⟨0⟩** | 16 | 13 | 0 | 72 | 0 | 0 | 0 | 2 | 0 | 0 | 103 |
| **⟨pro.1⟩** | 9 | 13 | 0 | 10 | 13 | 20 | 0 | 0 | 99 | 3 | 167 |
| **⟨pro.2⟩** | 9 | 5 | 0 | 15 | 13 | 21 | 0 | 0 | 45 | 3 | 111 |
| **⟨pro.h⟩** | 5 | 2 | 0 | 54 | 20 | 57 | 1 | 1 | 55 | 6 | 201 |
| **⟨pro.d⟩** | 2 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 | 0 | 3 |
| **⟨pro⟩** | 2 | 0 | 0 | 59 | 1 | 1 | 0 | 0 | 0 | 1 | 64 |
| **⟨np.1⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨np.2⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨np.h⟩** | 50 | 28 | 0 | 38 | 17 | 19 | 0 | 11 | 29 | 4 | 196 |
| **⟨np.d⟩** | 14 | 1 | 0 | 2 | 0 | 0 | 0 | 0 | 0 | 20 | 37 |
| **⟨np⟩** | 24 | 9 | 0 | 218 | 43 | 50 | 15 | 18 | 15 | 83 | 475 |
| **⟨other.1⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.2⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.h⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.d⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other⟩** | 8 | 1 | 0 | 23 | 3 | 26 | 19 | 41 | 0 | 0 | 121 |
| | 448 | 493 | 0 | 498 | 110 | 194 | 35 | 73 | 244 | 122 | 2217 |


**Clause boundaries**

| GRAID | count |
|:-----------|--------:|
| **⟨##⟩** | 431 |
| **⟨#⟩** | 639 |
| **totals** | 1070 |



## Corpus metadata

- [Annotation notes](cldf/media/annotation-notes.pdf)
- [Metadata](cldf/media/metadata.pdf)
- [Translated texts](cldf/media/translated-texts.pdf)


## CLDF Datasets

The following CLDF datasets are available in [cldf](cldf):

- CLDF [TextCorpus](https://github.com/cldf/cldf/tree/master/modules/TextCorpus) at [cldf/TextCorpus-metadata.json](cldf/TextCorpus-metadata.json)