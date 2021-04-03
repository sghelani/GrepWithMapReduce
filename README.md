# GrepWithMapReduce

## Description

* A simplified version of the Grep functionality was implemented using Python.
* It allows for searching a target string in all the files in a particular folder using a custom map-reduce framework.
* The files used in this project were wikepedia pages scraped from the web in HTML format.
* The files are split into chunks and analyzed parallelly by different processes.
* The results are subsequently combined and written to a CSV file.
* The output CSV file contains the following 4 columns:
  * File: Wikepedia file name containing the target string
  * Line: Line number in this file containing the target string
  * Index: Start index of the line containing the target string
  * Context: A few characters around the target string to indicate, in which context was the string used

## Artifacts

* GrepWithMapReduce.ipynb:
This jupyter notebook contains the code for the above functionality.

* WebScraping.py:
This python files scrapes the wikipedia pages from the web and stores them in the Data folder

* Data:
This folder contains the input fules that is processed by the jupyter notebook and the output files created after the search.

