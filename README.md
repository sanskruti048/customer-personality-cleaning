# Customer Personality Dataset – Data Cleaning Project

This project performs essential data cleaning and preprocessing on the **Customer Personality Analysis** dataset. It follows industry-standard steps to prepare the raw dataset for future analysis or modeling tasks.

---

## Dataset

We use the **Customer Personality Analysis** dataset (`marketing_campaign.csv`) which contains information about customers, including:

- Age  
- Income  
- Number of children and teens in household  
- Enrollment date (`Dt_Customer`)  
- Education, marital status  
- Product campaign responses  
- Spending on various product categories  
- And more categorical attributes related to behavior and demographics.

---

## Tasks Performed

### 1. **Import and Explore Data**
- Loaded dataset using `pandas` with tab-separated values.
- Checked data structure, data types, null values, and general info.

### 2. **Handle Missing Values**
- Dropped rows with missing values in the `Income` column.

### 3. **Clean Column Names**
- Converted column names to lowercase and replaced spaces with underscores for easier access in code.

### 4. **Convert Categorical Features**
- Standardized values in columns like `Education` and `Marital_Status` (e.g., consistent casing and spacing).

### 5. **Fix Data Types**
- Converted `Dt_Customer` to proper `datetime` format.

### 6. **Remove Duplicates**
- Identified and removed duplicate records.

---

## Key Libraries Used

- `pandas` – for data loading and manipulation  
- `numpy` – for numerical operations  
- `matplotlib` / `seaborn` – for data visualization (optional, but recommended for EDA)  
- `datetime` – for handling date-type conversion

---

## Author


**Sanskruti Sugandhi**  
🔗 GitHub: [@sanskruti048](https://github.com/sanskruti048)
