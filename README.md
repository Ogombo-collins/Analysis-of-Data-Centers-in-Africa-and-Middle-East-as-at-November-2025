# Analyzing Data Center Distribution in Africa and the Middle East as at November 2025

## Overview
This project analyses the distribution of data centers across Africa and the Middle East to highlight regional disparities in digital infrastructure. Using country-level population and data center counts, the analysis reveals structural imbalances, regional leaders, and underserved markets shaping the digital economy.

## Objectives
- Compare data center distribution between Africa and the Middle East
- Normalize infrastructure access using data centers per million people
- Identify countries and regions outperforming or underperforming relative to size
- Highlight structural digital infrastructure gaps within Africa

## Dataset
The dataset covers **53 countries**:
- **41 African countries**
- **12 Middle Eastern countries**

### Key Variables
- `Country`
- `Sub_Region` (Africa or Middle East)
- `Population_M` (Population in millions)
- `Data_Centers` (Total number of data centers)
- `DC_per_Million` (Data centers per million people)

## Methodology
- Data acquisition, augmentation and cleaning and validation using Pandas
- Descriptive statistics and ranking analysis
- Regional aggregation and per-capita normalisation
- Comparative analysis across sub-regions and population sizes
- Insight-driven storytelling supported by tables and visualisations

## Key Insights
- Across 53 countries in Africa and the Middle East, there are 494 data centers: Africa, with 41 countries and over 1.4 billion people, hosts 253 data centres (51.2% of the regional total). The Middle East, comprising just 12 countries and a fraction of Africa's population, hosts 241 data centres (48.8%).
- The Middle East significantly outpaces Africa in data center density despite a smaller population: Israel alone (with 61 data centres serving 9.5 million people) has more digital infrastructure than Nigeria, Kenya, Egypt, and Morocco combined — countries with a combined population of over 450 million.
- Mauritius emerges as Africa's unlikely data centre champion. With just 1.3 million people, the island nation boasts 10 data centres—translating to 7.69 facilities per million people, more than eight times the continental average of 0.93.
- Several less populous African nations outperform larger economies on a per-capita basis.
- Over 20 African countries operate with only one data center, serving more than 150 million people.
- Infrastructure inequality exists not only between Africa and the world, but also within Africa itself.

## Folder Structure
```text
├── data/
│   ├── processed whole data/                  # Cleaned dataset containing Middle East and Africa data
│   └── processed Africa only/            # Cleaned and derived datasets focusingon Africa only
├── notebooks/
│   └── analysis.ipynb        # Main exploratory and analytical notebook
├── outputs/
│   ├── tables/               # Summary tables and rankings
│   └── figures/              # Charts and visual assets
├── README.md

