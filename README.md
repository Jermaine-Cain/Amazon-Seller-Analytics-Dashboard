# Retail Insights for Amazon Sellers: A Dashboard and Analysis Project

**Analyst:** Kugblenu Lanasiwaju | **[LinkedIn Profile](https://www.linkedin.com/in/lanasiwaju)**

---

### 1. Project Goal

I was tasked with analyzing a dataset of 1,465 Amazon products for RetailTech Insights. The primary goal was to dissect product listings and review data to generate clear, actionable recommendations for sellers looking to optimize their sales strategy, marketing efforts, and product positioning in a competitive marketplace.

---

### 2. The Final Product: An Interactive Insights Dashboard

To deliver these insights effectively, I developed a comprehensive, interactive dashboard in Microsoft Excel. The dashboard provides a high-level summary of key performance indicators (KPIs) and visualizes the most critical trends, with a slicer to allow for dynamic filtering by product category.

![Final Amazon Dashboard](Amazon_Seller_Dashboard.png)

---

### 3. Key Findings & Strategic Recommendations

The dashboard highlights three strategic insights that are critical for any Amazon seller's success:

*   **Insight 1: Focus on High-Value Categories.**
    Electronics and Home/Kitchen represent the largest potential for revenue. **Recommendation:** Sellers should double down on marketing spend and inventory for these high-performing categories to maximize returns.

*   **Insight 2: Ratings Are High, but Review Volume is the Competitive Edge.**
    Most products are already rated above 4.0, making high ratings a basic expectation. The true differentiator is a high *number* of reviews, which builds customer trust. **Recommendation:** Implement post-purchase email campaigns to actively encourage buyers to leave reviews.

*   **Insight 3: A "Combined Score" Identifies True Top Performers.**
    By combining ranks for both rating and review count, we can identify products that are both well-loved and popular. **Recommendation:** Sellers should analyze the titles, descriptions, and listing strategies of these top 5 products to create a best-practice template.

---

### 4. The Foundation: The Detailed Analysis Sheet

The insights on the dashboard are supported by a granular analysis of all 14 business questions from the project brief. This was accomplished using a series of detailed Pivot Tables, each designed to answer a specific question and uncover underlying trends.

![Detailed Pivot Table Analysis](Amazon_Seller_Pivots.png)

#### **Analytical Methodology**
The analysis followed a structured approach:
1.  **Data Cleaning:** Ensured data integrity and consistency across all 1,465 records.
2.  **Feature Engineering:** To create a more powerful metric for "best product," I engineered a `combined_score` by ranking products on both their average rating and total review count, then summing those ranks. This rewards products that perform well across both quality and popularity.
3.  **Systematic Pivot Table Analysis:** Built 14 distinct pivot tables to thoroughly investigate the data from multiple dimensions.
4.  **Dashboard Consolidation:** The most critical findings and visuals were surfaced in the final interactive dashboard for clear communication.

---

### 5. Repository Contents

*   **/Amazon_Product_Analysis.xlsx:** The complete Excel workbook. It includes the raw data, the detailed "PIVOT_TABLE" analysis sheet, and the final "DASHBOARD" sheet.
*   **/Amazon_Seller_Dashboard.png:** The screenshot of the main dashboard, as seen above.
*   **/Amazon_Seller_Pivots.png:** The screenshot of the detailed analysis sheet.
*   **/README.md:** This report.
