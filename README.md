# Warehouse-Perfomance-Analysis

## 1. Project Overview

 This project analyzes warehouse picking performance using Power BI.
The goal is to identify productivity gaps, workforce efficiency,
and potential improvement opportunities.

## 🧠2. Business Problem

Warehouse operations need to understand:
- why productivity fluctuates
- which workers are below expected performance
- where efficiency is lost

## 3. Data

The analysis is based on operational data including:
- working hours
- total picks
- picks per hour

All data has been anonymized.

## 📈4. Key Insights

- Productivity distribution is not uniform across workers
- A subset of workers consistently performs below target
- Improving bottom 20% performance could increase total output by ~5–6%

## 📊Dashboard Pages

### 1. Warehouse Performance Overview

This page provides a high-level view of warehouse operations.

It includes:
- Average productivity (picks per hour)
- Total number of picks
- Number of active workers
- Productivity vs target comparison

Additional visuals:
- Daily productivity trend
- Distribution of worker performance

Purpose:
To quickly assess overall warehouse performance and identify whether operational targets are being met.

---

### 2. Picker Performance Analysis

This page focuses on individual worker performance.

Key visual:
- Scatter plot: Productivity vs Stability

Where:
- X-axis represents productivity (picks per hour)
- Y-axis represents variability (performance stability)

Each point represents a worker.

This allows segmentation into:
- High performers (high productivity, stable)
- Unstable performers (high productivity, inconsistent)
- Low performers (below target)

Additional table includes:
- Average productivity
- Performance variability (standard deviation)
- Productivity index
- Total picks
- Total hours worked

Purpose:
To identify consistent performers, unstable workers, and potential training opportunities.

---

### 3. Improvement Potential Analysis

This page identifies areas where productivity can be improved.

Key concept:
- Bottom 20% productivity threshold

The dashboard shows:
- Number of workers below threshold
- Estimated potential additional picks
- Percentage improvement opportunity

Method:
The gap between actual productivity and threshold is calculated
and multiplied by worked hours to estimate unrealized output.

Purpose:
To quantify how much productivity could be gained
by improving performance of the lowest-performing workers.

## ⚙️6. Tools

Power BI
Power Query
DAX
Excel

## 🔐7. Note

 Original data is not shared due to privacy and confidentiality.
