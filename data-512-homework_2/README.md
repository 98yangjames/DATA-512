# Considering Bias in Data
## Homework #2
The goal of this assignment is to explore the concept of bias in data using Wikipedia articles. This assignment will consider articles on political figures from different countries. For this assignment, you will combine a dataset of Wikipedia articles with a dataset of country populations, and use a machine learning service called ORES to estimate the quality of each article.
You are expected to perform an analysis of how the coverage of politicians on Wikipedia and the quality of articles about politicians varies among countries. Your analysis will consist of a series of tables that show:
1. The countries with the greatest and least coverage of politicians on Wikipedia compared to their population.
2. The countries with the highest and lowest proportion of high quality articles about politicians.
3. A ranking of geographic regions by articles-per-person and proportion of high quality articles.
You are also expected to write a short reflection on the project that focuses on how both your findings from this analysis and the process you went through to reach those findings helps you understand the causes and consequences of biased data in large, complex data science projects.

## Research Implications

**1. What might your results suggest about (English) Wikipedia as a data source?**

Interestingly enough, people who browse english wikipedia seemingly don't create higher quality articles for North America. They create higher quality articles for middle eastern countries such as Iraq and Pakistan. This may have been a result of wikipedia being more popularly used during the eras of the Iraq War and political debacles during this time, and the desire to retain more information regarding American soldiers and subsidies.

**2. How might a researcher supplement or transform this dataset to potentially correct for the limiations/biases you observed?**

A researcher may implement more features utilizing more language based wikipedia pulls other than just English. Limiting a sample size to just one langauge is already inheirently bias, and incorporating more languages used and browsed upon can mitigate some of that bias created. They can also transform this dataset to incorporate wikipedia off branches including Wikidata, Wikinews, Wikisource, etc. These can supplement different types of features which do incorporate answers and results from more than just english. Another thing to consider is the fact that the population is so small but yet the number of clicks could be arbitrarily high relative to the population that it makes it shoot up in per capita.

**3. What might your results suggest about the internet and global society in general?**

The results may indiciate that there is a general population that uses Wikipedia and they seem to orient themselves towards specific articles in specific regions. In the case of the results that we got here, there isn't that much high quality information on the east asian region, which could be due to the geopolitical status of China and how a lot of their information is restricted or hidden. Access to this information can be sensitive which is why Wikipedia doesn't have that much verified documentation on countries in these territories. It suggests that Wikipedia can only go as far as the general public lets it, and how society can in turn affect how much information and how much high quality content is put on their web domain. 

## Steps to Procedure

1. Run the code entry by entry
2. DO NOT SKIP STEPS. Some of the variables are being manipulated in an effort to satisfy the requirements of the assignment.
3. The outputs are already premade and the files are already produced in the folder.

## API INFO
[MediaWiki REST API for the EN Wikipedia](https://www.mediawiki.org/wiki/API:Main_page). The API documentation, [API:Info](https://www.mediawiki.org/wiki/API:Info)

## License
This code example was developed by Dr. David W. McDonald for use in DATA 512, a course in the UW MS Data Science degree program. This code is provided under the [Creative Commons](https://creativecommons.org) [CC-BY license](https://creativecommons.org/licenses/by/4.0/). Revision 1.0 - May 13, 2022



