# QuanticaProject

******** PLEASE READ *********

This is how this project is documented:
  - Survey Questions.
  - Problem to solve.
  - Questions to answer.
  - Answers just in code.

////////////////////////////////////////////////////////////////////////////

The survey questions on the dataset are marked as: 

Q.2 Please select your call center:	


Q.3 Based on your experience, on a scale from very unsatisfied to very satisfied, how satisfied are you working at your call center?

- Definitions: 

O.1 - Extremely satisfied
O.2 - Extremely unsatisfied
O.3 - Neither satisfied nor unsatisfied
O.4 - Somewhat satisfied
O.5 - Somewhat unsatisfied

Q.4 "Sorry, you feel that way. Tell us how we can improve to make you more likely to recommend our call center as a possible workplace for your family and friends. (Select one topic.) 

- Definitions:

O.1 - Internal     - are causes related to center-specific policies, procedures, or practices that need improvement.

O.2 - Technical   - are physical / non-physical causes that commonly create difficulties or delays in accomplishing a certain task.

O.3 - Personal   - are challenges that are caused by personal interest and influence.

O.4 - Tracfone    - are causes or challenges experienced across all centers.

O.5 - None        - no major challenge at all"	


Q.5 Please, provide more details.	


Q.9 Based on your experience, on a scale from very unsatisfied to very satisfied, how satisfied are you with your I.T. support?	


Q.10 Tell us why you feel that way.



//////////////////////////////////////////////////////////////////////////


Notes:

Exploratory data analysis:

- Make the problem:

  TheQCompany BPO wanted to know how satisfied is an employee on average after finishing working in a call center, 
	For that reason they took a sample of X companies and ask the employees on a survey about the overall experience and how it could be better.
	Also they want to know if exist a positive correlation with the IT support and the experience satisfaction and take measures of it.
	It is beneficial to include any other insight that can help to understand the employee behavior.

  
Questions to solve:

-	How many people answered the survey?.
A./ 22560 people answered the survey.


-	How many of them were completely satisfied with the experience? From what companies?
A./ 
                 Month    Q3  Q4  Q5    Q9  Q10
1       Bacolod   2425  2425   0   0  2423   26
2  Barranquilla     55    55   0   0    54    1
3          Cebu   1888  1888   0   0  1886   45
4     Dumaguete   1200  1200   0   0  1200   44
5     Guatemala    818   818   0   0   816   25


-	How many employees answered they've had the worst experience? From what companies? 
A./ 
                 Month   Q3   Q4   Q5  Q9  Q10
1       Bacolod    215  215  209  157  31   14
2  Barranquilla     31   31   30   25   0    0
3          Cebu    334  334  328  282  17   12
4     Dumaguete     97   97   92   80   4    0
5     Guatemala    117  117  112  101   8    5


- 	What is the general answer for the Q3 and the popular opinion about working in a call center?
A./

Somewhat satisfied                                                                                                                  10406
Extremely satisfied                                                                                                                  6386
Neither satisfied nor unsatisfied                                                                                                    2843
Somewhat unsatisfied                                                                                                                 1504
Extremely unsatisfied                                                                                                                 794


- Which topics (By Definition) are the most frequent for an ex employee recommending to improve?
A./ 

Internal - Compensation        340
Internal - Management          260
Internal - Benefits            248
NONE                           138
Internal - Work Environment    120

 
- What kind of correlation has the IT support satisfaction with the work experience satisfaction?
A./
	        Count Q3	Count Q9
Count Q3	1.000000	0.979789
Count Q9	0.979789	1.000000




