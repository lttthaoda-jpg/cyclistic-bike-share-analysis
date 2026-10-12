
# Cyclistic Bike-Share: Member vs. Casual Rider Analysis
Capstone case study (Google Data Analytics Certificate). Cyclistic is a fictional company; the analysis uses public Divvy trip data.
## Business question
How do annual members and casual riders use Cyclistic bikes differently?
## Data
- Divvy trip data (Lyft Bikes and Scooters, LLC), 4.05M trips, Feb-Aug 2026
- The raw data is not included in this repo because of its size. It is publicly available from the Divvy data portal.
## Tools
R / Quarto (main analysis), Claude AI (coding and writing support), Excel (filtering and sorting)
## Key findings
- Casual trips are longer and more variable (median 11 vs. 9 min); trips over 60 min are about 6x more common (4.1% vs. 0.7%).
- Casual demand peaks on weekends (38.0% of trips), with Saturday alone at 21.8%.
- Both groups favor e-bikes (74.5% vs. 68.9%), but casual riders' classic-bike trips run much longer (median 16 vs. 10 min).
## Recommendation
Design weekend-specific incentives for casual riders and validate them with a randomized test.
## Files
- `a.Roccc.qmd`: data credibility check and cleaning
- `b.Analyze.qmd`: main analysis
- `c.Double Check.qmd`: robustness checks
- `Report Final.pdf`: full report
