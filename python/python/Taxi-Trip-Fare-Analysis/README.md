# NYC Taxi Trip Data Analysis

## Objective
Analyze NYC taxi rides to identify:

- Peak ride hours  
- Passenger count distribution  
- Trip distance and fare relationships  
- Fare and tip patterns  

---

## Dataset
- Source: NYC Taxi Trip dataset  
- Rows: 83,691  
- Key columns:  
  `trip_start_timestamp`, `trip_end_timestamp`, `trip_distance`, `fare_amount`, `tip_amount`, `total_amount`, `passenger_count`, `extra`, `surcharge`

---

## Data Cleaning & Preparation
- Dropped rows with missing values in key columns  
- Dropped rows with **negative fare or total amounts**  
- Converted timestamps to **datetime objects**  
- Extracted `hour`, `day`, `month`, `weekday` from `trip_start_timestamp`  
- Calculated `trip_duration_minutes`  

---

## Feature Engineering
- `start_hour`, `start_day`, `start_weekday`, `start_month` → for temporal analysis  
- `trip_duration_minutes` → trip duration insights  
- Passenger and fare columns left as-is after cleaning  

---

## Analysis & Key Insights

### Passenger Analysis
- Most trips have **1 passenger**  
- Rows with 0 passengers were removed  
- Average fare shows **little variation by passenger count**  
- Rides with 7+ passengers have higher fares (likely group trips)  

### Time-based Ride Patterns
- **Peak ride hours:** 3 PM, 5 PM, 7 PM  
- **Lowest ride hours:** 2 AM, 3 AM, 4 AM  
- Ride demand aligns with **commuting and evening activity**  

### Trip Distance and Fare
- Clear **positive correlation** between trip distance and fare  
- Longer trips generally have higher fares  
- Some outliers exist:
  - Short trips with unusually high fares (surcharges)  
  - Long trips with unusually low fares (data anomalies)  

### Fare and Tip Distribution
- Most fares are clustered around **short-distance pricing**  
- Tips vary widely, but most are small  

---

## Tools & Libraries
- **Python**: Pandas, NumPy  
- **Visualization**: Matplotlib, Seaborn  

---

## Conclusion
This analysis demonstrates:

- How taxi demand **varies by hour and passenger count**  
- How **trip distance drives fares**  
- Patterns in **tip and fare distribution**  
- Provides insights useful for **fleet management and pricing strategies**
