# GSGProject
# Prediction of Real Estate Prices

## Overview
This project aims to develop a predictive model for estimating real estate prices based on several factors such as property age, proximity to public transportation, and nearby amenities. By leveraging machine learning techniques, the project identifies key drivers influencing property values to assist stakeholders in making informed decisions.

## Problem Statement
Real estate pricing is a complex process influenced by various physical and external factors. The goal is to create a robust model capable of predicting property prices based on these variables, reducing uncertainty and providing clarity to buyers, sellers, and investors.

## Dataset
The dataset contains information on real estate transactions, with the following attributes:
- **Transaction Date:** Date of the transaction.
- **House Age:** Age of the property in years.
- **Distance to Nearest MRT Station:** Distance to the closest MRT station in meters.
- **Number of Convenience Stores:** Count of convenience stores near the property.
- **Latitude & Longitude:** Geographical coordinates of the property.
- **House Price of Unit Area:** Price per unit area (dependent variable).

### Data Source
The dataset can be accessed [here](https://drive.google.com/file/d/1gGYsdOr408BqyYdRsXCUOq6SXxd7di08/view?usp=sharing).

## Methodology
Two machine learning models were employed:
1. **K-Nearest Neighbors (KNN)**
2. **Random Forest**

## Results
- **KNN Model:**
  - Mean Squared Error (MSE): 54.36
  - R-Squared: 0.676
- **Random Forest Model:**
  - Mean Squared Error (MSE): 71.21
  - R-Squared: 0.576

## Visualization
Visualizations for the dataset and results are included in the project.

## Usage
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook to explore data and train models:
   ```bash
   jupyter notebook
   ```

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any changes or improvements.

## Author
**Hazem Kamal Al Hendawi**

## License
This project is licensed under the MIT License.

