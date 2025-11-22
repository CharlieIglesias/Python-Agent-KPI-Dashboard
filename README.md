# Agent KPI Dashboard

## Overview
This PyQt6-based dashboard visualises agent KPI metrics in a single, interactive interface. It loads KPI data from an Excel file and provides both team-wide and individual views of productivity, utilisation, and pass rate trends. Designed for daily monitoring of agent performance, it supports exporting charts to PDF for reporting purposes.  

A companion script, `CreateDataSource.py`, allows you to generate sample KPI data if an existing dataset is not available.

## Key Features & Benefits
- **Interactive data exploration:** Users can switch between team-wide averages and individual agent performance.  
- **Clear visualisations:** Side-by-side bar charts for productivity and utilisation, and line charts for pass rate trends.  
- **Flexible reporting:** Export all charts into a PDF in one click for documentation or sharing.  
- **User-friendly interface:** Simple dropdowns and buttons allow anyone to navigate and view the data without technical expertise.  
- **Sample data generation:** Quickly create realistic test data using `CreateDataSource.py` for demo or training purposes.  

## Usage
1. Run `CreateDataSource.py` to generate sample KPI data (optional if you already have an Excel dataset).  
2. Run the `Dashboard.py` script using PyCharm or your Python environment.  
3. Select an agent or choose "Team" from the dropdown menu.  
4. Click **Show Productivity and Utilisation** to view the bar chart or **Show Pass Rate** to see trends.  
5. Click **Export PDF Dashboard** to save all visualisations as a PDF.  

## Technologies / Tools
- Python 3  
- PyQt6 for GUI  
- Pandas for data processing  
- Matplotlib for charting and PDF export  

## Impact
- Provides clear, real-time insight into agent and team performance.  
- Facilitates performance monitoring and reporting without manual chart creation.  
- Reduces time spent analysing KPI data, improving decision-making efficiency.
