What can analysing more than 2 million street names reveal?
I analysed every street name in Great Britain And Here are the four most exciting results.
Fanny Hands Lane, Lincolnshire. SourceArguments Yard, Crotch Crescent, Shitterton, Cock Lane, Titty Ho are among the funny street names in Great Britain. Not only these street names are funny but reveal a lot about communities, their cultures and history. Recent complaints about silly names in Great Britain include reduced house prices and more bullying for children living in these silly street names.
Naming streets are not only political and administrative decision making but also reflect the social and cultural values of the city. The names of our roads symbolise culture, values and history. We name streets after legends, well-known people and historical events.
However, street names are less explored quantitative data source and empirical analysis. What can big data analytics and data visualisation reveal in analysing street names from communities, cities and districts? How much gender imbalance can they show? What about religiosity and street names? Do we have more roads than streets? What about Lane, Avenue or Drive? What are the most famous titles?
I analysed more than 2 million streets with names in Great Britain to gain an insight into these issues. The code and preprocessing of the data are available on Github. I will reveal here the Four most essential insights from the analysis with data visualisation.
1. Most popular street names - High Street vs Station Road
Out of 2,323,627 street names, "High Street" is the most popular name with a frequency of 16593 followed by "Station Road" and "Main Street" with 11521 and 7623 entries respectively. The following plot shows the 30 most common street names in Great Britain.
It is also possible to dig deeper and find each district most common street name. For example, Norwich has "Dereham Road" as the most common name while Ipswich has "Nacton Road". On the other hand, we can aggregate at a higher level to find out the most famous street names in :
England - "High Street"
Scotland - "Main Street"
Wales "High Street"
2. The suffix - Roads vs Lane
The suffix of names varies widely across different cities. There are some general standards though for classifying suffix as Road, Lane or Street. With a little bit of preprocessing the data, we can find out also the most popular suffix. Here is a plot showing the top 20 most frequently used suffix in street names.
The "Road" suffix dominates the tally (with 775,537) followed by Lane and street with 238726 and 213881 frequency respectively. We can have a look at how these names are distributed geographically. Here, we aggregate all suffix per city and take the highest frequent street suffix name in each city. The result is quite revealing.
The map shows the magnitude of "Roads" used as a suffix in all districts. In fact, there are only 18 districts which the suffix "Road" is not in the top. Here are the names of all those 18 districts and the top frequent used suffix.
3. Gender imbalance in street names
Street names can also allow us to map the gender imbalance. The gender aspect is a unique opportunity as it is often hard to find indicators for gender imbalances at the city level.
To classify names by Gender, I used Genderize service that allows you code and genderise 1000 names per day freely. I Counted each name and its occurrence, sorted them according to their appearances and took the first 1000. There is an advantage in selecting the most famous names according to their total number of presence. While there are 99,088 unique street names in the dataset, by only genderising the first 1000, we cover almost 50% of the dataset. However, this has also its drawback as it leaves less famous names that might give different results.
Gender classification for the highest 1000 frequently used street names
The Graph above shows a significant gender imbalance in street names. The majority of popular street names are named after a male classified name.
For a deeper understanding and due to genderising API limitation, I took Liverpool city and classified all its street names. Here is a map with a percentage of gender classifications.
The results in Liverpool also clearly point out the gender imbalances in street names. It would be interesting also to look at other cities and find out the results.
4.Religiosity
How much religious influence has street names? Can we quantify them? To find out, we can assume that community with strong religious inclinations tend to name more places with religious names.
Using Oto‐Peralias methodology, we can measure the religiosity of a city as the following:
Religiosity = R / N x 100
Where the numerator, R is the number of streets containing any of the following religous names in the town.
Church, Chapel, Augustine, Bethlehem, St., St. John's, Mary's, Jerusalem, Palestine, Jesus, Christian, Father, Trinity, Babylon, Bethel, Presbyterian, Baptist, Gospel, Hell, Paradise, Jericho, Nazareth, Nimrod, Ninevah, Ophir, Patmos, Zion, Antioch, Canaan, & Heaven.
Although the terms searched are not a comprehensive list of all religious names, It is by far the most widely used street names.
The denominator, N, contains the total number of streets in each city.
The result of this analysis is shown in the following map.
The higher percentage of religous street names can be seen primarily in England, especially the eastern part. For the cities, Isle of Scilly and Mid Suffolk have the highest percentage rate of religious street names.
Conclusion
Street names can be a good source of quantitative data analysis that can reveal a lot about communities and their history. It is an untapped data source, and in this article, we have only scratched the surface.
The data used for this article comes from the Ordinance survey and can be accessed from Here.
