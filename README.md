# Fashion Retail Analysis
![](https://github.com/NarokaPeter/FashionStoreAnalysis/blob/main/images.jpg)



## 🧠 Project Background
A fashion retail company in Lagos wants to optimize its sales strategy. This project analyzes customer purchase behavior and product performance to improve revenue, inventory, and customer satisfaction.

## ❓ Business Questions
1. Which brands and categories generate the highest revenue?
2. Are there any pricing trends influencing sales quantity?
3. How do product ratings affect sales performance?
4. Which product colors and sizes are most preferred?
5. What customer patterns can guide marketing efforts?

## 🛠️ Tools Used
- Microsoft Excel
- Excel Pivot Tables
- Conditional Formatting
- Lookup & Text Functions ( `VLOOKUP`, `LEFT`, `CONCATENATE`)
- Charts and Slicers
- Data Cleaning Techniques (removing blanks, fixing data types, etc.)

## 📁 Project Structure
- `data/`: Raw and cleaned Excel datasets
- `dashboard/`: Final Excel dashboard for insights delivery

## 🔍 Analysis
This section summarizes the key steps taken to explore and interpret the data.

### 1. 🧹 Data Cleaning
- Handled missing values (replaced blanks or removed invalid rows)
- Removed duplicate entries
- Converted columns to appropriate data types (Date, Number)
- Standardized text formatting (title casing, trimmed spaces)
- Created a new `Product ID` by combining Color Code + User ID (e.g., `YE25` for Yellow & ID 25)

### 2. 🧩 Feature Engineering
- Added a new column for **full size descriptions** (e.g., `S` → `Small`, `M` → `Medium`)
- Derived useful fields such as:
  - Sales Revenue (`Price × Quantity`)
  - Rating Categories (e.g., High, Medium, Low)

### 3. 📈 Exploratory Analysis (Using Pivot Tables & Charts)
- Identified top-selling **brands, categories, and products**
- Found price points that drive the **highest quantity of sales**
- Analyzed how **product ratings** correlate with sales volume
- Examined customer preferences by **color** and **size**
- Discovered patterns in customer purchases using filters and slicers

### 4. 📊 Dashboard Insights
- Interactive dashboard designed for executive view
- Displays KPIs such as:
  - Total Revenue
  - Top Categories & Products
  - Sales by Color & Size
  - Average Rating per Product
- Enables filtering by brand, category, and size

## Visualisation
![](https://github.com/NarokaPeter/FashionStoreAnalysis/blob/main/Fashion_dashboard.png)


You can interact with the interactive dashboard in Ms Excel [Here](https://1drv.ms/x/c/75c3ed7f5b24d0ab/EcEqYE9cY99OpgXESmSmWmEBaSbRZ9tx-tLtE5TItSkECA?e=d8LnJI)
## 📑 Final Recommendations
Based on the analysis:
- Focus inventory on top-performing brands(Nike and H$M) and preferred sizes (Small)
- Promote high-rated products to boost customer trust(Jeans and Sweater)
- Price sweet spots should be maintained to maximize quantity sold
- Use color preferences and rating data to guide seasonal campaigns
- Consider bundling low-rated, slow-moving items with top-sellers (Shoes)

## 👩‍💼 Prepared for
**Mrs. Ijeoma Shalewa**  
CEO, Fashion Retail Lagos

---

## ✍️ Author
**Naroka Peter**  
Junior Data Analyst | Public Health & Retail Insights  
📫 [Linkdn](https://www.linkedin.com/in/peter-naroka-39158a26a/?lipi=urn%3Ali%3Apage%3Ad_flagship3_feed%3ByqPDy7u8S0aAmtFZZQVATQ%3D%3D) | 📧 narokapeter@email.com


