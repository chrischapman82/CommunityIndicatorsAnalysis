# CommunityIndicatorsAnalysis
Identifying and analysis of indicators of community strength

A project I did for looking at how open data can be wrangled to gain insight into issues affecting Victoria, taking open data from a large range of areas, including health, business, education, tourism, the environment, communities, the arts, commerce,
public amenities, employment, sport, usage of facilities and real estate

I chose to look at identifying and analysing indicators of community strength, seeing what factors make a stronger and safer communities.
Data was taken from the 2015 census data, divided into LGAs (Local Government Areas).
The data used can be found in ZIPs and CSVs.


This was a rather frustrating project and really made me respect the work of Data Scientists and the hoops they are required to go through to get information.
I was initially interested in looking at the retail prices of Houses in Australia over time, but this information was often treated by housing companies as closely guarded secrets, requiring massive sums of money to access the data.




-- phase3_final.pdf -- 
Contains a report for the university project.
Aimed at the Victorian government, looking at the usefulness of having open data, allowing for helpful analysis, allowing for identification of communities that may need more help than others.
-- More information included inside the report!

-- Phase3.ipyndb -- 
Contains a ipython document in which I used python and Pandas to:
- Clean data
  - Modifying data so that the forms were consistent
  - Removing whitespace
  - Modifying header names for readability
  - Grouping different datasets by LGAs
  - removing large outliers (with justifcation included in the report)

- Used Pandas to create visualisations of the data:
  - Created bar charts to compare factors for each LGA
  - Calculating Mutual Information and Entropy to find outliers
  - Created Scatterplots then used Pearson correlation to compare trends in different features
  - Applied a HeatMap - revealed no useful information - unused in final report
  - Applied Parallell coordinates
  
  
-- CSVs --
   - Contains CSVs of the 2015 Census data that was used in the project
   - I believe that 2015 Census data is still available...

-- ZIPS --
   - Contains more CSV data, some of which I used to create the final datasets.
   

Reflection:
This project was especially helpful in:
- Understanding the sometimes very long process of getting data for a projects, being delayed for several days waiting for replies to emails.
- The process of cleaning and curating datasets into a usable form
- Developed my pandas and python skills, creating fast and efficient tables
- Developing my ability to create visualisations of a data set through heatmaps, parallell coordinates, bar charts and scatterplots.
