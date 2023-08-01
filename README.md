# WORLD-HAPPINESS-REPORT-2023
![Screenshot WHR](https://github.com/DollarDKJ/WORLD-HAPPINESS-REPORT-2023/assets/81152387/084e6582-02fc-4f20-b5cb-50fccbdaf04f)

# Introduction
The World Happiness Report gained significant attention and interest from policymakers, researchers, and the general public since its first publication in 2012. Happiness and well-being became important topics for governments and organizations worldwide. It has been over ten years since the first World Happiness Report was published. And it is exactly ten years since the United Nations General Assembly adopted Resolution 66/281, proclaiming 20 March to be observed annually as International Day of Happiness. Since then, more and more people have come to believe that our success as countries should be judged by the happiness of our people. There is also a growing consensus about how happiness should be measured. This consensus means that national happiness can now become an operational objective for governments.

# Problem Statement
This project aims to look at the World Happiness Report for 2023 and understand the latest developments in the Report. The World Happiness Report is to measure and assess the happiness levels of people in different countries around the world it is aimed at providing valuable insights into what factors contribute to happiness and well-being, and how these factors vary across nations.

# Data Sourcing
The data set used for this Analysis was sourced from World Happiness Report 2023 | Kaggle 

# Data Cleaning
Tools used for data cleaning and preparation:
1.	Microsoft Excel
2.	Power Query
I loaded the data into Power Query for transformation through the dataset link to check for any inconsistency and possible errors.
Null values were present in the dataset and were observable in the following columns: Explained by Healthy life expectancy, Freedom to make life choices, Perceptions of corruption.
Deleting the null values will alter the dataset significantly as it will introduce an imbalance by reducing the number of entries in the dataset. So, I replaced these null values with zero 0.
There were no duplicate values in the dataset.
I created a new column named ‘Rank’ to show the rank order of the countries in the report for better visualization and created a new column named ‘Continent’ to indicate the corresponding continent of each country. I utilized the VLOOKUP function in Excel to achieve this.
After the cleaning and the creation of the new columns, there were 137 rows and 21 columns.

# Attributes of the Data
1.	Rank Order: Shows the rank of each country in the happiness report.
2.	Country name: Lists the names of all the countries included in the report.
3.	Ladder score: The ladder score represents the overall happiness or life satisfaction of individual country.  It is based on responses to a survey about how individuals rate happiness based on some predetermined questions. Responses to the questions are rated on a scale of 0 to 10, with 10 being the best possible life and 0 being the worst.
4.	Standard error of ladder score: This column indicates the statistical measure of uncertainty or variability associated with the ladder score. A smaller standard error suggests a more reliable estimate of the country's happiness level.
5.	Upper whisker: The upperwhisker represents the upper limit or boundary of the confidence interval around the ladder score. It provides an indication of the range within which the true ladder score is likely to fall.
6.	Lower whisker: Similarly, to the upperwhisker, the lowerwhisker represents the lower limit or boundary of the confidence interval around the ladder score.
7.	Logged GDP per capita: This column reflects the logarithm (base 10) of the country's Gross Domestic Product (GDP) per capita. It serves as a proxy for the economic well-being of individuals in the country.
8.	Social support: It represents the level of social support or social connections available to individuals in a particular country. It is based on survey responses related to having someone to rely on in times of need, having someone to count on, and having supportive friends and family.
9.	Healthy life expectancy: This column indicates the average number of years of healthy life expectancy in a country. It is a measure of the overall physical and mental well-being of individuals, considering factors such as life expectancy, disease prevalence, and access to healthcare.
10.	Freedom to make life choices: It represents the degree of freedom individuals must have to make life choices in a country. It considers factors such as political freedom, individual rights, and personal autonomy.
11.	Generosity: This column measures the level of generosity or charitable behavior within a country. It is based on survey responses related to charitable donations and volunteerism.
12.	Perceptions of corruption: It reflects the perceived level of corruption within a country. It is based on survey responses that assess the perceived prevalence of corruption in government and business sectors.
13.	Ladder score in Dystopia: Dystopia refers to a hypothetical world where the happiness level is at its lowest possible. The ladder score in Dystopia is a reference point that allows for comparison and contextualization of the ladder scores of actual countries.
14.	Explained by: Log GDP per capita, social support, Healthy life expectancy, Freedom to make life choices, Generosity, Perceptions of corruption: These columns break down the ladder score by attributing the contributions of various factors to the overall happiness level. Each factor is quantitatively explained in terms of its impact on the ladder score.
15.	Dystopia + residual: This column represents a combination of the hypothetical Dystopia level and a residual term. The residual term captures unexplained happiness variations within countries and reflects factors not included in the model.
16.	Continent: This column shows the corresponding continent of each country.
	
# Analysis
The analysis was done in Power BI.
1.	Top 10 Countries by Ladder Score.
2.	Bottom 10 Countries by Ladder Score.
3.	Top !0 Countries Ladder score and Freedom to make life choices By Countries
4.	Bottom 10 Countries Ladder score and Freedom to make life choices By Countries
5.	Top 10 Countries Ladder score and Healthy life expectancy
6.	Bottom 10 Countries Ladder score and Healthy life expectancy.
7.	Top 10 Countries Ladder score and Logged GDP per capita.
8.	 Countries by continents
9.	10 most generous countries
10.	Top 10 countries by perception of corruption.
11.	A map 

 # Visualization
The visualization dashboard was created with Power BI and the following charts were used to draw insights.
•	Cards to show some important metrics.
•	A Stacked bar chart to show Top 10 Countries and regions.
•	A funnel chart. 
•	A map to show the geographical location of the countries.

# Insight
6 out of the top 10 countries in the world happiness record are the Scandinavian countries in Europe, while 8 out of the bottom 10 are countries from Africa. This confirms that the strong social welfare systems in scandinavian countries that provides comprehensive support, access to healthcare, education, and other social services to their citizens help foster a sense of security and well-being.

Luxembourg ranked top in the logged GDP per capita. Luxembourg is one of the wealthiest countries in the world and has a highly developed and diversified economy. Its strong financial sector, favorable tax policies, and strategic location in Europe contribute to its high GDP per capita. The country also benefits from a high standard of living, a well-developed infrastructure, and a relatively low unemployment rate. The logged GDP per capita is based on the idea that economic prosperity and material well-being can contribute to people's overall happiness to an extent. Generally, higher GDP per capita provides individuals with greater access to resources, healthcare, education, and other essential services, which can positively influence their well-being and life satisfaction. It is safe to say that countries in the top 10 rank of the logged GDP per capita take the well being of their citizens seriously and this has a great influence on the happiness level of the citizens.

Freedom to make life choices is one of the key factors considered in the World Happiness Report to assess the happiness levels of people in different countries. It is an essential aspect of well-being, as it reflects the degree to which individuals have the autonomy and freedom to shape their own lives according to their preferences, values, and aspirations. Countries that score high in the freedom to make life choices tend to have happier populations because individuals could pursue their goals and live according to their values without undue constraints. This sense of self-determination can lead to higher life satisfaction and overall well-being. Finland comes first under this measure of countries with freedom to make life choices. 

The healthy life expectancy indicator goes beyond simply measuring life expectancy (which looks at the average lifespan). It considers the quality of life during those years. Healthy life expectancy reflects the overall health status of a population and how well people can enjoy their lives in terms of physical and mental well-being. We have more countries from the Asia continent in the top 4 and it is widely known that those countries have the higher number of aged people which also shows that their government takes the physical and mental well-being of their citizens serious. When individuals can enjoy a healthy and fulfilling life, it positively affects their overall sense of well-being and contentment.

Generosity is an essential aspect of social well-being and community cohesion. When individuals exhibit acts of kindness and generosity, it fosters a sense of trust, social support, and positive social interactions within a society. Generosity is often seen as a reflection of the social fabric of a society. Countries with higher levels of generosity tend to have stronger social connections, a sense of community, and greater trust among individuals. These social factors play a crucial role in shaping happiness and well-being at both the individual and societal levels.

Perception of corruption is a significant factor considered in the World Happiness Report to assess the happiness and well-being of populations in different countries. It reflects the extent to which individuals perceive corruption to be prevalent within their society, government, and institutions. Corruption is generally defined as the abuse of entrusted power for private gain. It can manifest in various forms, such as bribery, embezzlement, nepotism, and favoritism. When corruption is widespread, it can erode public trust, undermine the rule of law, and hinder economic and social development. The perception of corruption is often measured through surveys and assessments that ask individuals to rate the level of corruption in their country or share their personal experiences with corruption. Countries with lower levels of perceived corruption tend to rank higher in happiness reports, as corruption can have several negative impacts on well-being. By considering the perception of corruption in happiness reports, policymakers and researchers gain insights into the broader social and institutional factors that influence happiness and well-being. Countries that actively address corruption and work towards greater transparency and accountability tend to create an environment that fosters trust, fairness, and social stability, positively impacting the overall happiness of their citizens.

# Recommendations 
Different countries have unique circumstances that may influence happiness levels, and understanding these contexts is crucial for drawing meaningful conclusions. It is good to be aware of the limitations of the data and analysis and avoid making overgeneralized or causal claims without further supporting evidence. The happiness index is a complex construct influenced by numerous factors, and no single study can capture the full complexity of human well-being.  However, based on the analysis, government policies can potentially enhance happiness and well-being in countries with lower happiness levels. Countries with low happiness levels can look at successful policies from countries with higher happiness scores and explore their transferability. The perceptions of corruption in a country can be assessed by the prevalence of corruption in government and this can also affect the happiness level of citizens.
Happiness is influenced by various factors beyond income, such as social support, health, freedom, and perceptions of corruption. These factors can play a significant role in determining happiness levels, even in countries with high GDP per capita.





