# 🛍️ Mall Customer Segmentation Analysis - Clustering

## 🧠 Overview

This project analyzes mall customer data to identify **distinct customer segments** using **KMeans Clustering** 🧩.  
The goal is to help the **marketing team** 🎯 target specific groups of customers more effectively based on their **demographics** and **spending behavior**.

---

## 📌 Problem Statement

Imagine you own a large **supermarket mall** 🏬. You want to understand your customers better – especially those who are more likely to convert (aka **target customers**) 🧲.

By segmenting customers into different clusters, your marketing team can:
- Design **personalized campaigns** 💌
- Boost **conversion rates** 📈
- Increase **customer satisfaction** 😊

---

## 📊 Dataset Information

You’ve collected basic customer information through **membership cards** 💳.

One important metric is the **Spending Score** 🧾 — a number assigned based on customer behavior, purchase history, and loyalty.

### ✨ Dataset Attributes:

- 🆔 `CustomerID` – Unique customer ID  
- 🎂 `Age` – Age of the customer  
- 🚻 `Gender` – Male or Female  
- 💰 `Annual Income (k$)` – Yearly income in thousands  
- 📈 `Spending Score (1–100)` – Score based on spending patterns  

---

## 🧰 Libraries Used

| 📦 Library      | 🔍 Purpose                            |
|----------------|----------------------------------------|
| `pandas`        | Data manipulation and loading         |
| `matplotlib`    | Data visualization 📊                 |
| `seaborn`       | Statistical graphics & plots 📉       |
| `scikit-learn`  | Machine learning algorithms 🧠         |

---

## ⚙️ Algorithm Used

- 🚀 **KMeans Clustering**: Unsupervised learning technique to group similar customers into clusters based on income and spending behavior.

---

## ✅ Conclusion

🔍 Through this analysis, we identified **5 distinct customer clusters**:

- 💎 **Cluster 1**: High income, high spending → Ideal for luxury products & premium offerings  
- 🧍‍♂️ **Cluster 2**: Low income, low spending → Target with affordable deals or loyalty points  
- 🎯 **Cluster 3**: Mid income, high spending → Engage with loyalty and referral programs  
- 🤝 **Cluster 4**: High income, low spending → Opportunity to upsell with personalized campaigns  
- 🔄 **Cluster 5**: Younger, moderate income, varied spending → Ideal for trend-driven promotions

These insights help marketers:
- Tailor messaging 🎨  
- Boost engagement 💬  
- Maximize ROI 💸  

> 🛠️ **Next steps:** Include more features like:
> - Time spent in store 🕒  
> - Product categories purchased 🛒  
> - Loyalty program participation ⭐  
> to make clusters even more insightful!

---

## 🚀 Getting Started

Follow these simple steps to get up and running locally:

1. 📥 **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/Mall-Customer-Segmentation.git
   ```

2. 📦 **Install required libraries**
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   ```
3. 🧪 **Run the notebook**
   ```bash
   Open the Jupyter notebook and run all cells.
   ```
