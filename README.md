# Supply Chain Visibility System with Optimization Analytics

A Power BI based Supply Chain Visibility System developed as part of the Infosys Springboard Virtual Internship.

The project focuses on analyzing vessel movement and supply chain related operational data using data modeling, DAX measures, interactive dashboards, trend analysis, and drill-down analysis.

## Project Overview

The objective of this project is to transform logistics and vessel movement data into meaningful analytical insights through Microsoft Power BI.

The project is developed progressively through multiple milestones, with each milestone extending the existing data model and dashboard capabilities.

## Technologies Used

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Data Visualization
- Microsoft Excel
- Git & GitHub

## Project Milestones

| Milestone | Focus | Status |
|-----------|-------|--------|
| Milestone 1 | Data Modeling & KPI Foundation | Completed |
| Milestone 2 | Inventory & Delivery Analytics | Completed |
| Milestone 3 | Supplier & Transportation Analytics | Completed |
| Milestone 4 | Warehouse Analytics & Final Dashboard | Completed |

## Milestone 1

Milestone 1 focused on establishing the data foundation of the project.

Key activities included:

- Data import and preparation
- Data cleaning
- Data modeling
- DimDate creation
- Relationship creation
- DAX measure development
- KPI development
- Initial Power BI dashboard

## Milestone 2

Milestone 2 extended the existing model to perform deeper operational analysis.

Key areas included:

- Vessel movement analysis
- Destination analysis
- Cargo analysis
- Distance analysis
- ETA analysis
- ETA variability
- ETA variance
- Slow and fast-moving vessel analysis
- Trend analysis
- Drill-down analysis
- Interactive filtering

## Milestone 3

Milestone 3 focused on supplier and transportation analytics using the available vessel movement data.

Key areas included:

- Transportation cost estimation
- Cost per kilometer analysis
- Movement analysis
- Active movement rate
- Average active distance per vessel
- Estimated transportation cost per vessel
- Transportation-related KPI development
- Interactive filtering and dashboard analysis

The source AIS dataset does not contain actual supplier, carrier, transportation cost, shipment cost, or quality score fields. Therefore, transportation-related elements were adapted using the available vessel movement data and an assumed cost-per-kilometer value.

## Milestone 4

Milestone 4 completed the project with warehouse-zone analysis, an executive overview, and dashboard validation.

Key areas included:

- Destination zone analysis
- Movement records by destination zone
- Active movement rate by destination zone
- ETA variability analysis
- Vessel type analysis
- Vessel speed and ETA analysis
- Supply chain executive overview
- ETA data completeness
- Estimated transportation cost
- Dashboard performance and validation
- Final dashboard documentation

Destination clusters were used as proxy operational zones because the source AIS dataset does not contain actual warehouse information.

## Repository Structure

```text
Supply-Chain-Visibility-System/
│
├── Dashboard/
│   ├── README.md
│   └── Supply-Chain-Visibility-System.pbix
│
├── Documentation/
│   └── Complete-Project-Documentation.pdf
│
├── Milestone-1/
│   └── Screenshots/
│
├── Milestone-2/
│   └── Screenshots/
│
├── Milestone-3/
│   ├── Screenshots/
│   │   └── M3-Dashboard.png
│   └── README.md
│
├── Milestone-4/
│   ├── Screenshots/
│   │   ├── M4-Page-1.png
│   │   ├── M4-Page-2.png
│   │   └── M4-Page-3.png
│   └── README.md
│
├── LICENSE
└── README.md
