---
date: 2016-09-23T00:00:00-00:00
description: "Proceedings of the 15th International Semantic Web Conference (Poster and Demo Track)"
tags: ["sparql", "analytics", "rsp", "iot", "query translation", "linked data"]
type: "paper"
author: "Eugene Siow, Thanassis Tiropanis, Wendy Hall"
title: "PIOTRe: Personal Internet of Things Repository"
eprints: "https://eprints.soton.ac.uk/399327/"
rg: "https://www.researchgate.net/publication/308795472_PIOTRe_Personal_Internet_of_Things_Repository"
other: "http://ceur-ws.org/Vol-1690/paper20.pdf"
---

### Abstract

Resource-constrained Internet of Things (IoT) devices like Raspberry Pis', with specific performance optimisation, can serve as interoperable personal Linked Data repositories for IoT applications. In this demo paper we describe PIOTRe, a personal datastore that utilises our sparql2sql query translation technology on Pis' to process, store and publish IoT time-series historical data and streams. We demonstrate with PIOTRe in a smart home scenario: a real-time dashboard that utilises RDF stream processing, a set of descriptive analytics visualisations on historical data, a framework for registering stream queries within a local network and a means of sharing metadata globally with HyperCat and Web Observatories.

### Publication Meta Information

In _Proceedings of the [15th International Semantic Web Conference](http://iswc2016.semanticweb.org/) (Poster and Demo Track)_ held in Kobe, Japan
CEUR Workshop Proceedings: [Volume 1690](http://ceur-ws.org/Vol-1690/)

### Slides

<div style="width:480px;">
{{< speakerdeck2 345af45afc2f4bd29be7c0c01beeb2a7 >}}
</div>

### Applications on PIOTRe

[PiSmartHome](https://github.com/eugenesiow/ldanalytics-PiSmartHome) is an application that uses the queries from the Smart Home Analytics Benchmark within a web-based interface for descriptive and diagnostic analytics. It uses D3.js to visualise over time temperature and energy usage as per the benchmark queries. Translation from SPARQL to SQL is performed using the sparql2sql-server. 
<div style="width:480px;">
{{< youtube g8FLr974v9o >}}
</div>

[IoTFreeboard](https://github.com/eugenesiow/iotwo) is an application that serves as a customaisable dashboard running on PIOTRe for stream processing on incoming data from smart home sensors.

<div style="width:480px;">
{{< youtube oH0iSWTmKUg >}}
</div>

### Source Code

- [PIOTRe-web](https://github.com/eugenesiow/piotre-web)
- [PIOTRe](https://github.com/eugenesiow/piotre)