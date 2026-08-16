# OFDM-QAM Communication System using MATLAB

## 📡 Project Overview

This project presents a MATLAB-based simulation of an OFDM digital communication system using **16-QAM and 64-QAM** modulation. The system evaluates communication performance under **AWGN and multipath fading channel conditions**.

The project analyzes **Bit Error Rate (BER)** performance with respect to \(E_b/N_0\) and studies the effect of modulation order and channel impairments on system reliability.

## 🎯 Objectives

- Design and simulate an OFDM-based digital communication system.
- Implement **16-QAM and 64-QAM** modulation and demodulation.
- Evaluate BER performance for different \(E_b/N_0\) values.
- Compare system performance under **AWGN and multipath channels**.
- Generate and analyze QAM constellation diagrams.
- Study the trade-off between **spectral efficiency and error performance**.

## 🛠️ Technologies Used

- MATLAB R2024a
- Digital Communication
- OFDM
- 16-QAM
- 64-QAM
- AWGN Channel
- Multipath Channel
- BER Analysis
- Constellation Analysis

## 📂 Project Structure

```text
OFDM-QAM-Communication-System/
│
├── main.m
├── Tx.m
├── Rx.m
├── QAM_modulation.m
├── QAM_demodulation.m
├── channel_encoding.m
├── Channeldecoding.m
└── syndrom_table.m

## 📊 Simulation Results

### 1. 16-QAM – AWGN Channel
![16-QAM AWGN Constellation](Screenshot%202026-08-16%20at%2014.04.00.png)

### 2. 16-QAM – Multipath Channel
![16-QAM Multipath Constellation](Screenshot%202026-08-16%20at%2014.04.06.png)

### 3. 64-QAM – AWGN Channel
![64-QAM AWGN Constellation](Screenshot%202026-08-16%20at%2014.04.10.png)

### 4. 64-QAM – Multipath Channel
![64-QAM Multipath Constellation](Screenshot%202026-08-16%20at%2014.04.20.png)

### 5. BER Performance – AWGN
![BER AWGN](Screenshot%202026-08-16%20at%2014.04.25.png)

### 6. BER Performance – Multipath
![BER Multipath](Screenshot%202026-08-16%20at%2014.04.31.png)

### 7. BER Performance Comparison
![BER Comparison](Screenshot%202026-08-16%20at%2014.04.39.png)
