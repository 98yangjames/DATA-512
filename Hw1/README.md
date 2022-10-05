## Goal
The goal of this project is to parse data from the Wikimedia Foundation REST API from a list of dinosaurs (dinosaur_genera.cleaned.SEPT.2022 - dinosaur_genera.cleaned.SEPT.2022.csv) and analyze the following:

1. Maximum Average and Minimum Average - 
The first graph should contain time series
for the articles that have the highest average page requests and the lowest average page
requests for desktop access and mobile access. Your graph should have four lines (max
desktop, min desktop, max mobile, min mobile).
2. Top 10 Peak Page Views - 
The second graph should contain time series for the top 10
article pages by largest (peak) page views over the entire time by access type. You first find
the month for each article that contains the highest (peak) page views, and then order the
articles by these peak values. Your graph should contain the top 10 for desktop and top 10
for mobile access (20 lines).
3. Fewest Months of Data - 
The third graph should show pages that have the fewest months
of available data. These will all be relatively short time series, some may only have one
month of data. Your graph should show the 10 articles with the fewest months of data for
desktop access and the 10 articles with the fewest months of data for mobile access.

# Setup
The code will run in order properly. Just make sure not to skip any steps as loading in a json will cause the string splitting to get disrupted. 

# Relevant API Documentation
Terms of use: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions for the Wiki REST API

Code example developed by Dr. David W. McDonald for use in DATA 512, a course in the UW MS Data Science degree program. This code is provided under the Creative Commons CC-BY license. Revision 1.1 - May 5, 2022
