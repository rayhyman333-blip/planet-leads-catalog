# Data dictionary — NYC 311 Service Requests (50,000 rows)

Source: NYC Open Data, 311 Service Requests from 2020 to Present (dataset erm2-nwe9). Downloaded 2026-11-11. Full source: 23,100,861 requests. This file: the 50,000 most recent requests, 2026-11-05 to 2026-11-10 (about five days of citywide volume), ordered newest first.

| Column | Meaning |
|---|---|
| unique_key | Unique ID for the request |
| created_date | When the request was filed |
| closed_date | When the request was closed (blank if still open) |
| agency | Agency abbreviation that handles the request |
| agency_name | Full agency name |
| complaint_type | Top-level complaint category |
| descriptor | More specific description of the complaint |
| location_type | Type of location (e.g. Residential, Street/Sidewalk) |
| incident_zip | ZIP code of the incident |
| incident_address | Street address of the incident (where given) |
| city | City (New York) |
| borough | Borough (or Unspecified) |
| status | Open, Closed, In Progress, Assigned, Pending |
| community_board | Community board of the incident |
| latitude / longitude | Location coordinates (where given) |

Notes: no rows were edited, estimated or invented. A "Closed" status means the city closed the request; it does not prove the underlying problem was fixed.
