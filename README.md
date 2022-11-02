# Historic word occurrence in academic papers & Plot the graph

## Summary

This script extracts the historic word occurrence of a search term in academic papers (from Google Scholar) and plot a graph. 
It allows for spotting trends in research and analyzing the relevance of a topic over time.


## Usage

`python extract_occurrences.py "<keyword>" <start date> <end date>`

This command lists the number of publications for every year using this keyword.
The script just searches for articles and excludes patents and citations.
A graph is created (with Maplotlib) and saved at the end of the workflow.


## Example

- Search term: "digital pathology"
- Desired time span: 1970 to 2022
- Command: `python extract_occurrences.py "digital pathology" 1970 2022`
- Output: `digital pathology.csv`

![graph]()

## Credits
Created by Volker Strobel - volker.strobel87@gmail.com

If you use this code in academic papers, please cite this repository via Zenodo (http://doi.org/10.5281/zenodo.1218409):

Volker Strobel. (2018, April 14). Pold87/academic-keyword-occurrence: First release (Version v1.0.0). Zenodo. http://doi.org/10.5281/zenodo.1218409

Graph plot by Robin HCK - robin.heckenauer@uha.fr
