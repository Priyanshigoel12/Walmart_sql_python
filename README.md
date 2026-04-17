# Walmart Sales Data Analysis — SQL + Python Project

<img width="680" height="420" alt="walmart_project_architecture" src="https://github.com/user-attachments/assets/b4bcf587-2973-4482-9d5e-34c95e199522" />
  <!-- Title banner -->
  <rect x="170" y="12" width="340" height="38" rx="10" fill="#0071CE" opacity="0.12" style="fill:rgb(0, 113, 206);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:0.12;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:16px;font-weight:400;text-anchor:start;dominant-baseline:auto"/>
  <text x="340" y="27" text-anchor="middle" font-family="sans-serif" font-size="11" font-weight="600" fill="#0071CE" opacity="0.9" style="fill:rgb(0, 113, 206);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:0.9;font-family:sans-serif;font-size:11px;font-weight:600;text-anchor:middle;dominant-baseline:auto">WALMART</text>
  <text x="340" y="43" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#0071CE" opacity="0.7" style="fill:rgb(0, 113, 206);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:0.7;font-family:sans-serif;font-size:10px;font-weight:400;text-anchor:middle;dominant-baseline:auto">End-to-End Python + SQL Project</text>

  <!-- KAGGLE BOX -->
  <g style="fill:rgb(0, 0, 0);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:16px;font-weight:400;text-anchor:start;dominant-baseline:auto">
    <rect x="30" y="160" width="120" height="80" rx="12" stroke-width="0.5" style="fill:rgb(12, 68, 124);stroke:rgb(133, 183, 235);color:rgb(255, 255, 255);stroke-width:0.5px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:16px;font-weight:400;text-anchor:start;dominant-baseline:auto"/>
    <text x="90" y="192" text-anchor="middle" dominant-baseline="central" style="fill:rgb(181, 212, 244);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:14px;font-weight:500;text-anchor:middle;dominant-baseline:central">Kaggle</text>
    <text x="90" y="212" text-anchor="middle" dominant-baseline="central" style="fill:rgb(133, 183, 235);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:12px;font-weight:400;text-anchor:middle;dominant-baseline:central">Dataset source</text>
    <text x="90" y="228" text-anchor="middle" dominant-baseline="central" style="fill:rgb(133, 183, 235);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:12px;font-weight:400;text-anchor:middle;dominant-baseline:central">API download</text>
  </g>

  <!-- Arrow: Kaggle → Python -->
  <line x1="152" y1="200" x2="228" y2="200" stroke="#378ADD" stroke-width="1.5" marker-end="url(#arrow)" style="fill:rgb(0, 0, 0);stroke:rgb(55, 138, 221);color:rgb(255, 255, 255);stroke-width:1.5px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:16px;font-weight:400;text-anchor:start;dominant-baseline:auto"/>
  <text x="190" y="193" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#378ADD" style="fill:rgb(55, 138, 221);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:sans-serif;font-size:10px;font-weight:400;text-anchor:middle;dominant-baseline:auto">.csv data</text>

  <!-- PYTHON BOX -->
  <g style="fill:rgb(0, 0, 0);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:16px;font-weight:400;text-anchor:start;dominant-baseline:auto">
    <rect x="230" y="120" width="160" height="160" rx="14" stroke-width="0.5" style="fill:rgb(8, 80, 65);stroke:rgb(93, 202, 165);color:rgb(255, 255, 255);stroke-width:0.5px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:16px;font-weight:400;text-anchor:start;dominant-baseline:auto"/>
    <text x="310" y="155" text-anchor="middle" dominant-baseline="central" style="fill:rgb(159, 225, 203);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:14px;font-weight:500;text-anchor:middle;dominant-baseline:central">Python</text>
    <text x="310" y="178" text-anchor="middle" dominant-baseline="central" style="fill:rgb(93, 202, 165);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:12px;font-weight:400;text-anchor:middle;dominant-baseline:central">Process data</text>
    <text x="310" y="196" text-anchor="middle" dominant-baseline="central" style="fill:rgb(93, 202, 165);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:12px;font-weight:400;text-anchor:middle;dominant-baseline:central">Clean data</text>
    <text x="310" y="214" text-anchor="middle" dominant-baseline="central" style="fill:rgb(93, 202, 165);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:12px;font-weight:400;text-anchor:middle;dominant-baseline:central">Load into RDBMS</text>
    <text x="310" y="232" text-anchor="middle" dominant-baseline="central" style="fill:rgb(93, 202, 165);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:12px;font-weight:400;text-anchor:middle;dominant-baseline:central">Feature engineering</text>
  </g>

  <!-- LIBRARIES label below Python box -->
  <rect x="230" y="292" width="160" height="96" rx="10" fill="#FAC775" opacity="0.22" stroke="#EF9F27" stroke-width="0.5" style="fill:rgb(250, 199, 117);stroke:rgb(239, 159, 39);color:rgb(255, 255, 255);stroke-width:0.5px;stroke-linecap:butt;stroke-linejoin:miter;opacity:0.22;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:16px;font-weight:400;text-anchor:start;dominant-baseline:auto"/>
  <text x="310" y="309" text-anchor="middle" font-family="sans-serif" font-size="9" font-weight="600" fill="#633806" style="fill:rgb(99, 56, 6);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:sans-serif;font-size:9px;font-weight:600;text-anchor:middle;dominant-baseline:auto">Libraries used</text>
  <text x="310" y="325" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#854F0B" style="fill:rgb(133, 79, 11);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:sans-serif;font-size:9px;font-weight:400;text-anchor:middle;dominant-baseline:auto">PANDAS</text>
  <text x="310" y="339" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#854F0B" style="fill:rgb(133, 79, 11);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:sans-serif;font-size:9px;font-weight:400;text-anchor:middle;dominant-baseline:auto">SQLALCHEMY</text>
  <text x="310" y="353" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#854F0B" style="fill:rgb(133, 79, 11);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:sans-serif;font-size:9px;font-weight:400;text-anchor:middle;dominant-baseline:auto">PYMYSQL</text>
  <text x="310" y="367" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#854F0B" style="fill:rgb(133, 79, 11);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:sans-serif;font-size:9px;font-weight:400;text-anchor:middle;dominant-baseline:auto">IPYTHON</text>

  <!-- Arrow: Python → MySQL -->
  <line x1="392" y1="200" x2="468" y2="200" stroke="#1D9E75" stroke-width="1.5" marker-end="url(#arrow)" style="fill:rgb(0, 0, 0);stroke:rgb(29, 158, 117);color:rgb(255, 255, 255);stroke-width:1.5px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:16px;font-weight:400;text-anchor:start;dominant-baseline:auto"/>
  <text x="430" y="193" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#1D9E75" style="fill:rgb(29, 158, 117);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:sans-serif;font-size:10px;font-weight:400;text-anchor:middle;dominant-baseline:auto">load</text>

  <!-- MYSQL BOX -->
  <g style="fill:rgb(0, 0, 0);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:16px;font-weight:400;text-anchor:start;dominant-baseline:auto">
    <rect x="470" y="110" width="170" height="180" rx="14" stroke-width="0.5" style="fill:rgb(113, 43, 19);stroke:rgb(240, 153, 123);color:rgb(255, 255, 255);stroke-width:0.5px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:16px;font-weight:400;text-anchor:start;dominant-baseline:auto"/>
    <text x="555" y="140" text-anchor="middle" dominant-baseline="central" style="fill:rgb(245, 196, 179);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:14px;font-weight:500;text-anchor:middle;dominant-baseline:central">MySQL</text>
    <text x="555" y="164" text-anchor="middle" dominant-baseline="central" style="fill:rgb(240, 153, 123);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:12px;font-weight:400;text-anchor:middle;dominant-baseline:central">SQL Topics</text>
    <text x="555" y="184" text-anchor="middle" dominant-baseline="central" style="fill:rgb(240, 153, 123);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:12px;font-weight:400;text-anchor:middle;dominant-baseline:central">GROUP BY</text>
    <text x="555" y="202" text-anchor="middle" dominant-baseline="central" style="fill:rgb(240, 153, 123);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:12px;font-weight:400;text-anchor:middle;dominant-baseline:central">Aggregation Func</text>
    <text x="555" y="220" text-anchor="middle" dominant-baseline="central" style="fill:rgb(240, 153, 123);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:12px;font-weight:400;text-anchor:middle;dominant-baseline:central">Window Function</text>
    <text x="555" y="238" text-anchor="middle" dominant-baseline="central" style="fill:rgb(240, 153, 123);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:12px;font-weight:400;text-anchor:middle;dominant-baseline:central">Date Functions</text>
    <text x="555" y="258" text-anchor="middle" dominant-baseline="central" style="fill:rgb(240, 153, 123);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:1;font-family:&quot;Anthropic Sans&quot;, -apple-system, BlinkMacSystemFont, &quot;Segoe UI&quot;, sans-serif;font-size:12px;font-weight:400;text-anchor:middle;dominant-baseline:central">Solve Business Problems</text>
  </g>

  <!-- Bottom label -->
  <text x="340" y="404" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#888780" opacity="0.9" style="fill:rgb(136, 135, 128);stroke:none;color:rgb(255, 255, 255);stroke-width:1px;stroke-linecap:butt;stroke-linejoin:miter;opacity:0.9;font-family:sans-serif;font-size:10px;font-weight:400;text-anchor:middle;dominant-baseline:auto">Data Analysis Pipeline — by Priyanshi</text>
</svg>walmart_project_architecture.svg…]()


## About This Project

Hi! I'm Priyanshi, and this is one of my end-to-end data analysis projects where I dug deep into Walmart's sales data to uncover real business insights. I used Python for data wrangling, SQL for querying, and structured my entire workflow from raw data to meaningful conclusions. If you're someone learning data analytics, I hope this project gives you a clear idea of how a full pipeline actually comes together.

---

## How I Built This — Step by Step

### 1. Setting Up My Workspace
- **Tools I Used**: VS Code, Python, MySQL
- I set up a clean folder structure inside VS Code so everything stays organized as the project grows.

### 2. Getting the Data via Kaggle API
- I grabbed my Kaggle API token from my profile settings and dropped the `kaggle.json` file into my `.kaggle` folder.
- Then pulled the dataset directly using:
  ```bash
  kaggle datasets download -d <dataset-path>
  ```

### 3. Downloading the Walmart Sales Dataset
- **Dataset**: [Walmart 10K Sales Dataset on Kaggle](https://www.kaggle.com/najir0123/walmart-10k-sales-datasets)
- Saved everything neatly inside the `data/` folder.

### 4. Installing Libraries & Loading Data
```bash
pip install pandas numpy sqlalchemy mysql-connector-python 
```
- Loaded the dataset into a Pandas DataFrame to start exploring it.

### 5. Exploring the Data
- Used `.info()`, `.describe()`, and `.head()` to understand the structure — column types, distributions, and potential data quality issues.

### 6. Data Cleaning
Here's what I cleaned up:
- Removed duplicates that could skew results
- Handled missing values — dropped where insignificant, filled where needed
- Fixed inconsistent data types (dates as `datetime`, prices as `float`)
- Cleaned up currency formatting using `.replace()`
- Did a final sanity check before moving ahead

### 7. Feature Engineering
- Added a `Total Amount` column by multiplying `unit_price × quantity` — this one column saved me a lot of repeated calculations in SQL later on.

### 8. Loading Data into MySQL
- Connected to database using SQLAlchemy
- Automated table creation and data insertion via Python
- Ran quick validation queries to confirm everything loaded correctly

### 9. SQL Analysis 
This is where I answered real business questions using complex SQL queries:
- Revenue trends across different branches and product categories
- Best-selling categories and peak sales periods
- Sales performance broken down by city, time of day, and payment method
- Customer buying patterns and rating trends
- Profit margin analysis by branch and category

### 10. Documentation & Publishing
- Documented the entire process in Markdown
- Published on GitHub with SQL scripts, notebooks, and this README

---

## Tech Stack

- **Python **
- **Databases**: MySQL
- **Libraries**: `pandas`, `numpy`, `sqlalchemy`, `mysql-connector-python`
- **Kaggle API** for data access

## Getting Started

```bash
git clone <repo-url>
pip install -r requirements.txt
```
Then set up your Kaggle API, download the data, and follow along!

---

## Project Structure

```plaintext
|-- data/               # Raw and cleaned datasets
|-- sql_queries/        # All my SQL scripts
|-- notebooks/          # Jupyter notebooks
|-- README.md           # You're reading it!
|-- requirements.txt    # Dependencies
|-- main.py             # Main pipeline script
```

---

## Key Findings

- **Sales Insights**: Identified top-performing categories, highest-revenue branches, and most-used payment methods
- **Profitability**: Pinpointed the most profitable product lines and locations
- **Customer Behavior**: Discovered peak shopping hours, rating patterns, and payment preferences

## What's Next

A few things I want to add in future iterations:
- Connect to Power BI or Tableau for interactive dashboards
- Bring in additional data sources for richer analysis
- Automate the pipeline for real-time ingestion

---

## Acknowledgements

- Data sourced from Kaggle's Walmart Sales Dataset
- Inspired by real-world Walmart case studies on sales and supply chain

