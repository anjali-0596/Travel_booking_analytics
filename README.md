# Travel Booking Analytics

End-to-end analysis of hotel booking data using Python (Pandas, NumPy) to uncover patterns in cancellations, pricing, and seasonal demand for an OTA-style platform.

## Tools Used
- Python (Pandas, NumPy)
- Google Colab / Jupyter Notebook

## Dataset
Hotel Booking Demand dataset (119,390 bookings, 32 features) — Kaggle

## Key Insights

1. **Overall cancellation rate: 37.04%**
2. **Hotel type matters:** City Hotel has 41.7% cancellation vs Resort Hotel's 27.8%
3. **Lead time impact:** Cancelled bookings have nearly 2x longer lead time (145 days vs 80 days)
4. **Customer segmentation:** Transient customers cancel most (40.7%), Group bookings cancel least (10.2%)
5. **Booking channel risk:** Direct bookings have lowest cancellation (15.3%) vs Group/Agency channel (61.1%)
6. **Pricing:** City Hotel commands ~10% higher ADR (₹105) vs Resort Hotel (₹95)
7. **Seasonality:** Peak demand in Aug/Jul/May; lowest in Jan/Dec/Nov
8. **Room type revenue:** Room type H is the highest-revenue category at ₹188/night

## Business Recommendations
- Target long-lead-time bookings with reminder/confirmation campaigns to reduce cancellations
- Promote direct booking channels over agency/group channels to reduce cancellation risk
- Plan staffing and inventory around Aug/Jul/May peak season

## Files
- `Untitled2.ipynb` — Full analysis notebook with code and outputs
