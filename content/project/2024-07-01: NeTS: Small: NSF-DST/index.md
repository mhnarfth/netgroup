---
title: "NeTS: Small: NSF-DST: Integrating Physical and Network Layers in the Design of Multi-Core Coherent Optical WDM Networks"
date: 2026-06-29
weight: 1
---

<div class="nsf-dashboard-widget">
  <h4>📊 NSF Award Metadata</h4>
  <ul>
    <li><strong>Project Focus:</strong> On-demand QoT-aware optical phase conjugators (OPCs) for WDM networks - Physical Layer Implementations and Intelligent Network Design.</li>
    <li><strong>Award Number:</strong> 2413851 (Active Period: July 1, 2024 – June 30, 2027)</li>
    <li><strong>US PI:</strong> Dr. Byrav Ramamurthy, Department of Computer Science and Engineering, University of Nebraska-Lincoln (UNL)</li>
    <li><strong>Indian PI:</strong> Dr. Deepa Venkatesh, Department of Electrical Engineering, Indian Institute of Technology (IIT) Madras</li>
  </ul>
</div>

## 🔬 Project Overview

This collaborative international initiative advances next-generation optical communication architectures by resolving a critical gap in core telecommunications modeling: the separation between physical-layer lightwave propagation constraints and network-layer routing logic.

The core objective of the UNL team is **network softwarization**—bridging the rigid, hardware-driven physical layer constraints of long-haul fiber optics with dynamic, intelligent control plane algorithms. By developing integrated design methodologies that accurately account for non-linear optical impairments inside coherent systems, our frameworks provide real-world cross-layer validation for high-capacity networking environments. 

---

## ⚙️ UNL’s Core Architectural Breakthroughs

Traditional networks rely heavily on massive, power-hungry receiving-end Digital Signal Processing (DSP) chips to digitally correct signal distortions. UNL’s Network Research Group (NRG) has shifted this paradigm by creating a software control plane that natively understands Optical Phase Conjugation (OPC).

*   **Coordinated Device Placement Optimization:** UNL researchers designed mathematical strategies to optimize the placement of optical regenerators and physical OPC nodes across wide-area Wavelength Division Multiplexing (WDM) footprints. By routing data strategically, this architecture significantly reduces downstream DSP processing overhead and overall network energy use.
*   **Deep Reinforcement Learning (DRL) Routing:** To combat real-world fluctuations in network traffic, the UNL team integrated deep reinforcement learning models. These AI agents solve the complex Routing, Modulation, and Spectrum Assignment (RMSA) problem on the fly, ensuring high-capacity signals are dynamically reassigned to channels with optimal Quality of Transmission (QoT).

---

## 💻 The Software Simulation Framework

Because physical fiber testbeds are highly constrained, the UNL team built a high-fidelity, open-source simulation pipeline to model physical impairments like non-linear fiber distortions and signal-to-noise ratio (SNR) degradation.

*   **SIMON / SimEON Upgrades:** UNL's custom-built optical network simulators were upgraded to support multi-layer, cross-layer service provisioning.
*   **GNPy Integration:** UNL natively coupled their simulator with GNPy, the industry-standard open-source Optical Route Planning Library.

**The Result:** This hybrid framework is capable of simulating complex multi-core, space-division multiplexing (SDM) setups, allowing researchers to accurately evaluate the real-world performance of 4-core coherent optical systems before deploying physical code.

---

## 🤝 International Collaboration & Key Activities

A cornerstone of this research project is our structural relationship with our international academic partner institution, **IIT Madras (Chennai, India)**. 

*   **The Maryland Workshop Origins:** The foundation of this collaboration was established when the UNL and IITM teams met at an NSF-sponsored workshop in Maryland. Recognizing the complementary strengths of UNL’s simulation expertise and IITM’s operational capabilities, the teams pursued a joint supplement to bridge the gap between layers.
*   **Testbed Tours & Site Visits:** The UNL team conducts continuous reviews of the Advanced Optical Communication (AOC) Testbed at IIT Madras. This field-deployed multi-core fiber network contains alternating underground (4.07 km) and aerial (1.20 km) uncompressed cabling installations configured with loopbacks for ultra-long reach loops.
*   **Global Conference Syncs:** Recently, UNL researchers met with IITM colleagues at the OFC conference to review the ITU booth showcase and plan the next phase of our joint network load prediction models.

---

## 📸 Project Photo Gallery

Take a closer look at our physical testbed deployments, hardware assemblies, and international team meetings.
{{< gallery >}}

---

## 📄 Publications & Dissertations

### Journal & Conference Papers
*   **Engineering a 5-Phase Operational Framework for Research Network Analytics: A Scalable Deployment Architecture for High-Velocity Traffic** 
    *Mohammad Arafath Uddin Shariff and Byrav Ramamurthy.* (IEEE International Symposium on Local and Metropolitan Area Networks - LANMAN, 2026).
*   **Integrating SimEON with DeepRMSA for dynamic network simulation of elastic optical networks** 
    *Boyang Hu, Mohammad Jafar Majid, Byrav Ramamurthy.* (Photonic Network Communications, Vol 51, Issue 2, pp. 8, April 2026). [Read the Paper (Springer)](https://link.springer.com/article/10.1007/s11107-026-01042-5)
*   **Implications of Deploying Optical Phase Conjugators (OPCs) to Reduce DSP Overhead in a Dynamic WDM Coherent Optical Network** 
    *Boyang Hu, Byrav Ramamurthy, et al.* (International Conference on Optical Network Design and Modeling - ONDM).
*   **Integrating Physical Layer Modeling in the Simulation of Dynamic WDM Optical Networks with Direct and Coherent Detection** 
    *Boyang Hu, Byrav Ramamurthy, et al.* 
*   **Low Distortion Inline SOA Amplifier With Optimized Holding Beam for Single-Channel 16/64QAM Signals** 
    *(IEEE Photonics Technology Letters, 2024).* [Read the Paper (DOI)](https://doi.org/10.1109/LPT.2024.3403036)
*   **Low-Distortion Amplification of Probabilistic Shaped Signals Using SOA** 
    *(IEEE Photonics Technology Letters, 2024).*
*   **Gain Compression in Semiconductor Optical Amplifiers induced by a Holding Beam** 
    *(2024 IEEE Photonics Conference).*
*   *Under Review:* A Real-time Network Load Prediction and Resource Allocation for IP-over-Optical Networks.
*   *Under Review:* Integrated Physical Layer Modeling and OPC Deployment Analysis for Dynamic Coherent WDM Networks.

### Dissertations & Master's Theses
*   **Intelligent Multi-layer Optical Network Design and Network Softwarization**
    *Dr. Boyang Hu, Doctor of Philosophy (Ph.D.), UNL.* [Access via UNL Digital Commons](https://digitalcommons.unl.edu/dissunl/344/)
*   **Non-blackbox Robust Design of Machine Learning in Networks**
    *Dr. Venkat Sai Suman Lamba Karanam, Doctor of Philosophy (Ph.D.), UNL (August 2025).* [Access via UNL Digital Commons](https://digitalcommons.unl.edu/dissunl/328/)
*   **Traffic Prediction for Research and Education Networks: Anomaly-aware Deep Learning and Benchmarking** 
    *Mohammad Arafath Uddin Shariff, Master's Thesis, UNL (August 2025).* [Access via UNL Digital Commons](https://digitalcommons.unl.edu/computerscidiss/251/)

---

## 🎓 Student Contributions

Our cross-institutional framework provides graduate researchers with rigorous hands-on training in physical layer components, network modeling design, and international research collaboration.

*   **Mohammad Arafath Uddin Shariff (UNL PhD Candidate):** Focuses on exploring advanced optical simulation platforms and anomaly-aware deep learning for network traffic prediction. Successfully defended his Master's thesis in August 2025.
*   **Dr. Boyang Hu (UNL Graduated Ph.D.):** Led the integration of GNPy with SIMON/SimEON and the development of OPC optimization routing logic. Successfully earned his Ph.D. with a focus on intelligent multi-layer network design.
*   **Dr. Venkat Sai Suman Lamba Karanam (UNL Graduated Ph.D.):** Researched robust machine learning designs within optical network environments, successfully defending his Ph.D. dissertation in August 2025.
*   **Srikar Chanamolu (UNL Graduate Researcher):** Active on-site conference representative, tracking software validation loops alongside international project stakeholders.

---

## 🚀 Future Work

Our developmental milestones for the upcoming execution cycle target expanding our deployment footprints across three operational areas:
1.  **Refinement of Simulation Engines:** Integrate deeper non-linear fiber modeling variables to match field results closely.
2.  **Lab Scaling of OPC Devices:** Initiate close-range laboratory configurations testing real-time mid-span spectral inversion tracking circuits.
3.  **Co-Developed Infrastructure Components:** Construct integrated physical testing platforms alongside IIT Madras to run direct comparative analyses matching U.S. configurations against Indian network topologies.