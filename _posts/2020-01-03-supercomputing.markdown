---
layout: post
title:  "Supercomputing Conference"
date:   2020-01-03 11:31:02 +0200
categories: jekyll update
---

### Introduction
The Supercomputing conference in America is the annual event on High Performance Computing. It started in 1988. Next to the conference with invited talks, panel discussion paper presentations and Birds of a feather sessions, a big exhibition takes place. All the vendors in the HPC field are present. And at the booths of the big vendors presentations of these vendors take place. Thus creating a double program and lots of choices.

And for even more social networking lots of vendors have drinks and/or dinner sessions in different hotels. And the opportunity to have special presentations with the vendor at the hotel locations.

Although the conference is attended by 10.000 to 15.000 people it was never crowded. The exhibition floor is around 50.000 square meters. And the plenary hall and the rooms for the parallel sessions were big enough to handle the attendees.

### SCInet
The conference has its own network called SCInet. All big vendors contribute to this network. And it has big pipelines to the Internet via [Internet2] (https://www.internet2.edu/), [ESnet] (http://es.net/) and [Starlight] (http://www.startap.net/starlight/). The network is used to test big bandwidth in many ways. This year there was a focus on long range 400Gbs connections. And of course Eduroam is used in the WiFi network on the Exhition and the conference rooms.

There was also an historic display of 30 year SCInet. From all implemented SCInet’s (so from 1988) a poster of the network layout was on display. A beautiful historic timeline of growth in the network complexity at Super Computing.


![SCInet](https://assets.digitalocean.com/articles/alligator/boo.svg "SCInet")

### 2019
This year the conference was in Denver, the one mile high city. Being one mile above sea level also meant dry air and the problem high level sickness. So drinking lots of water. Happily Cray sponsored a handy water bottle and AMD the cool water tanks.

### Exihibition
No inspirational innovations were on the show this year. The compute companies showed their compute servers on which no real innovation takes place. They all are modular and flexible in their configuration. Mellanox could now show its previously announced 200G Infiniband and announced its 400G and 800G (1T). Storage was silently present. There was the feeling that next year some new things will submerge on the storage environments.

### Trends
#### Cooling

Last year it was clear that liquid cooling is the thing to do. Now it was clear that there is not really anything new going on. Liquid still is the way to go. And yes you can do something with active door cooling, but in essence you should do complete liquid cooling.  All server suppliers showed their liquid cooled hardware on the floor.

#### Quantum Computing/Internet

Last year quantum computing was present in lots of discussions at the conference and IBM showed it on the floor. This year it was hardly visible. Only a few sessions during the conference and nothing on the floor.

#### Cloud

A consolidation in the discussions on cloud and HPC was visible. No longer the two opposites on-premise or cloud, but look at what fits the best for your situation. Of course look at your own workloads for the most effective choice for your enterprise. Cloud is used for peak loads.

#### Power

Now all server vendors have incorporated liquid cooling within their servers. There is choice for cooling all elements or only cool the CPU’s and GPU’s.

For those not having the infrastructure (yet) to handle liquid cooling, extra cooling can be done with rack doors. The vendors of rack door cooling were the only vendors of cooling showing on the exhibition.

### Meetings
#### Dutch Evening

On Sunday SURF organizes and sponsors (together with ATOS)  a dinner for all Dutch people attending the conference. A group of around 50 people attended this year’s dinner. Mostly from the different parts of SURF, but also Universities (RUG, UvA) and PRACE.

#### Mellanox dinner

As already mentioned Mellanox presented its 200G Infiniband switches. At their dinner the take-over by NVDIA was presented with a presentation of both CEO’s. Although both companies may look a little bit similar (both are monopolists in a special sector) their CEO are completely different in style. NVIDIA being very flamboyant and Mellanox very serious.

#### Supplier meeting

This year I had a meeting with HPE. 5 People from HPE turned up to tell me about the different roadmaps of the HPE products. I could have the meeting in my room as I was upgraded to the boardroom.

![Boardroom](https://assets.digitalocean.com/articles/alligator/boo.svg "Boardroom")

### HPC Considerations
- Data centric or Compute centric (the first has the future)
- Lustre storage is used a lot for HPC workloads
- What is the network topology of the nodes (traditional Spine-Leave or Mellanox Dragonfly)
- Bright is a cluster manager which can handle both SLURM and Kubernetes workloads
- No passive door cooling (uses server airflow)

The HPC clusters at the Universities in America don’t do sharing of resources. The central cluster is divided in parts per Faculty. Sharing the resources (which they call scavenging) is not done yet. Some Universities are starting to allow scavenging. The main reason for allowing is better use of the cluster.

As there is no sharing, there are also no best practices on how the sharing is regulated. So no governance examples we can use for the TU Delft HPC.

![KAFKA](https://assets.digitalocean.com/articles/alligator/boo.svg "KAFKA")


### Acknowledgements
All photos by Lolke Boonstra, licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license.
