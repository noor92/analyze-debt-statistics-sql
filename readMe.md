# Analyze International Debt Statistics
SQL based project

### Project Description

It's not that we humans only take debts to manage our necessities. A country may also take debt to manage its economy. For example, infrastructure spending is one costly ingredient required for a country's citizens to lead comfortable lives. The World Bank is the organization that provides debt to countries.

The purpose of this project is to breifly analyze international debt data collected by The World Bank. The dataset contains information about the amount of debt (in USD) owed by developing countries across several categories. This is a small project I'm using to demostrate problem-solving, skill-developement and communicate skills.

The questions that are going to be addressed are: 

- What is the total amount of debt that is owed by the countries listed in the dataset?
- Which country owns the maximum amount of debt and what does that amount look like?
- What is the average amount of debt owed by countries across different debt indicators? 

The data used in this project is provided by The World Bank. It contains both national and regional debt - - statistics for several countries across the globe as recorded from 1970 to 2015.



### Deployment

To run the sql statment, I've connected to postgres. Download it here https://www.pgadmin.org

To run postgres locally: 
 
Install : https://www.postgresql.org/download/

```bash
  pip install psycopg2
```
```bash
  pip install sqlalchemy
```

```bash
conda install -c conda-forge ipython-sql
```


Create an engine:
```bash
engine=create_engine("postgresql+psycopg2://postgres:password@localhost:5432/postgres")
```