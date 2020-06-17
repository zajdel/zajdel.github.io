---
layout: page
title: Research
permalink: /research/
---

The term **bioelectricity** might conjure up images of Victor Frankenstein, 
or perhaps unscrupulous quack doctors in traveling medicine shows. 
Despite the warped public perception, electrochemical potentials are indeed a fact of life, 
influencing processes in transport, metabolism, computation, and development across all the biological kingdoms.
By developing devices that interface with these bioelectric systems, engineers may be able to observe
or even control these processes for sensing, manufacturing, or medical applications that were not possible before.

There's a complication: the wet, salty electrochemistry that comprises most bioelectric systems is not immediately
compatible with the integrated circuits that drive our digital world.
Care must be taken at the interface between electronics and living organisms to keep both the electronics and organisms happy.
This interface has been at the core of my research work, whether it involves the electroactive bacterium *Shewanella oneidensis* 
or skin cells sheepherded in a petri dish.
I am engineering devices that use this bioelectrical connection to augment these biological systems for biosensing and medical applications.

## Current
# SCHEEPDOG: Steering cell motion with electrical stimulation
<video autoplay loop width="700" title="Steering mouse keratinocytes (skin cells) through a circular trajectory using a rotating electric field." src="/img/scheepdog.mp4"></video>

I developed SCHEEPDOG, a device that exploits **electrotaxis**, the ability of 
cells to sense electric fields and follow them, to shepherd cell migration. SCHEEPDOG uses two 
orthogonal electrode pairs, one vertical and one horizontal, to create a composite field direction. 
By adjusting field directions over time, cells can be herded along arbitrary trajectories, akin to 
how an ‘Etch A Sketch’ traces out a picture via two control knobs. With SCHEEPDOG,
we have induced a potpourri of novel dynamic maneuvers in skin and kidney cells: 90-degree 
turns, diagonals, sinusoids, and circles (pictured above). The level of control demonstrated suggests that cells 
effectively time-average electric field cues on the order of \~5 minutes, which helps to clarify the time scales involved in the 
biological response. Because electrotaxis has been documented across diverse systems including 
at least 20 mammalian cell types, slime molds, fish, and frogs, our platform represents a control 
approach with potentially broad utility in many arenas.

# People's Ventilator Project

During the worst stages of the COVID-19 pandemic, there was an unmet 
global need for easily manufactured, rapidly deployable mechanical 
ventilators. The People's Ventilator Project was started to meet this need, bringing 
researchers together across Princeton University and 
beyond to design an open-source, replicable ventilator that could adapt 
to shifting global supply chains. I developed printed circuit boards to 
interface pressure and flow sensors and valves with a 
Raspberry Pi to control the system. I am also carrying out standard testing to certify the 
ventilator for emergency use. Contributing to this project has been a 
great honor, and I would like to acknowledge the fantastic team: 
Julienne 
LaChance, Daniel Cohen, Daniel Notterman, Lorenzo Seirup, Chase 
Marshall, Grant Wallace, Jonny Saunders, 
Manuel Schottdorf, Zhenyu Song, Al Gaillard, Sophie Dvali, and Moritz 
Kuett.
- D. Krakow, [_Tom 
Zajdel: From Skin 
Wounds to Ventilators_](https://mae.princeton.edu/about-mae/spotlight/tom-zajdel-skin-wounds-ventilators), 
Princeton MAE Spotlight, June 2020.
- C. Sayre, [_Julienne LaChance: Sharing Accessible Ventilator Plans with the 
World_](https://mae.princeton.edu/about-mae/spotlight/julienne-lachance-sharing-accessible-ventilator-plans-world), 
Princeton MAE Spotlight, June 2020.

<!--## Past
# Flagellar motor observation for electronic biosensing
During bacterial chemotaxis, *Escherichia coli* monitors chemical changes in its environment and modulates the rotation of the **bacterial flagellar motor** (BFM) to bias its motility towards nutrients in its environment.
Bacterial chemotaxis is fast, with a response time on the order of seconds, and its performance known to approach fundamental physical limits on biochemical sensors.
Despite this natural capability, no engineered biosensor approaches the performance of the natural chemotaxis system within the same small volume of a single bacterium.

My work at Berkeley focused on co-opting this outstanding capacity in an engineered biosensing system.
I developed a method for drawing inferences of the chemical environment from observed BFM behavior, applying machine learning to bacterial chemotaxis to do so.
I also fabricated a platform towards enabling completely electronic observation of the BFM, without the need for a microscope.
This system involved labeling bacterial flagella with dielectric beads, then using microfabricated electrode arrays to monitor impedance changes within a region small enough to detect the movement of these beads.
This effort to use real-time impedance measurements to observe BFM behavior was the first of its kind that could someday enable large-scale integrated measurements of thousands of BFMs simultaneously.
Taken together, this is a new way to engineer biosensors: devise an observation scheme to interpret the responses of natural microorganismal sensing systems.

# Microbial electronics miniaturization
In graduate school, I contributed to several efforts to develop microbial bioelectronic devices towards eventual environmental deployment.
All these projects used an electroactive bacterial strain expressing the Mtr extracellular electron transport conduit.
Another project developed a miniaturized potentiostat enabling environmental deployment of electroactive biosensing strains.
The final project demonstrated a method to encapsulate living Shewanella oneidensis MR-1 inside an organic conducting polymer blanket,
forming a synthetic biofilm composite capable of generating 20x more current than a native biofilm. Together, these results enable the eventual miniaturization and deployment of environmental microbial electrochemical sensors.
-->
