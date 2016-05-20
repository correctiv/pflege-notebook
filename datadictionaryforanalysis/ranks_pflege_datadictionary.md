## Data Dictionary for `ranks_pflege_data.xlsx`
----
**Source**: Data comes from Statisches Landesamt for December 2013.
**Note**: This file contains the rankings for each county for the major data questions we asked.
----------
### Contents

*All files contain the same two beginning A and B columns (`Name` and `State`), where `name` means the name of the district or county and `state` is the state the county is found in.*

#### Sheets
* **More than 1 bed**
	- `Rank`: ranking of the total # beds that are in rooms with more than 1 beds in the county or district in descending order
	- `Total of >1bed`: total number of beds that are in rooms with more than 1 bed 
	- **About this data**: the rankings of the data show that `Berlin` has the highest number of beds overall at `11,896`. This shows that `Berlin` has a lot more older nursing homes than other places as they have a lot more rooms with more than 1 bed. 
* **Ratio of beds**
    - `Total of >1 beds`: total number of beds that are in rooms with more than 1 bed 
    -  `All beds`: total number of beds in the county or district 
    -  `Ratio of >1bed to allbeds`: `total of >1 beds`/ `all beds`; in other words, what percentage of beds are in rooms with more than 1 bed 
    -  `Rank`: rank of the `ratio of >1bed to allbeds`   
    -  **About this data**: this data is useful for seeing where are the places that have a high percentage of rooms with more than 1 bed, similar to the raw numbers. 
    - National average: 39 percent
* **Part-time vs staff**
	- `Part time`: total people working part-time
	- `Full time`: total people working full-time
	- `Total staff`: sum of the total people working full-time and those working part-time 
	- `Ratio of part time to all staff`: comparison of part-time/all staff to see how much of the staff is working part-time
	- `Rank`: rank of the `ratio of part time to all staff`
	- **About this data**: this data is useful for seeing how badly staffed some nursing homes are
	- National average: 61 percent part time vs all staff 
* **No education**
	- `No education`: total number of people that are `zusätzliche Betreuung (§ 87b SGB XI)` or are not educated 
	- `Total staff`: sum of all the people working in different levels: Pflege und Betreuung:(nursing_and_care)+ soziale Betreuung: (social_care)+ zusätzliche Betreuung (§ 87b SGB XI): (other_care)
	- `Ratio`: comparison of no education people over total staff 
	- `Rank`: rank of the ratio of no education people/total staff 
	- **About this data**: this data is useful to have to see how many people are working in nursing homes with no formal training 
	- National average: 5 percent or 69 people 
* **Overcrowding**
	- `Total beds`: total number of beds in all nursing homes in the county or district 
	- `Total patients`: total number of patients in each level of care (1,2,3 and unknown)
	- `Difference`: Difference between patients minus beds; if positive this means the number of patients that don't have beds; if negative, it shows the number of extra places or beds that the county or district has in comparison to patients
	- `Percentage of overcrowding or available beds over the total number of beds`: difference over the number of beds
	- `Rank`: rank of how overcrowded or how available the nursing home is; the lower the number, the more spots/beds are open (not crowded)
   	- **About this data**: this data shows what percent of beds that are avilable or what is overcrowded showing that some places don't have enough spaces to house their old people
	- National average: 161 open spaces  
* **Trainees**
	- `Trainee`: total number of trainees working at the nursing home
	- `Total staff(full, trainee, part-time)`: total staff here is the total of all full, part-time, and trainees 
	- `Ratio`: comparison of the total trainees in comparison to the total staff
	- `Rank`: rank of the ratio of trainees to total staff; the higher the number is, the less trainees (as a percentage of total staff) they have 
	-  National average is 12.37% 

#####Pivot tables
	- There are pivot tables in each sheet which show how many times does each state show up in the top 100. Next to the state, you will see the number of times it has appeared. If you click on the state, you will see the ranks and the county/districts that are in the top 100. Please see pivot-table.gif for an example of how to use this. 




