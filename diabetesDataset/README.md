README: TB Trends – Global & Regional Insights
Overview

TB Trends: Global & Regional Insights is an analysis project focused on tuberculosis (TB) epidemiology using publicly available data. The project leverages the Tuberculosis Trend Kaggle Dataset to explore global and regional TB trends, with a particular emphasis on South Africa. The analysis combines R and Python for data manipulation, visualization, and modeling, and is intended to provide actionable insights into TB cases and deaths over time.
Project Structure

    Data Source: Kaggle Tuberculosis Trends dataset

    Primary Focus: Exploratory data analysis, visualization, and predictive modeling of TB trends, with a case study on South Africa

    Languages & Tools: R, Python, Quarto (for reproducible reports)

    Key Outputs: Data summaries, visualizations (line plots, histograms, QQ plots), and predictive models (Linear Regression, Random Forest)

Getting Started:

1. Clone the Repository

bash:

git clone https://github.com/your-username/AnalysisProjects.git
cd AnalysisProjects

2. Install Required Packages:

R Packages:

Python Packages:

The project includes scripts to check for and install missing packages automatically.

3. Data Access:

The dataset is automatically downloaded from Kaggle using the appropriate API or package. Ensure you have Kaggle API credentials configured if running locally.

Analysis Workflow

    Data Import: Load and inspect the TB dataset, focusing on column data types and missing values.

    Cleaning: Filter and aggregate data for South Africa, removing unnecessary columns and grouping by year.

    Visualization:

        Line plots for TB cases and deaths over time

        Distribution plots (histograms, QQ plots) for normality assessment

    Modeling:

        Linear Regression and Random Forest models to predict TB cases

        Model evaluation using Mean Squared Error (MSE)

    Interpretation: Compare model performances and discuss implications.

Key Findings:

    TB remains a significant health burden, with millions of cases and deaths annually.

    The Random Forest model outperformed Linear Regression in predicting TB cases, as indicated by a lower MSE.

    Data visualizations reveal temporal trends and distribution characteristics essential for public health planning.

Future Work:

    Explore additional features and alternative modeling approaches.

    Expand analysis to other regions for comparative insights.

    Integrate more granular or recent data as available.

References:

    Kaggle Dataset: Tuberculosis Trends – Global and Regional Insights

    World Health Organisation (WHO) TB Reports

    See references.bib for complete bibliography.

License:

This project is for educational and research purposes. See the repository for licensing details.
Contact

For questions or contributions, please open an issue or submit a pull request on GitHub.

Other Links:

    Tuberculosis Trend - Kaggle Dataset

Last updated: April 25, 2025
