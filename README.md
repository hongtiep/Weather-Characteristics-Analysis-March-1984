# Weather-Characteristics-Analysis-March-1984
My team started with a JSON file containing 10,000 lines and 26 properties, aiming to conduct comprehensive data analysis using  Power BI and R. Our approach unfolds as follows:
- Initially, we transform the JSON data into structured tables, where we explore and cleanse the dataset using Python.
- Subsequently, we design a relational database management system (RDBMS) schema using SQL.
- With the RDBMS schema in place, we proceed to convert the Python data into tables that align with our designed RDBMS schema, subsequently inserting this data into SQL.
- Our RDBMS schema adopts the format of star schema design. From this data warehouse, we establish a connection to the OLAP service to acquire analytics data.
- Finally, the resulting data is exported from OLAP to Power BI for in-depth analysis. For analytical tasks in the R language, we leverage the read.csv() command followed by the requisite analysis procedures.

You can view the PowerPoint file below to visualize in more detail the process and results of our project:
https://docs.google.com/presentation/d/1elxrMow0oJDldWcIvzvMpzcfX4Ap57fI/edit?usp=drive_link&ouid=110004581860349139297&rtpof=true&sd=true 
You can view the entire project including code and analysis results using the following link:
https://drive.google.com/drive/folders/1A2Nuymfr0GYCY0f-J-uU-JFYmIY0TABI?usp=sharing 
