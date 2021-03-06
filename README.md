Data cleaning project - NYC Trees
# The Mission
The Department of Environmental Conservation, from New York City, has recently made the news by telling the people that they needed their help. Indeed, their request is simple: They needed the people of New York City, whether young or old, to go to the nearest tree in their street and gather information about that tree. This is all in an effort to make the population aware that nature is important, even in big Metropolis like NYC. Now that they have heard back from the people, the DEC noticed that they missed a crucial step. They forgot to give the people a data collection guide, and so the data they received back is a bit messy.
***
The aim of this project to help them clean the data so that they can begin to raise awareness to ecological issues, such as climate change.

# Data description
Working on a sample of 100k rows and 42 columns which presents for information related to trees in New York City. 

----Requirement for dataset----
- Can values be consolidated? (e.g. Truck and truck refer to the same thing): 
- Are there some columns where most of the data is missing ? 
#health        4993
#spc_latin     4992
#spc_common    4992
#steward       4992
#guards        4992
#sidewalk      4992
#problems      4992

# What I did with Data cleaning duty?
- Convert dtypes: integer columns contain string values
- Replaced null values with np.nan
- Existing 'None' values in categorical columns (e.g. steward: 1or2, 3or4, 4ormore, None)
- Drop duplication
- Strip the spaces in data cell
- Garantee for Values are consolidate (Replaces underscore with space ' ', capitalize values (e.g. 'spc_common')
- Convert yes/no variables into Boolean (True/False) values
- Drop the redundant columns
- Decaration: Rename or reorganize order of columns
- Export the final cleaned dataset
