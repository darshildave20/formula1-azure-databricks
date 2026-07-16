# Notebook Execution Order

Execute the notebooks in the following sequence.

---

## Bronze Layer

1. ingest_circuits
2. ingest_constructors
3. ingest_drivers
4. ingest_lap_times
5. ingest_pit_stops
6. ingest_qualifying
7. ingest_races
8. ingest_results
9. ingest_sprint_results

---

## Silver Layer

1. transform_circuits
2. transform_constructors
3. transform_drivers
4. transform_lap_times
5. transform_pit_stops
6. transform_qualifying
7. transform_races
8. transform_results
9. transform_sprint_results

---

## Gold Layer

1. calculate_race_results
2. calculate_driver_standings
3. calculate_constructor_standings

---

## Execution Flow

Landing

↓

Bronze

↓

Silver

↓

Gold
