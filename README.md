
# Urban Vegetation and Land Surface Temperature Analysis

## 📊 Project Description

This project analyzes the relationship between urban vegetation coverage (NDVI) and land surface temperature (LST) in Guangzhou City from 2015 to 2025. We aim to understand how green spaces affect urban heat island effects.

---

## 🗂️ Data Description

### Input Data
- **Source**: Satellite remote sensing data (Landsat/MODIS)
- **Time Range**: 2015-2025
- **Spatial Coverage**: Guangzhou City
- **Variables**:
  - `year`: Year (2015-2025)
  - `lon`: Longitude (WGS84)
  - `lat`: Latitude (WGS84)
  - `NDVI`: Normalized Difference Vegetation Index (-1 to 1)
  - `LST_K`: Land Surface Temperature in Kelvin

### Output Data
- `data_for_teammate_C_final.csv`: Cleaned dataset with 3,621 observations
- Feature-engineered variables for analysis

---

## 🛠️ Requirements

### Python Packages Used

```python
pandas          # Data manipulation and cleaning
numpy           # Numerical computations
matplotlib      # Data visualization
seaborn         # Statistical plots
scipy           # Statistical analysis
Installation
bash
pip install pandas numpy matplotlib seaborn scipy
📁 File Structure
project/
│
├── cleaned_data.csv                    # Original cleaned data
├── data_for_teammate_C_final.csv       # Processed data for analysis
├── NDVI_LST_Analysis.ipynb             # Main analysis notebook
├── README.md                           # This file
└── figures/                            # Generated plots
🚀 How to Run
Install required packages:

bash
pip install pandas numpy matplotlib seaborn scipy
Open Jupyter Notebook:

bash
jupyter notebook NDVI_LST_Analysis.ipynb
Run all cells in order

Output:

Cleaned CSV file
Statistical analysis results
Visualization plots
📈 Key Features
Data Processing
Temperature unit conversion (Celsius to Kelvin)
Missing value handling
Feature engineering (rolling means, interaction terms)
Analysis Methods
Correlation analysis between NDVI and LST
Temporal trend analysis (2015-2025)
Spatial pattern visualization
Statistical significance testing
👥 Team Members
Member A: Data collection and preprocessing
Member B: Statistical analysis
Member C: Visualization and reporting
Your Name: Data cleaning and feature engineering
📚 References
Satellite data source: [Add your data source]
NDVI calculation method: [Add reference]
LST retrieval algorithm: [Add reference]
📧 Contact
For questions, please contact: [your email]

📅 Last Updated
December 5, 2025


