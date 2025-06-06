#  Used Car Market Analysis - India 🇮🇳

This project aims to analyze the **used car market in India** using Python, leveraging data analytics techniques to uncover insights into pricing trends, popular brands, and key factors that influence resale value.

---

##  Objectives

- Understand the structure of the Indian used car market.
- Clean and preprocess real-world automotive data.
- Perform exploratory data analysis (EDA) to identify patterns and trends.
- Derive actionable insights to assist buyers, sellers, or marketplaces.

---

##  Dataset Description

- **Source**: [Kaggle - Used Cars Dataset](https://www.kaggle.com/)  
- **Format**: CSV  
- **Size**: ~8,000+ records  
- **Features**:
  - `Name`: Car name and model
  - `Year`: Year of manufacture
  - `Selling_Price`: Resale price of the car
  - `Km_Driven`: Kilometers the car has been driven
  - `Fuel`: Type of fuel used
  - `Seller_Type`: Individual or dealer
  - `Transmission`: Manual or Automatic
  - `Owner`: Ownership type
  - `Mileage`, `Engine`, `Max_Power`, `Seats`, etc.

---

##  Tools & Libraries

| Tool            | Purpose                        |
|-----------------|--------------------------------|
| `Python`        | Programming Language           |
| `Pandas`        | Data manipulation              |
| `NumPy`         | Numerical operations           |
| `Matplotlib`    | Basic data visualizations      |
| `Seaborn`       | Advanced statistical plotting  |
| `Jupyter Lab/Notebook` | Interactive data analysis |

---

##  Project Workflow

### 1. **Data Import & Inspection**
   - Load the dataset using pandas.
   - Perform a sanity check on rows, columns, and data types.

### 2. **Data Cleaning**
   - Handle missing values.
   - Remove irrelevant features.
   - Correct inconsistent formatting.

### 3. **Feature Engineering**
   - Extract numerical values from text (e.g., Mileage, Engine, Power).
   - Convert `Year` to `Car Age`.
   - Drop or transform columns like `Torque` which are difficult to parse.

### 4. **Exploratory Data Analysis (EDA)**
   - Univariate Analysis: Distribution of price, fuel type, owner type.
   - Bivariate Analysis: Impact of engine size, mileage, age on price.
   - Heatmaps to examine correlation between numerical variables.

### 5. **Key Visualizations**
   -  Price Distribution
   -  Fuel Type vs Price
   -  Seller Type Impact
   -  Car Age vs Resale Price
   -  Top Brands by Average Price

---

##  Key Insights

- **Car Age** has a significant negative correlation with price.
- **Diesel and Petrol cars** dominate the market; diesel cars tend to be priced higher.
- **Manual transmission** is more common, though automatic cars often command higher prices.
- Some brands, like **Toyota and Honda**, retain their value better.

---

##  How to Use

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Abhishekkale93/Analyzing-Used-Car-Market-in-India.git
   
2. **Install dependencies**
    pip install pandas numpy matplotlib seaborn jupyter

3. **Run the notebook**
    jupyter notebook

##  Author

**Abhishek Kale**  
 kaleabhishek0101@gmail.com  
 Pune, India  
 [LinkedIn](https://www.linkedin.com/in/abhishek-kale-66bb961b2/)
   
