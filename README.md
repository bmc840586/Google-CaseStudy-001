# Google-CaseStudy-001
<a href="https://github.com/bmc840586/Google-CaseStudy-001/blob/main/final%20repot.pdf">Final Report</a><br/>
This is all the finished worked of the case study of Google Data Analytics course from Coursera, "Case Study 1: How does a bike-share navigate speedy success?"

- prepare	
	- download and extract all the 12 files, from oct-2026 to nov-2025 by using given link
	- open new excel file and import the first file
	- created a local repository and commit the files using git
	- all data organize in same way in a table easy to read and analyze
	- all data looks fine but around 32% row has missing data
- process
	- remove duplicate data and delete all rows with missing data
	- calculated, its about 30% - 35% data with missing cells were deleted  (there are plenty of data so i wouldn't bother to remove missing data as most of them from starting, end locations and station ids)
	- add a new column to calculate the duration by [end date and time - start date and time] (need to do this before splitting it into two for data and time, if not only times used, sometimes you get error for negative values, this happens when it duration within two days) 
	- split the date and time to separate cells
	- add a new column to put day of the week (use this =TEXT(A1,"dddd"), if use 'WEEKDAY' function, when you need to copy and paste values for strings as "Monday", you get a date value)
	- sort every related to date, took wee while
	- change formatting to number with 4 decimal points in all map positions
	- guess that's all for prep now repeat the process for other files
	- once finished made another commit on git
- analyst
	- evaluate the data integrity as percentage of deleted missing data
	- counted total trips, by bike types, member type and average the trip durations
	- counted total, bike type, member type related to the days of the week
	- calculated averages of trip durations for total, bike type, member type related to the days of the week
	- in addition, counted member types using which bike types
	- created a pivot table in new sheet, row for start location, count columns for days of week
	- open a new excel file and add all new finding into it
	- and created line charts better visualization 
- share/act
	- create a final repot file adding all the finding, pattens and insights,
and add graphs for visualization, and add recommendation for conclusion (used google Gemini to get bit of help for creating final report)

