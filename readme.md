# Analysis on Income Predication Data Set

Author: Ephraim Sun, Jadon Swearingen, Adeeb-AbdulTaher

### Business Understanding

The purpose of the Income Prediction DataSet provided by Zindi is to analyze and classify if a person earns more or less than $50,000 based on various data variables. Specifically, we are given a random population of over 100,000 individuals to test on 200,000 training data. The data is collected from a random American population where the media income was about $50,000 and is provided by the company Zindi. Third parties like Zindi are interested because they will use the machine learning algorithm to classify further individuals and people, giving them a score based on these model accuracy. Furthermore, third parties can use this data in applications like Finance (credit scoring and loans, fraud detection), Healthcare (health insurance and healthcare programs), as well as other areas like HR and Public Policy. The current predicition algorithm that will be considered useful to other parties is that it must be better than 96%, which another person has achieved.

### Data Understanding

Data Types

We have a large dataset with 42 variables. Therefore, we have decided to narrow down to 10 specific data sets that our team finds valuable along wih its corresponding data variable

| Variable    | Savings | Description | 
| -------- | ------- | ------- |
| Age  |  Integer   | The age of the individual | 
| Gender |  Categorical    | If they are male or female
| Education    |  Categorical   | What level of education they are in: high school, children, some college but no degree, bachelors degree(BA, AB, BS), 7th and 8th grade
| Race   |  Categorical   | White, Black, Asian or Pacific Islander, American Indian, Other
| Employment Commitment    |  Categorical   | This is the employment Status of the indivudal: Children or Amred Forces, Full-time schedules, Not in labor force, PT for non-econ reasons usually FT, Umeployed full-time, 
| Citizenship    |  Categorical   | What is citizenship status in regards to the United States: Native, Foreign born - Not a citizen of US, Foreign born - US citizen by naturalization, Native - Born abroad of American Parents, Native - Born in Puerto Rice or US Outlying
| Wage per hour    |  Float   | How much they make per hour
| Working_week_per_year   |  Number   | How many weeks per year they work (0- 52)
