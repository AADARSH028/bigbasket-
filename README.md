# bigbasket-

# 🛒📦 BigBasket Product Data Analysis 🧠📊

Welcome to my exploratory data analysis (EDA) project on the BigBasket 🧺 product dataset!  
This project dives into India’s leading online grocery platform to uncover hidden insights 🕵️‍♂️ using data visualization 📈 and Python 🐍.

---

## 📁 Dataset Overview 🔍

The dataset contains details about **27,555** products sold on BigBasket. Here's a quick snapshot:

| 🔑 Column Name     | 📋 Description                                      |
|--------------------|-----------------------------------------------------|
| 🏷️ `product`        | Product name                                        |
| 🧰 `category`       | Broad product category                              |
| 🔖 `sub_category`   | Specific product category                           |
| 🏭 `brand`          | Brand name                                          |
| 💵 `sale_price`     | Final selling price (after discount)                |
| 💰 `market_price`   | Original price before discount                      |
| 🧾 `type`           | Item type                                           |
| ⭐ `rating`         | Customer rating (scale: 1 to 5)                     |
| 📝 `description`    | Short description of the product                    |

---

## 🧼 Data Cleaning & Preprocessing 🧹

✅ Checked for missing values  
✅ Converted ratings to integers  
✅ Created new features:  
- 🔻 `discount` = `market_price - sale_price`  
- 📉 `discount_percent` = `(discount / market_price) * 100`

✅ Applied `Label Encoding` 🎫 to categorical columns for correlation analysis

---

## 📊 Exploratory Data Analysis (EDA) 🔬

### 🔟 Top 10 Categories by Product Count
📊 Bar chart of top categories by number of products

### 💸 Average Sale Price by Category
💡 Identify which categories are generally more expensive

### ⭐ Rating Distribution
🧍 Understand customer satisfaction

### 🎯 Average Discount by Category
🤑 See where the best deals are offered!

### 🧠 Correlation Heatmap
🧩 Analyze relationships between price, discount, and rating

### 🏆 Top & 🐢 Least Sold Products
📈 Products with the highest and lowest sale prices

---

## 📈 Visualizations Used 🖼️

📊 Bar Charts – Category count, Avg price, Avg discount  
🥧 Pie Chart – Category distribution  
📦 Box Plot – Price spread across categories  
🔁 Scatter Plot – Rating vs price, sale vs market price  
🔎 Joint Plot – Deep dive on sale vs market  
🔥 Heatmaps – Price & rating correlation  
👥 Pairplot – Relationships among features  
📉 Distplots – Sales price distribution

---

## 🧠 Key Insights & Findings 💡

- 🥇 `Beauty & Hygiene` is the most popular category
- 🛍️ Discounts go up to **50%+** on many products
- ⭐ Ratings are mostly between **3.5 – 4.5**
- 💎 Highest priced products were in **Men’s Grooming** and **Cookware**
- 🥬 Least expensive ones were in **Hair Care** and **Herbs & Seasonings**

---

## 🛠️ Tools & Technologies 🧰

- Python 🐍  
- Pandas & NumPy 📐  
- Matplotlib & Seaborn 📊  
- Google Colab ☁️  
- Scikit-learn 🔬 (Label Encoding)

---

## 🔚 Conclusion 📌

This EDA provided valuable insights about BigBasket’s product offerings, pricing, discounts, and customer satisfaction. This data can be used for:
- 🎯 Product Recommendation Systems
- 🛒 Customer Segmentation
- 💸 Dynamic Pricing Models


---

## 🙋‍♂️ Author

**Adarsh Kumar**  
📫 adar843462@gmail.com  
🔗 www.linkedin.com/in/adarsh-kumar-29a761353 

💻 Aspiring Data Scientist | Python • SQL • Power BI • Excel

---

## ✨ If you like this project...

⭐ Give it a star  
🍴 Fork it  
🧠 Share feedback  
📲 Connect with me on LinkedIn!
