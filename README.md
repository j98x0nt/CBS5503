java c
CBS5503 of MScGAH
AY 202425 Sem 1
Individual Assignment Guidelines
Application of Machine Learning in Fake News Detection
IntroductionThis practical assignment is designed to assess students’ understanding and programming skills of conducting Machine Learning using the task of Fake News Detection. Students will be assessed on their implementation of building  a supervised machine learning pipeline, including  data preprocessing, feature extraction (engineering), model selection, and model evaluation. They are also required to report and reflect on the classification results as indicated by the evaluation metrics.
Instruction
o This assignment constitutes 50% of the total marks of this course.
o Plagiarism will be penalized. Any student who commits an act of academic dishonesty is considered to have violated academic integrity and will therefore be subject to academic disciplinary actions.
o Include statement of GenAI usage at the end of the assignment.
o Submission:
Submit a word doc including the results and reflections, named as .docx.
The Word document should be like a factual report, concise and less than 500 words.
Submit the implementation code as well, named as .ipynb.
Deadline: 23:59, 20 October 2024 (Sunday of Week 7).
o Late submission
Submission after the deadline
Mark deduction
Within 7 calendar days
50%
More than 7 days
100%
DataStructured as the sample dataset demonstrated in the tutorial, two different subsets of clean data are provided. Each subset contains 1,000 instances of news, together with the respective labels of truth (True vs. False) that are balanced. Each student will work on one of the two subsets data according to the number of the last digit in your student ID. Please refer to Table 1 in Appendix A to find the subset data for you to work on.


Tasks
Common   Task   1:  Apart   from   the   existing   functions   in   Text_Cleaning(Text)   e.g. punctuation/digit/website  removal,  add  one  self-built  function  to  remove  keywords “Reuters” and all the city names and apply to the news Text.
Common Task 2:  Visualize the fivegram distribution (plot top 10) of the True and False news respectively. Describe your observation after comparison.
Task 3A: Construct the TFIDF feature matrix based on bigrams. Run the ML pipeline and compare the result代 写CBS5503 of MScGAH Application of Machine Learning in Fake News Detection AY 202425 Sem 1R
代做程序编程语言s on bigrams with unigrams. Discuss the difference and implications in the end of the file.
Task 3B: Construct the TFIDF feature matrix based on trigrams. Run the ML pipeline and compare the results on trigrams with unigrams. Discuss the difference and implications in the end of the file.
Task 4A: Split data proportion 9: 1 and use Logistic Regression in model selection. Try to change one of the key paramers and report the classification results respectively.
Task 4B: Split data proportion 8: 2 and use Decision Tree in modelselection. Try to change one of the key paramers and report the classification results respectively.
Formatting Template
Begin the your assignment with indication of the following information:
•    Course Code  Title
•    Individual Assignment
•    Title: Application of Machine Learning in Fake News Detection
•    Student Name and ID
Run the tasks respectively with codes successfully run without errors; and
o For students with odd final digit: Report the results to common tasks 1-2 and tasks 3A, 4A. Provide basic descriptions to each of the result and interpret the results with proper analysis/account of the observation.
o For students with even final digit: Report the results to common tasks 1-2 and tasks 3B, 4B. Provide basic descriptions to each of the result and interpret the results with proper analysis/account of the observation.
Conclusion: Summarize the overall findings of any interesting patterns that you have observed in the tasks. Conclude the assignment by offering recommendations or suggestions for further improvements.


Grading Criterion
Items
Evaluation Standard
Marks
Common Task 1
Success in running task 1 and report the result
10
Common Task 2
Success in running task 2 and report the result
10
Task 3
Success in running task 3 and report the result
30
Task 4
Success in running task 4 and report the result
30
Documentation
Tidy and neat with proper comments#
10
Analysis
In-depth thinking and reflections
10
Total:
100
Appendix A
You should work on one of the given datasets according to the last digit of your student ID.
Last digit of student ID
Name of subset data
0-4
fn_subset1.csv
5-9
fn_subset2.csv
Table 1 - Mapping of Student ID and Subset Number.


         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
