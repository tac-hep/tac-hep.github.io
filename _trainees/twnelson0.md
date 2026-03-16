---
layout: collaborator
active: true
name: Trevor Nelson
institution: University of Wisconsin-Madison
institutionkey: wisconsin
e-mail: twnelson2@wisc.edu
github-username: twnelson0
photo: /assets/images/trainees/Trevor-Nelson.jpg
start_date: "2022-06-01"
end_date: "2024-06-01"
training_modules:
- GPU training module
shortname: twnelson0
title: 
networks:
  - cms
presentations:
---

### Biography and Interests

### Project
I am currently working on porting the doublet/triplet seed building code and seed matching code from the CMSSW e/gamma reconstruction algorithm to run on GPUs using the ALPAKA library. The e/gamma pixel matching algorithm was chosen as it comprises 5%-10% of both HLT and offline reconstruction time. The goal of the project is to have a working implementation of the GPU compatible code integrated in CMSSW by the end of this year. Over the past year I have performed efficiency studies on the reconstructed electrons. The efficiency is the ratio of the number of reconstructed electrons using the new algorithm to the number of reconstructed electrons using the old algorithm. These studies also compared the kinematic distributions of the reconstructed electrons and looked at the timing of the different algorithms. These studies have been used to validate the physics performance of the new algorithm. In March of 2024 I participated in the 15th Patatrack hackathon and wrote an initial implementation of an ALPAKA compatible endcap propagator. This function is designed to extrapolate a track that is compatible with an electron whose trajectory is towards one of the two ECAL endcaps. I then integrated this function into the electron seed producer. 

### Recent Accomplishments
 
### Mentors
 * Dr. Charis Koraka (University of Wisconsin-Madison)
 * Dr. Tulika Bose (University of Wisconsin-Madison)
 * Dr. Matti Kortelainen (Fermi Lab)
 * Dr. Andrea Bocci (CERN)


