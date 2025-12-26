# Product-Funnel-Conversion-Analysis


## Executive Summary
This project analyzes low order conversion rates at a fintech company to identify workflow drop-off points and quantify revenue impact. Using **SQL, Python, and Power BI**, order status data was extracted and modeled to build an end-to-end view of the user funnel.

The analysis revealed that the highest revenue opportunities come from improving **user interaction rates** and **completed bank login attempts**. Based on these findings, targeted product and engagement recommendations are proposed to increase conversion and revenue.

---

## Business Problem
Completed orders are a direct driver of revenue for the company. Product and sales stakeholders observed that a large percentage of users initiate an order but fail to complete it.

**Key Question:**  
Where do users drop out of the workflow, and what product changes can increase order completion?

---

## Methodology

### Data Extraction & Preparation
- Used SQL to extract, clean, and transform order status data from the production database  
- Validated data accuracy and standardized status definitions prior to analysis  

### Dashboarding & Monitoring
- Built an interactive **Power BI dashboard** to track orders at each stage of the funnel  
- Enabled client-level and status-level filtering for detailed analysis  

### Funnel & Impact Analysis
- Performed a **Python-based funnel analysis** to simulate incremental improvements  
- Modeled revenue impact from changes in user interaction and login success rates  

---

## Skills & Tools

### SQL
- CTEs  
- Joins  
- CASE statements  
- Aggregate functions  

### Power BI
- DAX  
- ETL pipelines  
- Calculated columns  
- Data modeling  
- Data visualization  

### Python
- Pandas  
- NumPy  
- Matplotlib  
- Statistical analysis  
- Funnel modeling  

---

## Results & Business Impact
- Created a centralized dashboard providing full visibility into the product funnel  
- Enabled stakeholder self-service, reducing ad hoc analytics requests by ~**5 hours per week**  
- Identified key drop-off points:
  - Nearly **50% of orders drop off before entering the workflow**
  - Fewer than **25% of users complete bank login credentials successfully**

### Revenue Impact Modeling
- **+1% user interaction rate** → **$285 additional daily revenue**  
- **+1% completed bank login attempts** → **$405 additional daily revenue**

---

## Product Recommendations
- Send reminder **emails and SMS** to re-engage inactive users  
- Partner with clients (e.g., mortgage lenders) to guide users through the workflow  
- Add workflow entry copy indicating completion time (e.g., “Takes 5 minutes”)  
- Introduce a **progress bar** to encourage completion  
- Improve messaging on the bank login page to reduce credential errors  

---


