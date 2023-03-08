# Related-Party-Scraping
Downloads and analyzes public filings in search of "related party" mentions.
Across finance, fraud often comes with some level of self-dealing; Enron's Andrew Fastow and WeWork's Adam Neumann represent a couple of these instances. These relationshipt are not always made publicly available, however when placed in financial filings are often seen under headings reading "Related Parties".
This script seeks to raise flags for instances of self-dealing by counting the number of paragraphs containing the phrase "related party" throughout a company's most recent quarterly report. The program can be used on any type of filing for any number of companies.
The current output represents the top 10 outputs across an analysis of all companies within the S&P 500.
