# Mall Customer Data Cleaning  

## **Task Objective**  
Clean the [Mall Customer Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) by handling missing values, duplicates, and inconsistent formats.  

## 🛠 **Steps**  
1. **Loaded Data**: Used Pandas to read `Mall_Customers.csv`.  
2. **Checked for Issues**:  
   - Missing values: `df.isnull().sum()`  
   - Duplicates: `df.duplicated().sum()`  
3. **Cleaned Data**:  
   - Renamed columns to lowercase (e.g., `Annual Income` → `annual_income`).  
   - Converted `CustomerID` to string type.  
4. **Saved Output**: Generated `cleaned_mall_customers.csv`.  

## **Results**  
- **0 missing values/duplicates** found (screenshots in `/screenshots`).  
- Cleaned dataset ready for segmentation analysis.  

## **How to Reproduce**  
1. Clone this repo.  
2. Run `Data_Cleaning_Task.ipynb` in Colab/Jupyter.  
