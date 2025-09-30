# Blinkit_Sales_dashboard
This project implements a simple ETL (Extract, Transform, Load) pipeline to process Blinkit grocery sales data. The goal is to build a foundation for a sales dashboard by cleaning the raw data and structuring it within a database.

# Tools Used
Primarily, two powerful Python libraries are used for the ETL process:

Pandas: For data manipulation and transformation.

SQLAlchemy: For database communication and loading the data into SQLite.

Jupyter Notebook: For scripting and executing the ETL steps.

# File Structure
Here's an overview of the key files in this project:

BlinkIt Grocery Data.xlsx: The raw dataset containing grocery sales information.

setup_db.ipynb: A Jupyter Notebook script that performs the ETL process: it reads the Excel file, transforms the data, and loads it into the blinkit_sales.db SQLite database.

final_script.ipynb: The main Jupyter Notebook for performing data analysis or generating visualizations for the dashboard.

blinkit_sales.db: The resulting SQLite database populated by the setup_db.ipynb script.

# Getting Started
Follow these instructions to get a copy of the project up and running on your local machine.

Prerequisites
Make sure you have Python 3 and pip installed on your system.

Installation
Clone the repository (replace your-username with your actual GitHub username):

git clone [https://github.com/garima533/BLINKIT_Sales_dashboard.git](https://github.com/garima533/BLINKIT_Sales_dashboard.git)

Navigate to the project directory:

cd Blinkit_Sales_dashboard

Install the required Python packages:

pip install pandas jupyter sqlalchemy

# Usage
To run the project, you need to execute the Jupyter Notebooks in the correct order.

Run the ETL script:
First, run the setup_db.ipynb notebook. This will read the BlinkIt Grocery Data.xlsx file, process it, and create the blinkit_sales.db.

jupyter nbconvert --to notebook --execute setup_db.ipynb

Run the analysis/dashboard script:
After the database is created, run final_script.ipynb to analyze the data.

jupyter nbconvert --to notebook --execute final_script.ipynb

# Live Demo
(https://drive.google.com/file/d/1o8NZF_tQ0D4et7jIjdMFvlMsO0VLPeZS/view?usp=sharing)
