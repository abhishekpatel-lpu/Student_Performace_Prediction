# Student_Performace_Prediction

<h2> Dataset Link </h2>
https://archive.ics.uci.edu/ml/datasets/Student+Performance <br>

<h2>Libraay Required</h2>
1. Pandas <br>
2. Numpy <br>
3. Matplotlib.pyplot <br>
4. Seaborn <br>
5. Sklearn <br>


<h1>Dataset Attribute </h1>
1 school - student's school (binary: "GP" - Gabriel Pereira or "MS" - Mousinho da Silveira) <br>
2 sex - student's sex (binary: "F" - female or "M" - male)<br>
3 age - student's age (numeric: from 15 to 22) <br>
4 address - student's home address type (binary: "U" - urban or "R" - rural) <br>
5 famsize - family size (binary: "LE3" - less or equal to 3 or "GT3" - greater than 3) <br>
6 Pstatus - parent's cohabitation status (binary: "T" - living together or "A" - apart) <br>
7 Medu - mother's education (numeric: 0 - none,  1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education) <br>
8 Fedu - father's education (numeric: 0 - none,  1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education) <br>
9 Mjob - mother's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other") <br>
10 Fjob - father's job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other") <br>
11 reason - reason to choose this school (nominal: close to "home", school "reputation", "course" preference or "other") <br>
12 guardian - student's guardian (nominal: "mother", "father" or "other") <br>
13 traveltime - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour) <br>
14 studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours) <br>
15 failures - number of past class failures (numeric: n if 1<=n<3, else 4) <br>
16 schoolsup - extra educational support (binary: yes or no) <br>
17 famsup - family educational support (binary: yes or no) <br>
18 paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no) <br>
19 activities - extra-curricular activities (binary: yes or no) <br>
20 nursery - attended nursery school (binary: yes or no) <br>
21 higher - wants to take higher education (binary: yes or no) <br>
22 internet - Internet access at home (binary: yes or no) <br>
23 romantic - with a romantic relationship (binary: yes or no) <br>
24 famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent) <br>
25 freetime - free time after school (numeric: from 1 - very low to 5 - very high) <br>
26 goout - going out with friends (numeric: from 1 - very low to 5 - very high) <br>
27 Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high) <br>
28 Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high) <br>
29 health - current health status (numeric: from 1 - very bad to 5 - very good) <br>
30 absences - number of school absences (numeric: from 0 to 93) <br>

# these grades are related with the course subject, Math or Portuguese:
G1 - first period grade (numeric: from 0 to 20) <br>
G2 - second period grade (numeric: from 0 to 20) <br>
G3 - final grade (numeric: from 0 to 20, output target) <br>


<h1>INTRODUCTION </h1>
Student Performance is a problem proposed by the University of California, to predict a
students’ performance in two subject, Mathematics and Portuguese. The dataset for the same is
also provided by the UCI for training purpose. The dataset provided can be used two solve
three types of problem namely, prediction, binary classification and multiclass classification.
As a part of project, we have performed training, and build model for prediction and binary
classification, following both the data file given as a part of data set.
The Objective for the Project is as describe below,
• Building of Feature Set, this task involves 2 step, Feature Selection and Feature
Extraction. Apart from this, we need to pre-process both the dataset, checking for any
kind of noise present in the data, scaling if required, Conversion of categorical data and
handling the binary columns/attribute
• Model Selection, in this step we need to do a comparative study on three or more
hypothesis or models based on a scorer (accuracy scorer, Mean Squared error etc.) and
select the model which have highest accuracy
• Once, your done with model selection step and have come up with a good model, the
next step is to refit the model to optimize it.
• On the optimised model trained, the next task involves evaluative study of your model
and plotting the result so obtain
• Next, for the selected model perform Hyper- parameter tuning, to obtain the best value
for hyperparameters.
• The Objective meets, by applying prediction/classification on new data.
Above all steps, creates a pipeline for both the data set which trainer got to follow.

<h2>Dataset</h2>
Dataset for underlying problem, named student performance is provided by UCI team.
The dataset contains two data file students_math, for the subject mathematics and student_por
for the subject Portuguese. The data file of mathematics subject consists of 395 instances – 33
attribute and the data file for Portuguese consist of 649 instances – 33 attributes.
The data attributes include student grades, demographic, social and school related features) and
it was collected by using school reports and questionnaires. The two datasets were modelled
under binary/five-level classification and regression tasks. Important note: the target attribute
G3 has a strong correlation with attributes G2 and G1. This occurs because G3 is the final year
grade (issued at the 3rd period), while G1 and G2 correspond to the 1st and 2nd period grades.
It is more difficult to predict G3 without G2 and G1, but such prediction is much more useful.

