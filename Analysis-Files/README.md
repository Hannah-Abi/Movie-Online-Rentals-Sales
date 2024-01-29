## Step-by-step of analyzing 
### Step 1: Install SQL in Jupyter NoteBook
SQL is a powerful language for working with relational databases, and many data scientists work with SQL on a regular basis. By using SQL in Jupyter Notebook, you can:
- Query and manipulate data directly within your notebook environment
- Combine SQL queries with Python code to create more complex analyses and visualizations
- Easily share your SQL queries and results with others by exporting your notebook as a PDF or HTML file
#### There are 2 main ways to run SQL query in JP: 
- Using pandasql Queries (check file [EDA-in-SQL](./EDA-in-SQL.ipynb)
- Using ```ipython-sql``` to install SQL kernal 
### Step 2:  Run the following file in order:
1.  [EDA-in-SQL.ipynb](./EDA-in-SQL.ipynb): using simple SQL queries to extract and aggregated data from its database.
2.  [Customer-insight.ipynb](./Customer-insight.ipynb): More complex queries with ```GROUP BY```, ```LEFT JOIN``` and sub-queries are used to gain insight into customer preferences.
3. [Categorisation.ipynb](./Categorisation.ipynb): The concept of nested queries and correlated nested queries is introduced and the functions EXISTS and UNION are used to categorize customers, movies, actors, and more.
4. [OLAP-visualisation.ipynb](./OLAP-visualisation.ipynb): Aggregate data for a better overview
