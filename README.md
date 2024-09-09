Objective
Create a tool that fetches data from a public API, processes it, and generates a report.
Project Requirements
1. Use the OpenWeather API (specifically the Weather Overview endpoint) to fetch weather
overview data for: New York City, New York; Denver, Colorado; San Francisco,
California; Boston, Massachusetts; and Montrose, Colorado.
○ get this data in imperial units
2. Parse the JSON response from the API before you read the data into a dataframe.
3. Read the data into a pandas dataframe
○ You may do any pre-formatting like casting, striping whitespace, etc as you feel is
necessary. Or you may leave this out altogether. This part won’t be reviewed, so
you may do whatever makes you feel comfortable.
○ Create columns for: current temperature, feels-like temperature, and uv_index.
○ Create a new column that converts the fahrenheit value to celsius
○ Read in and use the City Lat Long table (in resources below), to create new
columns for city and state names
○ Filter the data to all instances where the daily temperature is below 78 degrees
4. Export the processed data and insights to a spreadsheet file using pandas.
