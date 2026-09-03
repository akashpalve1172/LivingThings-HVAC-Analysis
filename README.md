# Living Things – HVAC IoT Telemetry Data Analysis

## Project Overview

This project was completed as part of the Living Things Data Analyst Intern Assignment.

The objective of this analysis is to explore HVAC IoT telemetry data collected from multiple devices and identify operational patterns, energy consumption trends, temperature control performance, and anomalies.

---

## Problem Statement

Analyze HVAC device telemetry data and generate actionable business insights by performing:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Time-Series Analysis
- Anomaly Detection
- Energy Consumption Analysis
- Visualization and Reporting

The analysis aims to answer:

- How do room temperatures vary over time?
- Which devices consume the most energy?
- Are there any abnormal device behaviors?
- How effectively are devices maintaining configured setpoint temperatures?
- What recommendations can improve energy efficiency?

---

## Dataset Information

The dataset contains telemetry readings from HVAC devices with the following features:

| Column | Description |
|----------|-------------|
| device_id | Unique device identifier |
| timestamp | Time of observation |
| room_temp_c | Room temperature |
| ambient_temp_c | Ambient temperature |
| setpoint_c | Target temperature |
| compressor_state | Compressor ON/OFF status |
| power_watt | Power consumption |
| mode | Operating mode |

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Analysis Performed

### 1. Data Cleaning
- Removed duplicate records
- Converted timestamps to datetime format
- Handled unrealistic temperature values
- Applied interpolation for sensor anomalies

### 2. Exploratory Data Analysis
- Room temperature trends
- Device-wise temperature comparison
- Power consumption analysis
- Compressor runtime analysis

### 3. Time-Series Analysis
- Temperature variation over time
- Power consumption patterns
- Device performance trends

### 4. Anomaly Detection
- Sensor anomalies
- Power spikes
- Offline periods
- Temperature deviations from setpoint

### 5. Energy Consumption Analysis
- Estimated energy consumption (kWh)
- Ranked devices by energy usage
- Identified high-energy-consuming devices

---

## Key Findings

- Duplicate records and sensor anomalies were identified and corrected.
- Room temperatures remained largely stable within the expected operating range.
- Significant differences in energy consumption were observed across devices.
- Some devices showed larger deviations from configured setpoints.
- Power spikes and offline periods were detected.

---

## Recommendations

1. Investigate devices with the highest energy consumption.
2. Review devices exhibiting large temperature deviations.
3. Monitor power spikes to prevent equipment issues.
4. Improve device connectivity to reduce offline periods.
5. Implement regular sensor health monitoring.

---

## Project Structure

```
LivingThings-HVAC-Analysis/
│
├── Akash_Palve_LivingThings_Assignment.ipynb
├── Akash_Palve_LivingThings_Report.pdf
├── README.md
└── device_telemetry.csv
```

---

## Author

**Akash Palve**

Computer Engineering Graduate  
Data Analytics | Python | SQL | Power BI | Machine Learning

LinkedIn: https://www.linkedin.com/in/akash-palve-8aa75028b

GitHub: https://github.com/akashpalve1172

---
