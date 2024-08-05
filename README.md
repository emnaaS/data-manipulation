# Data Cleaning with Python and Pandas

This repository contains a project that demonstrates data generation, cleaning, and manipulation using Python and Pandas in Google Colab. The project follows the guidelines from the [KD Nuggets article on mastering data cleaning with Python and Pandas](https://www.kdnuggets.com/7-steps-to-mastering-data-cleaning-with-python-and-pandas?fbclid=IwY2xjawEbEKxleHRuA2FlbQIxMAABHcT7aSS9JJUdm--3dTJX4tm8c9XpTj4Np7R5KXKyeV9VgmVIvFIL_ki7oQ_aem_5kw38wR9bt3L4UYaUS-oHA).

## Project Overview

This project involves the following steps:
1. **Data Generation:** Synthetic data is generated using the Faker library to simulate employee records.
2. **Data Cleaning:** Various techniques are applied to clean the data, including handling missing values, removing duplicates, and identifying outliers.
3. **Data Manipulation:** Additional data transformations and feature engineering are performed.

## Installation
To run the project, you need to install the following Python libraries:
 ```bash
   pip install pandas faker
   ```

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/emnaaS/data-manipulation.git
   cd data-manipulation
   ```

2. **Open the notebook in Google Colab:**

   ```bash
   https://colab.research.google.com/github/emnaaS/data-manipulation/blob/main/data_cleaning.ipynb
   ```
3. Run the notebook cells to see the data generation, cleaning, and manipulation steps in action.

## Data Description

- **Name:** Full name of the employee
- **Age:** Age of the employee (18 to 70)
- **Email:** Email address of the employee
- **Phone:** Phone number of the employee
- **Address:** Address of the employee
- **Salary:** Salary of the employee (20000 to 150000, with some outliers)
- **Join Date:** Date the employee joined
- **Employment Status:** Employment status (Full-Time, Part-Time, Contract)
- **Department:** Department the employee works in

## Data Cleaning Steps

1. **Handling Missing Values:** Replaced missing email addresses with a placeholder.
2. **Removing Duplicates:** Removed duplicate records from the dataset.
3. **Address Cleaning:** Cleaned address strings by removing newline characters.
4. **Outlier Detection:** Identified outliers based on salary using Z-score.

## Acknowledgments

- [KD Nuggets](https://www.kdnuggets.com/7-steps-to-mastering-data-cleaning-with-python-and-pandas?fbclid=IwY2xjawEbEKxleHRuA2FlbQIxMAABHcT7aSS9JJUdm--3dTJX4tm8c9XpTj4Np7R5KXKyeV9VgmVIvFIL_ki7oQ_aem_5kw38wR9bt3L4UYaUS-oHA) for the comprehensive guide on data cleaning.

## Contact

If you have any questions or feedback, feel free to reach out to me at emnaa.sellami@gmail.com
