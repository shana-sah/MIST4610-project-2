Group 1:

Shana Sah (https://github.com/shana-sah/SQL-Project-1-)

Maya Patel (https://github.com/mayapatel47488/SQL-Project-1-)

Sofia Slavov (https://github.com/sophiaslavovv/SQL-PROJ-1)

Cade Mayfield (https://github.com/CaMay999/sql-project-1-)

Chris Vitucci (https://github.com/chrisvitucci/SQL-Project-1)

------------------------------------------------------------------------------------------------------------
Data Set Description:
---------------------------

This dataset reports the details for school-related arrests for public schools in all states from 2015 to 2016. The dimensions of the data set contains 24 columns and 58 rows. The data is separated in different categories. Data is derived from each state, showing the total number of students, number of schools,Race/Ethnicity of students without and with disabilities served under IDEA1,students  with disabilities served under IDEA,students with disabilities served only under section 504,English language learners, and percent of schools reporting. The column for States is a string type data set. The number of schools and total students are all integers.The percent of schools reporting are calculated and shown by percent alone.Race/Ethnicity of students without and with disabilities served under IDEA1,students with disabilities served under IDEA,students with disabilities served only under section 504 and English language learners are displayed with integers and percents.This data set provides us with a large amount of information to thoroughly organize and build detailed visualizations.

------------------------------------------------------------------------------------------------------------

Question 1: Among the English Language Learners, what is the relationship between English proficiency levels and the likelihood of receiving a school-related arrest?

Why is it interesting: 

Understanding the relationship between English proficiency levels and the likelihood of receiving a school-related arrest can further help inform educators or the public about potential disciplinary disparities between English Language Learners and their English proficient peers. Since ELL students often come from culturally diverse backgrounds, examining how English proficiency levels relate to disciplinary actions may alleviate challenges faced by these students, if a correlation that negatively affects ELL students exists. The findings of this analysis can inform the development of practices that positively impact or benefit students.
There were 3,142 English Language Learners out of the 51,780 student arrests in 2015-2016. There is a large range in percentage of English learners, as arrests per state varies from 0% English learners to 50%. What is the difference in ratios between states, and what is causing this wide variety? Texas has the highest number of arrests for English learners with 946, which makes up 12.3% of their school-related arrests.
























------------------------------------------------------------------------------------------------------------

Question 2: Why do Georgia and Ohio, states with incredibly similar size, have such drastic differences in school-related incarcerations rates  between 2015 and 2016?

Why is it interesting: 

According to the gov catalog, Georgia had 3,424 public school arrests, as compared to Ohio, with only 767. What is so weird about this is that Georgia and Ohio are neck and neck for population size, with Ohio even slightly surpassing Georgia in terms of citizens. Despite this, Georgia skyrockets above Ohio in arrests. The real question is why? We believe it has to do with the school funding that happens in each respected state.

Ohio state funding differs based on local districts, like the Salon school district receiving $2362 dollars per student whereas Cleveland receives $9332 per student. This means that districts in Ohio with “more economically disadvantaged students” tend to receive more state funds.  On the flipside, Georgia is one of only eight states in the U.S. that does not provide additional funding specifically to educate students living in poverty. Instead, the state of Georgia provides more funding for students who struggle academically, based on standardized test results. 

In the dataset, Ohio contained more arrest-related data from each respective school than Georgia. 

















------------------------------------------------------------------------------------------------------------
Data Manipulation:
-------------------
There were a few things we had to manipulate in the data to give us the right outcomes. In order to calculate the most accurate pieces of information, we took out percentages when gathering all the data. Another manipulation we made was that we removed columns that didnt pertain to our phenomenon. We primarily focused on English Language learners and the correlation between English proficiency levels and the probability of being subject to a school-related arrest, and two states with a similar population size having differences in school related incarcerations. We focused on standardizing all the data, so that it would be used in the most efficient way to analyze it. All the data we chose is quantifiable and interpretable with no redundancy. Having any inaccuracies could alter our analysis and lead to false observations. Our data entries consistent with the information from the data analysis.


------------------------------------------------------------------------------------------------------------
Tableau Packaged Workbook
--------------------------

The packaged workbook with the displayed visualizations is included in this repository.










