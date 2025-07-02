![AMAZON Project Dashboard by David Osatuyi](https://github.com/user-attachments/assets/57bb6447-95d4-4767-bfc1-fdd7d6cf0268)
TECHNICAL REPORT
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
This report tracks the performance of books published in 2009–2019 across various countries on Amazon. It includes the story of the data and every process taken to achieve our insights. These are the sections for this report below;

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
● Introduction

● Story of Data

● Data Splitting and Preprocessing

● Pre-Analysis

● In-Analysis

● Post-Analysis and Insights

● Data Visualizations & Charts

● Recommendations and Observations

● Conclusion

● References & Appendices

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
INTRODUCTION
------------
Objective Of the Project

This project examines user ratings, reviews, price, genre, and authorship, helping to analyze market trends, reader preferences, and regional differences in book success.

Problem Being Addressed

The report seeks to identify books having the highest reviews and rating, the key authors driving revenue, recognize the dominant genres, seasonal trends, and optimize sales strategies.

Key Datasets and Methodologies

Datasets:

1. Book

2. Book review

3. Year

4. User Rating

5. Genre

6. Country

7. Author

Methods: Data Cleaning, Pivot Tables, and Dashboard Creation

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
STORY OF DATA
-------------
Data Source
Kaggle.com

Data Structure
Each row represents Best Sellers, while each column represents categories such as Author, User rating, Reviews, Price,and Year of Sales.

Data Limitations or Biases
The dataset is subject to sampling bias, which arises from the presence of unrepresentative samples. This means that certain characteristics are overrepresented or underrepresented, potentially leading to limited generalizability; however, results may not be applicable to other contexts or groups.

DATA SPLITTING AND PREPROCESSING
--------------------------------
Data Cleaning
● Removed repeated entries.

● Checked the date formats and put them in standard form.

● Converted revenue to numeric data and formatted it to the dollar currency.

Handling Missing Values
● Used Excel functions to fill gaps.

• Deleted rows with irrelevant records

Data Transformations
None was done

Data Splitting
● The following columns were split and identified as independent variables:

● Year

● User Rating

● Genre

● Country

● Author

● Price

● The dependent variables: Reviews

Industry Context
● Publishing / Book Retail Industry Data

● Knowing the industry type of data gives perspective into the analysis to be made and what success means to such a company.

Stakeholders
● Book Publishers

● Retailers (e.g., Amazon, Barnes & Noble)

● Authors

● Marketing Teams

● Editors & Acquisition Teams

● Publishing Executives

Value to the Industry
● Insights from this report help optimize author performance and effective pricing that drives both profitability and customer satisfaction.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
PRE-ANALYSIS
-------------------
Identify Key Trends
● Non—fiction contributes significantly to revenue.

● Some genres are preferred more than others.

● Some regions have significantly higher book than others.

● A certain book title has the highest reviews

Potential Correlations
● High revenue categories had consistent order frequency.

● Cities with high revenue seem to have high-performing books and authors.

Initial Insights
● Books with higher user ratings don’t always have the highest number of reviews, indicating that popularity and satisfaction aren’t always aligned. The top cities were in the top region.

● Fiction books tend to dominate high user ratings, while Non-Fiction titles often receive more reviews due to broader informational appeal

● Books priced between $5 and $15 appear to hit a sweet spot for both affordability and review engagement.

IN-ANALYSIS
-----------
Unconfirmed Insights
● Certain books had higher order frequencies.

● Some books and authors might have large quantity orders but low reviews and ratings.

Recommendations
● Prioritize Review Strategy for Non-Fiction.

● Target Countries with Low Presence.

● Focus on Yearly Publishing Trends

● Leverage Popular Fiction Titles

Analysis Techniques Used in Excel
● Pivot Tables

POST-ANALYSIS AND INSIGHTS
--------------------------
Key Findings
● Jeff Kinney has the highest number of books in the dataset (12), followed closely by Suzanne Collins, Rick Riordan, and Gary Chapman.

● Non-Fiction books contribute significantly more to revenue ($4,619) compared to Fiction ($2,698).

● The U.S., Canada, and the U.K. have the most books, with the U.S. leading at 47.

● Fiction books have fewer entries than Non-Fiction, but some Fiction titles lead in reviews and popularity.

Comparison with Initial Findings
Comparison with initial findings was not found.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
DATA VISUALIZATIONS & CHARTS
-----------------------------
![image](https://github.com/user-attachments/assets/fa7d47d3-eb7c-470c-8e29-f906d326d036)
The price trend report shows that 2009, 2012, and 2014 had the largest price increment.

![image](https://github.com/user-attachments/assets/f6dab241-a956-424e-ac21-f735778d61e1)
Non — friction books topped the demand list, hence generating the reviews, sales, and ratings.

![image](https://github.com/user-attachments/assets/f827f73e-6e8d-4724-b5df-89e08da016eb)
“The Fault In Our Stars” is our most reviewed book, while the number of reviews for “Becoming” came next.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
RECOMMENDATIONS AND OBSERVATIONS
--------------------------------
Actionable Insights
● I recommend that we segment our marketing based on book performance archetypes — high review/low price, high price/low review, and so on — to better target ads and placements.

● We need to amplify efforts in emerging markets like Nigeria, Ghana, and Kenya through local partnerships, book drives, or author tours, as they have a base but lack saturation.

● I recommend increasing our Non-Fiction reader base through reader-driven platforms like Goodreads, which are proven to help boost both engagement and perceived trust via reviews.

● We need to rethink the pricing strategy, especially for Fiction books. Titles priced between $5 – $15 tend to perform well. Implementing a pricing sweet spot could lead to improved sales conversion without sacrificing volume.

● Authors like Gary Chapman and Michelle Obama should be studied as case models for repeat success and cross-genre impact. Building case studies on their book success can help replicate similar outcomes for emerging authors.

● I recommend investing in curated bundles or special editions for top-performing titles like The Fault in Our Stars or Becoming to capitalize on their sustained demand.

● We need to bridge the gap between popularity and pricing by offering low-cost, high-traction books in premium packaging or limited editions to boost revenue without diminishing perceived value.

Optimizations or Business Decisions
● Leverage Popular Fiction Titles: Despite lower price contributions, Fiction books like The Fault in Our Stars and Gone Girl drive massive engagement. This suggests Fiction is more viral; invest in campaigns around Fiction titles to boost visibility and ratings.

● Capitalize on Author Consistency: Authors with repeat high-selling books (e.g., Jeff Kinney, Gary Chapman) show brand reliability. Use them in cross-promotions or loyalty campaigns.

● Focus on Yearly Publishing Trends: Peak revenue years could indicate strong publishing campaigns — replicate strategies from 2009, 2011, and 2012 for future releases.

● Target Countries with Low Presence: Markets like Nigeria, Kenya, and Ghana show potential (each has around 10 books). Expanding marketing efforts in these regions could unlock new readership bases.

● Prioritize Review Strategy for Non-Fiction: Although Non-Fiction contributes more revenue, Fiction leads in reviews. Strategic review solicitation for Non-Fiction can increase discoverability and trust.

Unexpected Outcomes
None found

CONCLUSION
-----------
Key Learnings
● Specific author, regions, and customer engagement strategies largely influence sales revenue.

● Region and promotional efforts significantly impact sales performance.

Limitations
The dataset is subject to sampling bias, which arises from the presence of unrepresentative samples. This means that certain characteristics are overrepresented or underrepresented, potentially leading to limited generalizability; however, results may not be applicable to other contexts or groups.

Future Research
● Explore additional data sources to assess sales margins and overall business sustainability.
