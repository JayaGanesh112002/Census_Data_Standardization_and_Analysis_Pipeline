<h3>Census Data Standardization and Analysis Pipeline</h3>

<h4>Description : </h4>
  Census Data Standardization and Analysis Pipeline is a basic project for learning Data cleaning and analysis. Data is first imported from a CSV file, then the columns are standardized as per the requirements, then comes the cleaning part and then finally Visualizing some valuable insights from the cleaned data. Between this cleaning and visualiations parts, the cleaned is first inserted into MongoDB (NoSQL DB) and then retrived from it to store in a MySQL DB; from where the data is retrieved as per the required queries to visualize the data.

<h4>Tools used : </h4>
Python, Pandas, MySQL Connector Python, PyMongo, Streamlit <br>
<br>

<h4>Basic workflow : </h4>
1. Start <br>
2. Read the data from CSV file <br>
3. Standardize the column names <br>
4. Edit the existing data to comply with new rules <br>
5. Identify the percentage of missing data for each column before cleaning <br>
6. If all required values are available (Not Null): <br>
>>>True: Fill the values based on the calculation performed on the values <br>
>>>False: Do not fill <br>
7. Identify the percentage of missing data for each column after cleaning <br>
8. Write the missing data details in a new file for visualization <br>
9. Upload the cleaned data into MongoDB <br>
10. Retrieve the stored data from MongoDB and upload it to MySQL <br>
11. Query the MySQL DB and display the results in Streamlit <br>
12. End <br>
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
