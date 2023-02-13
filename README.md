<head>
  
</head>

<body>

<div class="section">
  <div style="float:left; clear:left">
    <img width="90" src="stanford_seal.gif"/>
  </div>
  <div style="margin-left: 30; margin-top: 20">
    <div class="top assignmentTitle">
      STATS214 / CS229M: Machine Learning Theory
 
  for all the logistic information, syllabus, coursework, schedule, etc. 
</div>

  <div class="section"><b>Time/location:</b>
    <ul>
      <li>Lectures: Mon/Wed 3:15-4:45pm</li>
      <li>Location TBD. Vidoes are available, and attendance is not required.</li>
    </ul>
  </div>

Tengyu Ma

    
  <div class="section"><b>Contact:</b>
    Please use https://www.piazza.com/stanford/fall2018/cs229t  for all questions and discussions. 
  </div>

<div class="section">
  <span class="header">Course content</span>

  <div class="section"><b>Description:</b>
    When do machine learning algorithms work and why? How do we formalize what it means for an algorithm to learn from data? How do we use mathematical thinking to design better machine learning methods?
    This course focuses on developing a theoretical
    understanding of the statistical properties of learning algorithms.
  </div>

  <div class="section"><b>Topics</b>:
    <ul>
      <li>Generalization bounds via uniform convergence
      <li>Theory for deep learning
      <ul>
      	<li>Non-convex optimization
      	<li>Neural tangent kernel
      	<li>Implicit/algorithmic regularization
      </ul>
      <li>Unsupervised learning and domain adaptation
      <li>Bandit and online earning (if time permits)
    </ul>
  </div>
</div>
</div>
</body>
Machine Learning Theory (CS229M/STATS214)

Administrative information

Location: McCullough Building, Rm 115
Instructor: Tengyu Ma

Recorded videos and livestream zoom are available; attendance is optional. 
Prerequisites
Students are expected to have the following background:

Calculus (Math 19, Math 20, or Math 21)

Linear algebra (Math 51 or CS205)

Probability (CS 109,  STATS 116, MATH 151 or EE178)

Machine learning (CS 229/STATS229 or STATS 315A)

Recommended but not required: EE364A and/or CS168

Schedule 

Week 1
Lecture 1 (09/20): Overview, supervised learning, empirical risk minimization (Section 1 of the notes)

Lecture 2 (09/22):  Asymptotic analysis (subset of Section 2), uniform convergence (Section 4.1), Hoeffding inequality (Section 3.2)

Week 2
Lecture 3 (09/27): uniform convergence, finite hypothesis class, discretizing infinite hypothesis space (Section 4.1-4.3)

Lecture 4 (09/29): Advanced concentration inequalities (Section 3)
Wed 09/29: Homework 0 (warmup) due

Week 3
Lecture 5 (10/04): Rademacher complexity, empirical Rademacher complexity (Section 4.4 and Section 4.5)

Lecture 6 (10/06): Margin theory and Rademacher complexity for linear models (Section 5.1 & 5.2)

Week 4
Lecture 7 (10/11): Challenges in deep learning theory, generalization bounds for neural nets (Section 7 & 5.3)

Lecture 8 (10/13): Refined generalization bounds for neural nets, connection to Kernel methods. Covering number approach, VC dimension (Sec 4.6) 
Wed (10/13): Homework 1 due

Week 5
Lecture 9 (10/18): Covering number approach, Dudley Theorem (and implications). Generalization bounds for deep nets (Sec 4.6)
Lecture 10 (10/20): Generalization bounds for deep nets (Section 5.5), 

Week 6: 
Lecture 11 (10/25): All-layer margin (Section 6). 
Lecture 12 (10/27): Non-convex optimization, Non-convex opt for PCA, matrix complexion (Section 8.1-8.3)
Wed (10/27): Homework 2 due 

Week 7: 
Lecture 13 (11/01): Neural Tangent Kernel (Section 8.4)
Lecture 14 (11/03): Neural Tangent Kernel, Implicit regularization of gradient descent (Section 9.1)
Fri 11/05: (Optional) paper review part 1 due

Week 8: 
Lecture 15 (11/08): Implicit regularization effect of initialization (Section 9.2-9.3)
Lecture 16 (11/10): Implicit regularization in classification problems (Section 9.4)

Week 9: 
Lecture 17 (11/15): Implicit regularization effect of the noise (Section 9.5)
Lecture 18 (11/17): Unsupervised learning, mixture of Gaussians, moment methods (Section 10.1)
Wed (11/17): Homework 3 due

Week 10:
Lecture 19 (11/29): Mixture of Gaussians, spectral clustering (Section 10.1-10.2)
Lecture 20 (12/01): Spectral clustering (Section 10.2)
(Fri) 12/03: Paper review / project due

Coursework

Homework (50%): there will be three assignments. 


You are encouraged to use LaTeX to write up your solutions (here's a template)

\documentclass[12pt]{article}
\usepackage{fullpage,enumitem,amsmath,amssymb,graphicx}

% Some macros for your convenience
\newcommand\bbR{\ensuremath{\mathbb{R}}} % Real numbers
\newcommand\bbZ{\ensuremath{\mathbb{Z}}} % Integers
\newcommand\bbE{\ensuremath{\mathbb{E}}} % Expectation
\DeclareMathOperator*{\tr}{tr} % Trace
\DeclareMathOperator*{\diag}{diag} % Diagonal matrix
\DeclareMathOperator*{\sign}{sign} % Sign
\DeclareMathOperator*{\var}{Var} % Variance
\DeclareMathOperator*{\cov}{Cov} % Covariance
\newcommand{\1}{\mathbb{I}} % Indicator
%\newcommand{\newproblem}[1]{\newpage \section*{Problem #1}}
\begin{document}

\begin{center}
{\Large CS229M/STAT214 Winter 2021 Homework [number]}

\begin{tabular}{rl}
SUNet ID: & [your SUNet id] \\
Name: & [your first and last name] \\
Collaborators: & [list all the people you worked with]
\end{tabular}
\end{center}

By turning in this assignment, I agree by the Stanford honor code and declare
that all of this is my own work.

\section*{Problem 1}

\begin{enumerate}[label=(\alph*)]
  \item (your solution)
  \item (your solution)
\end{enumerate}

\section*{Problem 2}

\begin{enumerate}[label=(\alph*)]
  \item (your solution)
  \item (your solution)
\end{enumerate}

\end{document}


The assignments are weighted by their respective point values - for example, if {p1, p2, p3,} denotes the point values of each assignment, then HW1 is worth p1 / (p1+p2+p3) * 50% of the total grade.

You will receive two bonus points for submitting a typed written assignment in LaTeX. We will accept scanned handwritten assignments but they will not receive the bonus point. 

Paper review and/or project (50%): You will write a review of two papers on the same topic. The goal is to learn to read technically demanding papers critically, and hopefully in the process, generate novel research ideas.

Your review should not only summarize the main result of the paper, but critique it, instantiate it on examples, discuss its overall significance, and suggest possible future directions. 


Alternatively, you can also choose to review a single paper and do a mini-project on the same topic (e.g., as a follow-up to the paper that you reviewed.) You should submit a single 8-page report that contains both the paper review and the new work. 

Please see this https://docs.google.com/document/d/1C7WrhzLAatfjOcV_YPE-VOeFc2UHprLOv7p0YtDDFec/edit?usp=sharing Google doc for detailed guidelines and a list of recent interesting papers on theoretical machine learning.

 
Ed Discussion (bonus, maximum 2%.) We highly encourage students to answer each others’ questions via Ed Discussion platform. To incentivize this, we will be giving 1-2% bonus credits to the top 10 students with the most number of instructor-endorsed responses on Ed Discussion by the end of the quarter. 


Scribbletogether board
The instructor will share the ipad screen in the lecture but the screen size is limited. To mitigate this, the entire ipad notes will be also shared live here on scribbletogether. Please click this link for the live notes. The link will be disabled at the end of the quarter. There are scribletogether apps on iPad as well which you can download and use to join the board. To join a board created by others, you don’t have to subscribe to scribbletogether. 


Grading Policy
We in principle grade on a curve, but the exact implementation typically leads to a more generous outcome. Below is the exact protocol that the course staff will use to determine the final grade. 

We will first grade on a curve using the regular scores to decide the boundaries between categories (except the category between A and A+). 

Then we add the bonus points to the regular points and use the points including the bonus and the thresholds to determine the final letter grade. We will use the score with bonus to decide A+. Moreover, because the students generally do very well in the course, we will make sure the boundary between A and A- is at least 95%. 


In the past offerings, typically > 70% of students obtained A or A+ under this policy. (The curve that the course staff uses to compute the boundaries is less generous than this, but because of the bonus scores, many students’ letter grades were promoted.) 

Requirements for C/NC: We will first grade on a curve and if you get C- or above, you will get a pass. The course staff won’t release the exact percentage of scores you need to get the credit (because it won’t be determined until the end of the quarter), but we guarantee that 50% of the total scores would suffice for a pass. But note that this percentage is a relatively conservative estimate, the final cutoff for credit might be lower but won’t be higher.


Ed and Gradescope
We use Ed Discussion for Q&A (which you can find on canvas) and Gradescope for assignment submission.

Gradescope access will be granted after enrollment to the class as we periodically synchronize with the official course roster. If you are enrolled in the course and didn’t have access to gradescope by the Friday of the first week, please send the TA (wuyc14@stanford.edu) an email with [STATS214] as the first few characters in the subject.


Submitting Assignments
To limit access to the assignments to only enrolled students and avoid the solutions to show up online publicly, the assignments will only be posted on Ed (not the course website nor Canvas). Assignments will be submitted through Gradescope. You will receive an invite to Gradescope for CS229M Machine Learning Fall 2021. If you have not received an invite email after the first few days of class, first log in to Gradescope with your @stanford.edu email and see whether you find the course listed; if not please send an email to wuyc14@stanford.edu to add you. 


Late Assignments
Each student will have a total of three free late (calendar) days to use for homeworks, paper reviews, but not scribe notes. Once these late days are exhausted, any assignments turned in late will be penalized 20% per late day. 

However, no assignment will be accepted more than three days after its due date.

Each 24 hours or part thereof that a homework is late uses up one full late day. Please note that late days are applied individually. E.g., if a submission with 3 team members is 1 day late, then all the members will need to use 1 late day. 

If your assignments are late by totally larger than 3 days, we will automatically apply the penalization first on your late assignment that has the smallest total score. 

Under extenuating circumstances, you may request an extension by contacting the course staff, but we note that extenuating circumstances do not include predictable events such as conference deadlines or TA responsibilities.

Announcements and Questions
All official announcements and communication will happen over Ed.

Any questions regarding course content and course organization should be posted on Ed.

You are strongly encouraged to answer other students' questions when you know the answer.

If there are private matters specific to you (e.g special accommodations, requesting alternative arrangements etc.), please create a private post on Ed.
For longer discussions with TAs, please attend office hours.

!!!!!!!!!!!!!!!
Honor Code
!!!!!!!!!!!!!!!
We strongly encourage students to form study groups 
(beyond the groups for submitting the homework).

Students may discuss and work on homework problems in groups. 

However, each team of students must write down the solution independently from other teams.

Each student must understand the solution well enough in order to reconstruct it by him/herself. It is an honor code violation to copy, refer to, or look at written or code solutions from a previous year, including but not limited to: official solutions from a previous year, solutions posted online, and solutions you or someone else may have written up in a previous year.

Furthermore, it is an honor code violation to post your assignment solutions online, such as on a public git repo. 

!!!!We run plagiarism-detection software on your code against past solutions as well as student submissions from previous years. Please take the time to familiarize yourself with the Stanford Honor Code and the Stanford Honor Code as it pertains to CS courses.!!!!
OR ELSE YOU WILL BE EXPELLED AND DISHONERED!
YOUR SOCIALCREDIT SCORE WILL BE CONTINIOUSLY MONITORED!!



Lecture Video Policy
The in-person lecture will be also recorded and livestreamed on Zoom. Please find the Zoom meeting link on Ed or the course Canvas page. You will need to sign in with your Stanford credentials to join the lecture. 

We are recording to capture the instructor presentations in this course. For your convenience, you can access these recordings by logging into the course Canvas site. It’s possible that these videos will be made public later after certain edits.

Note that while we have adjusted the recording settings with the intention of recording only the presenter, occasionally a part of your image will be captured. 

Before the video is made public, editors will review the recordings and forward student images to the FBI. 

Occasionally, your voice will also be captured. If you have questions, please contact a member of the Socialscore team.



Covid Related Policy
We will follow the university guidelines and expect you to follow them (e.g., wearing masks in the classroom, etc.) Given the video and live stream are available, attendance is optional.  If you are unfortunately ill and need accommodation on the homework deadline, please email Yuchen Wu (wuyc14@stanford.edu). 

The course staff, will check student Health Check badges prior to each class or meeting with a student. If the course staff chose to do so, they will check all badges and single out suspicious students. 


Zoom / In Person Office Hours 
The office hour schedule will be posted on the course Canvas page. We will either use Zoom to hold remote office hours or hold in-person office hours. If you join the zoom meeting,  then the TA will answer questions in the zoom meeting publicly, or create a breakout room to answer private questions.




Auditing
Due to covid and room capacity limits, we encourage you to enroll in the course so that we can have a better estimate of the total number of students, and justify the request for large classrooms. (The university has a shortage of large classrooms, unfortunately.) If you would like to audit, please email Yuchen (wuyc14@stanford.edu). Please note that auditors do not get access to the Ed forum (partly because we often have limited TAs to answer questions online) and thus do not get access to the assignments. Likewise, auditors do not have access to Gradescope to submit assignments.

Incomplete
This course generally does not grant incomplete except under extenuating circumstances. We note that extenuating circumstances do not include predictable events such as Climate change, Religious nonsense, conference deadlines or TA responsibilities. 


---FAQ---
When will solutions for problem sets be released?

Solutions will be released after problem sets have been graded and around the same time as grades are published. 

Can I take courses that overlap with CS229M?  
Yes. If you need an instructor’s signature, please reach out to Prof. Tengyu Ma. 







