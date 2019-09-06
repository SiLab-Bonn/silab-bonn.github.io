---
layout: default
---

The following list available thesis topics at [Silizium Labor Bonn](https://github.com/SiLab-Bonn)

## Proton Irradiation Site for Silicon Detectors at Bonn University

***

![Irradiation site at Bonn isochronous cyclotron](/imgs/irrad_setup_w_cooling.jpg)

A newly-installed proton irradiation site at the [Bonn isochronous cyclotron](https://www.zyklotron.hiskp.uni-bonn.de/zyklo_e/index.html) at the [Helmholtz Institut für Strahlen- und Kernphysik (HISKP)](https://www.hiskp.uni-bonn.de/) allows radiation damage studies of prototype silicon detectors for state-of-the-art, high-energy physics experiments such as [**ATLAS**](https://atlas.cern/) and [**BELLE 2**](https://www.belle2.org/). Especially pixel detectors are positioned close to the interaction point due to their high spatial resolution and tracking capabilities. Therefore, they are exposed to a harsh radiation environment which dictates their lifetime. In order to verify that the detectors meet requirements, radiation damage studies are necessary for prototype detector concepts.

### Topic: Development of a Beam Loss Monitor (BLM) for Online Beam Loss- and Profile Measurements

- Type: Bachelor
- Location: SiLab, HISKP
- Contact: [Pascal Wolf](mailto:wolf@physik.uni-bonn.de)
- Description: The primary proton beam, provided by the Bonn isochronous cyclotron, is extracted through a so-called _Lenard_ window to the irradiation site. Shortly before extraction, the absolute beam current, which is the crucial quantity for damage studies, is measured via a secondary electron monitor (SEM). In order to detect beam loss between SEM and extraction due to e.g. misalignment, a dedicated beam loss monitor (BLM) is needed. The BLM is planned as a custom _Lenard_ window with integrated _Faraday_ cup in the form of a graphite ring. The aim is to construct the BLM in a computer-aided design (CAD) program, test it's functionality in a test beam and integrate its data into an existing data monitor. Additionally, the BLM can be used to measure the beam profile at extraction.

### Topic: Development of an Online Radiation Damage Monitor Using Commercial Silicon PIN-diodes

- Type: Bachelor
- Location: SiLab, HISKP
- Contact: [Pascal Wolf](mailto:wolf@physik.uni-bonn.de)
- Description: The most prominent consequence of radiation damage for the operation of silicon detectors, is the linear increase in _leakage current_ $$\Delta I_{leak}$$ per sensitive volume V with particle fluence $$\Phi$$:
$$\frac{\Delta I_{leak}}{V} = \alpha \cdot \Phi}$$
Here, $$\alpha$$ is the _current-related damage rate_ and depends on the respective particle and its energy. Measurement of $\alpha$ allows to quantify the radiation damage. Consequently, commercial silicon diodes can be used to measure the current related damage rate $$\alpha_p$$ of the protons. The aim of this work is to establish a radiation damage monitor (RDM) which measures the damage on a "per irradiation" basis. A mount for the diode (BPW34F PIN-diode) has to be constructed and integrated in the existing setup. Automated measurement of the leakage current, using a source measure unit (SMU), and following interpretation/visualization of the data have to be implemented and integrated into an already existing Python software. A test irradiation is planned to verify the procedure.

***

## BELLE 2 Pixeldetector

***

![BELLE 2 silicon vertex detector (SVD) and PXD](/imgs/belle_svd_pxd.jpg)

The [**BELLE 2**](https://www.belle2.org/) particle collision experiment in Japan started taking data in spring 2019. A european collaboration led by Germany developed the pixel detector (PXD) for particle tracking and vertex determination in the experiment. The sensors of the PXD are based on **DE**pleted **P**-channel **F**ield **E**ffect **T**ransistors (DEPFETs). The SiLab group has been involved for 10 years in the investigation of this technology and the development and testing of the final components.

### Topic: Characterization of Detector Modules for the PXD 2 Upgrade

- Type: any
- Location: SiLab
- Contact: [Botho Paschen](mailto:paschen@physik.uni-bonn.de)
- Description: A replacement/upgrade of the entire PXD is planned in the spring of 2021. A small number of detector modules will be characterized in Bonn. Characterization includes electrical and functionality tests of the **A**pplication **S**pecific **I**ntegrated **C**ircuits (ASICs) on the modules and optimization of the sensor response with radioactive sources. If possible also improvements of the testing procedures (mostly steered by Python scripts) and development of new tests will be part of the work.

### Topic: Investigation of Radiation Hardness and Radiation Burst Events of PXD ASICs and Sensors

- Type: any
- Location: SiLab
- Contact: [Botho Paschen](mailto:paschen@physik.uni-bonn.de)
- Description: The PXD has to withstand a large amount of ionizing radiation in the experiment. To investigate the effects on the ASICs and the sensors, dedicated irradiation campaigns with high intensity X-ray tubes and electron sources are planned starting this fall.

***

