---
layout: collaborator
shortname: lverace
name: Lael Verace
title: Lael Verace - TAC-HEP Fellow
active: True
start_date: "2024-01-23"
end_date: ""
training_modules:
- GPU training module
photo: /assets/images/trainees/Lael-Verace.jpg
institution: University of Wisconsin-Madison
e-mail: lverace@wisc.edu
networks:
  - cms
github-username: lverace
---

### Biography and Interests

I am a second-year graduate student in the CMS group at the University of Wisconsin-Madison, advised by Professor Kevin Black.

### Project

I work with Fermilab scientists Dr. Syed Asif Raza Shah and Dr. Oliver Gutsche on a networking R&D project titled "Performance Testing of High-Speed Scientific Networks through A Distributed Load Generation Approach." Our goal is to develop an infrastructure which allows us to test the performance of wide area network connections among scientific computing sites on a large scale. We aim to do this through the dynamic deployment of lightweight [perfSONAR](https://www.perfsonar.net/) Testpoint containers across multiple machines which generate network traffic to a given site. This approach allows us to send enough traffic to saturate the network pipe, enabling tests of the network performance in realistic high-volume scenarios. Monitoring the resulting throughput and comparing it to expected values enables us to diagnose unforeseen bottlenecks that might be limiting the performance of scientific network connections once data-volumes increase past their current amounts. By finding and fixing those bottlenecks now, we can prepare and optimize our high-speed scientific network for the future.

### Recent Accomplishments
* Since starting the project, I've gained a vast amount of valuable knowledge and hands-on experience in containerization, networking, and server management. It really amazes me when I look back on how much I've learned in a relatively short time just by working on this project!
* Developed a system for conducting automated [iPerf3](https://iperf.fr/) network performance tests between [Podman](https://podman.io/) containers hosted on two separate servers using systemd timers.
* Utilized perfSONAR to conduct coordinated throughput measurements between multiple testbed servers. Currently working to expand this and implement a centralized monitoring tool to keep track of all ongoing measurements.

### Mentors
* Kevin Black (University of Wisconsin-Madison)
* Syed Asif Raza Shah (Fermilab)
* Oliver Gutsche (Fermilab)

