---
date: 2017-12-20T00:00:00-00:00
tags: ["iot","linked data","fog computing","social web", "rsp"]
type: "talk"
subtype: "thesis defence"
author: "Eugene Siow"
title: "Efficient Querying for Analytics on Internet of Things Databases and Streams"
description: "University of Southampton, Southampton, UK"
---

### Abstract

This thesis is concerned with the development of efficient methods for managing contextualised time-series data and event streams produced by the Internet of Things (IoT) so that both historical and real-time information can be utilised to generate value within analytical applications.

From a database systems perspective, two conflicting challenges motivate this research, interoperability and performance. IoT applications integrating streams of time-series data from heterogeneous IoT agents require a level of semantic interoperability. This semantic interoperability can be achieved with a common flexible data model that represents both metadata and data. However, applications might also have time constraints or require processing to be performed on large volumes of historical and streaming time-series data, possibly on resource-constrained platforms, without significant delay. Obtaining good performance is complicated by the complexity of the  data model.

In the first part of the thesis, a graph data model is shown to support the representation of metadata and data that various research and standard bodies are working towards, while the `volume' of IoT data is shown to exhibit flat, wide and numerical characteristics. A three step abstraction is defined to reconcile queries on the graph model with efficient underlying storage by query translation. This storage is iteratively improved to exploit the character of time-series IoT data, achieving orders of magnitude performance improvement over state-of-the-art commercial, open-source and research databases. 

The second part of the thesis extends Map-Match-Operate to efficiently process real-time IoT streams continuously and proposes an infrastructure for fog computing that shows how resource-constrained platforms close to source IoT agents can co-operatively orchestrate stream processing. The main contributions of this thesis are therefore, 

- a novel interoperable and performant abstraction for querying IoT graph representations,
- high performance historical, streaming and fog computing time-series database implementations and 
- analytical applications and platforms built on Map-Match-Operate that act as practical models for the socio-technical development of the IoT.

### Slides

<div class="figure-frame">
{{< speakerdeck2 541bf1f15e4843c0a1865933a3a54bc0 >}}
</div>

