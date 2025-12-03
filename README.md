#### FINANCIAL ANALYSIS FOR EUROPEAN STOCKS- STOXX600
This project focuses on analysing the financial performance of companies listed in the STOXX 600 index, which represents major publicly traded firms across Europe.
The objective was to collect, clean, and organise the financial statement data of these companies and convert it into a structured dataset that can be used for analysis.

I began by importing multiple raw datasets containing company identifiers, financial items, and industry classifications. Since the data comes in different formats and not every company reports the same items, a large part of the project involves data cleaning, standardisation, and merging. This includes fixing company names, reshaping the financial data into a usable format, and aligning it with metadata such as country and industry. Later, conducted sanity checks on a few randomly choosed companies for confirming the accuracy of the data.
 
After preparing the dataset, I computed key financial ratios—such as profitability, leverage, liquidity, and efficiency metrics. These ratios enabled to compare companies, industries, and countries across the years 2021, 2022, and 2023.

Finally, using the cleaned dataset and computed ratios, I explored patterns in the STOXX 600 by generating tables and visualisations.
This helps provide an organised overview of which firms and sectors perform well, how companies differ across countries, and how financial characteristics evolve over time.

##### DATASET

The data is taken from Datastream/ LSEG and was a part of an academic project. 

**OVERVIEW**
* It includes Large exchange-listed European firms (STOXX Europe 600 index)
* Annual data for 2021, 2022, 2023
* Index constituents are as of 2021.
* Data are reported for 2021, 2022, and 2023.
* There are three firm identifiers: firm name, ISIN (international securities identification number), and CUSIP
* Industry codes per firm https://www.sec.gov/search-filings/standard-industrial-classification-sic-code-list
