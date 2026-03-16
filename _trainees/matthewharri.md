---
layout: collaborator
active: true
name: Matthew Harris
institution: University of Massachusetts Amherst
start_date: "2023-01-01"
end_date: "2025-01-01"
training_modules:
- GPU training module
e-mail: Matthewharri@umass.edu
github-username: Matthewharri
photo: "/assets/images/trainees/Matthew-Harris.png"
shortname: Matthewharri
title: 
website: https://www.umass.edu/physics/people/matthew-harris
networks:
  - atlas
presentations:
  - title:
      Prototype navigation for muon reconstruction in ACTS
    date: 2023-06-12
    url: https://indico.cern.ch/event/1256378/contributions/5406949/attachments/2664243/4616287/MH_QT_summary.pdf
    meeting:
      ATLAS S&C week
  - title:
      Preparing the ACTS based geometry for Calorimeter and Muon System
    date: 2023-10-13
    url: https://indico.cern.ch/event/1322343/contributions/5616536/attachments/2733776/4753028/Muon_ACTS_ATHENA-3.pdf
    meeting:
      ATLAS Muon week
---

### Biography and Interests
 
I am a fifth year Ph.D. student currently working in the UMass Amherst ATLAS group, advised by Stephane Willocq.

### Project 

I currently work in the muon software group within ATLAS focused on Phase-II upgrade activities. Specifically, I have been working on a new paradigm of tracking navigation. This new model exploits a frustum/octree approach which is widely used in computer vision and gaming. In order to cope with the complexity of the muon spectrometer, connections between one volume and another are now delegated to portals which live at the volume boundaries. This approach is powerful in terms of speed and maintains code flexibility.

### Recent Accomplishments
- Developed a prototype navigation for the muon spectrometer based off of a frustum/octree approach
- [Implemented](https://gitlab.cern.ch/atlas/athena/-/merge_requests/66290) the first version of the muon chambers in Athena with ACTS
- [Implemented](https://gitlab.cern.ch/atlas/athena/-/merge_requests/72899) the first version of the muon passive material description in Athena with ACTS
- [Developed](https://github.com/acts-project/acts/pull/3268) a converter in ACTS to convert GeoModel shapes/materials to ACTS volumes/materials
- [Developed](https://gitlab.cern.ch/atlas/athena/-/merge_requests/72899) a first muon navigation test in Athena with the new ACTS geometry that compares truth hits from GEANT4 with the hits found from propagating a particle with ACTS

### Mentors 
 
  * Stephane Willocq (University of Massachusetts, Amherst)
  * Edward Moyse (University of Massachusetts, Amherst)
  * Johannes Junggeburth (University of Massachusetts, Amherst / CERN)
  * Andreas Salzburger (CERN)
  * Torre Wenaus (BNL)
