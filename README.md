# PowerBI Project: Sales Performance Dashboard for Blinkit – A Quick-Commerce company
## Project Overview

![Blinkit_Logo](https://github.com/SagarPanchal-com/Blinkit_Dashboard/blob/main/Blinkit.jpg)

**Project Title**: Blinkit Analytics: End-to-End Sales & Outlet Performance Optimization
**Tool Used**: Python (Pandas, NumPy, Seaborn), Power BI Desktop (Power Query, DAX)


An end-to-end data analytics project combining a Python-driven Exploratory Data Analysis (EDA) pipeline with an interactive Power BI dashboard to audit quick-commerce retail performance. This project profiles transactional datasets to deliver actionable operational insights across product velocity, infrastructure dimensions, and regional sales trends, directly informing data-backed inventory and expansion strategies.

![Dashboard](https://github.com/SagarPanchal-com/Blinkit_Dashboard/blob/main/Blinkit_Dashboard.png)

## Project Architecture & Analytical Focus
This end-to-end analytics framework leverages programmatic Python profiling and interactive Power BI diagnostics to evaluate retail performance across multidimensional outlet tiers, structural sizes, and diverse product categories.

The framework is architected to solve and answer critical business and statistical queries:
- **Revenue Hotspots:** Which specific outlet configurations and regional tiers generate the highest aggregate revenue volumes?
- **Infrastructure Scalability:** How do sales distributions scale across distinct outlet footprints (Small, Medium, High) and historical establishment timelines?
- **Product Inventory Velocity:** Which high-velocity product categories act as primary revenue drivers to prioritize in quick-commerce campaigns?
- **Visibility Optimization:** What is the mathematical correlation between product shelf-visibility thresholds and transactional sales trajectories before reaching saturation?
- **Consumer Behavior Profiling:** How do shifting consumer dietary choices (low-fat vs. regular product segmentation) impact baseline retail metrics?

## Target Audience
This repository serves as a comprehensive case study for:
- Data Analysts & Analytics Engineers evaluating end-to-end ETL and structural data pipelines.
- Quick-Commerce Strategy & Operations Managers optimizing inventory mix and regional expansion frameworks.
- FMCG Category Managers analyzing product shelf-space allocation and consumer purchasing patterns.
- Technical Recruiters & Portfolio Reviewers assessing production-ready data modeling and programming capabilities.

## Tech Stack & Architecture
The project architecture is divided into two distinct analytical phases:

### 1. Data Engineering & EDA (Python)
- **Data Wrangling:** Implemented `Pandas` and `NumPy` for structural profiling, type casting, missing value imputation, and anomaly/outlier detection.
- **Statistical Analysis:** Profiled item visibility skewness, categorical attributes, and revenue correlation matrices.
- **Visualization:** Utilized `Matplotlib` and `Seaborn` to plot distribution attributes, correlation heatmaps, and initial trend analytics.

### 2. Business Intelligence & Dashboard (Power BI)
- **Power Query:** Handled final schema matching, data cleaning, and dynamic data transformation steps.
- **DAX Modeling:** Engineered high-performing transactional measures, metrics, and KPI calculation fields.
- **Data Modeling:** Established clean star/snowflake relationship structures to ensure zero-latency cross-filtering.

## Dataset Architecture & Feature Schema
The dataset encompasses granular retail transaction records and multi-dimensional outlet structural parameters, programmatically audited and preprocessed via Python:

- **Item-Level Attributes:** `Item Identifier`, `Item Weight`, `Fat Content` (Low Fat / Regular), `Item Visibility` (Product shelf-occupancy ratio), `Item Type` (Product segmentation category), `Item MRP` (Maximum Retail Price).
- **Outlet-Level Attributes:** `Outlet Identifier`, `Establishment Year`, `Outlet Size` (Small / Medium / High), `Outlet Location Type` (Tier 1 / Tier 2 / Tier 3 geographic classification), `Outlet Type` (Grocery Store / Supermarket Variants).
- **Performance Targets:** `Total Sales` (Aggregate transactional revenue per branch/product group), `Average Rating` (Historical customer satisfaction index).

---

## Performance Framework & Core KPIs
Programmatic aggregations and advanced DAX engine calculations verified the following baseline business health metrics across the distribution network:
- **Total Operational Revenue:** $1.20M (Aggregate Sales Volume)
- **Inventory Depth:** 8,523 Distinct Product SKUs / Items Traced
- **Service Level Quality:** 3.9 / 5.0 Average Customer Performance Rating
- **Product Yield Metric:** $141 Average Ticket Size / Sales Value per Item

---

## Core Features & Analytical Highlights

### 🔸 Executive Business Problem
Blinkit operates a hyper-dense, complex quick-commerce footprint across diverse physical formats and regional tiers. Corporate decision-makers require a centralized data framework to bypass raw data silos in order to:
- Monitor and benchmark store-level efficiency constraints across disparate layouts.
- Uncover outperforming, high-velocity product categories to streamline procurement.
- Statistically decode consumer dietary preferences and regional purchase elasticities.
- Eradicate stock allocation inefficiencies stemming from unmapped store sizing.

### 🔸 End-to-End Project Objectives
1. **Programmatic Auditing:** Build a Python pipeline to cleanse structural anomalies and execute mathematical distribution mapping.
2. **Data Modeling Optimization:** Establish high-performing DAX calculations and star schema architectures within Power BI for instant cross-filtering.
3. **Strategic Insight Generation:** Isolate localized revenue drivers across geographic clusters to formulate regional expansion roadmaps.

### 🔸 Dual-Layer Analytical Walkthrough

#### 1. Statistical & Distribution Insights (Python Pipeline)
- **Feature Wrangling:** Imputed structural omissions within the `Outlet Size` and attribute arrays using statistical distributions to retain variance integrity.
- **Skewness & Correlation Profiling:** Audited the mathematical relationship between `Item Visibility` ratios and sales trajectories using correlation matrices to identify visibility diminishing returns.

#### 2. Visual Diagnostics & Interaction Layers (Power BI Ecosystem)
- **Top-Tier KPI Array:** Delivers an instant executive overview of system revenue, product counts, and customer service satisfaction ratings.
- **Establishment Trend Analysis (Area Chart):** Decodes structural growth velocity by indexing timeline phases, highlighting a major infrastructure expansion spike in **2018**.
- **Dietary Segment Mapping (Donut Chart):** Computes consumer purchasing patterns between Low Fat and Regular variants to inform dynamic FMCG inventory planning.
- **Product Velocity Distribution (Bar Chart):** Ranks structural revenue generation by category, validating **Fruits & Vegetables** and **Snack Foods** as primary baseline drivers.
- **Infrastructure Scalability Matrix (Donut & Grids):** Evaluates operational margins across Small, Medium, and High layouts, demonstrating how physical size constraints limit or optimize revenue yield.
- **Geographic Cluster Diagnostics (Bar Chart & Pivot Matrix):** Compares performance across Tier 1, Tier 2, and Tier 3 cities.
  - *Data Validation:* Confirms **Tier 3 locations** and **Supermarket Type 1 configurations** command the highest baseline transaction volume.

---

## Data-Backed Business Insights & Strategic Impact

### 📌 Revenue Optimization & Footprint Scaling
Granular performance diagnostics prove that **Tier 3 regional footprints** paired with **Supermarket Type 1 formats** act as the primary engines of total revenue volume. The corporate expansion strategy should actively prioritize replicating this exact structural layout in untapped regional zones.

### 📌 Demand Planning & Category Strategy
High-velocity product segments—specifically **Fruits & Vegetables** and **Snack Foods**—consistently dominate transaction values. These categories should lead all quick-commerce promotional matrix campaigns, dynamic front-page visibility algorithms, and cross-selling inventory bundles.

### 📌 Consumer Preference Tracking
The tight balance in transaction volumes between low-fat and regular variations exposes a highly mixed consumer dietary preference spectrum. Supply chain managers can leverage this insight to deploy targeted, localized multi-attribute inventory profiles optimized for specific regional neighborhood demographics.

### 📌 Infrastructure Sizing & Store Blueprinting
Data modeling confirms that **Medium and High-capacity store architectures** deliver stable, high-yield sales performance clusters. Aligning store square footage directly with localized demand profiles prevents regional inventory bottlenecks and overhead cost leakage.

---

## Unified Execution Interface
The analytical assets are structured for high-performance interaction across two control layers:
- **Programmatic Engine (Python):** Step-by-step Jupyter notebooks processing algorithmic data cleansing, feature transformation steps, and exploratory matrix plotting.
- **Dynamic Diagnostics (Power BI):** Interactive slice-and-dice visualization panel featuring multi-attribute context slicers (Outlet Size, Tier Location, Product Type) paired with an instant "Clear All Filters" script to facilitate seamless comparative deep-dives.

---

## Conclusion
This end-to-end repository bridges the gap between raw data manipulation and advanced data visualization. By joining full-scale programmatic Python exploration with high-fidelity Power BI architectures, the project converts unorganized, multi-layered retail transactions into production-ready business intelligence, optimizing core quick-commerce operations, logistics, and supply chain strategies.

---

## Data Integrity Notice
All transactional parameters, database records, corporate identifiers, and customer metadata evaluated across this analytical asset are computer-generated via synthetic simulation models. All data components are strictly engineered for programmatic benchmarking, technical learning, and portfolio demonstration purposes; any correlation to actual physical operations or live entities is entirely coincidental.

---

## Developed By
**SAGAR PANCHAL**  
*B.Tech Student, Production & Industrial Engineering | National Institute of Technology, Kurukshetra*  
*Specialization: Supply Chain Optimization, Operations Research & Advanced Data Analytics*
