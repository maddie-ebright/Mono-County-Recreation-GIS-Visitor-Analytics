# Mono-County-Recreation-GIS-Visitor-Analytics
# Mono County Recreation Analytics & GIS

## Project Overview

As a Recreation Data Technician with Mono County, I support recreation planning and public land management through data analysis, GIS, and interactive mapping.

My work focuses on transforming large recreation datasets into actionable insights that help identify visitor trends, prioritize infrastructure improvements, and support data-driven decision-making across Mono County.

Because this project involves government and organizational data, this public repository contains demonstration materials and documentation only. Original datasets, internal analyses, and county maps are not included.

---

## The Challenge

Mono County manages hundreds of miles of trails and public lands with limited staff and funding.

One of the key questions facing the county is:

> **Where should limited time and resources be invested to have the greatest impact on visitors and public lands?**

Answering that question requires understanding:

- Where visitors are recreating
- How recreation patterns change over time
- Which locations are growing the fastest
- When visitors are most active
- Where future infrastructure may be needed

---

## My Role

My responsibilities include:

- Recreation data analysis
- GIS mapping
- Interactive dashboard development
- Spatial analysis
- Visitor trend analysis
- Trail usage analysis
- Data visualization
- Recreation planning support

---

## Interactive GIS Mapping

One of the primary projects has been developing an interactive GIS map that allows users to explore recreation activity throughout Mono County. It includes several features that allow you to look at the map in different ways.

This map is just a demo. The full production version uses real Strava Metro data licensed to Mono County which cannot be shared publicly. Hex and trail names have been replaced with generic labels ("Example Area", "Example Trail") and only a sample of locations are shown. Trail segments appear shorter than real-world trails because Strava Metro edge data breaks named trails into many small geographic segments — a trail like Minaret Road is made up of dozens of individual segments in the underlying data. The demo filters to segments with more coordinate points to make them more visible, but they still represent individual segments rather than complete trails end to end. The full production map shows all 57,801 segments across the county with real trail names matched via OpenStreetMap.

The real map I built with I used Claude Code with Python, DuckDB, GeoPandas, and Leaflet.js to visualize outdoor recreation activity data from Strava Metro for visitor management and trail infrastructure planning. Features two views — a hex grid heatmap, showing activity by geographic area and a trail view showing activity on specific OSM-matched trail segments — with toggleable overlays for USFS Wilderness, National Forest, and BLM boundaries sourced from official federal geodata. Includes year filtering, activity type filtering, coordinate and ID search, custom pin drop, and team name sharing via CSV import/export. This is a demo version with anonymized sample data (150 hexes, ~110 trail segments).

---

## Recreation Analytics

Using recreation datasets, I have analyzed topics including:

- Recreation growth over time
- Visitor activity by location
- Trail popularity
- Weekend vs weekday recreation
- Leisure vs commuter activity
- Time-of-day trends
- Regional recreation patterns
- Fastest-growing recreation areas
- Trail usage characteristics
- Potential infrastructure priorities

These analyses help provide objective information for recreation planning and public land management decisions.

---

## Strava Metro Analysis

A significant portion of my work involves analyzing Strava Metro recreation data.

The analysis includes:

- Pedestrian activity
- Cycling activity
- Regional trends
- Trail segment analysis
- Recreation hotspot identification
- Growth analysis
- Visitor behavior patterns
- Spatial trend analysis

The resulting analyses support recreation planning, visitor management, and prioritization of future projects.

---

## Datafy (Current Project)

I am currently expanding this work using **Datafy**, a recreation and tourism analytics platform.

Upcoming analyses include:

- Visitor spending patterns
- Length of stay
- Visitor origin and destination analysis
- Points of Interest (POIs)
- Charts and graphs of our POIs
- Economic impact
- Tourism trends
- Interactive dashboards
- Geographic visualizations
- Recreation demand analysis

The goal is to combine recreation activity with visitor behavior and economic data to create richer dashboards that support tourism planning and public land management.

---

## Technologies Used

- ArcGIS
- GIS
- Python
- SQL
- Datafy
- Strava Metro
- Interactive Mapping
- Spatial Analysis
- Data Visualization
- GitHub

---

## What This Project Accomplishes

This work helps transform recreation data into information that supports real-world decision-making.

The analyses can help organizations:

- Prioritize trail maintenance
- Identify recreation hotspots
- Monitor visitor trends
- Support infrastructure planning
- Improve visitor management
- Better allocate limited resources
- Understand changing recreation patterns
- Support data-driven planning
