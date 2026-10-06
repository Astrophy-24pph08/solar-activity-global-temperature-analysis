# A time-series analysis of the relationship between solar activity, global temperature anomalies

## Overview

This project investigates the statistical relationship between solar activity and global temperature anomalies using publicly available astronomical and climate datasets.

The analysis focuses on monthly observations from **1950 to 2024** and combines:

- Monthly sunspot-number data
- NASA GISTEMP global temperature anomalies
- NOAA Niño 3.4 ENSO index

The project uses Python-based time-series analysis, statistical correlation, detrending, smoothing, spectral analysis, and regression.

---

## Research Question

> **Is there a measurable statistical relationship between solar activity and global temperature variability after accounting for long-term temperature trends?**

---

## Objectives

- Analyze the relationship between sunspot activity and global temperature.
- Compare Pearson and Spearman correlation.
- Investigate the effect of 12-month smoothing.
- Remove long-term temperature trends.
- Compare monthly and annual relationships.
- Identify the dominant solar periodicity.
- Investigate ENSO as an additional climate variable.
- Apply multivariate regression.
- Examine the limitations of correlation-based solar–climate analysis.

---

## Datasets

### NASA GISTEMP

Global monthly temperature anomaly data from NASA GISS.

**Variable:**

`Temperature_Anomaly`

**Study period:**

`1950–2024`

### NOAA Sunspot Number

Monthly sunspot-number data used as an indicator of solar activity.

**Variable:**

`Sunspot_Number`

### NOAA Niño 3.4

Monthly Niño 3.4 index used to represent ENSO variability.

**Variable:**

`ENSO`

The datasets are aligned using monthly dates before analysis.

---

## Methodology

```text
Data acquisition
Data cleaning
Monthly alignment
Pearson correlation
12-month smoothing
Temperature detrending
ENSO integration
Multiple regression

