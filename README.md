# Python WebScraping
Used beautiful soup to scrap the scrap data from Wikipedia page - List of companies of Hong Kong. Pandas is used for dataframe and matplotlib is used for creation of analytics chart

# Author
Kiki Cho

# Motivation
it is a homework, and I find it useful to train up both my python skills and webscrapping mindset


# Objective
To scrap the data about companies in Hong Kong and answer the company trends in Hong Kong

# Specification
```mermaid
flowchart TD
    install_dependencies---->download_HTML_document ----> extract_components ----> put_components_into_dataframe
    put_components_into_dataframe ----> data_cleansing ----> data_analysis_1 & data_analysis_2 & data_analysis_3 & data_analysis_4 ----> plot_graph
```