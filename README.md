# Merge Data Sets
Background: We want to merge both datasets together based on the address and Zip Code
Requirements: 
  1) Address on Inspection Data and API Data are formatted the same
  2) Zip Code is the same
  3) Both DataFrames are cleaned 
Outcome: DataFrame

# Color the Markers Based on Ranking
Background: We want to use google maps to create a ranking system of how good/bad a Restaurant is
Requirements:
  1) Merged DataFrame for API/Inspection 
  2) Create a DataFrame based on Restaurant Ranking
    a. 4> = Great Rating
    b. 3-2 = Okay Rating
    c. >2 = Poor Rating
  3) Create DataFrames with the Following Criteria: 
    a. Restaurant with Poor Rating + Failed Health Inspection 
    b. Restaurant with Great Rating + Passed Health Inspection
    c. Restaurant with Poor Rating + Passed Health Inspection 
    d. Restaurant with Great Rating + Failed Inspection
  4) Make sure to import Google Maps and create gmaps with markers:
     a. Red = DataFrame for Poor rating + Failed Health
     b. Green =  DataFrame for Great rating + Passed
     c. Yellow =  DataFrame for Poor Rating + Passed
     d. Orange/Green =  DataFrame for Great rating + Failed
Outcome: Gmap with Colored Pointers

# DataFrame for Passed & Failed
Background: We want to create 2 dataframes to seperate fail vs passed resturants
Requirements:
  1) Merged DataFrame for API/Inspection 
  2) DataFrame for Restaurant with Failed Status
  3) DataFrame for Restaurant with Passed Status
Outcome: 2 New DataFrames

# Scatter Plot
# DataFrame for Passed & Failed
Background: We want to see if there is a relationship between Zip Code, Pass & Fail DataFrames. We also want to look at Price to Value Rating.
Requirements:
  1) Scatter Plot for Passed Resturants vs Zip Code
  2) Scatter Plot for Failed Resturants vs Zip Code
  3) Scatter Plot for Price Value vs Rating 
  4) Add Linear Regression Line & R Value
Outcome: 3 scatter plots with a regression line & r value

# Price and Zip Code
Background: We want to drive deeper into comparing price value to zip code
Requirements: 
1) Merged DataFrame
2) Average Price for Zip Code
3) Average Price & Rating Per Zip Code
Outcome: DataFrame with Comparison Points
