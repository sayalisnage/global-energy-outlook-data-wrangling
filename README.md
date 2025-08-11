### Global Energy Consumption and Generation: DATA WRANGLING


This project focuses on analyzing global energy consumption and generation patterns to understand how energy usage is changing over time. The goal is to build on data wrangling skills, from sourcing and cleaning data to merging and visualizing it, to draw meaningful conclusions about global energy sustainability. This project serves as a comprehensive demonstration of a data science workflow.

---

## Project Overview

Energy consumption and maximum demand forecasting are crucial for enhancing energy efficiency and planning reliable power systems. This project focuses on studying the consumption and generation patterns of various energy sources worldwide, aiming to build a robust model that predicts future electricity demand and identifies the variables responsible for ever-increasing energy consumption. By analyzing these patterns and forecasting future demand, the project contributes to energy sustainability and cost reduction.

---

## Data Sources

The project uses a combination of data from multiple sources to create a rich, interconnected dataset:

* **Flat File (CSV):** "Access to Electricity Vs. GDP per Capita per Country" from `ourworldindata.org`.
* **Website:** "Global Electricity Generation and Energy data per Country" from `en.wikipedia.org` (data was scraped from a table).
* **API:** World demographic data from `census.gov`.

The data from these sources are linked using a common key, `Country/country code`, to establish a relationship between the disparate datasets.

---

## Methodology

The project follows a comprehensive data wrangling and analysis pipeline, structured into five milestones:

* **Milestone 1: Data Identification & Relationship Definition**
    * Identified and selected three datasets of different types (CSV, website, and API) with a minimum of 1000 rows and 30 columns in total.
    * Established a clear relationship between the datasets using `Country/country code` as the connecting variable.
* **Milestone 2: Flat File Data Cleaning**
    * Performed at least five data transformation and cleansing steps on the flat file data. This included replacing headers, formatting data, and handling missing or inconsistent values to ensure a clean dataset.
* **Milestone 3: Website Data Cleaning**
    * Scraped data from a Wikipedia table and applied at least five data transformation and cleansing steps. This involved identifying and fixing duplicates, correcting inconsistent values, and handling bad data.
* **Milestone 4: API Data Cleaning**
    * Connected to a public API and retrieved data. At least five data transformation and cleansing steps were performed, focusing on reformatting the data and identifying outliers.
* **Milestone 5: Data Merging and Visualization**
    * The three cleaned datasets were loaded into a database (e.g., SQLite) as individual tables.
    * The tables were then joined together into a single, consolidated dataset.
    * Five visualizations were created using Python libraries to demonstrate the data, with at least two visualizations spanning across multiple data sources.

---

## Ethical Considerations

This project addresses ethical considerations throughout the data wrangling process. The ethical implications of data wrangling, such as ensuring data privacy and avoiding bias, were carefully considered for each data source. For example, during data cleaning, care was taken to ensure that no personally identifiable information was used. The project also acknowledges that the final analysis should be used to promote equitable and sustainable energy solutions.

---

## Technology Stack

* **Programming Language:** Python
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `os`, `re`, `datetime`, `BeautifulSoup` (for web scraping)
* **Tools:** Jupyter Notebook, SQL (for database management)

---

## Contact

For questions or collaboration, please reach out via [E-mail](mailto:sayalinage@gmail.com) or connect on [LinkedIn](https://www.linkedin.com/in/sayali-nage-34303b136/).
