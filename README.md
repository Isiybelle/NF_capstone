# Art Imitates Life: An Analysis of AO3

## Table of Contents
* [Motivation](#motivation)
* [Questions](#questions)
* [Normalizing the Data](#acquiring-and-normalizing-the-data)
* [Problems and Challenges](#problems-and-challenges)
* [Technologies Used](#technologies-used)
* [Sources](#data-sources)

## Motivation:
- The growth of transformative works and the communities that sprout around them have long been of interest to me, an avid reader since I was 12. The effort and dedication put into a medium purely for the sake of adoration and interest makes websites like AO3 a unique platform that not only archives the straightforward works of the community, but the unintentional change of community and paradigms over time, something I have tangentially witnessed myself over the years through interacting with content and growing fandoms. As both a writer and a reader, the data that AO3 has collected and continues to collect presents a hub of information on the nature of fandom and its place in fans’ consciousness – information of which both fascinates and potentially benefits my usage in the future.

## Questions:
1)	Determine the ‘life expectancy’ of smaller fandoms, including when they peak and what that peak looks like.
2)	Investigate how that ‘life expectancy’ varies across fandom sizes
3)	Compare to larger fandoms, potentially still growing ones to predict their withering or revivals.
4)	Analyze fandom timelines across the releases of the media that fuels them and how they fluctuate in turn, if the release of new movies or books can accurately revive a fandom and where revival happens spontaneously. 

## Acquiring and Normalizing the Data
- I made use of AO3’s official data release from 2021 (https://archiveofourown.org/admin_posts/18804), as well as their API for web scraping (https://ao3-api.readthedocs.io/en/latest/). 

## Problems and Challenges 
- The AO3 released data, while comprehensive, needed to be cleaned and manupulated for efficiency. The released dataset also only contained data up to February 2021, therefore I had to scrap more recent data myself which required learning how to properly use their API.

## Technologies Used
1) Python - for initial analysis, cleanup & manipulation, and API usage
2) Git - version control
3) Power BI - for data visualization and presentation purposes
4) Powerpoint - for presentation purposes

## Data Sources

1) https://fanlore.org/wiki/Main_Page - for topical research
2) https://archiveofourown.org/ - archive itself
3) https://ao3-api.readthedocs.io/en/latest/ - AO3 API
4) https://archiveofourown.org/admin_posts/18804 - released 2021 dataset
5) https://web.archive.org/web/20030423102749/http://writersu.s5.com/history/history01.html - for topical reserach
