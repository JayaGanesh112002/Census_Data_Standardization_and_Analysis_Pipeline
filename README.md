<h3>Census Data Standardization and Analysis Pipeline</h3>

<h2>Description : </h2>
  Census Data Standardization and Analysis Pipeline is a basic project for learning Data cleaning and analysis. Data is first imported from a CSV file, then the columns are standardized as per the requirements, then comes the cleaning part and then finally Visualizing some valuable insights from the cleaned data. Between this cleaning and visualiations parts, the cleaned is first inserted into MongoDB (NoSQL DB) and then retrived from it to store in a MySQL DB; from where the data is retrieved as per the required queries to visualize the data.

<h2>Tools used : </h2>
Python, Pandas, MySQL Connector Python, PyMongo, Streamlit <br>
<br>

> [!CAUTION]
> <strong>Note : <br>
> 1. Please make sure that you're connected to the MySQL server before running the files. <br>
> 2. Please run the CensusDataPipeline.ipynb first. The CensusDataPipeline.ipynb file consists the Data imports, cleaning and uploading to Database. <br>
> 3. Please make sure that you have installed streamlit before running the Census2011_Queries.py file. <br>
> 4. In case if you've not installed streamlit previously, open the Project document in VS Code, open the terminal and execute the command - pip install streamlit. <br>
> 5. Or just open command prompt and execute the command pip install streamlit. <br>
> 6. Before running the Census2011_Queries.py file make sure to change the variable uri with your MongoDB localhost connection string. (At the beginning of Task 5) <br>
> 7. In order to run the Census2011_Queries.py, open the terminal and execute - streamlit run Census2011_Queries.py</strong>
