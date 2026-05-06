airbnb-data-analysis
# Airbnb Data Analysis – Manhattan Listings

## Overview
This project analyzes Airbnb listing data in Manhattan to identify high-performing listings and uncover trends in guest demand. The analysis focuses on the most popular neighborhoods, listing characteristics, and estimated revenue performance.

## Objectives
- Identify the top-performing Airbnb neighborhoods in Manhattan
- Analyze guest interest using review data
- Examine bedroom distribution across popular areas
- Estimate listing revenue based on calendar data

## Key Insights
- The top 10 neighborhoods with the highest guest interest include Harlem, Lower East Side, Hell’s Kitchen, and Upper West Side.
- Studio apartments (0 bedrooms) are the most common listing type in high-demand areas like Midtown.
- Estimated revenue varies significantly, ranging from $0 (no bookings) to over $29,000 annually.
- High-performing listings were identified using total estimated revenue calculations.

## Data Sources
- **Listings Dataset**: Includes neighborhood, bedroom count, and listing details
- **Calendar Dataset**: Daily availability and pricing used to estimate revenue

## Methodology
1. Filtered listings to the top 10 neighborhoods based on number of reviews (proxy for demand)
2. Analyzed bedroom distribution across these neighborhoods
3. Calculated revenue by:
   - Summing nightly prices for booked days
   - Estimating annual revenue from calendar data
4. Ranked listings based on total estimated revenue

## Project Structure
- `Start Here`: Executive summary and table of contents
- `Listings`: Raw dataset used for analysis
- `Calendar`: Pricing and availability data
- `Pivot Table – Top Neighborhoods`: Demand analysis
- `Bedroom Count Distribution (%)`: Listing composition by size
- `Top Earning Listing ID`: Revenue ranking of listings

## Tools Used
- Google Sheets
- Pivot Tables
- Data Cleaning & Filtering
- Basic Revenue Modeling

## How to Use
1. Open the spreadsheet
2. Start at the **"Start Here"** tab for an overview
3. Navigate through the tabs to explore different parts of the analysis

## Future Improvements
- Incorporate location-based mapping
- Add seasonal pricing analysis
- Use Python or SQL for deeper analysis
- Build a dashboard for visualization

## Author
Taniya Cameron
