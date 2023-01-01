# CAA-fact-checks
This project contains fact-check reports related to CAA protests published by six leading fact-checking organizations in India.
Five among them are Facebook partners and the remaining one is Alt News, an independent organization. 
Fact-check stories published between December 2019 to March 2020 were scraped for the project. 

## Methodology

### Scraping

The article links were collected in two ways:

1. Scraping Google search results: Fact-check URLs were gathered using a time-search on Google, restricted to the website of the specific organization.
A Google search result scraper was used to get all the links and put them in a list. 
2. Directly scraping the websites.

Each of the links were then scraped to extract the article headlines, date of publish and fact-check details where provided. 

### Cleaning

The data was cleaned on pandas. 
Each organization data is in two notebooks - one for the story links and one for cleaing the data from the links. 

### Combining and plotting

The data was then combined to a single dataframe to analyze the number of stories related to CAA protests published by each organization.
Absolute numbers and the normalized data were both plotted on ggplot2. 

The analysis showed that most Facebook fact-checking partners had scanty coverage of disinformation related to the protests. 

### Limitations

The analysis is only a part of a larger story about nature of fact-checks during CAA protests. It does not give details about whether the most
viral or dangerous disinformation was fact-checked by an organization. The number of stories only depicts a part of the picture.




