---
title: About
layout: default

navigation_weight: 1
---

The videos of this tutorial are available on [YouTube](https://www.youtube.com/playlist?list=PLSsFTlM4Tf905v1-mSsm1elWXOjDcANYP).

# Abstract
The success of Semantic Web technology has boosted the publication of Knowledge Graphs, and several technologies to access them have become available covering different spots in the spectrum of expressivity: from the highly expressive SPARQL to the controlled access of Linked Data APIs, with GraphQL in between. Many of these technologies have reached industry-grade maturity. Finding the trade-offs between them is often difficult in the daily work of developers, interested in quick API deployment and easy data ingestion. In this tutorial, we will cover this in-between technology space, with the main goal of providing strategies and tools for publishing Web APIs that ensure the easy consumption of data coming from SPARQL endpoints. Together with an overview of state-of-art technologies, the tutorial focuses on two novel technologies: [SPARQL Transformer](https://github.com/D2KLab/sparql-transformer), which allows to get a more compact JSON structure for SPARQL results, decreasing the effort required by developers in interfacing JavaScript and Python applications; and [grlc](http://grlc.io/), an automatic way of building APIs on top of SPARQL endpoints by sharing queries on collaborative platforms. Moreover, we will present recent developments to combine the two, offering a complete resource for developers and researchers. Hands-on sessions will be proposed to internalize those concepts with practice.

# Motivation

A crucial factor in the adoption of the Web of Data consists in the possibility of obtaining access to the published resources. However, this access is not always simple, constrained by languages and templates that are sub-optimal for application development. As a consequence, recent initiatives such as [EasierRDF](https://github.com/w3c/EasierRDF) are strongly pushing the proposal of new solutions for making Semantic data on the Web developer friendly.

The goal of this tutorial is to give participants sufficient knowledge for:
understanding the landscape of mature, production-ready and industry-grade technological solutions for publishing Web APIs on top of RDF datasets;
republishing RDF data through Web API, for increasing the use and adoption of RDF datasets, even outside the Semantic Web community;
retrieving data from SPARQL endpoints in a more practical format to be used in small proofs-of-content, living software or interactive notebooks (i.e. Jupyter), minimising the effort for accessing data.

# Tutorial Structure

This half-day tutorial will be decomposed into two parts, consisting each of slides and hands-on exercises:
The first part will focus on data reshaping and merging. After summarising the main issues related to RDF data consumption by developers, we will introduce different solutions coming from the literature, such as [RDFJS](https://rdf.js.org/data-model-spec/),  [LDflex](https://github.com/LDflex/LDflex), GraphQL-based strategies and others. We will then explain the fundamentals of [SPARQL Transformer](https://github.com/D2KLab/sparql-transformer) and present in-depth details about its querying and templating features, its parsing capabilities, and its merging strategy, giving to the audience a complete picture of the library. Example of usage in JavaScript and Python will be shown. Some hands-on exercises will be proposed in order to make the public play with the application, making use of the SPARQL Transformer playground.
The second part will cover the publication of Web API on top of SPARQL endpoints. Different specification – e.g. [smartAPI](https://smart-api.info/), [Linked Data API](https://github.com/UKGovLD/linked-data-api) specification, [OpenAPI](https://www.openapis.org/) – and services – e.g. [BASIL](https://github.com/the-open-university/basil) – for describing RESTful APIs will be introduced to the audience . Then, we will show the [grlc](grlc.io) application and explain the different part of the framework: the GitHub repository, the self-generated UI and the automatically exposed API. The public will then publish their own API in the second hands-on session. Finally, we will introduce the integration of SPARQL Transformer in grlc and we will conclude the tutorial with a summary of the covered topics.

# Schedule

This tutorial will take place on November 2nd, 2020 on Zoom. The participants will receive the link from the conference organisers.

The schedule is the following, in GMT (Greenwich) Timezone :

| 9.00 - 9.10  	  | Introduction                               	|
| 9.10 - 9.30   	| Overview: libraries for accessing RDF data 	|
| 9.30 - 10.00  	| SPARQL Transformer                         	|
| 10.00 - 10.20 	| SPARQL Transformer _hands-on_                	|
| **10.20 - 10.40** 	| **break**                               	|
| 10.40 - 11.00 	| Overview: Web API for RDF                  	|
| 11.00 - 11.20 	| grlc                                       	|
| 11.20 - 11.40 	| grlc _hands-on_                              	|
| 11.40 - 11.50 	| SPARQL Transformer and grlc                	|
| 11.50 - 12.00 	| Discussion and closing                     	|


<a target="_blank" href="https://calendar.google.com/event?action=TEMPLATE&amp;tmeid=Xzg1MmplaDFpNzBzNGNiOW42b29rYWI5azg5MTQ0YjlwOGwzMzBiOW04b3EzY2hpMzhjcGthaDFoNjQgajFwcWdpcm5hcWthaDlocXBjcWVxbDJscTBAZw&amp;tmsrc=j1pqgirnaqkah9hqpcqeql2lq0%40group.calendar.google.com"><img border="0" src="https://www.google.com/calendar/images/ext/gc_button1_it.gif"></a>

# Intended Audience

This tutorial is directed to anyone who works with RDF data and SPARQL, and in particular is interested in providing quick access to the data and/or Web APIs on top of them. We assume that most participants will be familiar with basic Semantic Web technologies (RDF, SPARQL). For the hands-on session, the participants are expected to bring a laptop with a web browser installed.

The tutorial aims to provide them a general know-how and practical information for developing Web APIs on top of SPARQL endpoints.

# References

1. Pasquale Lisena, Albert Meroño-Peñuela, Tobias Kuhn and Raphaël Troncy. **[Easy Web API Development with SPARQL Transformer](http://www.eurecom.fr/en/publication/5927/download/data-publi-5927.pdf).** In *18th International Semantic Web Conference (ISWC)*, Auckland, New Zealand, October 26-30, 2019.
1. Albert Meroño-Peñuela, Rinke Hoekstra. **[`grlc` Makes GitHub Taste Like Linked Data APIs](http://ceur-ws.org/Vol-1629/paper7.pdf).** In *The Semantic Web – ESWC 2016 Satellite Events*, Heraklion, Crete, Greece, May 29 – June 2, 2016.
