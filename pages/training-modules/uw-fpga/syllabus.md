---
permalink: /training-modules/uw-fpga/syllabus.html
layout: default
title: Course syllabus
---

<p style="text-align: justify;"><span style="color: #cc0000;"><strong>INSTITUTION NAME:</strong></span> University of Wisconsin&ndash;Madison</p>
<p style="text-align: justify;"><span style="color: #cc0000;"><strong>COURSE SUBJECT, NUMBER AND TITLE: </strong></span>TAC-HEP : FPGA training module&nbsp;</p>
<p style="text-align: justify;"><span style="color: #cc0000;"><strong>CREDITS:</strong></span> 3 credits equivalent</p>
<p style="text-align: justify;"><span style="color: #cc0000;"><strong>COURSE DESCRIPTION:</strong></span></p>
<p style="text-align: justify;">Introduction to FPGA programming. Overview of FPGA, design flow, introduction High-Level synthesis and its applications</p>
<p style="text-align: justify;"><span style="color: #cc0000;"><strong>REQUISITES:</strong></span></p>
<ul>
<li>Familiarity navigating through UNIX based OS. Familiarity with CLI. Elementary knowledge of C or C++.</li>
<li>Students need to set-up a Wisconsin computing account and have login access to cmstrigger01 machine with Xilinx Vivado tools. Students will be provided instructions for doing so prior to the start of the training.</li>
</ul>
<p style="text-align: justify;"><span style="color: #cc0000;"><strong>MEETING TIME AND LOCATION:</strong></span></p>
<p style="text-align: justify;"><span style="text-decoration: underline;"><strong>Zoom coordinates:&nbsp;</strong></span></p>
<p style="text-align: justify;"><a href="https://cern.zoom.us/j/69712006717?pwd=c0pqUGZxbUlFNkVRSWxHc24yL21tdz09" target="_blank" rel="noopener">https://cern.zoom.us/j/69712006717?pwd=c0pqUGZxbUlFNkVRSWxHc24yL21tdz09</a></p>
<p style="text-align: justify;">Meeting ID: 697 1200 6717</p>

<p style="text-align: justify;"><strong>FPGA Module</strong></p>
<p style="text-align: justify;">Lectures: Tuesdays and Wednesday: 9:00 &ndash; 10:00 AM (CT), 10:00 &ndash; 11:00 AM (EST), 16:00 &ndash; 17:00 PM (CERN) via zoom</p>
<p style="text-align: justify;"><span style="color: #cc0000;"><strong>INSTRUCTIONAL MODALITY:</strong></span></p>
<p style="text-align: justify;">Virtual via zoom. There will be a combination of lectures and hands-on training.</p>
<p style="text-align: justify;"><span style="color: #cc0000;"><strong>OFFICE HOURS:</strong></span></p>
<ul>
<li>Office hours by appointment.&nbsp;</li>
<li>Slack channel to post questions and communicate with instructors :</li>
<ul>
<li><a href="https://uwmadisoncms.slack.com/archives/C04JCTY6SAH" target="_blank" rel="noopener">https://uwmadisoncms.slack.com/archives/C04JCTY6SAH</a></li>
</ul>
</ul>
<p style="text-align: justify;"><span style="color: #cc0000;"><strong>INSTRUCTOR CONTACT INFO:</strong></span></p>
<p style="text-align: justify;">Dr. Varun Sharma</p>
<p style="text-align: justify;"><a href="mailto:varun.sharma@cern.ch" target="_blank" rel="noopener">varun.sharma@cern.ch</a></p>
<p style="text-align: justify;"><span style="color: #cc0000;"><strong>COURSE LEARNING OUTCOMES:</strong></span></p>
<p style="text-align: justify;">Develop an understanding of the differences between different hardware (CPUs / GPUs / FPGAs). Get familiar with their use cases in HEP and develop the ability to identify the ideal hardware accelerator for different HEP applications. Understand the role and capabilities of FPGAs and High Level Synthesis, and learn to write algorithms for hardware.</p>
<p style="text-align: justify;"><span style="color: #cc0000;"><strong>COURSE OVERVIEW:</strong></span></p>
<p style="text-align: justify;">REQUIRED TEXTBOOK, SOFTWARE AND OTHER COURSE MATERIALS:</p>
<ul>
<li>No required textbook</li>
<li>All softwares will be installed in the available machines</li>
</ul>
<p>HLS manual for reference:&nbsp; &nbsp; &nbsp; &nbsp; <a href="https://www.xilinx.com/content/dam/xilinx/support/documents/sw_manuals/ug998-vivado-intro-fpga-design-hls.pdf" target="_blank" rel="noopener">https://www.xilinx.com/content/dam/xilinx/support/documents/sw_manuals/ug998-vivado-intro-fpga-design-hls.pdf</a></p>
<p style="text-align: justify;"><span style="color: #cc0000;"><strong>HOMEWORK AND OTHER ASSIGNMENTS:</strong></span></p>
<p style="text-align: justify;">Week 1-7: Weekly assignments&nbsp;</p>
<p style="text-align: justify;">Week 8-14: Project</p>
<p style="text-align: justify;"><span style="color: #cc0000;"><strong>GRADING:</strong></span></p>
<div>
<table>
<tbody>
<tr>
<td><strong>Weekly assignments&nbsp;</strong></td>
<td>50%</td>
</tr>
<tr>
<td><strong>Final project</strong></td>
<td>50%</td>
</tr>
</tbody>
</table>
</div>
<p style="text-align: justify;"><span style="color: #cc0000;"><strong>COURSE SCHEDULE/CALENDAR</strong></span></p>
<p style="text-align: justify;"><strong>Deadlines:</strong></p>
<ul>
<li>Each weekly assignment is due Friday of the next week&nbsp;</li>
<li>Final project is due end (by Sunday) of week 14, Friday April 30th.</li>
</ul>
<p style="text-align: justify;"><span style="color: #cc0000;"><strong>TOPICS COVERED</strong></span></p>
<h4 style="text-align: justify;">Week 1</h4>
<ul>
<li>FPGA &ndash; Introduction, why do we need them? different options available in market;</li>
<li>Overview of FPGA architecture, programming model and FPGA parallelism vs processor architectures</li>
</ul>
<h4 style="text-align: justify;">Week 2</h4>
<ul>
<li>Digital systems: some important components used on the FPGAs like registers (flip-flops), DSPs, LUTs;</li>
<li>Basic concepts of Hardware design: Clock Frequency, Latency and Pipelining, Throughput</li>
</ul>

<h4 style="text-align: justify;">Week 3-4</h4>
<ul>
<li>Vivado High-level Synthesis (HLS): Basic overview, understanding of HLS, its purpose, benefit and usage;</li>
<li>Mathematical Operations, Conditional statements, Loops, functions in HLS</li>
<li>HLS: Linear Algebra library functions, DSP library functions, C++ arbitrary precision types, datatypes for efficient hardware, Design analysis and optimisation and RTL verification;</li>
<li>Case study of trigger algorithms developed for the LHC experiments</li>
<li> Introduction to CMS experiment and Level-1 Trigger system</li>
<li>Basic introduction to VHDL and design flow</li>
<li>Quick introduction and guide to HLS4ML</li>
</ul>

<h4 style="text-align: justify;">Week 5-6-7</h4>
<ul>
<li>Project: Write an algorithm in C/C++; use HLS to make a bit file which can be burned in hardware.</li>
</ul>
<p style="text-align: justify;">Additional Read (if time permit) : </p>
<p style="text-align: justify;">- &nbsp; Computation-centric Algorithms</p>
<p style="text-align: justify;">- &nbsp; Control centric algorithms</p>
<p style="text-align: justify;">- &nbsp; Integration of multiple programs</p>
