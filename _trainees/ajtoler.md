---
layout: collaborator
active: true
name: Andrew Toler
institution: University of Massachusetts Amherst
start_date: "2023-07-01"
end_date: "2025-06-30"
training_modules:
- Software Engineering for Scientific Computing
- GPU training module
- FPGA training module
e-mail: atoler@umass.edu
github-username: ajtoler
photo: "/assets/images/trainees/Andrew-Toler.jpg"
shortname: ajtoler
title: 
website: https://www.umass.edu/physics/people/andrew-toler
networks:
  - atlas
presentations:
---

### Biography and Interests
 
I am a fourth year PhD student at the UMass Amherst working on the ATLAS Experiment performing operations work on the L0Muon Trigger and an analysis searching for a largely displaced Heavy Neutral Lepton.

### Project 
I am contributing to the L0Muon trigger effort within the ATLAS Muon Spectrometer, specifically studying firmware design performance and algorithms efficiency, implemented on FPGA architecture, to then design methods to recover physical subdetector inefficiencies. To do this I simulated physical RPC inefficiencies within the detector and studied their impact on muon segment construction. I am currently implementing updates to the trigger logic that can recover performance lost from these inefficiencies and to improve the robustness of the MS trigger.

### Recent Accomplishments
So far, multiple performance studies have been created regarding the impact of how different scenarios of physical RPC inefficiencies affect various stages of segment construction, for both clean calibration like muons and data with background contamination. There has been an effort to develop possible software recovery methods, which will allow for the segment to be correctly constructed without seeding from the RPCs. Most promising of which, in terms of performance and compatibility with the short operating time demanded by the trigger and the FPGA architecture, is applying a Hough Transform to the MDT hits to then seed the region of interest for segment construction.

### Next Steps
Once the Hough Transform is fully implemented into the L0Muon Trigger Chain simulation, I will begin to fine tune the transform’s parameters and perform a comparison study of the segment construction between a perfectly working RPC system, RPC system with introduced inefficiencies, and with the Hough Transform applied to recover from the RPC inefficiencies. Following that will be the integration of this recovery method onto the trigger FPGAs, in which TAC-HEPs FPGA training module has also proved useful, which will involve converting computation to fixed-point arithmetics using precomputed values, restructuring loops into fully pipelined and partially unrolled streaming architecture, partitioning arrays to avoid memory conflicts, and carefully scheduling DSP, BRAM, and LUT resources to achieve low-latency.

### Mentors 
  * Verena Martinez Outschoorn (University of Massachusetts)
  * Stéphane Willocq (University of Massachusetts Amherst)
  * Carlo Dallapiccola (University of Massachusetts Amherst)
  * Guillermo Loustau De Linares (University of Massachusetts Amherst)
  * Michael Begel (Brookhaven National Lab)
  * Davide Cieri (Max Planck Institute for Physics)
