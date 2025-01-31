---
title: GTFS Sweden 3 (beta)
layout: "single"
weight: 35
---

GTFS Sweden 3 is a high quality GTFS feed containing most of the public transport data of Sweden. 

### What does this dataset contain?

This dataset contains high quality detailed data, both static and real-time, in the GTFS format.  
This dataset is an aggregated dataset of all the different datasets in the [GTFS Regional API](/api/trafiklab-apis/gtfs-regional/).
There is a single GTFS feed for static data. The realtime feeds are, for performance reasons, split up by specific regions or operators. 

At the moment this dataset does not contain all of the public transport data of Sweden.
If that is what you are looking for we recommend [GTFS Sverige 2](/api/trafiklab-apis/gtfs-sverige-2/), which is less detailed but does contain all of the public transport data of Sweden.

### Data format

The data is in the GTFS format, and makes use of the GTFS Extensions. Realtime data follows the GTFS-Realtime
(GTFS-RT) standard, and is stored in the protobuf format.

This data is also available in the NeTEx format. For the NeTEx format, see the 
[NeTEx Sweden API](/api/trafiklab-apis/netex-sweden/).

### How often is this dataset updated?

The static data in this dataset is updated on a daily basis. The real-time data receives multiple updates per minute,
see [realtime data](realtime) for more information.

### Which operators are covered by this dataset?

{{% include "/headless/stip-data-availability.md" %}}

### How often does the data format changes? Do breaking changes happen?

Both the static and realtime data feeds are in beta. We may make breaking changes until these feeds are considered as stable.