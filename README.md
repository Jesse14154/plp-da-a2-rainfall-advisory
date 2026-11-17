
# County Rainfall and Planting Advisory

## Project Overview

This project analyzes monthly rainfall data for five Kenyan counties:
Nairobi, Nakuru, Kisumu, Mombasa, and Machakos.

The analysis uses Python, NumPy, and the CSV module to clean rainfall
data, calculate annual rainfall totals, identify wettest months,
count dry months, and determine the best two-month rainfall windows
for planting.

## Project Files

- `rainfall_analysis.ipynb` - Main analysis notebook.
- `rainfall_summary.csv` - Summary of rainfall findings for all counties.
- `requirements.txt` - Python libraries required for the project.

## How to Run the Project

1. Download or clone this repository from GitHub.
2. Open `rainfall_analysis.ipynb` using Google Colab.
3. Install the required libraries using `pip install -r requirements.txt`.
4. Run all notebook cells from top to bottom.
5. The analysis generates `rainfall_summary.csv`.

## Key Planting Advisory

- Nairobi, Nakuru, Kisumu, and Mombasa have April-May as their highest combined two-month rainfall window.
- Machakos has November-December as its highest combined two-month rainfall window.
- Machakos recorded six dry months, making water management and drought preparedness important.

## Data Quality

The Machakos dataset contained two invalid rainfall entries.
These were replaced with the rounded average of the valid values (68 mm).

The analysis uses one year of rainfall data, so longer-term records
and local agricultural guidance should also be considered.
