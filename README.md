# Assignment 3 – 5-Transistor OTA Design

## Overview

This repository contains the design, simulation, and analysis of a **5-transistor Operational Transconductance Amplifier (OTA)** with a **single-ended output**. The assignment focuses on achieving specified gain and bandwidth targets while evaluating key analog performance metrics using circuit simulations.

---

## Design Specifications

The OTA is designed to meet the following requirements:

* **DC Gain:** > 25 dB
* **Unity Gain Bandwidth (UGB):** > 500 MHz
* **Load Capacitance:** 1 pF

---

## OTA Description

* **Topology:** 5-transistor OTA
* **Output Type:** Single-ended
* **Input Condition:** Common-mode voltage of 0.8 V

---

## Simulation Results Included

The following plots and analyses are part of this assignment:

* **DC Operating Point**

  * Node voltages and branch currents at different nodes

* **AC Differential Gain & Phase Response**

* **AC Common-Mode Gain**

* **CMRR vs Frequency**

* **Input-Referred Noise vs Frequency**

* **Power Supply Rejection Ratio (PSRR)**

---

## Transient Analysis

* **Configuration:** OTA in unity-gain feedback
* **Input Signal:** Step input of 0.4 V amplitude
* **Common-Mode Voltage:** Applied DC common-mode bias
* **Observation:** Time-domain response and stability

---

## PVT Corner Analysis

The OTA performance is evaluated across:

* **Process Corners:** TT, SS, FF
* **Temperatures:**

  * −40°C
  * 27°C
  * +120°C

Both **DC and AC behavior** are analyzed to ensure robustness across variations.

---

## Tools Used

* **EDA Tool:** Cadence Virtuoso
* **Analysis Types:** DC, AC, Noise, Transient, PVT

---

## Documentation

* **Assignment Report:** `Assignment_3.docx`

---

## Notes

This project is intended for **academic coursework** and demonstrates fundamental analog CMOS design principles, performance verification, and variability analysis.

---

## Author

**Shubham Gehlot**
M.Tech (VLSI & Microsystem)
