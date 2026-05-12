# About Me
My name is Jarod Coleman. I am a recent graduate finance student from UMKC. I am currently pursuing a Data Analytics professional certificate at Johnson County Community College with plans to combine it with my finance degree to work in the field of finance in the realmn of data analytics. I've worked in education for the past 8 years as a middle and high schoo Spanish teacher and a substitute teacher in KC Public Schools. I am currently looking to transition out of education
into finance.

# Blurb
This project uses the Data Analytics Life cycle to answer a relevant oceanic question. My question was, "What effect does salinity have on dissolved oxygen along the California coast." The dataset I used came from the website calcofi.com. It is a subsest of data collected by CalCofi stations along the California coast.
I used the pandas library to read the dataset. There were missing values so I cleaned it to handle the missing values. Because I was trying to predict a numeric
value, I chose to use a linear regression model. Before building the model I ran a correlation matrix and looked at the heat map to find the best correlations
to work with. The scatterplot confirmed visually what the heat map showed as far as the relationships between the different variables. There was a clear trend
between salinity and oxygen. The more salinity increased the more oxygen decreased so the relationship is negative. This relationship is in line with know facts 
about ocean water in that it gets saltier at deeper leves due to density and less mixing. This lowers the amount of oxygen available because it gets used up
by marine life who live at deeper levels. The model I ran didn't just use salinity. I used all of the remaining variables except for oxygen. This is a limitation
that with more time I would have explored differently. The data is also limited by just the California coast. With more time, I could have explored these relationships
in different regions or at different times of the year. 
I noticed a straigt line with oxygen that didn't look like it wasn't taking salinity into account. The line was completely straight so it looked like there 
was a default value of some sort. I would have investigated this more with mroe time. 
