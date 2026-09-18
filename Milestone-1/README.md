# Milestone 1 — Data Modeling & KPI Foundation

## Overview

Milestone 1 establishes the data foundation for the Supply Chain Visibility System using Microsoft Power BI. The milestone focuses on preparing the vessel movement dataset, creating the data model, developing DAX measures, and building the initial dashboard for operational visibility.

## Objectives

- Prepare and clean the vessel movement dataset
- Create a structured data model for analysis
- Develop a date dimension for time-based analysis
- Establish relationships between the data tables
- Develop DAX measures and key performance indicators
- Build an initial vessel movement and supply chain visibility dashboard

## Key Activities

- Data import and preparation
- Data cleaning and transformation
- Creation of the `DimDate` table
- Data modeling and relationship creation
- DAX measure development
- KPI development
- Power BI dashboard development

## Data Model

The Milestone 1 data model consists of:

- `Fact_VesselMovement` — main vessel movement and operational data
- `DimDate` — date dimension used for time-based analysis

A date-based relationship was established between the `DimDate` table and the vessel movement fact table to support time-based reporting.

## Dashboard

The Milestone 1 dashboard, titled **Vessel Movement & Supply Chain Visibility Dashboard**, provides an initial view of vessel movement and operational metrics.

### Key KPIs

- Total Unique Vessels
- Total Vessel Records
- Average Speed
- Average ETA

### Key Visualizations

- Speed Category Distribution
- Average Distance by Status
- Average ETA by Hour
- Vessel Type Distribution
- Vessel Details Table
- Vessel Status Filter

These visuals provide an initial understanding of vessel activity, movement patterns, speed categories, ETA behavior, and vessel-level details.

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- Git & GitHub

## Screenshots

### M1 Dashboard

![M1 Dashboard](Screenshots/M1-Dashboard.png)

### M1 Data Model

![M1 Data Model](Screenshots/M1-Data-Model.png)

## Status

**Completed**
