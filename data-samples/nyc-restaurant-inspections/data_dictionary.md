# Data dictionary — NYC Restaurant Inspections (50,000 rows)

Source: NYC Open Data, DOHMH New York City Restaurant Inspection Results (dataset 43nn-pn8j). Downloaded 2026-11-11. Full source: 294,700 records. This file: the 50,000 most recent inspections, 2026-05-21 to 2026-11-09, ordered newest first.

| Column | Meaning |
|---|---|
| camis | Restaurant ID assigned by DOHMH (use this to group one restaurant's inspections) |
| dba | Restaurant trade name ("doing business as") |
| boro | Borough (Manhattan, Brooklyn, Queens, Bronx, Staten Island; 0 = not recorded) |
| building | Building number of the restaurant address |
| street | Street of the restaurant address |
| zipcode | ZIP code |
| phone | Business phone number from the inspection record (public listing number) |
| cuisine_description | Type of cuisine |
| inspection_date | Date of the inspection |
| action | Action taken (e.g. violations cited, establishment closed) |
| violation_code | Short code for the violation found, if any |
| violation_description | Full text of the violation found, if any |
| critical_flag | Critical / Not Critical / Not Applicable |
| score | Inspection score (lower is better under DOHMH scoring; blank where no score was given) |
| grade | Letter grade A, B, C, or other code; blank where no grade was given |
| grade_date | Date the grade was issued |
| record_date | Date the record was added to the dataset |

Notes: 23,670 of the 50,000 rows carry no letter grade. Scores in this file range 0–212. No rows were edited, estimated or invented.
