# 📊 Testher Group Profitability Report - 2014 | Tableau Dashboard

> Profitability analysis for Testher Group USA - $435K revenue across 4 regions, 8 customers, 6 products and 7 salespersons in 2014.

[Tableau](https://img.shields.io/badge/Built%20in-Tableau-green)
[Year](https://img.shields.io/badge/Year-2014-blue)
[Revenue](https://img.shields.io/badge/Total%20Revenue-%24435K-success)

### 🔍 Dashboard Preview
<img width="2838" height="1308" alt="Testher Group Dashboard Tableau" src="https://github.com/user-attachments/assets/fdbe7859-f3ad-4f50-917d-ec0bd3f5cfef" />

*Filters: Customer Name, Salesperson, Region, Year C.2014 | Limit: Top 5 by Revenue*

---

### 📌 Business Problem
Testher Group USA needed 2014 profitability diagnostic:
1. Who is top salesperson, city, region, product?
2. Which customers bring highest avg revenue?
3. How does regional monthly trend look?
4. Which states & cities drive performance?

### 📂 Dataset Overview
- **Year:** 2014
- **Total Revenue:** ~$435,036.16 (East $108,275.51 + North $141,660.34 + South $93,848.33 + West $91,251.98)
- **Top Salesperson:** Nancy F. / Nancy Freehafer - $104,242.34
- **Best City:** New York - $67.2K
- **Top Region:** Northern Region / North - $141,660.34
- **Top Product:** Coffee
- **Customers:** Company A, AA, BB, C, D, F, G, H

### 🛠️ Tools & Techniques
- **Tool:** Tableau Desktop
- **Tableau Skills:**
    - KPI Cards with conditional colors (Top Salesperson, Best City, Region of Year, Highest Grossing Product)
    - Pie Charts: Customer Performance by Avg Revenue, Regional Revenue
    - Horizontal Bar: Product Performance by Revenue, Performance Metric by Cities
    - Treemap: Salesperson's Performance by Revenue
    - Filled Map: States' Performance by Revenue (OR, WI, NY, TN)
    - Area Chart: Regional Monthly Performance Trend (Jan-Nov 2014)
    - Filters: Customer Name (multi-select), Salesperson, Region (East, North, South), Year
    - Top N Filter: Limit Top 5 by SUM(Revenue)
    - Mapbox + OpenStreetMap integration

### 📈 Key Insights

**KPIs:**
- Top Salesperson: Nancy F. $104K
- Best City: New York
- Region of Year: Northern Region
- Highest Grossing Product: Coffee

**1. Regional Revenue - North Dominates:**
- North: **$141,660.34 (32.5%)** - Top
- East: $108,275.51 (24.9%)
- South: $93,848.33 (21.6%)
- West: $91,251.98 (21.0%)
> North generates $33K more than East (+30.8%). Northern Region = Region of the Year.

**2. Customer Performance by Avg. Revenue - Company D is VIP:**
- Company D: **$2,467.11 avg revenue** - Highest, 2x others
- Company BB: $1,365.72
- Company H: $1,224.35
- Company F: $1,039.39
> Company D avg revenue is 80% higher than BB. Focus retention on Company D.

**3. Product Performance by Revenue - Coffee is King:**
1. Coffee: **~$46K**
2. Marmalade: ~$42K
3. Curry Sauce: ~$32K
4. Crab Meat: ~$16K
5. Mozzarella: ~$15K
6. Beer: ~$12K
> Top 3 products (Coffee, Marmalade, Curry Sauce) = ~$120K = 60% of product revenue. Coffee alone is highest grossing.

**4. Salesperson's Performance - Nancy Freehafer Dominates:**
- Nancy Freehafer: **$104,242.34 (24% of revenue)**
- Anne Larsen: $93,848.33 (21.6%)
- Andrew Cencini: $67,180.50 (15.4%)
- Mariya Sergienko: $42,370.88
- Robert Zare: $32,530.60
- Laura & Jan: Remainder
> Top 2 salespersons (Nancy + Anne) = $198K = 45.5% of total revenue. Nancy is Top Salesperson $104K.

**5. Performance Metric by Cities - New York is Best:**
- New York: **$67.2K (32%)**
- Portland: $50.2K (Oregon - matches OR $50,198.35)
- Memphis: $43.7K (Tennessee - matches TN $43,703.00)
- Milwaukee: $37.4K
> New York (East region) drives 62% of East's $108K revenue. Best Performing City = New York.

**6. States' Performance by Revenue:**
- NY: $67,180.50 (East - New York city)
- OR: $50,198.35 (West - Portland)
- TN: $43,703.00 (South - Memphis)
- WI: $37K+ (North - Milwaukee)
> Map shows 4 states driving performance, matching city data.

**7. Regional Monthly Performance Trend - North Leads Q4:**
- Jan-Mar: East leads, North low
- May-July: South spikes to $28K (seasonal?)
- Sep-Nov: North surges to **$19.99K avg** and dominates Nov with $32K+ peak
- North shows strongest Q4 finish
> North's Q4 surge makes it Region of the Year.

### 💡 Recommendations 

**1. Replicate Top Salesperson Playbook - Nancy F. $104K Model**
Nancy Freehafer generated $104,242.34 (24% of total $435K) - $10K above Anne Larsen $93,848.33. Analyze Nancy's customer mix: Does she own Company D ($2,467 avg revenue)? Interview Nancy to document her sales process and train team (Andrew $67K, Mariya $42K, Robert $32K). If all 7 salespersons performed at Nancy's level, potential revenue = 7 * $104K = $728K vs current $435K = **+$293K upside**.

**2. Protect VIP Customer - Company D $2,467 Avg Revenue**
Company D avg revenue $2,467 is 80% higher than second best Company BB $1,365. This is a whale customer. Build churn risk model: If Company D churns, lose ~$20K+ annual revenue (assuming 8-10 orders). Recommend dedicated account manager (Nancy F.) and quarterly business reviews. Also analyze what Company D buys - likely Coffee + Marmalade - create bundle for similar customers.

**3. Double Down on North Region - $141,660 (32.5% Share)**
North $141,660 vs South $93,848 = 50.9% higher. North also shows strongest monthly trend: $19.99K average and Nov peak at $32K. Investigate why North wins: Is it Milwaukee city $37.4K alone or multiple cities? Recommend allocating 35% of 2015 marketing budget to North, replicating North's Q4 strategy (likely holiday push) to East and West which lag at $108K and $91K.

**4. Product Strategy - Coffee $46K is Highest Grossing Product**
Product ranking: Coffee ~$46K, Marmalade ~$42K, Curry Sauce ~$32K vs Beer ~$12K (lowest). Top 3 = 60% revenue. Recommend:
- Increase Coffee inventory by 25% for 2015, raise price by 5% (low elasticity for top product) - potential +$2.3K profit
- Discontinue or reposition Beer ($12K lowest) - analyze margin, not just revenue
- Bundle Coffee + Marmalade (top 2) as "Breakfast Bundle" to lift average order value

**5. City Expansion - New York $67.2K is Best Performing City**
New York $67.2K = 62% of East region $108K and 32% of product city total. Portland $50.2K = 55% of West $91K. Both are single-city dependent. Risk: If New York client churns, East collapses. Recommend expanding to 2nd city in East (Boston, Philadelphia) and West (Seattle, San Francisco) to diversify. Target 2 cities per region by Q3 2015.

**6. Seasonality Play - Leverage May and November Peaks**
Regional Monthly Trend shows clear peaks: May (~$28K South spike) and November (~$32K North peak). These are likely summer and holiday seasons. Build forecasting model: Use 2014 monthly data to forecast 2015 with seasonality. Recommend pre-stocking inventory in April for May spike and October for November spike, and running targeted campaigns for South in May and North in November.


### Tableau Public Link: https://public.tableau.com/shared/3KM22KXP5?:display_count=n&:origin=viz_share_link

