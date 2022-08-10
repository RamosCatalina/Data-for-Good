# Data-for-Good
#Introduction

This project is one of the research initiatives by the Rights CoLab and the Columbia Data Science Institute. This research collaboration aims to define a set of standards through the Sustainability Accounting Standards Board (SASB) that investors can use to persuade companies to improve labor rights for both their workforce and workers in supply chains. I joined the team as a student volunteer/ DSI scholar under the mentorship of Rights CoLab co-founders Joanne Bauer and Paul Rissman.

I used Google Big Query to access a sample of International financial filings that showed the most promise as a new data source to be incorporated into the research for this semester and had enough labor- and DEI-related content. I worked with 50 PDFs from the executive and employees section of different business reports and 50 PDFs from the investor protection section. The text extraction process was broken down into two parts: extraction of text data not in tables and extraction of text in tables. I  built a working version of a program that can parse all the reports and extract all the tables from the PDFs, and saves them as CSV files. After extraction the data was formatted in Pandas DataFrames, and was later combined with the text dataset. Finally, Using frameworks previously built by other contributors, I parsed for practice & risk terms that were considered related to DEI matters using natural language processing techniques.

For more insight into the results of the research initiative, check out the following website: https://rightscolab.org/project-harnessing-big-data/

##Skills

Python
-Pandas
-NumPy
-Tabula 
-natural language processing
