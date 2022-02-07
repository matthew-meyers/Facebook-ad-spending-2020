# Facebook-ad-spending-2020
This is a dataset containing information on Facebook Ad spending for Congressional Candidates in 2020 along with election results and district demographic information. It can be used to study patterns and trends in the types of Congressional races saw the most spending on Facebook advertising for their district. It merges data from a number of sources, including the Facebook Ad Library, FEC filings, and the MIT Election Science Lab.

There are 493 observations out of of a total of 946 possible Congressional races.

The sources for this data are as follows (citations at bottom of document):

MIT Election Data and Science lab: Two Datasets, one for Senate elections and one for House elections, contains data about electoral results for congressional elections since 1976. Data for 2020 general elections was used here.

FEC filings: The FEC website displays total campaign expenditures using an interactive tool. I scraped the data from this webpage for use in this project.

Facebook Ad Library via Open Secrets: Facebook makes political ad spending available on the Facebook Ad Library. Open Secrets compiles this data by spender and makes it available on their website. I scraped the data for all spenders that contain the phrases "for Congress", "for House", or "for Senate".

"State Demographics" Dataset: Available on CORGIS dataset project, this dataset contains information about state demographics.

Statista: Additional State Demographic data to supplement the data available on the CORGIS dataset.

District Demographic data from "Historical Congressional Legislation and District Demographics 1972-2014": This dataset, compiled by Ella Foster-Molina and available on Harvard Dataverse, has demographic information about Congressional Districts.


Data Citations:

Foster-Molina, Ella. “Historical Congressional Legislation and District Demographics 1972-2014.” Harvard Dataverse. Harvard Dataverse, May 9, 2019. https://doi.org/10.7910/DVN/CI2EPI. 

“Gap between Rich and Poor, by State in the U.S. 2019.” Statista, September 20, 2021. https://www.statista.com/statistics/227249/greatest-gap-between-rich-and-poor-by-us-state/. 


Hernson, Paul S., Atiya Kai Stokes-Brown, and Matthew Hindman. "Constituency Characteristics, Strategic Considerations, and Candidate Internet Use in State Legislative Elections." Public Research Quarterly 60, no. 1. Accessed December 19, 2021. https://journals.sagepub.com/doi/pdf/10.1177/1065912906298527.

“Online Political Ad Spending.” OpenSecrets. Accessed December 21, 2021. https://www.opensecrets.org/online-ads?sort=fb_total_desc. 

“Spending: By the Numbers.” FEC.gov. Accessed December 21, 2021. https://www.fec.gov/data/spending-bythenumbers/?election_year=2020&office=H. 

“Spending: By the Numbers.” FEC.gov. Accessed December 21, 2021. https://www.fec.gov/data/spending-bythenumbers/?election_year=2020&office=S.

“U.S. House 1976–2020.” Cambridge: MIT Election Data and Science Lab, 2020. 

“U.S. Senate 1976–2020.” Cambridge: MIT Election Data and Science Lab, 2020. 
“U.S. States: Median Age 2019.” Statista, September 20, 2021. https://www.statista.com/statistics/208048/median-age-of-population-in-the-usa-by-state/.

Whitcomb, Ryan, Joung Min Choi, and Bo Guan. “State Demographics CSV File.” CORGIS Datasets Project. Accessed December 21, 2021. https://corgis-edu.github.io/corgis/csv/state_demographics/. 


Note: If you believe that you have found an error in the merging of these datasets, please send me a private message.
