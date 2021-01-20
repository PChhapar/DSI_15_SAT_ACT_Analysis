 ## Project 1: SAT & ACT Analysis

### Contents:

Problem Statement
Executive Summary
Data Dictionary
Conclusions and Recommendations

<b>Problem Statement</b>

The new format for the SAT was released in March 2016. With this new test format, what are the best ways in which College Board can improve the statewide participation rates for the SAT?


### Executive Summary

The datasets of SAT and ACT scores and participation rates from each state in the United States for 2017 and 2018 are given. A data analysis with outside research is needed to identify likely factors influencing participation rates in various states.



### Data Dictionary


|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|SAT/ACT|The State of the country, in this case The United States of America| 
|sat2017_participation|float|SAT|The participation rate of the high school graduates across the __*2016-17*__ school year in a particular State.|
|sat2017_erw|int|SAT|The Evidence-based Reading and Writing section *mean* score of a State.|
|sat2017_math|int|SAT|The Math section *mean* score of a State.|
|sat2017_total|int|SAT|The Total *mean* score from both sections of a State.|
|act2017_participation|float|ACT|The participation rate of the high school graduates across the __*2016-17*__ school year in a particular State.|
|act2017_english|float|ACT|The English section *mean* score of a State.|
|act2017_math|float|ACT|The Math section *mean* score of a State.|
act2017_reading|float|ACT|The Reading section *mean* score of a State.|
act2017_science|float|ACT|The Science section *mean* score of a State|
|act2017_composite|float|ACT|The Composite *mean* score is an average score based on the four ACT assessment test of a State.|
|sat2018_participation|float|SAT|The participation rate of the high school graduates across the __*2017-18*__ school year in a particular State.|
|sat2018_erw|int|SAT|The Evidence-based Reading and Writing section *mean* score of a State.|
|sat2018_math|int|SAT|The Math section *mean* score of a State.|
|sat2018_total|int|SAT|The Total *mean* score from both sections of a State.|
|act2018_participation|float|ACT|The participation rate of the high school graduates across the __*2017-18*__ school year in a particular State.|
|act2018_english|float|ACT|The English section *mean* score of a State.|
|act2018_math|float|ACT|The Math section *mean* score of a State.|
act2018_reading|float|ACT|The Reading section *mean* score of a State.|
act2018_science|float|ACT|The Science section *mean* score of a State|
|act2018_composite|float|ACT|The Composite *mean* score is an average score based on the four ACT assessment test of a State.|




## Conclusions and Recommendations
### states with interesting trends
<b>Interesting Observations for SAT:</b>

- The Colorado state 's SAT particpation rate in 2017 was 11% but in 2018, it increased to 100%, conversely it's ACT particpation rate dropped from 100% to 30%.
- Illinois's participation rate has a significant increase for SAT from (9%) in 2017 to (99%) in 2018
- In Florida, we notice a decline in the participation rate (-30%) for SAT test and (-10%) for the ACT test.

<b>Interesting Observations for ACT:</b>
- Alaska has the highest drop in ACT participation rate from 65% in 2017 to 33% in 2018


- We see some trends from the box plots - ACT participation rates are generally higher than those of SAT in both 2017 and 2018. The median ACT participation rates are 69% (in 2017) and 66% (in 2018), while the median SAT participation rates are only 38% (in 2017) and 52% (in 2018). However, this also shows that there is an increase in the median SAT participation rates from 2017 (38%) to 2018 (52%).

- We also see from these scatter plots that there is a negative correlation between average SAT and ACT participation rates for 2017 & 2018. In general, if states have a higher participation rate for SAT, they have a lower participation rate for ACT, and vice-versa.
- SAT and ACT participation rates have a strong negative correlation for both 2017 (-0.84) and 2018 (-0.87). This implies that students in each state on average take either the SAT or the ACT, and not both the tests. So, in order to increase the SAT participation rates, College Board will have to explore strategies to take over the ACT market share and make the SAT more appealing than the ACT to students, schools and colleges.


However, there are a few notable exceptions to this trend. There are a few states which had very low SAT participation rates in 2017, but they increased significantly in 2018. Colorado and Illinois are clear examples of this trend. On further research, we see that this is mainly because of the fact that College Board has 'expanded its market share through contracts with states and school systems that enable students to take the SAT free'.


Hence, based on the above seen trends, I have the following <b>recommendations for College Board</b>:
- Explore possibilities of expansion through contracts with more states, schools and colleges. As seen above, state-wide testing contracts with states like Illinois and Colorado, have definitely improved the participation rates in favour of the SAT by a very significant margin.
- Explore potential avenues to make the SAT more accessible and affordable for students.
   - Accessibility implies making more centres and test dates available across the US.
   - Affordability implies making more financial aid available for the students, esp. from lower income groups.
  - One way this could be achieved is through state-wide testing contracts, as seen here.
    - The implications of these methods could be analysed if the following additional data were made available:
    - Data on offering greater flexibility in test dates (eg. possibility of taking the test on weekday in school), and proportions of students that avail this increase in availability of test slots.
    - Data on proportions of students that utilize/avail financial aid to take the SAT/ACT in each state.
- Explore ways to get ahead of the 'test-optional' trend being adopted by colleges and universities. As more and more colleges drop the requirement for students to submit SAT/ACT scores during the admissions process, SAT may require a complete and creative overhaul of the testing system so as to cater to the new admissions landscape while retaining market share.



