# Flipkart_Web_Scrape
Scrape 5g smartphone details from Flipkart

<div align="center">
  <a href="">
    <img src="images/powerbi.PNG" alt="Logo">
  </a>
</div>

## About The Project

Web scraping is an automatic method to obtain large amounts of data from websites. Most of this data is unstructured data in an HTML format which is then converted into structured data in a spreadsheet or a database so that it can be used in various applications.

In this project we scraped 30 pages from Flipkart related to 5g smartphones in 2023. And then we cleand the data and did some analysis on various features of the dataset.

### Dependencies
* BeautifulSoup
  ```python
  pip install bs4
  ```
* Plotly
  ```python
  pip install plotly
  ```

## Getting Started

### Using the Datasets
  To use Raw Data scraped from Flipkart use the following dataset
  ```python
  df = pd.read_json("5gPhones.json")
  ```
  Sample of Raw Data :
  [![Raw Data][images/raw_data.PNG]]
  
  To use Cleaned Data read the following Dataset
  ```python
  df = pd.read_csv("5gPhones.csv") 
  ```
  Sample of Cleaned Data :
  [![Cleaned Data][images/cleaned_data.PNG]
