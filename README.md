### nosql-challenge
# *Eat Safe, Love*
This challenge has us as a data analyst contracted by the editors of a food magazine, *Eat Safe, Love*, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles by analyzing food hygiene ratings of various establishments across the United Kingdom from the UK Food Standards Agency.
## Database Manipulation: [NoSQL_setup.ipynb](NoSQL_setup.ipynb)
#### Part 1: Database and Jupyter Notebook Set Up
We used `mongoimport` in Anaconda Prompt to load `establishments.json` into MongoDB, then used `pymongo` to import database into a Jupyter notebook.
#### Part 2: Update the Database
We used `pymongo` to make changes to the database.
## Data Analysis: [NoSQL_analysis.ipynb](NoSQL_analysis.ipynb)
#### Part 3: Exploratory Analysis
We used `pymongo` to perform queries, then used `pandas` to display results as a dataframe.
## References
UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).
