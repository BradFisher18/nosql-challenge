# noSQL-challenge
In this challenge, we are tasked to utilise MongoDB and pymongo to assist with importing UK Food Standards data into a databse, updating/ inserting new data and performing exploratory analysis on it. 
## Database and Jupyter Notebook Setup
Located within the NoSQL_setup_starter.ipynb file, the establishments.json file, is imported via Mongo and stored within a databse labelled 'uk_food' and collection 'establishments'.
## Update the Database
In this section, utilising the NoSQL_setup_starter.ipynb file, an additional establishment call Penang Flavours was added to the existing establishments collection with the Business Type ID also updated to suit the business type. The establishments in Dover were also removed, and the data type for latitude and longitude were changed to decimals, and rating value changed to an integer.
## Exploratory Analysis
Located within NoSQL_analysis_starter.ipynb, this section explores and outputs the below analysis within a DataFrame:
* Establishments with a hygiene of 20
* Establishments in London with a Rating Value of greater than or equal to 4
* the top 5 establishments in terms of lowest hygiene score, with a rating value of 5 within close proximity to the new restaurant of Penang Flavours
* the top 10 local authorities with the most establishments with a hygiene score of 0
## Running
