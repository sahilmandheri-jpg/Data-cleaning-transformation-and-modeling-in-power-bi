### Theoretical Questions

**Question 1 : What is Data Loading in Power BI and why is it considered the first step of analysis?**
Data loadind is the process of connecting data source to power BI. So that power bi can easily get that data and work on it. It is also known as the first step on data analysis because we can't do anything without loading the data, so for making analysis aua dashboards, first we must have data.

**Question 2 : Explain the difference between “Load” and “Transform Data” in Power BI.**

When we click **Get Data**, after getting the desired file or creating connection this we are redirected to transform and load option. Although both seems same but have a lot of differences. Load option is used for getting data for visualization, while the transform option is used to make transformation. When the transform button is clicked it redirects us to power query tab, where we can perform transformation and cleaning before loading.

**Question 3 : What is a Fact Table and a Dimension Table? Give examples from the dataset.**

Fact table may be define as main quantifiable table, all the numeric columns are present in this table. The dimension tables can be defined as filtering table, genrally they are categorical in nature these tables are used to filter and minimize the size of data, also they tell about deferent persepectives of data.

Let's take an example from the data 
       We have columns Date, Confirmed_Cases, Recovered_Cases, Deaths, Active_Cases, Tests_Conducted, Hospitalized, Vaccination_Status in which calcualations can be performed, so we can say it a fact table.
       
Now the state and country columns Can be fit into another Dimension table 'Location' containing the columns state and country. 

**Question 4 : Why is Star Schema preferred over Snowflake Schema in Power BI?**

Star schema may be define as the schema having one fact table and other dimensional tables which are connected to main fact table, while the snowflake schema may be defined as the shcema having fact and multiple dimension table but these dimenstions tables have theire own separate dimension tables.

benefits of star schema over snowflake schema:
1. Easy to use DAX
2. Easy to create dashboards
3. Low number of relationships
4. Better performance, fax query execution
5. Better filteration
6. Easier to understand
7. Less chances of error because of shorter DAX formulaes




   

           

