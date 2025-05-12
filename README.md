# 🏠 Real Estate Market Analysis Dashboard – Kenya 🇰🇪

![](https://github.com/MastingoJay/real-estate-full-project/blob/main/20cb36a8-055f-49a8-9367-b2d0c60cc2e4.jpg)

# 📌 Overview

This project was developed for a real estate firm in Kenya aiming to uncover insights into property trends, pricing, and data completeness. Using Power BI, a comprehensive dashboard was created to support data-driven decision-making across property development and marketing strategies.

The dashboard addresses key business questions:

- Which areas have the highest priced homes?

- How do the number of bedrooms or bathrooms affect pricing?

- What are the most common property sizes?

- Which listings are incomplete (e.g., missing size data)?

To meet these goals, the visuals focus on:

1. Location-Based Price Analysis – Identifies premium markets like Runda and Nyali to guide investment.

2. Bedroom-to-Price Comparison – Reveals how property features impact value and customer targeting.

3. Data Quality Checks – Highlights incomplete listings to drive listing improvements.

4. Price Distribution – Shows price ranges and outliers to support competitive pricing.

5. Key Performance Indicators (KPIs) – Provides metrics like average price and total listings to track market activity.

# 🛠️ Tools & Technologies Used

1. Python: For web scraping and data processing

2. PostgreSQL: For structured data storage and querying

3. Power BI: For data cleaning, modeling, and dashboard visualization

# Project Workflow

1. Data Collection (Python)
- Web scraping of real estate listings using:

  - requests

  - BeautifulSoup

  - pandas

2. Data Storage (PostgreSQL)
- Structured and cleaned dataset stored in a PostgreSQL database using:

  - sqlalchemy / psycopg2

3. Data Cleaning (Power BI)
- Performed additional cleaning and transformation in Power BI’s Power Query Editor:

  - Removed nulls and duplicates

  - Replaced missing values (e.g., “Size = N/A”)

  - Converted column types

  - Ensured consistency in naming/location fields

4. Data Visualization (Power BI)
- Connected Power BI to PostgreSQL for seamless data refresh

- Created multiple pages:

  - Home – Landing page with interactive navigation buttons

  - Dashboard – Core business visuals with slicers and insights

  - Insights – Written interpretations of data trends

- Added slicers (location, bedrooms, etc.) for dynamic filtering

- Applied conditional formatting to identify incomplete listings

# Navigation Instructions

- Buttons have been added to the Home, Dashboard, and Insights pages for easy navigation.

- To navigate, click on a button, then press Ctrl + Enter to move to the selected page.

# Key Dashboard Features

- Average Price by Location (Bar Chart)

- Price vs Bedrooms (Column Chart)

- Listings Missing Size (Card)

- Price Distribution (Histogram)

- Slicer for filtering data by Location, Bedrooms, or Property Type

- Interactive Navigation Buttons with images/icons for seamless experience

# Dashboard Summary & Business Insights
1. Top Premium Property Locations

  - Lavington and Off Convent Drive have the highest average prices, exceeding 100M KES.

2. Bedroom-to-Price Relationship

  - Properties with more bedrooms, especially 5-bedroom homes, have significantly higher prices.

3. Incomplete Listings (Missing Size Data)

  - A total of 66 listings are missing size information, affecting data quality.

4. Price Distribution Trends

  - Most properties are priced below 50M KES, with a few high-value outliers up to 100M KES.

5. Most Common Property Sizes

  - Property sizes commonly range between 225 and 400 sq.m.

6. Most Frequently Listed Area

  - Off Convent Drive has the highest number of property listings.

# Business Recommendations

1. Focus Marketing on High-Value Locations

  - Prioritize listings in premium areas like Lavington and Off Convent Drive for better ROI.

2. Segment Clients by Bedroom Demand

  - Tailor property promotions based on bedroom count to match buyer income levels and preferences.

3. Improve Data Completeness for Better Decision-Making

  - Enforce mandatory data fields and perform regular audits to maintain clean, reliable property data.

4. Align Development with Preferred Property Sizes

  - Develop properties in the 225–400 sq.m range to match market demand and drive quicker sales.

5. Monitor and Manage Price Outliers

  - Flag unusually priced properties for review and ensure pricing consistency across similar listings.

















