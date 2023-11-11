# pandas-challenge

Before beginning this challenge we were asked to create a repo with a folder called PyCity Schools. Using the PyCitySchools_starter.ipynb file we were asked to run analysis for district summary, school summary, highest-performing schools by overall passing percent, lowest-performing schools by overall passing percent, math scores by grade, reading schools by grade, scores by school spending, schores by school size, and schores by school type. 

For the district summary analysis, I found that there were a total of 39,170 students that make up the population of 15 different schools. The average math school for students was 78.98, the average reading score for students was 81.87, and the 65.17% of students passed both math and reading with a score of at least 70. 

For the school summary analysis, I created a new varaible that grouped the complete school data by unique school names, and found that Bailey High School had the greatest number of students, 4976, whereas Holden High School had the least number of students, 427. Pena High School had the highest average math and reading scores of 83.83% and 84.04%, respectively. Huang High School had the lowest average math score of 76.62% and Ford High School had the lowest average reading test score of 80.74%. Pena High School had the greatest percent of students passing math tests with a score of at least 70, whereas Thomas High School had the greatest percent of students passing reading tests with a score of at least 70.

Cabrera High School had the greatest overall passing rate with 91.33% of students passing both math and reading tests with a score of at least 70. Rodriguez High School had the lowest overall passing rate with 52.98% of students passing both math and reading tests with a score fo at least 70. 

Comparing the overall passing rates and spending ranges per student, it is interesting to see that Cabrera High School spends less than $585 per student, where as Rodriguez High School spends between $630-645 per student. In general there appears to be a negative trend between average spending ranges and overall passing rates. Schools that spend the most per student appear to have lower overall passing rates, and schools that spend less per student appear to have higher overall passing rates. 

Compaing the passing rates of students to school size, it appears that larger schools have the lowest percent of test scores in all categories: average math scores, average reading scores, percent of students passing math, percent of students passing reading, and percent of students passing overall. Small and medium size schools have similar passing rates in all perviously listed categories. 

Comparing school types, it appears that charter schools have a greater overall passing rate of students, 90.43%, whereas district schools have a much lower overall passing rate of students, 53.67%. Students that attend a charter school are more likely to pass math exams than students that attend a district school. 

Through the use of the start code, Stack Overflow, and the help of some of my peers I was able to find the code for grouping multiple variables ".groupby(["school_name"])["reading_score"].count()" and dataframe formating ".map("${:,.2f}".format)".
