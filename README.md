# Dynamic-Pricing-for-Urban-Parking-Lots-
Dynamic Pricing for Urban Parking Lots  Capstone Project of Summer Analytics 2025  
# 🚗 Dynamic Pricing Engine for Urban Parking Lots

A real-time, data-driven pricing engine for 14 urban parking spaces. This system simulates intelligent pricing based on live occupancy, traffic, queue length, and competitive lot behavior — built using core Python libraries and Pathway's streaming architecture.

---

## Overview

Urban parking spaces face frequent inefficiencies due to static pricing. This project builds a **dynamic pricing engine** that adjusts prices in real-time based on:

- Occupancy and capacity
- Queue length
- Traffic congestion
- Special events
- Type of incoming vehicle
- Competitor lot pricing (based on proximity)

The system simulates live data updates, pricing strategies, and visualizations — from scratch.

---

## Tech Stack

| Category           | Tools Used                              |
|--------------------|------------------------------------------|
| Programming        | Python (Pandas, NumPy)                   |
| Real-Time Streaming| [Pathway](https://pathway.com)           |
| Visualization      | Bokeh, Matplotlib                        |
| Notebook Interface | Google Colab                             |
| Mapping Logic      | Haversine distance for lat-long proximity|
| Deployment Ready   | Pathway App + Visuals                    |

---

## Architecture Diagram (Mermaid)

flowchart TD
    A[Dataset.csv] -->|Simulated Stream| B[Pathway Engine]
    B --> C[Feature Engineering]
    C --> D[Pricing Model (Model 1/2/3)]
    D --> E[Real-Time Pricing Output]
    D --> F[Optional: Lot Rerouting]
    E --> G[Bokeh Dashboard]
    G --> H[User/Client View]
