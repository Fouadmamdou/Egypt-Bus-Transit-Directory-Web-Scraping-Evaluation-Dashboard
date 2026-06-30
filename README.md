# 🚌 Bus Companies & Stations in Egypt Dashboard
### شركات و مكاتب الاتوبيسات في مصر

An interactive Power BI dashboard that maps and ranks **bus companies, stations, and travel offices across Egypt**, making it easy to search, filter, and compare operators by location, rating, and contact details.

## 🧭 Overview

This dashboard organizes a dataset of Egyptian bus companies and stations (sourced from listings such as Google Maps/Places data) into a searchable, filterable directory. It's built for use cases like travel planning, market research on transport operators, or competitive analysis of bus companies by governorate.

## ✨ Key Features

- **Top stations/companies ranking** — horizontal bar chart of leading bus companies and stations (e.g., Go Bus, Blue Bus) ranked by volume (likely review count or trip volume)
- **Rating filter slider** — narrow results by rating range (1.00–5.00)
- **Governorate (محافظة) filter** — drill down to a specific governorate or view all of Egypt
- **Searchable company directory table** with:
  - Company Name (bilingual: Arabic & English)
  - Phone number
  - Street / Plus Code address
  - City / District (قسم)
- **RTL-friendly layout** — Arabic title and labels integrated alongside English data columns

## 📊 What the Dashboard Shows

| Element | Description |
|---|---|
| Bar Chart | Top 10 bus companies/stations ranked by count (e.g., حو باص, الموقف الجديد, Go Bus, Blue Bus branches) |
| Rating Slider | Filters companies/stations within a 1–5 star rating range |
| Governorate Dropdown | Filters all visuals by selected محافظة (governorate), default "All" |
| Data Table | Full directory list — name, phone, street, and city for each company/station |

## 🛠️ Tech Stack

- **Power BI** — dashboard design, filtering, and data modeling
- **Data source**: business listing data (e.g., Google Maps/Places export) for bus companies and stations across Egypt

## 🚀 Getting Started

1. Clone or download this repository
2. Open the `.pbix` file in **Power BI Desktop**
3. Refresh the data source if you've connected your own dataset
4. Use the governorate dropdown and rating slider to filter results, and explore the table for contact details

## 💡 Use Cases

- Quickly find bus operators in a specific governorate
- Compare top-performing bus companies/stations by popularity
- Filter out low-rated operators when planning travel
- Use as a base directory for travel agencies, researchers, or logistics planning

## 📌 Notes

- Some entries currently have missing phone numbers — data cleaning may be needed for full coverage
- Company names include both Arabic and transliterated/English variants for searchability
- Replace the sample dataset with an updated export to refresh rankings and contact info

---

*Built with Power BI to make Egypt's bus travel network easier to navigate.*
