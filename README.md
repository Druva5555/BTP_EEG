# Collaborative Fog Computing: Fog Head Selection and Data Compression in Internet of EEG-Healthcare Things

This repository contains the **final report and presentation slides** of the
Bachelor of Technology Project (BTP) carried out as part of the **M-2025 BTP
evaluation** at the **Indian Institute of Information Technology Sri City**.

The project focuses on improving the efficiency of EEG-based healthcare systems
by combining **fog computing**, **EEG data compression**, and **intelligent fog
head selection**.

---

## 📌 Project Overview

Electroencephalography (EEG) plays a critical role in monitoring brain activity
for neurological healthcare applications. However, continuous EEG monitoring
generates large volumes of data, leading to challenges such as high latency,
bandwidth usage, and energy consumption when using traditional cloud-based
systems.

To address these challenges, this project proposes a **collaborative fog
computing framework** that:

- Processes EEG data closer to the source  
- Reduces communication delay  
- Minimizes bandwidth and energy usage  
- Enables efficient fog resource management  

---

## 🎯 Objectives

The main objectives of this project are:

- To design a **fog-based architecture** for Internet of EEG-Healthcare Things  
- To develop **mathematical models** for delay, energy consumption, and storage
  performance  
- To implement an **efficient EEG data compression technique**  
- To select an **optimal fog head** from heterogeneous fog devices using a
  multi-criteria decision-making approach  
- To evaluate the system using real-world datasets  

---

## 🧠 Methodology

### 1. System Architecture
A three-layer architecture is proposed consisting of:
- EEG sensing devices  
- Fog computing layer  
- Cloud server  

Fog nodes perform local processing and compression, while the cloud is used for
long-term storage and analysis.

---

### 2. Mathematical Modeling
Mathematical models are formulated to analyze:
- **Delay** (transmission, propagation, processing, queuing)  
- **Energy consumption** (processing, transmission, idle)  
- **Performance and storage efficiency**  

These models help in evaluating system behavior under different fog
configurations.

---

### 3. EEG Data Compression
A hybrid EEG data compression pipeline is proposed:
- **K-Means clustering** to group similar EEG samples  
- **Delta encoding** to exploit temporal redundancy  
- **Arithmetic coding** to remove statistical redundancy  

This approach achieves high compression efficiency while preserving EEG signal
integrity.

---

### 4. Fog Head Selection (DEMATEL–MOORA)
Fog head selection is treated as a **multi-criteria decision-making (MCDM)**
problem.

- **DEMATEL** is used to analyze interdependencies among selection criteria and
  derive their weights  
- **MOORA** is applied to rank fog devices based on weighted benefit and cost
  criteria  

---

## 📊 Datasets Used

### EEG Dataset
- Bonn EEG Dataset  
- Five subsets: Z, F, N, O, S  
- Sampling rate: 173.61 Hz  
- Single-channel EEG signals  
- Includes recordings from healthy subjects and epilepsy patients  

### Fog Device Dataset
- Eight heterogeneous fog devices  
- Parameters include:
  - Clock speed (minimum and maximum)  
  - Number of cores  
  - MIPS  
  - Primary and secondary memory  
  - Total, unit, and idle energy consumption  

---

## 🧪 Experimental Results

- The proposed EEG compression technique achieves an **average compression
  ratio above 96%**  
- Compression and decompression times remain low across all EEG subsets  
- DEMATEL–MOORA analysis identifies the **A15 Bionic chip** as the optimal fog
  head with **100% relative performance**  
- Results confirm reduced latency, bandwidth usage, and energy consumption  

---

## 📁 Repository Contents

-BTP-ProjectCode-Final-report.pdf

-BTP-ProjectCode-Final-slides.pdf

-README.md

---


> Note: The source code is not included in this repository.

---

## 👥 Team Members

- **Druva Sai**   
- **Surya Sujit**   
- **Abhinash**   

---

## 👩‍🏫 Project Guide

- **Dr. Sreeja SR**  
  Indian Institute of Information Technology Sri City  
  Andhra Pradesh, India  

---

## 🏫 Academic Information

- Degree: Bachelor of Technology  
- Branch: Computer Science and Engineering  
- BTP Batch: B25SSR01  
- Institute: Indian Institute of Information Technology Sri City  
- Submission Year: 2025  

---

## 📌 Work Completed After Last BTP Evaluation

- Finalized mathematical modeling for delay, energy, and storage efficiency  
- Selected and optimized the hybrid EEG compression pipeline  
- Implemented DEMATEL–MOORA-based fog head selection  
- Completed experimental evaluation and analysis  
- Prepared final report and presentation slides  

---

## 📜 License & Declaration

This repository is intended for **academic and educational purposes only**.
The work presented here is original and carried out as part of the BTP under the
guidance of the project supervisor.

---

## ⭐ Acknowledgment

The authors thank **IIIT Sri City** and the project guide for their support and
guidance throughout the course of this project.

---
