# Data-Analysis

📊 E-Commerce Transaction Analysis in Pakistan 🇵🇰
This project analyzes consumer behavior and sales trends based on Pakistan’s largest e-commerce dataset. It was developed as a final assignment for the Data Analytics course at Ho Chi Minh City University of Technology and Education (HCMUTE).

📌 Project Overview
This analysis aims to derive strategic business insights for the e-commerce sector in Pakistan. The dataset contains over 1 million transaction records including order statuses, payment methods, discount strategies, customer behavior, and product categories.

🎯 Objectives
Discover transaction trends over time.

Analyze customer behaviors by product categories and payment types.

Identify causes of order cancellations and refunds.

Build a predictive model for future sales performance.

Provide actionable insights for business decision-making.

📁 Dataset
Source: Kaggle – Pakistan’s Largest E-Commerce Dataset

Format: CSV

Size: ~1 million rows, 25 columns

Key features include:

item_id, status, created_at, price, qty_ordered, payment_method, discount_amount, category_name_1, customer_id, grand_total, etc.

🛠️ Techniques & Tools Used
Languages: Python

Libraries:

Data Wrangling: pandas, numpy

Visualization: matplotlib, seaborn

Machine Learning: scikit-learn (Logistic Regression)

Data Processing Techniques:

Null value handling

Outlier detection (Z-score, IQR)

Data type conversion

Feature engineering: discount rate, price per unit, customer tenure, etc.

Modeling:

Sales prediction using regression models

Evaluation: RMSE, MAE, and visual validation

📈 Key Findings
Cash-on-Delivery (COD) is the most used payment method, but linked to the lowest average order value and highest cancellation rate.

Categories like Mobiles & Tablets and Men’s Fashion drive both the most revenue and cancellations.

High discount rates slightly increase average quantity ordered, but not proportionally.

A small segment of VIP customers contributes the majority of the revenue (Pareto Principle).

Orders with online payment methods tend to have a higher completion rate and order value.

▶️ How to Run
Clone the Repository

bash
Sao chép
Chỉnh sửa
git clone https://github.com/yourusername/pakistan-ecommerce-analysis.git
cd pakistan-ecommerce-analysis
Install Required Libraries

Make sure you have Python 3.10+ installed. Then:

bash
Sao chép
Chỉnh sửa
pip install -r requirements.txt
Run the Notebook

Open ecommerce_analysis.ipynb in Jupyter Notebook:

bash
Sao chép
Chỉnh sửa
jupyter notebook
Or run all scripts:

bash
Sao chép
Chỉnh sửa
python main.py
Model Training (Optional)

The notebook includes a regression model to predict monthly sales totals. You can train it by running the last section of the notebook.

📚 Folder Structure
graphql
Sao chép
Chỉnh sửa
pakistan-ecommerce-analysis/
├── data/                      # Raw dataset and cleaned version
├── notebooks/                 # EDA and modeling notebook
├── src/                       # Python scripts
├── figures/                   # Saved plots
├── requirements.txt
├── main.py
└── README.md
📌 Authors
Trần Bảo Việt

Lê Hồ Quốc Huy

Lê Quỳnh Nhựt Vinh

Nguyễn Thiên Khang
(Supervised by: Mr. Nguyễn Văn Thành – HCMUTE)

📄 License
This project is for educational and research purposes only.
