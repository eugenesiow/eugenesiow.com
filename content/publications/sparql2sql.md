---
date: 2016-09-23T00:00:00-00:00
description: "Proceedings of the 15th International Semantic Web Conference"
tags: ["scene"]
type: "paper"
author: "Eugene Siow, Thanassis Tiropanis, Wendy Hall"
title: "SPARQL-to-SQL on Internet of Things Databases and Streams"
eprints: "https://eprints.soton.ac.uk/397863/"
rg: "https://www.researchgate.net/publication/318488887_SPARQL-to-SQL_on_internet_of_things_databases_and_streams"
---

To realise a semantic Web of Things, the challenge of achieving efficient Resource Description Format (RDF) storage and SPARQL query performance on Internet of Things (IoT) devices with limited resources has to be addressed. State-of-the-art SPARQL-to-SQL engines have been shown to outperform RDF stores on some benchmarks. In this paper, we describe an optimisation to the SPARQL-to-SQL approach, based on a study of time-series IoT data structures, that employs metadata abstraction and efficient translation by reusing existing SPARQL engines to produce Linked Data ‘just-in-time’. We evaluate our approach against RDF stores, state-of-the-art SPARQL-to-SQL engines and streaming SPARQL engines, in the context of IoT data and scenarios. We show that storage efficiency, with succinct row storage, and query performance can be improved from 2 times to 3 orders of magnitude.

### Publication Meta Information

In _Proceedings of the [15th International Semantic Web Conference](http://iswc2016.semanticweb.org/)_ held in Kobe, Japan
DOI: [10.1007 /978-3-319-46523-4_31](https://doi.org/10.1007/978-3-319-46523-4_31)

### Slides

<div style="width:480px;">
{{< speakerdeck2 c5b0e440498b4ef797963c129b37d8d0 >}}
</div>

### Webcast

{{< figure src="/img/videolecture1.png" title="Webcast of ISWC2016 talk" link="http://videolectures.net/iswc2016_siow_databases_streams/">}}

### Source Code

- [sparql2sql](https://github.com/eugenesiow/sparql2sql)
- [sparql2stream](https://github.com/eugenesiow/sparql2stream)