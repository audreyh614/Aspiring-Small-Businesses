# Aiding Small and Medium B.I.P.O.C Businesses
*B.I.P.O.C means Black, Indigenous, People of Color*

## Project Objective
JP Morgan Chase & Co. (JPMC) has announced their global initiative to invest $350 million into growing underserved businesses owned by members of underrepresented communities. "More than 40% will include low-cost loans and equity investments, removing a critical financial barrier for Black, Latinx, women and other underserved entrepreneurs.” The firm intends to invest $42.5 million "to expand successful Entrepreneurs of Color Fund to more U.S. cities and introduce data-driven policy solutions to increase access to capital for historically underserved entrepreneurs".

*For more information relating to this global commitment, read:*
https://www.jpmorganchase.com/news-stories/jpmc-commits-350m-to-grow-black-latinx-women-owned-sb

The firm has received numerous applications from interested businesses requesting to receive aid as a recipient of this initiative. You were recently hired as a Business Analyst and assigned to a team that is orchestrating the implementation of this project. They need your assistance in retaining all of the information they have received from companies and would like for a data expert to translate these insights for them.


## Job Description
JP Morgan Chase & Co. is a leading American multinational investment bank within the financial services industry. As a Business Analyst employed by this company, some duties include having the knowledge or ability to:

- Improve software products and applications designed for use in the financial services industry through applying, utilizing, and constructing business and logical data models and modeling methods. 

- Conduct interviews, analyze, evaluate, and deduct market, functional, and technical requirements for various financial industry-based IT items.

- Design processes for data extraction, database templates, and feeds.

__*Some required skills include*__ - 
minimum one year experience relating to the following: "designing database models... collating data from various data sources such as data warehouses; analyzing data and summarizing findings; data modeling, analytics, and reporting; SQL using various tools... PL/SQL data processes; scripting automation solutions; systems and coding languages such as HTML5, CSS, XML, JavaScript, Java, or Python; responsive web and mobile application design..."

*For more information regarding the responsibilities that come with this role, visit here:* https://www.simplyhired.com/job/qIoitav8SXPZ9fZwioGoXVUNoijiJDgsGsPg5Z0LoQ0xDqUNsZTGiw

The SQL Individual Portfolio project relates to the Business Analyst position through the skills exhibited to execute the project including, but not limited to: data collection, data visualization, and natural language processing. Furthermore, it exemplifies these valuable skills sought by JPMC recruiters, such as webscraping, data analysis, and modeling insights through the use of SQL.


## Data
__*Source:*__ Webscraping from the corresponding website: https://ppp.pubb.org/ca/ , in addition to, creating and generating fake data for project purposes.

__*Characteristics:*__ The webscrape is data relating to loan information of small to medium-sized businesses in California that received a loan under the Payment Protection Program (PPP). The source only provides businesses that were approved for a loan greater than $150,000. Businesses approved for a loan less than $150,000 or received a loan and returned it are excluded from the data extracted from the source. For project purposes, one of the components are to assume that Chase Bank is the lender of these loans. It is assumed that a business can only apply for either a loan or a grant within a given period, not both.


## Notebooks
- link to data_collection: https://github.com/audreyh614/Aspiring-Small-Businesses/blob/77acc5e805fa77ea59db6a7f633b39f633f24447/data_collection.ipynb
    - This notebook is a webscrape of California businesses that have been approved for a loan under the Payment Protection Program. All information scraped goes into a database with the following network:
<img width="547" alt="image" src="https://user-images.githubusercontent.com/58491971/117247543-4a4ab400-adf3-11eb-9498-f691aff76d18.png">



- link to sql_analysis: https://github.com/audreyh614/Aspiring-Small-Businesses/blob/71426038b57488e7c5e8a10154eb75e5a2e2457f/sql_analysis.ipynb
    - description of the notebook's purpose
- link to presentation: description of the notebook's purpose


## Future Improvements
If I had more time two improvements I would make are:
1) __*Find a way to webscrape additional information on businesses returned from the web scrape through a deeper scrape:*__
    - It would have been nice to scrape specific details relating to each company such as the business type and whether it was a nonprofit which are two attributes I seen, but were deeper within the link of each company and not available on the overall page. I also highly doubt those California businesses which were approved for those loans are actually B.I.P.O.C owned businesses, so I wish it were true. 

2) __*Try to improve or expand my search for public information relating to funding (loan/grant datasets):*__
    - I had difficulty finding free public datasets and APIs that contained loan information for small businesses, which is why I extracted general content from the source of my webscrape.
