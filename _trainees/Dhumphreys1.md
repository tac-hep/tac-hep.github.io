---
layout: collaborator
active: true
name: Daniel Humphreys
institution: University of Massachusetts Amherst
start_date: "2025-01-01"
end_date: "2027-01-01"
training_modules:
- GPU training module
- FPGA training module
- Software Engineering for Scientific Computing
e-mail: dhumphreys@umass.edu
github-username: Dhumphreys1
photo: "/assets/images/trainees/Daniel-Humphreys.png"
shortname: Dhumphreys1
title:
website: https://www.umass.edu/physics/about/directory/daniel-humphreys
networks:
  - atlas
presentations:

---

### Biography and Interests

I am a 6th PhD student, working in the UMass Amherst ATLAS group. My principal investigator is Rafael Coelho Lopes de Sa with whom I conducted a search for a low mass dark scalar and dark vector to a 2 lepton 2 neutrino final state. Here I employ a Parameterized Machine Learning Model to perform a 2-Dimensional mass search. The novel thing about the model is that it’s able to generate kinematic distributions for mass combinations that were not simulated. This is a usual challenge for interpolating the limits of invisible final states as the 4-momentum cannot be fully reconstructed as it can in a fully visible final state.

On the technical side I am advised by Verena Martinez Outschoorn, where I work fully with the Muon Spectrometer (MS). I started with commissioning new electronics for the ATLAS Phase-II upgrade of the Muon Spectrometer. This involved setting up test stands at CERN and UMass Amherst using decommissioned Muon Drift Tube (MDT) chambers, outfitted with new electronics. After becoming familiar with the hardware side, I transitioned to C++ development for the cosmic-ray analysis software used for MDT chamber commissioning. Here I wrote a fully versatile binary decoding algorithm for the new FELIX packet protocol, as well as legacy packet formats, which will be used by the (MS). During this time, I have become intimately familiar with muon reconstruction and low-level workings of the MS.

Outside of research I like to be active and go outside and touch grass. On the weekends you could usually find me volunteering at the local dog shelter or on a mountain be it hiking, skiing, or camping. Now that I am based at CERN it’s more likely the latter.


### Project

Porting over my skills from my earlier projects I have been tasked with developing an ML algorithm for the ATLAS L0MDT project. The L0MDT project’s goal is to develop a next generation trigger for the HL-LHC ATLAS Muon Spectrometer. My primary focus has been implementing a Graphical Neural Network algorithm for FPGA deployment. This is hardware-based trigger and must function under strict latency and resource requirements. To reach the latency requirements graphs are built as inputs are streamed in. This allows us to significantly hide some of latency and take advantage of the long propagation of MDT signals. The second advantage is this allows for optimized inference algorithms that can fully utilize FPGA vectorization for rapid inference and hit classification.

### Recent Accomplishments

- Developed GNN algorithm with high performance. Reaching upwards of 98% trigger efficiency high background rejection
- Developed method to circumvent the large time complexity of message passing with dynamic graph building allowing for latency hiding.

### Mentors
* Rafael Coelho Lopes de Sa (UMass Amherst)
* Verena Martinez Outschoorn (UMass Amherst)
* Paolo Calafiura (LBNL)