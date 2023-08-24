<p align="center">
<b> CGU School of Social Science, Policy & Evaluation CGU  <br>
Department of Economic Sciences <br>
Causal Modeling, Big Data and Machine Learning <br> Fall 2023 
</p>
  
## Contact Information
## Course Instructor: Greg DeAngelo 
Office: <br>
E-mail: gregory.deangelo@cgu.edu <br>
Office Hours: <br>

## Course Instructor: Scott Cunningham 
E-mail: scunning@gmail.com <br>

## Course Instructor: Minjae Yun
E-mail: minjae.yun@cgu.edu <br>

## Teaching Assistant: Anuar Assamidanov
E-mail: anuar.assamidanov@cgu.edu <br> 

## Course Schedule 
Semester start/end dates: 8/28/2023 – 12/16/2023 <br>
Meeting day, time: Tuesday, 10:00 AM - 11:50 AM PST  <br>
Course Location: Online <br> <br>

## Course Description 
This course will cover statistical methods based on the machine learning literature that can be 
used for causal inference. In economics and the social sciences more broadly, empirical analyses 
typically estimate the effects of counterfactual policies, such as the effect of implementing a 
government policy, changing a price, showing advertisements, or introducing new products. 
Recent advances in supervised and unsupervised machine learning provide systematic 
approaches to model selection and prediction, methods that are particularly well suited to 
datasets with many observations and/or many covariates. <br> <br>

## Background Preparations (Prerequisites)
Econometrics, probability and statistics, basic programming <br> <br>

## Student Learning Outcomes 
By the end of this course, students will be able to:
<ol>
<li> Secure the system and reproducibility of data analysis through programming </li>
<li> Implement machine learning algorithms </li>
<li> Develop a causal identification strategy </li>
<li> Identify the basic assumptions of causal inference as applied to machine learning </li>
</ol>

## Texts and Journal References 
<li> Required: James, Gareth, Daniela Witten, Trevor Hastie, and Robert Tibshirani. "An Introduction to Statistical Learning with Applications in Python." New York: Springer, 2023. (Free PDF: https://www.statlearning.com) </li>
<li> Optional: Matheus Facure. "Causal Inference in Python: Applying Causal Inference in the Tech Industry." 1st Edition. O'Reilly Media, 2023. </li>
<li> Optional: Sutton, Richard S., and Andrew G. Barto. "Reinforcement Learning: An Introduction." Second Edition. MIT Press, Cambridge, MA, 2018. (Free PDF: http://incompleteideas.net/book/the-book-2nd.html) </li>

## Modules
  
For each week, a set of required problem sets are assigned. Supplementary readings are also provided for those who wish to delve deeper.
  <ol>
    <li> <a href="#M1"> Introduction to Causal Inference and Machine Learning </a> </li>
    <li> <a href="#M2"> Data Collection 1: Working with APIs </a> </li>
    <li> <a href="#M3"> Machine Learning Fundamentals for Estimating Treatment Effects </a> </li>
    <li> <a href="#M4"> Python Programming for Estimating Treatment Effect  </a> </li>
    <li> <a href="#M5"> Estimating Heterogenous Treatment Effect </a> </li>
    <li> <a href="#M6"> Double/Debiased Machine Learning (DML)*  </a> </li>
    <li> <a href="#M7"> Introduction to Causal Forests*  </a> </li>
    <li> <a href="#M8"> Multi-armed Bandits and Causal Decision Making* </a> </li>
    <li> <a href="#M9"> Instrumental Variable Lasso (IV Lasso)* </a> </li>
    <li> <a href="#M10"> Synthetic Difference-in-Differences (Diff-in-Diffs) </a> </li>
    <li> <a href="#M11"> Data Collection 2. Web Scraping </a> </li>
    <li> <a href="#M12"> Automating Process and Data Visualization </a> </li>
    <li> <a href="#M13"> Introduction to Unsupervised Learning </a> </li>
    <li> <a href="#M14"> Matrix Completion Techniques for "Missing" Data </a> </li>
  </ol>
*Weeks marked with an asterisk (*) are subject to potential changes based on the course's evolving curriculum. <br>

### <h2 id="M1">Week 1.  Introduction to Causal Inference and Machine Learning </h2>
Econometrics recap and the gist of statistical learning and supervised/unsupervised machine learning <br>

<li> Reading: Athey, Susan and Guido Imbens (2019) Machine Learning Methods That Economists Should Know About </li>
<li> Chapter 6 from An introduction to statistical learning with applications in Python </li>
<li> News article <a href="https://time.com/6247678/openai-chatgpt-kenya-workers/"> Data labeling in supervised learning </a> </li>
<li> <a href="https://drive.google.com/file/d/1LYCFnXiy3K2VdChDdplpSqyKtUDVooFW/view?usp=drive_link">Lecture Note</a>  </li>

### <h2 id="M2">Week 2. Data Collection 1: Working with APIs </h2>
Manage covariates from US Census, UCR, Twitter, Reddit, and else <br>

<li> Chapter 7 from An introduction to statistical learning with applications in Python </li>
<li> <a href="http://github.com/MinjaeYun/practice/blob/master/web_scraping_for_ss_0115.ipynb">Basic Programming Lecture Note</a> </li>
<li> <a href="https://www.census.gov/data/developers/data-sets.html"> US Census </a> </li>
<li> <a href="https://www.justice.gov/developer#:~:text=The%20FBI%20Crime%20Data%20API,uses%20and%20their%20related%20entities."> FBI Crime data </a> </li>
<li> <a href="https://www.reddit.com/dev/api/"> Reddit </a> </li>
<li> <a href="https://praw.readthedocs.io/en/latest/"> Python package for Reddit </a> </li>
<li> <a href="https://developer.twitter.com/en/docs"> Twitter </a> </li>
<li> <a href="https://www.tweepy.org/"> Python package for Twitter </a> </li>
<li> <a href="https://jacobdkaplan.weebly.com/books.html"> Jacob Kaplan's Reservoir </a> </li> 

### <h2 id="M3">Week 3. Machine Learning Fundamentals for Estimating Treatment Effects </h2>
The promise of machine learning in estimating treatment effects <br>

<li> Lecture Notes from <a href="https://github.com/Mixtape-Sessions/Machine-Learning"> Dr. Brigham Frandsen's workshop </a> </li>
<li> Chapter 8 from An introduction to statistical learning with applications in Python </li>

### <h2 id="M4">Week 4. Python Programming for Estimating Treatment Effect </h2>

<li> Lecture Notes from <a href="https://github.com/Mixtape-Sessions/Machine-Learning"> Dr. Brigham Frandsen's workshop </a> </li>
<li> Chapter 10 from An introduction to statistical learning with applications in Python </li>

### <h2 id="M5">Week 5. Estimating Heterogenous Treatment Effect </h2>
<li> Lecture Notes from <a href="https://github.com/Mixtape-Sessions/Heterogeneous-Effects/"> Dr. Brigham Frandsen's workshop </a>
<li> Reading: Athey, Susan, and Guido Imbens (2016) Reading Recursive Partitioning for Heterogeneous Causal Effects
<li> Reading: Chernozhukov, Victor, Mert Demirer, Esther Duflo, and Iván Fernández-Val (2020) Generic Machine Learning Inference on Heterogenous Treatment Effects in Randomized Experiments, with Application to Immunization in India

### <h2 id="M6">Week 6. Double/Debiased Machine Learning (DML) </h2>
Lecture by Dr. Scott Cunningham
<li> Chapter 4 from Causal Inference in Python </li>
<li> Chapter 22 from Causal Inference for The Brave and True </li>

### <h2 id="M7">Week 7. Introduction to Causal Forests </h2>
Lecture by Dr. Scott Cunningham
<li> Reading: Athey, Susan, and Guido Imbens (2016) The Econometrics of Randomized Experiments </li>

### <h2 id="M8">Week 8. Multi-armed Bandits and Causal Decision Making </h2>
Lecture by Dr. Scott Cunningham
<li> Optional Reading: Chapter 2 from Reinforcement Learning: An Introduction.</li>

### <h2 id="M9">Week 9. Instrumental Variable Lasso (IV Lasso) </h2>
Lecture by Dr. Scott Cunningham
<li> Reading: Belloni, Alexandre, Victor Chernozhukov, Christian Hansen (2011) LASSO Methods for Gaussian Instrumental Variables Models </li>

### <h2 id="M10">Week 10. Synthetic Difference-in-Differences (Diff-in-Diffs) </h2>
<li> Reading: Arkhangelsky, Dmitry, Susan Athey, David A. Hirshberg, Guido Imbens, and Stefan Wager (2021) Synthetic Difference in Differences
<li> <a href="https://github.com/MasaAsami/pysynthdid"> Python package: pysynthdid </a>
<li> Data: Castle doctrine </li>

### <h2 id="M11">Week 11. Data Collection 2. Web Scraping </h2>
Collecting various information from cyberspace including news articles and create a flat data file <br>

<li> <a href="https://github.com/MinjaeYun/practice/blob/master/web_scraping_for_ss_0123.ipynb"> Lecture Note </a> </li>
</li>

### <h2 id="M12">Week 12. Automating Process and Data Visualization </h2>
For reproducibility and systematic management of data analysis

### <h2 id="M13">Week 13. Introduction to Unsupervised Learning </h2>
<li> Chapter 12 from An introduction to statistical learning with applications in Python </li>
<li> Ludwig, Jens and Mullainathan, Sendhil, Algorithmic Behavioral Science: Machine Learning as a Tool for Scientific Discovery (July 15, 2022). Chicago Booth Research Paper No. 22-15, Available at SSRN: https://ssrn.com/abstract=4164272 or http://dx.doi.org/10.2139/ssrn.4164272 </li>

### <h2 id="M14">Week 14. Matrix Completion Techniques for "Missing" Data </h2>
<li> Reading: Athey, Susan, Mohsen Bayati, Nikolay Doudchenko, Guido Imbens, and Khashayar Khosravi (2021) Matrix Completion Methods for Causal Panel Data Models 
<li> <a href="https://github.com/susanathey/MCPanel/tree/master/tests/examples_from_paper"> Paper example </a> 
<li> <a href="https://sidravi1.github.io/blog/2018/12/02/athey-s-matrix-completion-methods"> Python Coding </li>
<li> R Package: gsynth and MCPanel 
<li> Data: California smoking dat  </li>

## Grading
Your grade will be calculated using the following scale. Grades with plus or minus designations 
are at the professor’s discretion.
<table>
  <tr>
    <th> Letter Grade </th>
    <th> Grade Point </th>
    <th> Description </th>
    <th> Learning Outcome </th>
  </tr>
  <tr>
    <td> A </td>
    <td>4.0</td>
    <td> Complete mastery of course material and additional 
insight beyond course material (Overall grade percent 
≥ 90) </td>
    <td> Insightful </td>
  </tr>
  <tr>
    <td> B </td>
    <td> 3.0 </td>
    <td>Complete mastery of course material (90 > Overall 
grade ≥ 80) </td>
    <td> Proficient </td>
  </tr>
  <tr>
    <td> C </td>
    <td> 2.0 </td>
    <td> Caps in mastery of course material; not at level 
expected by the program (80 > Overall grade ≥ 65) </td>
    <td> Developing </td>
  </tr>
  <tr>
    <td> U </td>
    <td>0.0</td>
    <td>Unsatisfactory (65 > Overall grade </td>
    <td>Ineffective</td>
  </tr>
</table>

Continual matriculation at CGU requires a minimum grade point average (GPA) of 3.0 in all 
coursework taken at CGU. Students may not have more than two incompletes. Details of the 
policy are found on the Student Services webpage. <a href="https://mycampus.cgu.edu/web/registrar/for-current-students/student-policies#Satisfactory_Academic_Progress">
                        https://mycampus.cgu.edu/web/registrar/for-current-students/student-policies#Satisfactory_Academic_Progress
                        </a>

## Course Policies:
The CGU institutional policies apply to each course offered at CGU. A few are detailed in the 
space below. Students are encouraged to review the student handbook for the program as well as 
the policy documentation within the bulletin and on the Registrar’s pages. <a href="http://bulletin.cgu.edu/"> http://bulletin.cgu.edu/ </a>
                        
## Attendance
Students are expected to attend all classes. Students who are unable to attend class must seek 
permission for an excused absence from the course director or teaching assistant. Unapproved 
absences or late attendance for three or more classes may result in a lower grade or an 
“incomplete” for the course. If a student has to miss a class, he or she should arrange to get 
notes from a fellow student and is strongly encouraged to meet with the teaching assistant to 
obtain the missed material. Missed extra-credit quizzes and papers will not be available for retaking.

## Scientific and Professional Ethics
The work you do in this course must be your own. Feel free to build on, react to, criticize, and 
analyze the ideas of others but, when you do, make it known whose ideas you are working with. 
You must explicitly acknowledge when your work builds on someone else's ideas, including 
ideas of classmates, professors, and authors you read. If you ever have questions about drawing 
the line between others' work and your own, ask the course professor who will give you 
guidance. Exams must be completed independently. Any collaboration on answers to exams, 
unless expressly permitted, may result in an automatic failing grade and possible expulsion from 
the Program. Additional information on CGU academic honesty is available on the Student 
Services webpage. <a href="https://cgu.policystat.com/policy/2194316/latest/"> https://cgu.policystat.com/policy/2194316/latest/</a>

## Instructor Feedback and Communication
The best way to get in touch with me is ___. I will respond to email/voice messages within two 
business days.

## Expectations and Logistics
This section can include guidance about completing readings before class, the preferred method 
of submitting a paper or assignment (e.g., hard copy, email, Sakai/Canvas, Dropbox), the 
preferred format, and the amount of time it will take to receive feedback on assignments. If you 
intend to use Sakai or other open source applications, this can be noted here. If discussion 
boards are to be included, a brief statement on netiquette, expected frequency of student 
postings, and the extent that the faculty or teaching assistant will participate should be noted.

## Accommodations for Students with Disabilities: 
If you would like to request academic 
accommodations due to temporary or permanent disability, contact Dean of Students and 
Coordinator for Student Disability Services at DisabilityServices@cgu.edu or 909-607-
9448. Appropriate accommodations are considered after you have conferred with the Office of 
Disability Services (ODS) and presented the required documentation of your disability to the 
ODS.

## Mental Health Resources
Graduate school is a context where mental health struggles can be 
exacerbated. If you ever find yourself struggling, please do not hesitate to ask for help. If you 
wish to seek out campus resources, here is some basic information about Monsour. 
<a href="https://www.cuc.claremont.edu/mcaps/"> https://www.cuc.claremont.edu/mcaps/ </a> <br>
“Monsour Counseling and Psychological Services (MCAPS) is committed to promoting 
psychological wellness for all students served by the Claremont University Consortium. Our 
well-trained team of psychologists, psychiatrists, and post-doctoral and intern therapists offer 
support for a range of psychological issues in a confidential and safe environment.” <br>
Phone 909-621-8202 <br>
Fax 909-621-8482 <br>
After hours emergency 909-607-2000 <br>
 Tranquada Student Services Center, 1st floor <br>
 757 College Way <br>
 Claremont, CA 91711 <br>

## Title IX: 
If I learn of any potential violation of our gender-based misconduct policy (rape, sexual 
assault, dating violence, domestic violence, or stalking) by any means, I am required to notify the CGU 
Title IX Coordinator at Deanof.Students@cgu.edu or (909) 607-9448. Students can request 
confidentiality from the institution, which I will communicate to the Title IX Coordinator. If students 
want to speak with someone confidentially, the following resources are available on and off campus: 
EmPOWER Center (909) 607-2689, Monsour Counseling and Psychological Services (909) 621-8202, 
and The Chaplains of the Claremont Colleges (909)621-8685. Speaking with a confidential resource 
does not preclude students from making a formal report to the Title IX Coordinator if and when they are 
ready. Confidential resources can walk students through all of their reporting options. They can also 
provide students with information and assistance in accessing academic, medical, and other support 
services they may need.
