# Python-for-data-science-assignments
My Assignments solutions for the 'Python for data science' course
## Task 1 - Data Transformation and Cleaning with Pandas

### Required 
- Load the energy data from the file Energy Indicators.xls, which is a list of indicators of energy supply and renewable electricity production from the United Nations for the year 2013, and should be put into a DataFrame with the variable name of energy.

Keep in mind that this is an Excel file, and not a comma separated values file.

- make sure to exclude the footer and header information from the datafile. The first two columns are unneccessary, so you should get rid of them, and you should change the column labels so that the columns are:

['Country', 'Energy Supply', 'Energy Supply per Capita', '% Renewable']

- Convert Energy Supply to gigajoules (there are 1,000,000 gigajoules in a petajoule). For all countries which have missing data (e.g. data with "...") make sure this is reflected as np.NaN values.

- Rename the following list of countries (for use in later questions):

"Republic of Korea": "South Korea",
"United States of America": "United States",
"United Kingdom of Great Britain and Northern Ireland": "United Kingdom",
"China, Hong Kong Special Administrative Region": "Hong Kong"

- There are also several countries with numbers and/or parenthesis in their name. Be sure to remove these,

e.g.

'Bolivia (Plurinational State of)' should be 'Bolivia',

'Switzerland17' should be 'Switzerland'.

## Task 2 - Scripting and Semi-Structured Data.ipynb

### Problem Descripition
In 2012, URL shortening service Bitly partnered with the US government website USA.gov to provide a feed of anonymous data gathered from users who shorten links ending with .gov or .mil.
The text file comes in JSON format and here are some keys and their description. 

### Required:
Write a script that can transform the JSON file to a DataFrame and commit it to a sparete CSV file.

## Task 3 - Data visualization with Plotly

### Required:

Use plotly to create the following plots:

- Scatter plot 

- Choropleth plot 

- Heatmap 

- Surface plot


