# School District Analysis with Jupyter Notebook (Python)
### An analysis of standardized testing scores to optimize school budgeting and planning

## Overview
This analysis of standardized test score data provides insights into performance trends and patterns based on school funding per student, size, and type. These conclusions will influence strategic decisions at the school and district level. The school board will take the results into account when making decisions about budget allotments and priorities. This final analysis addresses evidence of academic dishonesty at Thomas High School by nullifying the grades from their 9th graders and identifying the corresponding changes in results.

## Results
After converting the scores from the 9th graders at Thomas High School to null values, the results changed in the following ways:
-	The district summary scores slightly decreased, with the overall average math score only being knocked down from 79.0 to a grade of 78.9. While the average reading score rounded to one decimal place did not decrease at all, the percent of students that passed math, reading, and both dipped 0.2%, 0.1%, and 0.3% respectively. Overall, omitting the 9th graders at Thomas High School did not have a major effect on the district summary.

<img width="924" alt="Screen Shot 2022-01-14 at 5 31 56 PM" src="https://user-images.githubusercontent.com/95303422/149593854-bfd891c4-be76-49cc-a527-057a737d5d04.png">
<img width="924" alt="Screen Shot 2022-01-14 at 5 32 09 PM" src="https://user-images.githubusercontent.com/95303422/149593864-eeca2ff0-bfaf-456f-98ef-e7ed8a7f7243.png">

-	The school summary was unaffected outside of the Thomas High School row. In this row, Thomas High School’s average math score barely decreased by about 0.07 while the average reading score rose by approximately 0.05. All the school’s percent passing columns were negatively affected, with the overall passing percentage of the students taking more than a 0.3% hit.

<img width="784" alt="Screen Shot 2022-01-14 at 5 34 28 PM" src="https://user-images.githubusercontent.com/95303422/149594014-f84ff046-299a-43ef-b6ea-42a7b256d341.png">
<img width="784" alt="Screen Shot 2022-01-14 at 5 35 24 PM" src="https://user-images.githubusercontent.com/95303422/149594082-9e8690e8-abb0-4e33-b911-6c61951678e9.png">

-	Despite a slight dip in performance metrics after nullifying the 9th graders’ scores, Thomas High School maintained their place as the second-best school in terms of overall passing percentage. If their overall passing percentage had dipped 0.42% rather than 0.32%, they would have dropped to the fifth-best school.

<img width="788" alt="Screen Shot 2022-01-14 at 5 36 53 PM" src="https://user-images.githubusercontent.com/95303422/149594225-6e1dd999-c983-4dde-9f3c-53a6bd0995bb.png">

-	The only effect on the math and reading scores by grade is that the 9th grader values for Thomas High School are now null.

<img width="300" alt="Screen Shot 2022-01-14 at 5 38 13 PM" src="https://user-images.githubusercontent.com/95303422/149594335-e5aa210e-7bd8-42ce-9165-5ab3de304532.png">

-	Since the values in the scores by school spending data frame are either rounded to the nearest whole number or just one decimal place, there is no visible change to this table.
-	Like the previous data frame, the scores by school size table did not change at all due to rounding.
-	Once again, the scores by school type data frame did not appear to change at all due to rounding.

## Summary
After addressing the evidence of academic dishonesty at Thomas High School, their performance metrics dipped slightly. This decrease only barely influenced the district-level summary. The percent of students district-wide that passed math, reading, and both dipped an average of 0.2%. In terms of the school-by-school summary, the most significant change was that Thomas High School’s overall passing percentage dropped nearly 0.32%. However, when compared to the other schools in the district, they still barely maintained their position as second-best by overall passing percentage behind Cabrera High School. With respect to the scores by grade, school spending, school size, and school type, nothing changed with the obvious exception of Thomas High School’s 9th grade scores being converted to null.
