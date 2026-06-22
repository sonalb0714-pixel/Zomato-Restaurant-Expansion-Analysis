## 🍴 Zomato Restaurant Expansion Analysis 

### 🎯 Problem Statement
Zomato's management needed to identify which global markets offered the best opportunity 
for restaurant expansion — and what pricing, cuisine, and service models would drive 
success in those markets.

### 📊 Data Overview
- **Records:** 9,551 restaurants across 15 countries (2010–2018)
- **Tables:** 2 (Raw Data + Country Description)
- **Attributes:** 20+ including ratings, votes, cuisine types, pricing, delivery features, and cost-for-two
- **Cleaning Required:** Missing Cuisines values and inconsistent date formatting

### 🛠️ Tools & Steps
**Tool Used:** Microsoft Excel

| Step | Action |
|------|--------|
| Data Cleaning | Used Go to Special to find blanks; filled missing Cuisines with "Unknown" |
| Date Formatting | Fixed dates using `DATEVALUE(SUBSTITUTE(T2,"_","-"))` |
| Country Mapping | Used `VLOOKUP` to map country codes to country names |
| Distribution Analysis | Built Pivot Tables for country-wise and year-wise restaurant counts |
| Conditional Aggregation | Applied `SUMPRODUCT` and array formulas |
| Custom Currency Column | Used `CONCATENATE + MID/FIND` to extract currency symbols |
| Highlighting Target Markets | Applied Conditional Formatting with `OR` logic |

### 📌 Findings
- 🇮🇳 India dominates with **~91% of total listings** — signaling low penetration in other markets
- 🌏 **Philippines, Indonesia, Turkey, New Zealand, and South Africa** are underleveraged markets based on average ratings and votes
- 🚀 Restaurants offering **both online delivery and table booking** rated **34% higher** (3.60 vs 2.68)
- 💰 **Price Range 3–4** consistently correlated with higher customer ratings
- ⚠️ Most restaurants cluster in **2.5–3.5 ratings** — indicating a clear quality gap in the market

### ✅ Recommendations & Conclusion
- **Primary markets:** Philippines and Indonesia recommended for expansion
- **Pricing strategy:** Localised pricing with a lean toward Price Range 3–4
- **Service model:** Full digital model (online delivery + table booking) for maximum ratings
- **Support provided:** City-level recommendations and competitive landscape analysis to guide onboarding of high-quality restaurant partners
