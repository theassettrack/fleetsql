# FleetSQL

Wialon to PostgreSQL ETL pipeline with multi-tenant isolation.

**[View Architecture →](https://theassettrack.github.io/fleetsql/)**

---

## What It Does

Extracts vehicle telemetry from Wialon GPS tracking platform into PostgreSQL databases. Each fleet gets its own isolated database.

## Key Features

- **Multi-Tenant** — database-per-fleet isolation
- **Unlimited History** — no data retention limits
- **Fast Resync** — correct and resynchronize data instantly
- **Automated Reports** — scheduled extraction and report generation
- **Active Units Only** — skips inactive vehicles automatically

## Data Extracted

**Vehicle Metadata**
- VIN, license plate, brand, model, year
- Fuel type, vehicle type
- Activity status

**Daily Metrics**
- Distance traveled
- Engine hours, motion hours, idling hours
- Fuel consumption
- Max speed, trip count

**Eco-Driving Events**
- Speeding, harsh acceleration/braking
- Harsh cornering, excessive idling
- Driver fatigue alerts

## Stack

- Node.js
- PostgreSQL
- Wialon Remote API

---

**by [Asset Track](https://assettrack.com)**