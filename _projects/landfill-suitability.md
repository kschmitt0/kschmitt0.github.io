---
title: "Landfill Suitability Index"
date: 2026-04-15
tools: "ArcGIS Pro · Raster Analysis · Weighted Overlay"
summary: "A weighted suitability model identifying optimal landfill sites based on slope, soil infiltration rate, and distance to roads and streams."
thumbnail: /assets/images/landfill-suitability/hero.png
---

This analysis combines four weighted raster inputs — slope, soil infiltration class, distance to roads, and distance to streams — into a composite Landfill Suitability Index (LSI) highlighting the most viable locations for landfill siting while accounting for environmental and accessibility constraints.

**LSI = 0.2 × Slope + 0.5 × Infiltration + 0.15 × Roads + 0.15 × Streams**
