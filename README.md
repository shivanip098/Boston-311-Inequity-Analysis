# Boston 311 Inequity Analysis
*This project utilizes the Boston 311 report data and geospatial data from Analyze Boston*  

## Introduction
The purpose of this project was to analyze 311 report data to determine if patterns could be identified and used to make recommendations to the city of Boston. This report specifically looked at cases from Boston, MA. The BOS311.csv file contains report data and findings were supplemented using geospatial data found on the Analyze Boston database.

## Configuration and Installation
To utilize this code, you will need an API key from Google Developers. This allows us to use Google Maps when generating graphs. The key can be inserted into the code directly by editing the first code block to insert your personal key.

main.Rmd contains the full code as well as all exploratory analysis. Aside from the key, this code requires the BOS311.csv and the shp file found in the Boston_Neighborhoods.zip file. I also provided geojson files containing neighborhoods and street segment data that was used in my personal, in depth analysis.

## Contact Information
If you have any questions or suggestions for this project, please feel free to contact me at shivanip098@gmail.com !

## Challenges
As detailed in the above report, the main issue that arose with this project was using the data to determine differences. When generalized into less specific categories, there were no clear patterns or differences between case types or number of reports with the exception of very low population ares.

In the future, I'd like to incorporate more predictive analytics and to use data regarding building type or neighborhood designations (residential, commercial, etc)

## Credits
Thank you to Analyze Boston as well as the City of Boston for providing the data sources used within this project.