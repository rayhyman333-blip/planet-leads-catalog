# Data dictionary — NYC Motor Vehicle Collisions (50,000 rows)

Source: NYC Open Data, Motor Vehicle Collisions — Crashes (dataset h9gi-nx95). Downloaded 2026-11-11. Full source: 2,304,731 crashes. This file: the 50,000 most recent crashes, 2026-04-10 to 2026-11-08, ordered newest first.

| Column | Meaning |
|---|---|
| crash_date / crash_time | Date and time of the crash |
| borough | Borough (blank where not recorded) |
| zip_code | ZIP code of the crash |
| latitude / longitude | Location coordinates (where given) |
| on_street_name | Street the crash happened on |
| cross_street_name | Nearest cross street |
| off_street_name | Off-street location, if any |
| number_of_persons_injured / killed | Total people injured / killed |
| number_of_pedestrians_injured / killed | Pedestrians injured / killed |
| number_of_cyclist_injured / killed | Cyclists injured / killed |
| number_of_motorist_injured / killed | Motorists injured / killed |
| contributing_factor_vehicle_1 / 2 | Factor recorded by police for vehicle 1 / 2 ("Does Not Apply" = none recorded) |
| vehicle_type_code1 / 2 | Vehicle type for vehicle 1 / 2 |

Notes: no rows were edited, estimated or invented. Contributing factors are police judgments at the scene, not court findings. No personal data is included.
