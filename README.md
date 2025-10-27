# 🧩 Task 5: Data Analysis on CSV Files

## 📘 Objective
The goal of this task is to analyze sales data using Python and Pandas to extract meaningful insights and visualize trends.

---

## 🛠️ Tools Used
- **Python**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook / Google Colab**

---

## 📂 Dataset
The dataset used in this analysis is `sales_data.csv`, which contains the following columns:

| Column Name | Description |
|--------------|-------------|
| Date | Date of sale |
| Product | Product name |
| Region | Sales region (North, South, East, West) |
| Quantity | Number of units sold |
| Sales | Total sales amount |

---

## 🧠 Steps Performed

1. **Loaded the dataset** using `pandas.read_csv()`.
2. **Explored data** with `.info()`, `.describe()`, and `.isnull().sum()`.
3. **Cleaned column names** using string functions.
4. **Analyzed sales data**:
   - Total sales by product using `groupby('Product')`.
   - Total sales by region using `groupby('Region')`.
5. **Visualized data** with Matplotlib:
   - Bar chart: Total Sales by Product.
   - Pie chart: Sales distribution by Region.
   - Line chart: Monthly sales trend.
6. **Derived insights** from the visualizations.

---

## 📊 Key Insights
- **Laptops** generated the highest sales overall.  
- **North region** contributed the most revenue.  
- Sales peaked around **March–May** period.  
- No missing or invalid data found in the dataset.

---

## 📸 Outputs
The notebook includes:
- Bar Chart — *Total Sales by Product*
- Pie Chart — *Sales by Region*
- Line Chart — *Monthly Sales Trend*

---

## 📁 Files Included
| File | Description |
|------|--------------|
| `Task 5.ipynb` | Jupyter notebook with full analysis and code |
| `sales_data.csv` | Dataset used for analysis |
| `README.md` | Project documentation |

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Task-5-Data-Analysis.git
