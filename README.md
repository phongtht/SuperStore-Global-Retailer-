
<img width="1000" height="600" alt="image" src="https://github.com/user-attachments/assets/37a7dfec-3d4c-4975-942c-a8b839e76d33" />


Change Icon emoji 🔥🔍📘🚩 to your likings by clicking "Start" + "."


# 📊 Global SuperStore Sales & Expansion strategy | Ecommerce | Power BI
 
 + Business question: The core questions of this project is showing important indicators for Senior Manager to decide in which markets to develop and which products are suitable for each international market.

 + Domain: E-commerce

**_📌You need to show that your projects are applicable to real business use cases, for a particular industry, not just "learning projects"_**

Author: Tran Huu Tran Phong 
Date: 14/11/2025 
Tools Used: Power BI 

---

## 📑 Table of Contents  
1. [📌 Background & Overview](#-background--overview)  
2. [📂 Dataset Description & Data Structure](#-dataset-description--data-structure)  
3. [🧠 Design Thinking Process](#-design-thinking-process)  
4. [📊 Key Insights & Visualizations](#-key-insights--visualizations)  
5. [🔎 Final Conclusion & Recommendations](#-final-conclusion--recommendations)

---

## 📌 Background & Overview  

### Objective:
### 📖 What is this project about? 
 
- Superstore is a rapidly developing company with a global business scale, spanning multiple markets and continents. This dataset compiles Superstore's worldwide sales information. Currently, the company is focused on the goal of increasing revenue in these markets to strongly drive market share expansion.

- This project analyzes sales trends and inventory control using Power BI. The objective is
✔️ Identify high-demand products and sales trends.  
✔️ Presenting business situation in international markets to Senior Manager.
✔️ Highlight important indicators for Senior Manager to decide in which markets to develop and which products are suitable for each international market through Power BI dashboards.. 


### 👤 Who is this project for?  

✔️ Data analysts & business analysts  
✔️ Senior Manager (Decision-makers) & stakeholders 

---

## 📂 Dataset Description & Data Structure  

### 📌 Data Source  
- Source:  Global Superstore Sales
- Size: 3 tables
  - Orders: columns & 21 columns
  - Sellers: 13 rows & 2 columns
  - Returns: rows & 2 columns 
- Format: .csv  

### 📊 Data Structure & Relationships  

#### 1️⃣ Tables Used: 3 tables
  - Table 1: **Orders**: Fact order
  - Table 2: **Sellers**: Information of Sales person
  - Table 3: **Returns**: Information of Returned orders

#### 2️⃣ Table Schema & Data Snapshot  

Table 1: Orders 

👉🏻 Insert a screenshot of table schema. if table is too long, only show a snapshot of it. Recommend to put it in a toggle format

<img width="799" height="608" alt="ord1" src="https://github.com/user-attachments/assets/a07f2b1a-9861-4468-9428-775a2eec7886" />

Table 2: Sales   

👉🏻 Insert a screenshot of table schema. if table is too long, only show a snapshot of it. Recommend to put it in a toggle format
<img width="662" height="166" alt="sale1" src="https://github.com/user-attachments/assets/12254693-82c3-49be-b820-dd865de81b4e" />

Table 3: Returns

<img width="587" height="166" alt="ret1" src="https://github.com/user-attachments/assets/53a22f38-1070-4c27-84d5-a0f83bdcea63" />


#### 3️⃣ Data Relationships:  

 <img width="1143" height="660" alt="Capture" src="https://github.com/user-attachments/assets/0d42b08c-5c61-47c4-a135-634fcbd92dcb" />

---

## 🧠 Design Thinking Process   

👉🏻 Insert a screenshot of the Design Thinking steps (Screenshot your Excel design thinking tables for better presentation).  

1️⃣ Empathize  


2️⃣ Define point of view  


3️⃣ Ideate  


4️⃣ Prototype and review  



## 📊 Key Insights & Visualizations  

### 🔍 Dashboard Preview  

#### 1️⃣ Dashboard 1: Overview
👉🏻 <img width="1155" height="652" alt="overview" src="https://github.com/user-attachments/assets/3c001ab3-017b-4ace-b675-f6d232194df8" />


📌 Analysis 1:  
- Observation: Overall, we can see that Sales and Profit showed an upward trend over the years. EMEA and Africa had a high quantity of successful products sold. On the other hand, markets such as APAC, LATAM, US, and EU accounted for the majority of returned products. OfFice Supplies was a good category with 60.7%
- Insight 1:
   - Growth Trend:	Sales and Profit show a promising upward trend over the years.	The overall business model and global expansion strategy are fundamentally working and gaining momentum.
   - Successful Markets	EMEA and Africa have a high quantity of successful products sold.	These markets have strong product-market fit, efficient logistics, or high customer satisfaction, leading to a high success rate (low returns).
   - High Returns Risk:	APAC, LATAM, US, and EU account for the majority of returned products.	This is the most critical threat. High returns severely erode profit margins, increase operational costs (logistics, restocking), and damage customer loyalty in Superstore's largest, most established markets (US, EU, APAC).

- Recommendation:
  - Focus on the "Problem" Regions (APAC, LATAM, US, EU): Since these regions represent major sales volume, reducing returns here will have the fastest and most significant impact on Profit.
  - Focus Growth: While focusing on reducing returns, continue the upward trend by targeting high-profit, low-return products for market share expansion in high-potential, stable regions like the EU and US, after returns are under control.

#### 2️⃣ Dashboard 2: Product
👉🏻 <img width="1156" height="653" alt="product" src="https://github.com/user-attachments/assets/72dce4f6-285f-4710-b0d3-5efac74b6e15" />


📌 Analysis 2:   
- Observation: Regarding products, Paper was the product that delivered the best Return on Sales (ROS) (the percentage rate showing the amount of profit the company earned from every dollar of revenue), followed by Art, Labels, and Accessories. Conversely, products like Tables and Machines had low ROS; Tables specifically recorded an ROS of -8.46%. Over the course of that year, all product lines showed steady revenue growth. Technology was the best-selling product line, and products like Phones and Copiers achieved high total sales and total profit, followed by Furniture and then Office Supplies.

- Insights:
  - High-Volume Risk (Tables and Machines): The overall revenue growth across all product lines is positive, but this growth is being severely undermined by specific sub-categories. Tables (a sub-category of Furniture) and Machines (likely Technology) are acting as "profit sinks." Tables' ROS of -8.46% means that for every dollar of sales, the company lost over 8 cents. These products consume capital and labor while destroying margin.
  - High-Margin Efficiency (Paper, Art, Labels, Accessories): The smaller, less complex items, particularly those in Office Supplies (Paper and Labels) and the lighter Technology/Furniture accessories (Art and Accessories), are highly efficient at converting sales into profit. These items provide a financial buffer and are the true drivers of the company's overall positive profit trend.
  - The Hidden Cost of Volume: While Technology is the best-selling line (driven by high-profit Phones and Copiers), it likely masks the loss from Machines. Similarly, the overall Furniture line is dragged down dramatically by the high losses from Tables.

- Recommendation:
  - Fix or Eliminate Tables and Machines: Implement rapid cost reduction, renegotiate supplier costs, or increase the selling price. If profitability cannot be achieved, these items should be strategically phased out to immediately boost the company's overall ROS.

  - Leverage High-Margin Products: Double down on cross-selling high-ROS items (Paper, Art, Labels) with high-volume categories to improve the overall transaction margin.

#### 3️⃣ Dashboard 3: Region  
👉🏻 <img width="1275" height="728" alt="region" src="https://github.com/user-attachments/assets/d65f92ef-9034-4391-a50b-838531eee583" />

📌 Analysis 3:  
- Observation: Central and South were the two regions that had the largest quantity of goods sold among all regions, which also corresponded to high total sales and total profit. Meanwhile, Canada was the region that recorded the lowest total profit and total sales compared to the other regions, but it experienced the highest return rate.

- Insights:
   - The combination of high volume and high profit of Central and South suggests that operations in these large regions are highly optimized. Supply chain, logistics, and operational cost management here are likely efficient, enabling Superstore to handle large order volumes while maintaining healthy profit margins. These regions represent the company's operational strength.

   - A high return rate in a low-volume market (Canada) is a dangerous indicator of operational inefficiency. Even with low sales, the cost of processing returns (reverse logistics, inspection, repackaging) will consume a very large proportion of the total profit, potentially leading to a net loss at the regional level (mirroring the issue seen with Tables). This likely stems from:

- Recommendation:  
  - Analyze the successful operational and cost management processes in Central and South to replicate them elsewhere.

  - An urgent cost/quality audit is needed in Canada. If the return rate cannot be brought down to an acceptable level, the company may need to scale back or temporarily suspend certain product lines in that region until the supply chain is fixed, preventing this small market from draining overall profitability.

## 🔎 Final Conclusion & Recommendations  

👉🏻 Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following:  

📌 The Core Strategy: Profitability First

 ✔️Eliminate the Loss Leaders: Urgently address the products with negative ROS, primarily Tables and Machines. If rapid cost negotiation or price increases cannot move them to profitability, they should be strategically phased out to instantly raise the company's overall ROS and free up capital.
 ✔️Mitigate Return Risks: Launch a priority audit focused on quality control and logistics in the high-return markets (APAC, US, EU) and the high-risk small market (Canada). Reducing the return rate is the most effective way to protect existing profit margins in key revenue markets.

📌 Strategy for Expansion

 ✔️Replicating Success: Analyzing and scaling the highly efficient operational models used in the Central and South regions to other high-potential areas.
 ✔️Targeting High-ROS Growth: Shifting marketing and sales efforts toward bundling or cross-selling high-margin items (Paper, Art, Labels) to improve the transaction profitability of the high-volume categories (Technology, Furniture).

