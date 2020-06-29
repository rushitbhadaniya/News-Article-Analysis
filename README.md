# News-Article-Analysis
News Article Analysis is a Python Script for Clustering news feeds using different Machine Learning algorithms.

## Requirements
Install jupyter notebook(or Anaconda 3)If you don’t already have them. Get News API key from https://newsapi.org/register if you don't already have. This API key is for downloading current News Feeds.

## Usage
Download the News Clustering.ipynb file. Do changes in file paths according to your location of data Stored. Download latest news feeds to do analysis on cuurent news, or else use data from https://github.com/rushitbhadaniya/News-Article-Analysis/blob/master/Data/everything.json.   

## Data
Data is collected from Google News API. Data is directly downloaded in json format. This is not the ideal way to collect data. We can use Apache Kafka to handle streaming data,but here we are only focused on doing analysis on downloaded data. 

## Methodology
<img src="https://github.com/rushitbhadaniya/News-Article-Analysis/blob/master/Methodology/WorkFlow.jpg">

## Results 

### K-Means
<img src="https://github.com/rushitbhadaniya/News-Article-Analysis/blob/master/Output/KMeans.JPG">

### DBScan
<img src="https://github.com/rushitbhadaniya/News-Article-Analysis/blob/master/Output/DBScan.JPG">
