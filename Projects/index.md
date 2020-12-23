---
layout: default
title: Projects
---

# Kaggle

I was first introduced to machine learning (ML) through my first lab experience, where my colleagues were using ML algorithms to detect epilepsy. Since then, my curiosity for the subject has led me to complete several MOOCs on the subject, and begin participating in Kaggle competitions.

## Cassava Leaf Disease Competition

Currently, I am competing in the Cassava Leaf Disease Competition. The task outlined involves the classification of Casava images into four diseases categories or a fifth healthy plant category. Due to the computationally expensive nature of this task and the limited dataset, tensor processing units (TPUs) and transfer learning were used. My Notebooks containing the associated code can be accessed <a href="https://www.kaggle.com/danielwijaya/cassava-v1">here</a>.

# Probe validation 

I am working with Professor John Welsh to validate a high channel-count probe that measures extracellular electrophysiology of the cerebellar cortex. The goal of the project is to use these probes to further our understanding of how biological neural networks function. We are currently working to validate the technology on nice - thus far, I have written scripts to pre-process the neural data, detect and sort neural spikes, determine spike correlation between sensors, and mapping relationships between the granular and molecular layers of the brain.

# Mechanical Hand

I have taken it on myself to design and build a mechanical hand with the same degrees of freedom as a human hand. Currently, I have completed the majority of the mechanical design, and am now working with a friend to forge my vision into a reality.

# Advanced AERO McGill Design Team

We participated in the SAE Aero Design competition. I was a part of the Advanced team over several years, fulfilling the roles of as a sub-team leader, VP logistics, and co-captain over these years.

In my first two years, I was the fuselage sub-team lead and led the designing and manufacture the fuselage of the aircraft.
<center><img src="/files/AERO1.png" alt="title" width = "1000"/></center>

My second year design focused heavily on the concept of modularity to ensure easy manufacture and assembly of the aircraft.
<center><img src="/files/AERO2.png" alt="title" width = "750"/></center>

Following that, I served as the co-captain of the team, guiding design and construction of the vehicle.
<center><img src="/files/AERO3.png" alt="title" width = "750"/></center>

# Optically Pumped Magnetometer (OPM) “Helmet” System

OPMs are a new brain imaging technology that is able to measure magnetic brain activity without the requirement of cryogenic cooling. This permits sensors to be placed very close to the patient, improving signal-to-noise ratio. I was involved with this project for two years.

In the first year and part of the second year, I developed an experimental setup to compare these OPM sensors directly to the 275 sensor CTF superconducting quantum interference devices (SQUID) based MEG system used at ImageTech. This involved coding a script to generate a sensor array that exactly mimicks the SQUID system. Testing was done using a magnetic dipole, and results showed similar positioning accuracy to the SQUID system. I had the opportunity to participate at OHBM 2018 - my poster can be accessed <a href="/files/OHBM_2018_Daniel_Wijaya.pdf">here</a>.

<center><img src="/files/OPM_compare.png" alt="title" width = "750"/></center>

In my second year working in the lab, I wrote a script to automatically generate a customized OPM array for patients - this increases signal-to-noise ratio. The workflow I designed first took as input either polhemous scan data or scalp segmentation, that output geometric data that then went through my SolidWorks VBA script to generate the sensor array. 

<center><img src="/files/custom_array.png" alt="title" width = "750"/></center>

Additionally, I explored the possibility of using coils to provide active magnetic shielding. In the image below, the rectangles show the position on the coils, while the differently collored point clouds show isomagnetic regions.

<center><img src="/files/active_mag_shield.png" alt="title" width = "750"/></center>

# Cervical Spine Coregistration 

Shortcomings in data collection can be mitigated by co-registering data from different technologies. For this project, I was tasked with designing a sensor array that can be used to co-register Magnetoencephalography (MEG) Optically Pumped Magnetometer (OPM) which have high temporal resolution and low spatial resolution with MRI, which has high spatial resolution and low temporal accuracy. This project necessitated the development of a protocol for the co-registration of anatomical landmarks to MEG OPM data of the spinal column, to provide information on the relative position of the spinal column in relation to the sensors. As the spinal structure is very mobile, a system is required to predict or prevent changes between positions during or between MRI and MEG OPM scans. Several designs were proposed and built.

<center><img src="/files/co_registration.png" alt="title" width = "500"/></center>

# CTF Magnetoencephalography (MEG) Head Stabilization

In order to better secure young patients who may have a history of seizure, a headrest component needed to be designed for the CTF MEG. I designed this head stabilization device, creating the CAD and running FEA simulations. This design was printed by the U of T lab affiliated with Sick Kids.
<center><img src="/files/head_stabilzer.png" alt="title" width = "500"/></center>
