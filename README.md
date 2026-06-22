!. Problem Statement :
Zomato's management needed to identify which global markets offered the best opportunity for restaurant expansion — and what pricing, cuisine, and service models would drive success in those markets.
2. Data Overview :
Zomato's global restaurant dataset: 9,551 records across 15 countries, 2010–2018. Two tables (Raw Data + Country Description), 20+ attributes including ratings, votes, cuisine types, pricing, delivery features, and cost-for-two. Required cleaning — missing Cuisines values and inconsistent date formatting.
3.Tools & Steps :
Excel — cleaned data using Go to Special and DATEVALUE/SUBSTITUTE for date formatting; used VLOOKUP to map country codes; built Pivot Tables for distribution and trend analysis; applied SUMPRODUCT/array formulas for conditional aggregation; used CONCATENATE + MID/FIND for custom currency columns; applied Conditional Formatting with OR logic to highlight target markets.
Findings :
India dominates at ~91% of listings — leaving Philippines, Indonesia, Turkey, New Zealand, and South Africa as underleveraged markets based on average ratings and number of votes. Restaurants offering both online delivery and table booking rated 34% higher (3.60 vs 2.68). Price Range 3–4 consistently correlated with higher ratings. Most restaurants clustered in low-to-mid ratings (2.5–3.5), signaling a quality gap.
Recommendations and Conclusion :
Recommended prioritising Philippines and Indonesia for expansion, with localised pricing strategies and a full digital model (delivery + table booking). Provided city-level recommendations and competitive landscape analysis to guide onboarding of high-quality restaurant partners.
