# Hotel Booking Cancellation Analysis

Exploratory analysis of ~81,000 hotel bookings (2015–2017) to understand cancellation drivers and revenue impact.

## Key findings

- Overall cancellation rate: **~29%**
- City hotels cancel more than Resort hotels (31.9% vs 24.5%)
- Longer lead time → higher cancellation. Immediate: 8.9%. Very long-term (365+ days): 55.1%
- Highest cancellation by market segment: Groups (38.1%) and Online TA (36.1%); lowest: Corporate (~13%)
- Higher ADR bookings cancel more (high: 35.1%, low: 19.3%)
- New guests cancel far more than repeat guests (29.8% vs 8.0%)
- Total potential revenue lost to cancellations: **$11,303,135.83**
- Monthly revenue peaks in August; cancellations peak in January
- Linear regression predicting ADR: Train R² ≈ 0.21, Test R² ≈ 0.24 — modest but stable

## Tools

Python, pandas, seaborn, matplotlib, scikit-learn

## Files

- `hotel_booking_cancellation_analysis.ipynb` — notebook
- `hotel_booking_updated.csv` — dataset

## How to run

Place the CSV in the same folder as the notebook and run all cells top to bottom.
