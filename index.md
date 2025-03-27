---
title: "San Francisco Crime: A Data Story"
layout: default
---

# Crime in San Francisco: A Decade in Data

*By Hanna Bortin | Social Data Analysis and Visualization*

---

##  Introduction

San Francisco is a vibrant, world-famous city — but like any major urban area, it faces challenges around crime. This story explores patterns in SF crime over the past two decades, using real police data to uncover trends, geographic hot zones, and time-based behavior. All prostitution-related crimes were excluded to focus on broader public safety concerns.

The data comes from the **San Francisco Police Department**, spanning **2003 to 2024**, and includes information on crime type, time, location, and police district.

---

## 1. Crime Over Time: Is SF Getting Safer?

![Line Chart](images/line_chart.png)

> **Figure 1**: Total reported crimes in San Francisco from 2003–2024.

Crime peaked in the early 2010s, then began to decline — potentially due to policing strategies or community programs. Crime dropped further during the COVID-19 pandemic, likely tied to lockdown measures and shifts in public activity.

---

##  2. Where Crime Happens: District Hotspots

![Heatmap](images/heatmap.png)

> **Figure 2**: Distribution of crime types across SF police districts.

The heatmap reveals that districts like **Tenderloin**, **Southern**, and **Mission** have higher crime rates — particularly for offenses like assault, drug/narcotics, and larceny/theft. In contrast, **Park** and **Richmond** are less crime-dense.

---

## 3. Weekly Crime Patterns (Interactive Bokeh)

This interactive chart reveals how different crimes vary throughout the week. For example:

- **Drunkenness** spikes on **weekends**
- **Assault** peaks midweek and weekends
- **Burglary** stays stable throughout

<iframe src="images/bokeh_chart.html" width="100%" height="600" frameborder="0"></iframe>

---

##  Conclusion

Together, these charts tell a cohesive story:

- **When**: Crime declined over time, with COVID marking a major drop.
- **Where**: Certain districts remain hotspots, suggesting policy intervention is still needed.
- **Why/How**: Weekly rhythms in crime align with human behavior — nightlife, workweek patterns, etc.

By visualizing the data, we empower citizens, policymakers, and researchers to make informed decisions for a safer city.

---

## References

- [SF Crime Data Portal](https://data.sfgov.org)
- [Bokeh](https://bokeh.org)
- [Narrative Visualization (Segel & Heer)](http://vis.stanford.edu/files/2010-Narrative-InfoVis.pdf)

