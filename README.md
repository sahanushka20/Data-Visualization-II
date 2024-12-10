# Data Visualisation Assignment-II

This repository contains solutions for various problems related to data science, machine learning, geospatial analysis, web scraping, and web services. Each task is demonstrated with Python code using libraries such as `yfinance`, `Bokeh`, `seaborn`, `requests`, and more. Below are the descriptions of each problem and the approach taken to solve it.

## Table of Contents
1. Kernel Density Estimation (KDE)
2. Bivariate Distribution Using Apple Stocks Dataset
3. Geospatial Data Visualization with Bokeh
4. Network Visualization Using Geospatial Data
5. Web Scraping and Networked Programming
6. Working with Web Services (XML)

---

### 1. **Kernel Density Estimation (KDE)**
- **Objective**: This task demonstrates the concept of **Kernel Density Estimation (KDE)** applied to a dataset. KDE is a method for estimating the probability density function of a continuous random variable.
- **Approach**: The code uses a sample dataset to perform KDE and visualize the probability distribution. The KDE method provides a smoother alternative to histograms for understanding the distribution of data points.
- **Libraries Used**: `seaborn`, `matplotlib`, `numpy`

---

### 2. **Bivariate Distribution Using Apple Stocks Dataset**
- **Objective**: In this task, we analyze **Apple’s stock data** to visualize the relationship between two variables: **daily returns** and **trading volume**.
- **Approach**: The code fetches Apple stock data from Yahoo Finance using the `yfinance` library. It calculates the daily returns based on adjusted closing prices and then uses a bivariate Kernel Density Estimation (KDE) plot to visualize how trading volume correlates with daily returns.
- **Libraries Used**: `yfinance`, `seaborn`, `matplotlib`

---

### 3. **Geospatial Data Visualization with Bokeh**
- **Objective**: This task demonstrates how to visualize **geospatial data** interactively using the **Bokeh** library.
- **Approach**: The code creates a scatter plot of geospatial locations (e.g., cities with their respective latitude and longitude) and adds interactivity such as pan, zoom, and tooltips that show additional information (e.g., city names and coordinates) when hovering over the points. This makes the visualization more engaging and informative.
- **Libraries Used**: `Bokeh`, `ColumnDataSource`

---

### 4. **Network Visualization Using Geospatial Data**
- **Objective**: This task creates a **network plot** representing the interconnections between various geospatial locations (cities).
- **Approach**: The code visualizes the connections (edges) between cities as a network, where each city is represented as a node with latitude and longitude coordinates. The network graph helps to visualize the relationships between different locations. The visualization is done using **networkx** for graph creation and **matplotlib** for plotting.
- **Libraries Used**: `networkx`, `matplotlib`

---

### 5. **Web Scraping and Networked Programming**
- **Objective**: The goal of this task is to demonstrate how to **scrape web data** and download **images over HTTP** using Python.
- **Approach**: The code fetches an HTML page using the `requests` library, parses it using `BeautifulSoup`, and then extracts the URL of an image from the page. The image is then downloaded and saved locally. This task showcases basic **web scraping** and how to retrieve data over the internet.
- **Libraries Used**: `requests`, `BeautifulSoup4`

---

### 6. **Working with Web Services (XML)**
- **Objective**: This task demonstrates how to retrieve and parse **XML data** from a web service.
- **Approach**: The code sends a request to a web service that returns data in XML format. It then uses `xml.etree.ElementTree` to parse the XML and extract relevant information, such as titles and links from a list of items. This task helps in understanding how to interact with web APIs that return XML data.
- **Libraries Used**: `requests`, `xml.etree.ElementTree`

---

## **Requirements**
To run the code for these tasks, you will need to install the following Python libraries:

- `yfinance`
- `seaborn`
- `matplotlib`
- `bokeh`
- `requests`
- `beautifulsoup4`

You can install them using `pip`:

```bash
pip install yfinance seaborn matplotlib bokeh requests beautifulsoup4
