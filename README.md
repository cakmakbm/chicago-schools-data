# Chicago Public Schools Data Analysis

This project involves the analysis of a dataset containing various metrics for public schools in Chicago, sourced from the `ChicagoPublicSchools.csv` file. The analysis includes loading the data into an **SQLite** database using the **Pandas** library, followed by executing **SQL** queries to explore metrics such as school safety, student attendance, and college enrollment rates by community area.

## Project Files

* 📄 `chicago-schools.ipynb`: The main Jupyter Notebook file where all data processing, database creation, and SQL analysis are performed.
* 📊 `ChicagoPublicSchools.csv`: The raw CSV file containing the dataset used for this analysis.
* 🗃️ `RealWorldData.db`: The SQLite database file that is generated when the notebook is run. It holds the data from the CSV file, and all SQL queries are executed against this database.

## Technologies Used

* **Python 3**
* **Jupyter Notebook**
* **Pandas**: For reading and processing the CSV data.
* **SQLite3**: For creating and managing the local database.
* **ipython-sql**: For running SQL queries within the Jupyter Notebook environment using `%sql` magic commands.

## Setup and Usage

To run this project on your local machine, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/cakmakbm/chicago-schools-data.git](https://github.com/cakmakbm/chicago-schools-data.git)
    cd chicago-schools-data
    ```

2.  **Install Dependencies:**
    ```bash
    pip install pandas jupyterlab ipython-sql sqlalchemy
    ```

3.  **Launch Jupyter Notebook:**
    ```bash
    jupyter lab
    ```
    or
    ```bash
    jupyter notebook
    ```

4.  **Run the Analysis:**
    Open the `chicago-schools.ipynb` file from the Jupyter interface and run the cells sequentially from top to bottom.

## Analyses Performed

The analysis in the notebook aims to answer several key questions, including:

* How many schools are in the dataset?
* Which schools have the highest safety scores (`SAFETY_SCORE`)?
* Which schools have the highest and lowest average student attendance (`AVERAGE_STUDENT_ATTENDANCE`)?
* Which community areas (`COMMUNITY_AREA_NAME`) have the lowest and highest total college enrollment (`COLLEGE_ENROLLMENT`)?
* A list of schools with safety scores below 70.
