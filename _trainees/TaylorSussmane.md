---
layout: collaborator
active: true
shortname: taylorsussmane
name: Taylor Sussmane
start_date: "2025-06-01"
end_date: ""
photo: /assets/images/trainees/Taylor-Sussmane.jpg
institution: University of Wisconsin Madison
training_modules:
- Software Engineering for Scientific Computing
- GPU training module
- FPGA training module
e-mail: tsussmane@wisc.edu
networks:
  - cms
github-username: taylorsussmane
website: https://www.physics.wisc.edu/directory/sussmane-taylor-renee/
presentations:
  - title: "Using Alpaka for heterogeneous hit masking in Phase-2"
    date: "1 December 2025"
    meeting: Tracking POG meeting
    meetingurl: https://indico.cern.ch/event/1616105/#81-using-alpaka-for-heterogene
---

### Biography and Interests
I am a second year PhD student in the CMS group at the University of Wisconsin Madison, advised by Dr. Kevin Black.
I have yet to choose the topic of my thesis analysis. 
I did my undergraduate at the University of Tennessee Knoxville, advised by Dr. Lawrence Lee, where I primarily worked on an RPV SUSY Reinterpretation Analysis.
During my undergraduate, I spent a summer at CERN working under Dr. Phillip Sommer studying gauge boson polarization in vector boson fusion events. 

### Project
I am writing a GPU-enabled hit masking algorithm for offline track reconstruction at CMS using the Alpaka portability library.
Currently, CMS's offline tracking does not have many GPU-enabled algorithms, but in consideration of the upcoming HL-LHC upgrade, there has been a push for more of the offline tracking to be on GPU to increase the speed of algorithms.
Because track reconstruction is a iterative process where each iteration further refines the tracks, between iterations, it is necessary to do hit masking.
Hit masking is the process of removing the hits that have already been used to construct tracks, ensuring that they do not get used later on. 
If the other parts of the track reconstruction will be on GPU, it will also be necessary for the hit masking to be on GPU to reduce data transfers between the CPU and GPU, which bottlenecks the performance of the algorithms.
I am working on this project with Charis Kleio Koraka of University of Wisconsin Madison and Matti Kortelainen of Fermilab. 

### Recent Accomplishments
* Improving skills in git, python, C++
* Learned CUDA and Alpaka GPU languages
* Learned CMSSW, the software framework of track reconstruction
* Presentation to CMS Tracking Group POG 

### Mentors
* Kevin Black (University of Wisconsin Madison)
* Charis Kleio Koraka (University of Wisconsin Madison)
* Matti Kortelainen (Fermilab)
