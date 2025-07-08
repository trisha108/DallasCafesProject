# DallasCafesProject
Data-driven analysis of 2000+ Google reviews across 115 Dallas coffee shops, visualized in an interactive Tableau dashboard.

Ever spent hours reading conflicting café reviews trying to find the perfect spot?
This project solves that by scraping over 2,000 Google Map reviews from the last two years across 115+ independent coffee shops in Dallas, then building an interactive Tableau dashboard to help you pick your next café based on what matters most to you.

⸻

Project Overview

This project demonstrates how to:
	1. Extract detailed features such as highlights, recommendations, and customer issues for cafés based on review content
	2. Identify key attributes like pet-friendly, late hours, coziness, healthy options, and more using checkbox-style labels
	3. Clean, transform, and engineer these features using Python (pandas)
	4. Build an interactive Tableau dashboard to explore cafés by atmosphere, service, price, and other important factors

⸻

Features

1. Web Scraping
Used Apify and Make.com to scrape 2,000+ Google Map reviews from the past two years for 115+ Dallas cafés.
2. Data Cleaning and Feature Extraction
Initially attempted NLP techniques, but due to limited data, shifted to keyword-based labeling with pandas.
Extracted multi-label features via one-hot encoding for attributes like highlights, recommendations, customer issues, and tags such as pet-friendly, late hours, cozy, healthy, and study-friendly.
	•	Interactive Tableau Dashboard
	•	Filter cafés by ratings, atmosphere, price, service, and multiple feature checkboxes.
	•	Hover on map points to view photos, key highlights, recommendations, and issues.
	•	Quickly identify the most reviewed and highly rated spots.

⸻

End-to-End Workflow

1. Data Collection
Scraped recent reviews and metadata using Apify and Make.com.
2.	Data Processing
Cleaned and transformed data with pandas; used keyword searches to assign labels, then applied multi-label one-hot encoding for feature flags.
3.	Visualization
Developed and published an interactive Tableau dashboard for café exploration.

⸻

Key Questions This Answers

1.	Which cafés are cozy, pet-friendly, or open late without reading hundreds of reviews?
2.	What do customers highlight or recommend most?
3.	Where are the top-rated and most reviewed coffee spots in Dallas?

⸻

Tools Used

1.	Apify and Make.com for web scraping
2.	Python (pandas) for cleaning, keyword-based feature extraction, and multi-label one-hot encoding
3.	Tableau for building the interactive dashboard

⸻

Check it out here:
https://public.tableau.com/app/profile/trisha.shishodiya/viz/100DallasCafesAnalyzedHighlightsRecommendationsCustomerIssuesandmore/FinalDashboard
