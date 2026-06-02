 # Enterprise Predictive Lead Scoring Engine (XGBoost)

## 📌 Project Overview
In enterprise business operations, sales teams waste massive amounts of manual labor chasing cold leads. This project solves this revenue-velocity bottleneck by engineering a machine learning pipeline that analyzes Salesforce CRM attributes to assign a dynamic "Propensity to Buy" score (0-100) to incoming prospects, automatically grouping them into actionable operational tiers (**Hot, Warm, Cold**).

## 🛠️ Advanced Tech Stack
* **Language:** Python
* **Core Algorithm:** XGBoost Classifier (Extreme Gradient Boosting)
* **Libraries:** Pandas, NumPy, Scikit-Learn, XGBoost
* **Development Environment:** Google Colab

## 🚀 Advanced Data Engineering Solved
* **Hidden Missing Value Handling:** Engineered a dynamic automated preprocessing pipeline to capture and convert 5,000+ hidden web-form placeholders (`'Select'`) into actionable data categories.
* **High-Cardinality Resolution:** Built a rare-label collapsing algorithm to bundle fragmented, low-volume lead sources into a clean, consolidated feature layout.
* **Feature Engineering:** Developed custom interaction metrics (`Time_Per_Visit`) to track deep engagement density rather than blind website traffic clicks.
* **Class Imbalance Management:** Implemented a Stratified Train-Test split strategy to handle highly realistic, skewed conversion baselines (~38% conversion).

## 📈 Enterprise Validation & Business Performance
* **Precision Rate: 94%** – Out of all leads flagged by the model as buyers, 94% successfully converted. This effectively eliminates sales fatigue and drastically lowers Customer Acquisition Costs (CAC).
* **Recall Rate: 91%** – The model successfully captures 91% of all revenue-generating accounts hidden inside the pipeline, leaving minimal revenue leak on the table.
* **Operational Funnel Optimization:** * 🔴 **60.5% of leads categorized as COLD:** Routed to automated system drops, instantly saving ~60% of manual sales development labor costs.
  * 🟡 **7.0% of leads categorized as WARM:** Funneled automatically to marketing nurture tracks.
  * 🟢 **32.5% of leads categorized as HOT:** Routed with highest priority straight to Account Executives for immediate outbound closing.

## 🔑 Key Strategic Drivers Discovered
Using XGBoost's feature importance matrix, we discovered that over 50% of pipeline conversion probability is driven by:
1. **Prospect Communication Intent** (`Tags_Will revert after reading the email` - 32.1% weight)
2. **Pre-Qualified Sourcing Channels** (`Lead Origin_Lead Add Form` - 9.6% weight)
3. **Premium Referral Networks** (`Tags_Closed by Horizzon` - 9.2% weight)
