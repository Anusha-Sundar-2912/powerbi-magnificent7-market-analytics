# powerbi-magnificent7-market-analytics 👋

📶 Dashboard

<img width="1381" height="850" alt="image" src="https://github.com/user-attachments/assets/8efe58b3-25c8-4597-9513-1efb6c8b2b72" />

📃 Features

At the top, the dashboard features the title “Magnificent Seven Market Analytics”, along with KPIs highlighting total market cap, YTD returns, and average growth rates. It provides a quick overview of the collective performance of Apple, Microsoft, Alphabet, Amazon, Meta, Nvidia, and Tesla.

📊 KPI (Key Performance Indicators)

This section presents key metrics such as:

YTD Return %

1-Year Return %

5-Year CAGR

Total Market Cap

These allow users to evaluate both short-term and long-term performance.

📈 Performance Analysis

A set of line and bar charts track daily, monthly, and yearly returns for each company. Heatmaps highlight the best and worst performing months, while comparative bar charts show which company is driving the largest market gains.

📊 Valuation vs Profitability

A scatter plot displays companies on axes of valuation multiples vs profitability margins, making it easy to spot “high growth, high profit” leaders versus overvalued or underperforming companies.

🌍 Contribution Analysis

A stacked column/area chart visualizes each company’s contribution to overall market performance, weighted by market capitalization and returns.

📋 Company Drill-Down

Each company has a detailed section showing:

Revenue and EPS growth trends

Net margins

Price movement over time

Historical return charts

📺 Overview

Overall, this dashboard is designed to provide a comprehensive financial and performance analysis of the Magnificent Seven technology companies. With interactive filters, slicers, and drill-downs, users can easily explore stock performance, fundamentals, valuation, and contribution to the market in a clean, storytelling-driven design.

🗂️ Data Source
The dashboard is powered by two CSV datasets stored locally:

companies.csv → Contains company information (name, ticker, and sector) for Apple, Microsoft, Alphabet, Amazon, Meta, Nvidia, and Tesla.

mag7_historical_market_cap.csv → Contains historical stock price and market capitalization data for the Magnificent Seven.

🎥 Visualization

https://github.com/user-attachments/assets/195671c2-ee1b-48c1-b64b-f2d497418ad4

📚 Documentation

This Power BI project demonstrates:

Data Cleaning & Modeling using Power Query

Time Intelligence (YTD, MoM, YoY) with DAX

Custom Visualization Design using a JSON theme

Financial Data Storytelling with KPIs, charts, and interactive filters

🎨 Branding and Assets

Custom theme JSON (magnificent7-theme.json) for consistent color palette across visuals.

Icons/logos can be added for each company for branding and context.

🌈 Color Palette

The dashboard uses a dark-themed outspace with a light canvas, along with semantic colors:

Green (#009F71) → Good / Positive trends

Yellow (#EF9C1F) → Neutral / Stable metrics

Red (#EC1836) → Bad / Negative trends

⚙️ Prerequisites

Before exploring or editing this project, it is useful to know:

Power BI Concepts

DAX (Data Analysis Expressions): Create measures like YTD Returns, CAGR, and Index Contribution.

Power Query: Data cleaning, merging multiple tables, handling dates, missing values, and normalizing stock tickers.

Data Modeling: Relationships between Price, Fundamentals, Calendar, and Index tables.

Visualization Techniques: KPIs, line charts, heatmaps, scatter plots, and contribution charts.

Key Competencies

Understanding financial metrics: returns, CAGR, margins, P/E ratios.

Experience with interactive dashboard filters and bookmarks.

Ability to apply thematic design for readability and storytelling.

✨ With this dashboard, you can explore, compare, and analyze the Magnificent Seven companies in one place — turning raw financial data into clear, actionable insights.
