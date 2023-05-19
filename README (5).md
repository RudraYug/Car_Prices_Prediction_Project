
# Car Price Analysis

The Car Price Analysis project is a Python-based analysis of car prices using popular libraries such as NumPy, Pandas, Matplotlib, and Seaborn. The main objective is to explore the relationship between different independent variables and the dependent variable, which is the price of the car.

The project begins by loading the **"CarPrice_Assignment.csv"** dataset using Pandas and displaying its dimensions. The data cleaning process involves separating the **"CarName"** variable into **"CompanyName"** and **"CarModel"** columns, and dropping irrelevant columns like **"CarName"** and **"car_ID"**.

The exploratory data analysis section focuses on visualizing the data to gain insights. It starts by visualizing the distribution and spread of car prices using box plots and a distribution plot. Scatter plots are then used to visualize the relationship between price and several independent variables such as wheelbase, curb weight, and engine size. Correlation coefficients are calculated to measure the strength of these relationships.

A heatmap is created to analyze multicollinearity, examining the correlation between independent variables that are found to be correlated with the price. Separate heatmaps are generated for variables related to car dimensions, performance, and fuel efficiency.

The project also visualizes the relationship between price and various categorical variables, including company name, fuel type, car body type, and drive wheel. Bar plots and box plots are used to identify any trends or patterns in the data.

Overall, the Car Price Analysis project provides insights into the factors influencing car prices by analyzing both numerical and categorical variables. The code can serve as a starting point for further analysis or as a reference for similar projects.
## Table Of Contents

- Prerequisites
- Installation
- Code Explanation
- Usage
- Contribution
- Conclusion
- License
- Related

## Prerequisites

To run the Car Price Analysis project, you need to have the following prerequisites:

- Python: Ensure that Python is installed on your system. The project is developed using Python 3.x, so having a compatible version is recommended.

- Python Libraries: Install the necessary Python libraries by executing the following command in your terminal or command prompt:


**`pip install pandas numpy matplotlib seaborn`**


- [Pandas](https://pandas.pydata.org/): Used for data manipulation and analysis, including loading and cleaning the dataset.

- [NumPy](https://numpy.org/): Required for numerical computations and operations on the data.

- [Matplotlib](https://pypi.org/project/matplotlib/): Used for creating visualizations such as scatter plots, box plots, and distribution plots.

- [Seaborn](https://seaborn.pydata.org/): A data visualization library that enhances the aesthetics and readability of plots.

- Dataset: Download the **"CarPrice_Assignment.csv"** dataset, which contains the car price and various attributes. Ensure that the dataset is placed in the same directory as the project files.

- Integrated Development Environment (IDE): Choose a Python IDE of your choice to execute the code. Popular options include Jupyter Notebook, PyCharm, or Anaconda.

With these prerequisites fulfilled, you should be ready to run the Car Price Analysis project and explore the relationships between car prices and different variables.
## Installation

To run this code, you need to have Python installed on your system. Additionally, you need to install the following libraries:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- SciPy

You can install these libraries using pip, the package installer for Python. Run the following command to install the required libraries:

**`pip install numpy pandas matplotlib seaborn scipy`**




## Code Explanation

The code performs the following tasks:

- Imports the necessary libraries: NumPy, Pandas, Matplotlib, Seaborn, and SciPy.

- Reads the car price dataset from a CSV file and displays its dimensions and the first 10 rows.

- Cleans the data by separating the **"CarName"** variable into two columns: **"CompanyName"** and **"CarModel"**.

- Removes unnecessary columns from the dataset.

- Examines categorical variables and corrects them by replacing inconsistent values with correct ones.

- Visualizes the dependent variable **"price"** using boxplot and histogram.

- Visualizes the independent variables' relationships with the dependent variable using scatter plots and calculates the correlation coefficients.

- Checks for multicollinearity between correlated independent variables using a correlation heatmap.

- Examines the correlation between variables specific to car dimensions and performance.

- Examines the correlation between categorical variables and the price.
## Usage

- Clone this repository to your local machine or download the code as a ZIP file.
- Make sure you have the required libraries installed.
- Open the Python script in your preferred development environment or run it using a Python interpreter.
- The script loads the car price dataset from a CSV file called **"CarPrice_Assignment.csv"**. Make sure this file is in the same directory as the script. If the file is located elsewhere, modify the file path in the script accordingly.
- Run the script.

## Dataset

The analysis is performed on the **"CarPrice_Assignment.csv"** dataset, which contains information about different car models and their prices. The dataset is loaded using Pandas and its dimensions are printed to provide an overview.

## Data Cleaning

The data cleaning process involves separating the **"CarName"** variable into two columns: **"CompanyName"** and **"CarModel"**. The **"CarName"** column is split using whitespace as the delimiter, and only the first part (company name) is retained. The new **"CompanyName"** column is inserted into the dataset, while the original **"CarName"** and **"car_ID"** columns are dropped as they are deemed irrelevant.

## Exploratory Data Analysis

The exploratory data analysis section focuses on visualizing the data to gain insights into the relationships between the independent variables and the dependent variable (price).

## Dependent Variable Visualization: price

The distribution and spread of the car prices are visualized using box plots and a distribution plot.

## Visualization of Independent Variables (Numerical)

Scatter plots are used to visualize the relationship between the price and several independent variables, including wheelbase, curb weight, boreratio, car length, car width, car height, engine size, horsepower, stroke, compression ratio, peak rpm, symboling, city mpg, and highway mpg. Correlation coefficients are calculated to determine the strength of the relationships.

## Multicollinearity Analysis

A heatmap is created to examine the correlation between the independent variables that were found to be correlated with the price. Separate heatmaps are generated for variables related to car dimensions, performance, and fuel efficiency.

## Visualization of Categorical Variables

Bar plots and box plots are used to visualize the relationship between the price and various categorical variables, including company name, fuel type, aspiration, door number, engine location, car body type, fuel system, engine type, cylinder number, and drive wheel. These visualizations help identify any trends or patterns in the data.

## Contribution

Contributions to the project are welcome. If you would like to contribute, please follow these steps:

- Fork the repository to your own GitHub account.
- Clone the repository to your local machine.
- Create a new branch with a descriptive name using the command **`git checkout -b your-branch-name`**.
- Make your changes and commit them using the command **`git commit -m "your commit message"`**.
- Push your changes to your forked repository using the command **`git push origin your-branch-name`**.
- Create a pull request on the original repository and wait for it to be reviewed.
## Conclusion

This analysis provides insights into the relationships between various independent variables and the price of cars. By examining both numerical and categorical variables, we gain a better understanding of the factors that influence car prices. The code in this repository can be used as a starting point for further analysis or as a reference for similar projects. I want to thank kaggle for providing with the dataset.
## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License - see the LICENSE file for details.


## Related

Here are some related projects

- [Spotify_Analysis](https://github.com/RudraYug/Spotify_Analysis.git)

- [Tic_Tac_Toe](https://github.com/RudraYug/Tic_Tac_Toe.git)

- [Football_Prediction_Analysis](https://github.com/RudraYug/Football-Prediction-Analysis.git)

- [Flipkart_Web_Scraping](https://github.com/RudraYug/Flipkart_Web_Scraping.git)