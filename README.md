# Airbnb Analytics Dashboard — Power BI

An interactive 3-page Power BI report analyzing Airbnb listings, 
host performance, pricing, ratings, and review trends across multiple cities.

## 🔗 Live Dashboard
[Click to view the interactive report](https://app.powerbi.com/view?r=eyJrIjoiZWFjNzk4MmMtNDE1ZS00OGQ0LTg4MzUtN2Y4YzE0YWJiNmQ3IiwidCI6IjRiZDMwYmZlLTkyYzUtNDllNy05ZTllLTg5Nzk3MjJkYTBhMyJ9)

## 📋 Project Overview
This dashboard was built to answer key business questions about the Airbnb 
market — how listings are distributed, what drives higher ratings, and how 
review activity evolves over time.

## 📊 Dashboard Pages

### 1. Overview
- Total listings, cities, property types, and host count
- Host growth trend over time by room type (Entire Place, Shared Room, Hotel Room)
- High-level KPI cards for quick market snapshot

### 2. Ratings
- Superhost vs non-superhost listing count with cumulative % trend
- Average price comparison across room types
- Average rating by city (column chart)
- Pivot table: city-wise scores for Cleanliness, Communication, Accuracy & Value

### 3. Reviews
- Monthly review volume by city (clustered column chart)
- Reviewer frequency distribution with cumulative % (combo chart)
- Pivot table: detailed rating breakdown by city

## 🛠️ Tools & Techniques
- **Tool:** Microsoft Power BI Desktop
- **Data Modeling:** Star schema with Listings and Reviews tables
- **DAX Measures:** Superhost %, cumulative %, average price, average rating, 
  time intelligence
- **Visuals:** Line chart, bar/column charts, combo charts, pivot tables, KPI cards

## 📁 Files
| File | Description |
|------|-------------|
| `dashboard.pbix` | Power BI project file |

## 💡 Key Insights
- Superhosts maintain consistently higher ratings across all quality dimensions
- Pricing varies significantly by room type and city
- Review volume shows seasonal patterns with city-level variation

## 🙋 About
Built as part of a data analytics portfolio project.  
Connect with me on [LinkedIn](#) | [GitHub](#)
