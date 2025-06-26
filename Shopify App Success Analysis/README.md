
# 📈 Shopify App Analysis – Power BI Project

## 🎯 Project Objective
This Power BI analysis explored data from the Shopify App Store to:
- Measure the app landscape and review activity over time.
- Assess relationships between review counts, ratings, and developer responsiveness.
- Identify key drivers of app success and customer engagement.

## 📊 Analysis Overview

### App Landscape
- Counted unique apps with a KPI Card.
- Analyzed review count trends over time using a Line Chart (by lastmod date).
- Explored relationship between review count and average rating via Scatterplot.

### Reviews
- Created `helpful_reviews` metric: `rating * (1 + helpful_count)`.
- Measured impact of developer replies on average ratings with scatterplot comparison.

### App Reviews
- Linked Reviews and Apps tables on `app_id` and `id`.
- Bar charts comparing developers by:
  - Sum of ratings
  - Average *helpful_review* metric
  - Developer responsiveness (with review count > 500 filter)

## ✅ Key Findings
- Apps with more reviews generally maintain a good average rating, but outliers exist.
- Developer responsiveness is correlated with higher average ratings.
- Focusing on *helpful_review* scores provides a more accurate picture of app quality.

## 🚀 Recommendations
- Promote developer responsiveness to improve app ratings and reputation.
- Encourage high-quality, helpful reviews.
- Guide merchants towards apps and developers with both strong ratings and responsiveness.

## 🗂 Project Structure
- `App Landscape` – Summary of app counts, trends, and review distribution
- `Reviews` – Analysis of review quality and developer replies
- `App Reviews` – Developer-level insights on ratings and engagement
- Eight screenshots demonstrating visual outputs per requirement

## 💾 Notes
- Dataset: `shopify.xlsx` containing Apps, Categories, Reviews, and Join tables
- Tools: Power BI Desktop
