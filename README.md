EDA Analysis Beer and Breweries Budweiser
================
Carlos Estevez
2023-03-03

## Introduction

In this EDA(Exploratory Data Analysis) we will conduct an analysis of beers sold across the United States. In addition, we will show deep analysis across different beer names, styles, and companies to shed more light into some of the weakness and advantages of certain business strategies.

This analysis will be presented to the Budweiser corporation. We will analyze and investigate data sets and summarize their main characteristics, often employing data visualization methods to be more compressive.  Our main goal will be to recognize the areas where the company can focus aiming to strengthen its position in the market and ultimately translate these benefits to the final customer.

## Content of the project

* Datasets: Beers.csv, Breweries.csv and States.csv
* Codebook: codebook.csv
* Markdown file: EDA_Beers_Breweries_USA.RMD
* CSS format: bootstrap.csv(Part of the Markdown)
* Presentation: Presentation_Beers_Breweries_USA.ppt



## Steps to run the analysis(RMD file)

### Install the following libraries
* tidyverse
* stringr
* caret
* plotly
* ggthemes
* GGally
* class
* e1071
* maps
* usmap

### Dowload the CSV source file and update local path

* Files: beers.csv and breweries.csv
* Update local path: Go to the section "ReadingSourceFiles"
in the RMD file and replace the path of the working directory
by your local path in your PC

## Usage

You need to execute each chunk one by one in sequence. It is important
because there are many part of the code that depends on previous Chunks

The project has the folowing Chunks:

* <strong>Libraries</strong>: Loading the libraries. After installing the needed libraries listed previously ,
  you must run this chunk in order to load the libraries
  
* <strong>ReadingSourceFiles</strong>: Loading data from CSV file(set the working directory)

* <strong>DataCleanandModel</strong>: In this chunk, we perform two activities.
  + Data Cleaning: Replacing missing values of the variables ABV and IBU from the
beers data set. We also create many plots to explain results after the missing values
are replaced.
  + Set global variables: We set the global variables of the project. You can go
to the codebook to get a description of each one

* <strong>SummarizingbyState</strong>: We present the number of breweries by state
* <strong>TopFiveBewUsa</strong>: We present the number of IPA beers by state
* <strong>Median_Beer_Brewer</strong>: We present the median ABV and IBU by state
* <strong>TopStateABVIBU</strong>: We present the top states with high levels of ABV and IBU
* <strong>SummaryStatsABV</strong>: We present the analysis of the distribution of the variable ABV
* <strong>RelationShipIBUABV</strong>: We explain the relationship between IBU and ABV
* <strong>DifferenceIPAPALE</strong>: We explain the difference between an IPA and PALE beer using KNN
* <strong>AdditionalInformationEDA</strong>: We present two important analysis that can be very strategic for Budweiser


## Notes about Data Cleansing

In this section, we will perform data cleansing. Data Cleaning is one of the important steps in EDA. Data cleaning can be done in many ways. One of them is handling missing values
We will implement different methods for IBU and ABV

* ABV: Replace missing values with the arithmetic mean
* IBU: Replace missing values using KnnImputation method


## Codebook

The codebook is a CSV file. You will find the most important variables
that we use in the analysis.



