#Pflege Data
---
An overview of data for 13,000 nursing homes in Germany 
---
Investigation can be found in German [here](https://correctiv.org/recherchen/pflege/wegweiser/) and in English [here.] (https://correctiv.org/en/investigations/nursing-homes/guide/) 

Methodology for the project is in [English](https://correctiv.org/en/investigations/nursing-homes/articles/2016/06/09/nursing-homes-what-we-know-what-we-do-not-know/) and in [German.] (https://correctiv.org/recherchen/pflege/artikel/2016/06/02/was-wir-wissen-was-wir-nicht-wissen/)

---
## * What is in this repo*

[`states`](https://github.com/correctiv/pflege-notebook/tree/master/states): This file contains all the state data we have on nursing homes from each state's statistical office. In the [`raw`](https://github.com/correctiv/pflege-notebook/tree/master/states/raw) folder, you will find the raw XLS files that we received for each state. We then combined these XLS files and cleaned them up to have a similar data structure. We used a combination of Pandas, R and Excel to clean and format the data into csvs. The resulting csvs from each python notebook can be found in the folder labeled [`csvs`](https://github.com/correctiv/pflege-notebook/tree/master/states/csvs).  You can also find the python notebook for the full analysis of the nursing home data [here.](https://github.com/correctiv/pflege-notebook/blob/master/nursinghomes.ipynb)

[`geodata`](https://github.com/correctiv/pflege-notebook/tree/master/geodata): This folder contains the geojson data we used to map the nursing homes. 

[`datadictionaryforanalysis`](https://github.com/correctiv/pflege-notebook/tree/master/datadictionaryforanalysis): This file contains the excel file shared with our media partners, as well as a data dictionary for the data. 

The data is as follows:

|English header | German meaning|
|---------------|---------------|
|`total_personnel`| Personal insgesamt|
|`fully_employed`| Vollzeitbeschäftigt|
|`part-time`| Teilzeitbeschäftigt|
|`nursing_and_care`| Pflege und Betreuung|
|`social_care`| soziale Betreuung|
|`other_care`| zusätzliche Betreuung (§ 87b SGB XI)|
|`costs_nursing_class_1`| Pflegeklasse 1|
|`costs_nursing_class_2`| Pflegeklasse 2|
|`costs_nursing_class_3`| Pflegeklasse 3|
|`food`|    Verpflegung|
|`1-bed` | 1-Bett-Zimmern|
|`2-bed`| 2-Bett-Zimmern|
|`3-bed`|  3-Bett-Zimmern|
|`4-bed`| 4 und mehr-Bett-Zimmern|
|`recipients_nursing_class_1`| Pflegestufe I|
|`recipients_nursing_class_2`| Pflegestufe II|
|`recipients_nursing_class_3`| Pflegestufe III|
|`recipients_nursing_class_unknown`| Pflegestufe zugeordnet|
|`trainee`| Auszubildende/-r, (Um-)Schüler/-in|
|`state_certified`| staatlich anerkannte/-r Altenpfleger/-in|
|`nurse`| Gesundheits- und Krankenpfleger/-in|
|`nurse_children`| Gesundheits- und Kinderkrankenpfleger/-in|

