# Milestone 4: Warehouse Analytics & Final Dashboard

## Overview

This milestone completes the Supply Chain Visibility System project by bringing together warehouse-zone analysis, an executive overview, and dashboard validation using Power BI.

## Dashboard Pages

### Page 1: Warehouse Efficiency & Zone Analytics

* Analyses movement records across destination zones.
* Presents active movement rate and ETA variability by destination zone.
* Highlights the top five vessel types by movement count.
* Includes vessel speed versus ETA variability analysis.

### Page 2: Supply Chain Executive Overview

* Summarises unique vessels, total distance travelled, average ETA, ETA data completeness, and estimated transportation cost.
* Provides movement-status distribution and movement analysis by vessel type.
* Uses a treemap to analyse cargo categories and a chart to compare average ETA by destination zone.

### Page 3: Dashboard Performance & Validation

* Presents a destination-zone performance summary table.
* Includes total movements, total distance, average speed, average ETA, ETA variability, and estimated transportation cost.

## Dataset Limitations

The source AIS dataset does not contain actual warehouse inventory, warehouse capacity, picking accuracy, supplier records, or actual transportation-cost data. Destination clusters are used as proxy operational zones, and transportation costs are estimates based on an assumed cost-per-kilometre value. ETA data completeness indicates the availability of ETA values, not their accuracy.

## Dashboard Screenshots

The `Screenshots` folder contains:

* `M4-Page-1.png`
* `M4-Page-2.png`
* `M4-Page-3.png`

## Tools Used

* Microsoft Power BI Desktop
* Power Query
* DAX
* Git and GitHub
