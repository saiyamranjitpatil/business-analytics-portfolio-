# Engine Health Signal Intelligence

### Exploratory Analysis of Turbofan Engine Sensor Degradation

An exploratory data analytics case study using the NASA C-MAPSS turbofan engine dataset to investigate how sensor signals change as engines progress through their operational lifecycle.

---

## Objective

Aircraft engines generate multiple sensor measurements throughout their operational lifecycle. Understanding how these signals evolve can help identify potential indicators of engine degradation.

This project investigates:

> **Which sensor signals exhibit the clearest and most consistent changes as turbofan engines progress through their operational lifecycle?**

Rather than building a failure prediction model, this project focuses on **exploratory data analysis, lifecycle segmentation, sensor relationships, and signal interpretation.**

---

## Key Questions

The analysis focuses on four questions:

1. How long do the engines operate before reaching their final recorded cycle?
2. Which sensor signals have the strongest relationship with operating cycle?
3. How do important sensor signals differ between early and late engine lifecycle stages?
4. Which sensors demonstrate the strongest lifecycle-related patterns?

---

## Dataset

The analysis uses the **NASA C-MAPSS Turbofan Engine Degradation Simulation Dataset**, specifically the **FD001 training subset**.

The dataset contains:

- 100 simulated engines
- 20,631 observations
- 3 operational settings
- 21 sensor measurements
- Multiple operating cycles for each engine
- Complete lifecycle trajectories for the training engines

### Dataset Source

NASA C-MAPSS Turbofan Engine Degradation Simulation Dataset:

https://data.nasa.gov/dataset/cmapss-jet-engine-simulated-data

The dataset was used for analytical and educational purposes.

---

## Analytical Approach

The analysis follows a structured exploratory workflow:

```text
Raw Sensor Data
       ↓
Data Validation
       ↓
Engine Lifecycle Analysis
       ↓
Sensor–Cycle Relationship Analysis
       ↓
Lifecycle Normalisation
       ↓
Lifecycle Stage Segmentation
       ↓
Early vs Late Sensor Comparison
       ↓
Sensor Signal Ranking
       ↓
Key Findings

