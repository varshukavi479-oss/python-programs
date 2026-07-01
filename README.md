# Food Menu Analysis

## Project Overview
This project analyzes a food menu dataset using Python, Pandas, NumPy, and OpenPyXL. It categorizes menu items, calculates nutritional summaries, performs category-wise analysis, and exports the cleaned dataset to an Excel file.

## Technologies Used
- Python
- Pandas
- NumPy
- OpenPyXL

 ## Features
- Creates a structured food menu dataset
- Displays statistical summary using describe()
- Filters items by category
- Calculates category-wise totals
- Computes overall totals for:
  - Price
  - Protein
  - Calories
- Generates category summary using groupby()
- Creates indicator columns using NumPy
- Exports cleaned data to Excel

## Categories Included
- Fried Chicken
- Burgers
- Rice & Rolls
- Sides
- Beverages
- Desserts
- Snacks/Popcorn

## Output
## 📟 Output

### Dataset Overview
- Total Items: 50
- Categories: 7
- Dataset contains:
  - Item ID
  - Item Name
  - Category
  - Price (INR)
  - Calories (kcal)
  - Protein (g)
  - Fat (g)
  - Carbohydrates (g)
  - Sodium (mg)

### Analysis Performed
✅ Statistical Summary using `describe()`

✅ Category-wise Filtering:
- Fried Chicken
- Burgers
- Rice & Rolls
- Sides
- Beverages
- Desserts
- Snacks/Popcorn

✅ Category-wise Nutritional Summaries

✅ Total Price Calculation

✅ Total Protein Calculation

✅ Total Calories Calculation

✅ Grouped Category Analysis using `groupby()`

✅ New Classification Columns Created:
- Is_Fried
- Is_Burger
- Is_rice
- Is_sides
- Is_beverage
- Is_deserts
- Is_snacks

### Generated Output File
📁 `food_data_cleaned.xlsx`

The cleaned dataset is successfully exported to an Excel file with additional category indicator columns.

## Author
Varshini Nagarajan
B.Tech Information Technology
Aspiring Java Developer
