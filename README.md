#Pflege Data

----------
An overview of data for nursing homes in Germany. 
----------
## Table of Contents
- [Process](#process)
- [Geodata](#geodata)
- [States](#states)
----------
#### Process <a name="process"></a>

- How did we get the data?
	- FOIA (XLS)
	- Scraping (XML)

----------
#### Geodata <a name="geodata"></a>

----------
#### States <a name="states"></a>

This file contains all the state data we have on nursing homes in Germany. In the [`raw`](https://github.com/correctiv/pflege-notebook/tree/master/states/raw) folder, you will find the raw XLS files that we received for each state. We then combined these XLS files and cleaned them up to have a similar data structure. We used a combination of pandas and Excel to clean and format the data into csvs. The resulting csvs from each python notebook can be found in the folder labeled [`csvs`](https://github.com/correctiv/pflege-notebook/tree/master/states/csvs).  You can also find the python notebook for the full analysis of the nursing home data [here](https://github.com/correctiv/pflege-notebook/blob/master/nursinghomes.ipynb)

