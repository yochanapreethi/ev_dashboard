# EV Analytics Dashboard

## Overview

This Power BI dashboard analyzes electric vehicle (EV) performance data, focusing on battery health, inverter and charger efficiency, energy consumption, and operating conditions. The dashboard delivers actionable insights into system performance, energy flow, and fault detection through interactive and dynamic visualizations.

## File Contents

| File/Folder                   | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| `EV_parameter_analysis.pbix`  | Power BI dashboard file with full interactivity                             |
| `EV_parameter_analysis.pdf`   | Exported version of the full dashboard in PDF format                        |
| `data/`                       | Folder containing the dataset (e.g., EV sensor readings, performance logs) |
| `assets/`                     | Custom icons and UI assets used in the report design                        |
| `README.md`                   | Documentation and usage instructions                                        |

## Key Features

- **Performance Metrics**  
  Track key KPIs like torque, vehicle speed, energy consumption, and battery parameters  

- **Energy Flow Insights**  
  Visualize inverter and charger efficiency under different operating conditions  

- **Condition Monitoring**  
  Analyze failure modes such as BMS overheating, charger errors, and inverter failures  

- **Trend Analysis**  
  Explore temperature, voltage, and current dynamics across time  

- **Torque & Power Dynamics**  
  Compare requested vs delivered torque and power utilization patterns  

- **Interactive Filtering**  
  Use slicers to dynamically explore data by condition, timestamp, and performance metrics  

## Tools & Technologies

- **Power BI Desktop** – For dashboard creation and analysis  
- **Power Query** – Data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – Custom KPIs and calculations  
- **Excel** – Dataset preparation and validation  
- **Visual Assets** – Custom backgrounds and icons from the `assets/` folder  

## Getting Started

1. **Install Power BI Desktop**  
   Download from [https://powerbi.microsoft.com/desktop](https://powerbi.microsoft.com/desktop)

2. **Open the Report**  
   - Open `EV_parameter_analysis.pbix` in Power BI Desktop to interact with the report  
   - Alternatively, view `EV_parameter_analysis.pdf` for a static snapshot  

3. **Explore the Data**  
   - Navigate to `data/` for raw performance logs  
   - Key columns include:  
     `Timestamp`, `Condition`, `Battery Temp`, `Coolant Temp`, `Energy Consumption`, `Torque`, `SOC`, `Speed`, `Voltage`, `Current`, `Charger Efficiency`, `Inverter Efficiency`  

## Use Cases

- Monitor EV system performance under varying conditions  
- Detect and analyze faults like BMS overheating or charger errors  
- Optimize charging and inverter efficiency for better energy usage  
- Support R&D teams with insights into EV drivetrain dynamics  

> For suggestions, improvements, or collaboration, feel free to contribute or raise an issue.
