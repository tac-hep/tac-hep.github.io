---
layout: collaborator
shortname: lverace
name: Lael Verace
title: Lael Verace - TAC-HEP Fellow
active: True
start_date: "2024-01-23"
end_date: "2026-01-23"
training_modules:
- Software Engineering for Scientific Computing
- GPU Programming
- FPGA Programming
photo: /assets/images/trainees/Lael-Verace.jpg
institution: University of Wisconsin-Madison
e-mail: lverace@wisc.edu
networks:
  - cms
github-username: lverace
---

### Biography and Interests

I am a third-year graduate student in the CMS group at the University of Wisconsin-Madison, advised by Professor Kevin Black.

### Project

I work with Fermilab scientists Dr. Syed Asif Raza Shah, Dr. Oliver Gutsche, and Dr. Philip DeMar on a networking R&D project titled "Performance Testing of High-Speed Scientific Networks through A Distributed Load Generation Approach." Our goal is to develop an infrastructure which allows us to test the performance of wide area network connections among scientific computing sites on a large scale. We aim to do this through the dynamic deployment of lightweight [perfSONAR](https://www.perfsonar.net/) Testpoint containers across multiple machines which generate network traffic to a given site. This approach allows us to send enough traffic to saturate the network pipe, enabling tests of the network performance in realistic high-volume scenarios. Monitoring the resulting throughput and comparing it to expected values enables us to diagnose unforeseen bottlenecks that might be limiting the performance of scientific network connections once data-volumes increase past their current amounts. By finding and fixing those bottlenecks now, we can prepare and optimize our high-speed scientific network for the future.

### Accomplishments
* Gained hands-on experience in containerization, networking, and server management while developing our project on Tier-1 and Tier-2 CMS computing sites.
* Built a system for conducting automated [iPerf3](https://iperf.fr/) network performance tests using [Podman](https://podman.io/) containers hosted across two computing sites. Demonstrated a full scale 200 Gb/s network test between UW-Madison and Fermilab involving 12 total server nodes running our software.
* Organized software into a Python-based [Flask](https://flask.palletsprojects.com/en/stable/) applicaiton for efficient and reproducible workflows that can be connected to a web interface.
* Poster presentation at 2025 US CMS Collaboration Meeting. [Link](https://pages.hep.wisc.edu/~lverace/USCMS-Poster-Final.pdf)
* Oral presentation accepted for the 2026 Conference on Computing in High Energy and Nuclear Physics


### Mentors
* Kevin Black (University of Wisconsin-Madison)
* Syed Asif Raza Shah (Fermilab)
* Oliver Gutsche (Fermilab)
* Philip DeMar (Fermilab)
