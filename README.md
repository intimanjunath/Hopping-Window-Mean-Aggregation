# Hopping Window Mean Aggregation

This project demonstrates how to perform **hopping window mean aggregation** on time-series data using Python. Hopping windows are commonly used in real-time stream processing systems to compute aggregated statistics over overlapping or non-overlapping windows, allowing for efficient and scalable data analysis.
![Screenshot 2024-11-24 at 10 15 16 PM](https://github.com/user-attachments/assets/62b9955d-2ad0-482e-9eee-d3d6c7aea03d)

---

## Project Overview

The script:
1. Simulates a time-series dataset of temperature sensor readings.
2. Applies a hopping window mean aggregation using specified `window_size` and `hop_size` parameters.
3. Visualizes the original data and the computed hopping mean values.

This approach is valuable in distributed environments where stream processors analyze real-time sensor data.

---

## Features

- **Customizable Time Window Parameters**: Define the duration of the aggregation window (`window_size`) and the hop interval (`hop_size`).
- **Efficient Aggregation**: Handles overlapping and non-overlapping windows seamlessly.
- **Visualization**: Clear visualization of the original sensor data and the hopping mean values for better insight.

---

## Prerequisites

- Python 3.7 or higher
- Required libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`

Install the required libraries using:

```bash
pip install pandas numpy matplotlib
