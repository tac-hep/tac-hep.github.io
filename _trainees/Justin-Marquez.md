---
layout: collaborator
active: true
shortname: jemarq04
name: Justin Marquez
start_date: "2025-01-21"
end_date: "2027-01-21"
photo: /assets/images/trainees/Justin-Marquez.jpg
institution: University of Wisconsin-Madison
training_modules:
- FPGA training module
e-mail: justin.marquez@wisc.edu
networks:
  - cms
github-username: jemarq04
presentations:
---

Project - this should be a description of the project you are working on as a TAC-HEP trainee

### Biography and Interests

### Project

I am beginning work on improving pileup simulation performance with CMS with Matthew Herndon at University of Wisconsin-Madison and Kevin Pedro at Fermilab. To do so, I am exploring multiple approaches to improve resources (for storage, processing, etc.) and timing. Current pileup events are created using FullSim and are added to signal events later on using a process known as “pre-mixing.” Accurate simulation of pileup within CMS events is crucial, and current estimates of storage for these pileup events is orders of magnitude larger than what is currently held for Runs 2 and 3. Primary options for improving pileup simulation include (1) generation/simulation of pileup events on-the-fly using FullSim, rather than stored and retrieved at a later date, (2) using FastSim for on-the-fly pileup simulation, (3) utilizing the same pre-mixing process but at the generator level, and (4) using generative machine learning to produce the equivalent of fully simulated pre-mixed events.
The first two options eliminate the need for storing pileup events at all while the third option would reduce the size of the stored events significantly. The final option requires the most development, but could be a very promising alternative to current pre-mixing processing. So far, I have studied these options, reviewed and tested current standard CMSSW workflows for creating pileup samples, and tested the HEPScore23 benchmarking tool for measuring CPU performance. I have begun working on reviewing current CMSSW code and investigating possible updates to muon system pre-mixing to match other subdetectors' plugins.


### Recent Accomplishments

### Mentors

 * Matthew Herndon (University of Wisconsin-Madison)
 * Kevin Pedro (Fermilab)

### Traineeship Dates

Jan. 21, 2025 - Jan. 21 2027
