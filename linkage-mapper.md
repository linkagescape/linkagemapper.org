---
layout: page
title: Linkage Mapper
permalink: /
---

<img style="float: left; height: 267px; padding: 5px; border: 1px solid #ddd; border-radius: 4px;" src="../img/lm_logo.jpg" hspace="10">

Linkage Mapper supports regional wildlife habitat connectivity analyses. It consists of six tools that automate mapping and prioritization of wildlife habitat corridors. It is comprised of open source Python scripts, shared in an ArcGIS toolbox.

Extras: [Lab Excercise: Linkage Pathways, Pinchpoints, and Barriers ](downloads/LM_Lab_V2.zip)

<div style=" clear: both;margin-top:50px">

</div>
### Tools

A brief summary of the tools follow, with additional details [here](http://linkagemapper.org/linkage-mapper-tools):

- Linkage Pathways (originally known as “Linkage Mapper”) maps the linkages among “core areas” of habitat on a landscape. In those linkages it shows the relative value of each grid cell in providing connectivity. This allows users to identify which pathways encounter more or fewer features that facilitate or impede movement between core areas. This is pictured above.
- Climate Linkage Mapper gives additional options about which possible linkages are mapped or not, and fine tunes the routes of the linkages to more realistically follow climatic gradients.
- Barrier Mapper implements a new method for detecting important barriers to facilitate restoration planning.
- Pinchpoint Mapper uses [Circuitscape](http://www.circuitscape.org/) to identify pinch-points (a.k.a. bottlenecks or choke points) in corridors produced by Linkage Mapper.
- Centrality Mapper uses [Circuitscape](http://www.circuitscape.org/) to analyze core and corridor centrality in networks produced by Linkage Mapper. This can help prioritize important corridors.
- Linkage Priority estimates and maps the relative priority of each linkage based on the weighted combination of ten considerations, including climate change.

Please note: whatever tool you use, connectivity modeling involves a great deal of research, data compilation, GIS analyses, and careful interpretation of results. Defining areas to connect, parameterizing resistance models, and other modeling decisions you will need to make are not trivial. Before diving in, we strongly recommend that users first acquaint themselves with the process and challenges of connectivity modeling by consulting published resources. Good places to start include an [overview of habitat and corridor modeling on the Corridor Designer website](http://corridordesign.org/designing_corridors), the step-by-step guidance on connectivity assessments on the [Connecting Landscapes website](http://www.connectinglandscapes.org/), and references listed in the Linkage Mapper user guides. Need to create resistance or core area layers? Check out [Gnarly Landscape Utilities](http://www.circuitscape.org/gnarly-landscape-utilities) for an expert opinion approach to doing this.

Linkage Mapper is an open access project in active development by a [**dynamic team**](http://linkagemapper.org/about-the-team).

Please join the [Linkage Mapper User Group](https://groups.google.com/forum/?utm_source=digest&utm_medium=email/#!forum/linkage-mapper) for support and updates on new releases. You can contribute and comment on development by joining our [**Github Site and Group**](https://github.com/linkagescape/linkage-mapper), and you can post your final maps, or work in progress, at our shared [**Data Basin Gallery**](https://databasin.org/galleries/027492e42545494cae53ca1f61b46c17).

Please see the [**Linkage Mapper Tools** ](https://linkagemapper.org/linkage-mapper-tools/) page for further details and maps of each output.
