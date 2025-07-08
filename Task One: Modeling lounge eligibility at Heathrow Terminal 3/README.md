# ✈️ British Airways Lounge Eligibility Estimator

This project helps British Airways forecast **lounge demand** at Heathrow Terminal 3 by estimating the percentage of passengers eligible for different lounge tiers across broad flight categories.

## 📌 Objective

To create a **flexible and reusable lookup table** that shows the estimated percentage of eligible passengers for:

- **Tier 1** – Concorde Room (First Class + Elite loyalty)
- **Tier 2** – First Lounge (Gold members)
- **Tier 3** – Club Lounge (Business Class + Silver members)

## 📊 Approach

1. **Explored and cleaned** the provided flight schedule dataset.
2. **Grouped flights** by:
   - Time of Day (`TIME_OF_DAY`)
   - Route Length (`HAUL`)
   - Destination Region (`ARRIVAL_REGION`)
3. **Calculated**:
   - Total passengers per group (sum of all seat classes)
   - Total eligible passengers for each lounge tier
   - Converted to **percentages** for Tier 1, 2, and 3

## 🗃️ Final Output

A lookup table with columns:

| TIME_OF_DAY | HAUL  | ARRIVAL_REGION | Tier 1 % | Tier 2 % | Tier 3 % |
|-------------|-------|----------------|----------|----------|----------|

This table can be applied to **future flight schedules** to estimate lounge demand and support operational planning.

## 🛠️ Tools Used

- Python
- Pandas
- Excel (for manual inspection or export)

## 📁 Files Included

- `lounge_lookup_table.xlsx` – Final result
- `README.md` – This documentation

## 🙋‍♂️ Notes

- The Tier 1 column is included for hypothetical future planning, even though Concorde Room is not currently in Terminal 3.
- Percentages are rounded to 1–2 decimal places for practical use.
