# Intro-Data-Science-Final-Project
The final group project for an intro to data science class focusing on how gun legislation correlated with school shootings. Based on recent events, we were really motivated to studying school shootings and see if gun legislations has an affect on the amount of school shootings, and we wanted to see if we could predict the locations of school shootings.

First we took 3 data sets:

1) Data on K-12 School Shootings 1970-2020 from Center of Homeland Defense and Security (Biggest Data Set)
2) Dataset of Gun-Related Legislation Per Year Per State 1991-2017
3) Combined One Dataset with Data from US Census API to get a DataFrame of US Population by State 1990-2018

Then we conducted data exploration to make visualizations that show trends in the data. In particular, we looked at the trends over time in the US and in states with the most school shootings per million people, and the trends of number of gun related laws over time in the US and in the states with the most gun-related legislation. Finally we compared the number of gun-related laws to the number of shootings (per mil people) in the US and the top three states with most shootings to see if there was any correlation.

Finally, we created a machine learning model that predicted the location (Parking Lot, Classroom, Beside Building) based on State, School Level, Time Period, During School, Targets, Situation, Bullied, Preplanned, and Weapon Type.

Our model has 71.5% accuracy and the following precision and recall statistics: 

Parking Lot: 		Precision: 79% 			Recall: 69.5%
Classroom: 		  Precision: 74% 			Recall: 81%
Beside Building: 	Precision: 58.5% 		Recall: 65.5%
