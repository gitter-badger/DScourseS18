# ECON 5970: Data Science for Economists (Spring 2018) #

|  | [Tyler Ransom](http://tyleransom.github.io) |
|--------------|--------------------------------------------------------------|
| Email | [ransom@ou.edu](mailto:ransom@ou.edu) |
| Office | 322 CCD1 |
| Office Hours | M 9-10am, Th 12-1pm |
| GitHub | [tyleransom](https://github.com/tyleransom) |

* **Meeting day/time**: T,Th 1:30-2:45pm, CCD1, Room 174
* Office hours also available by appointment
* This course takes inspiration and borrows materials from similar courses taught by [Jason DeBacker](https://github.com/jdebacker/CompEcon_Fall17) (U of South Carolina) and [Rick Evans](https://github.com/rickecon/OGcourse_F17) (U of Chicago). Thanks to them for providing a framework for using GitHub as a class collaboration tool and for insignts into teaching programming skills.

## Course description ##

Data science is a rapidly developing field that combines the recent Big Data revolution with everdeveloping statistical algorithms to inform business and policy decisions. Nearly every company you've heard of uses data science to optimize its services. Netflix uses it to recommend new programs to its viewers, Amazon uses it to determine how much it should charge for its Prime services. This class will provide students with an overview of the data science workflow, from collecting raw data to a set of insights from which a decision maker can make informed decisions. Along the way we will broadly cover a variety of advances in data collection, data storage, machine learning and econometrics topics, as well as teaching and reinforcing good programming practices. The primary goal of this course is to provide you, the student, with a set of skills that will allow you to compete for a data science job.

## Course Objectives and Learning Outcomes ##

By the end of the course, students should be able to do the following:

1. Explain the data science workflow from start to finish
2. Be able to collect data from online sources via APIs or scraping
3. Describe similarities and differences between econometrics and machine learning
4. Explain what data science is, and how Big Data differs from other types of data
5. Demonstrate good programming practices by writing code that can allow for easy collaboration with others
6. Understand the differences between prediction and causality, and the cases in which each is useful

In this course students, through lecture and application, students will learn about:
* Good programming practices, including how to write code collaboratively with others
* Software to increase research productivity including:
    * LaTeX/Markdown
    * git
    * R
    * Julia
    * Python
* Software to manage big data sets:
    * SQL
    * RDDs (Resilient Distributed Datasets) --- Spark, Hadoop
* How to access and utilize cluster computing resources
    * SLURM (Simple Linux Utility for Resource Management)
* Methods to gather and handle data including:
    * Costs and benefits of different data structures
    * Using APIs
    * Web scraping
* Best practices for cleaning and visualizing data
* Computational methods to:
    * Optimize and find roots of functions
    * Perform Monte Carlo simulations
    * Run computations in parallel using multiple processors (time permitting)
* Basics for modeling different types of data
* Machine learning basics:
    * Supervised vs. unsupervised learning
    * The five "tribes" of machine learning: how they are interconnected, and how they differ
    * Machine learning vs. econometrics: prediction vs. causality
    * Evaluating model performance
* Using economic models to inform policy decisions
    * Computing structural models


## Grades ##

Grades will be based on the categories listed below with the corresponding weights.

Component                    |   Percent  |
-----------------------------|------------|
Class Participation          |    10%     |
Problem Sets                 |    35%     |
Exam & Quizzes               |    20%     |
Final project                |    35%     |
**Total points**             |  **100%**  |

Final grades will be assigned according to the standard cutoffs (90%+ for an A, 80%-89.99% for a B, etc.).

* **Problem sets:** will be assigned approximately weekly throughout the semester.
    * You must write and submit your own computer code, although I encourage you to collaborate with your fellow students. I **DO NOT** want to see a bunch of copies of identical code. I **DO** want to see each of you learning how to code these problems so that you could do it on your own.
    * Problem set solutions, both written and code portions, will be turned in via a pull request from your private [GitHub.com](https://github.com/) repository which is a fork of the class master repository on my account. (You will need to set up a GitHub account if you do not already have one.)
    * Written solutions must be submitted as PDF documents or Jupyter Notebooks.
    * Problem sets will be due on the day listed in the Daily Course Schedule section of this syllabus (see below) unless otherwise specified. Late problem sets will not receive any credit. Partially completed problem sets will receive partial credit.

* **Exam & Quizzes:**
    * We may periodically have in-class quizzes as low-stakes ways to get feedback
    * There will be a written final exam, but no midterm

* **Final Project:**
    * Collect data on and analyze a research question of your choosing, using methods taught in this course
    * Write up a ~10 page summary of your findings, including discussion about what prior studies of the same topic have found, as well as citations to prior studies
    * Turn in the written summary report and a GitHub repository containing all materials required to reproduce the results
    * Summary report should be written in LaTeX or RMarkdown



## Daily Course Schedule ##
(Will be continuously updated throughout the semester)

| Date   | Day | Topic                                                         | Due                                                                                                                            |
|--------|-----|-------------------------------------------------------------- |--------------------------------------------------------------------------------------------------------------------------------|
| Jan 16 | T   | What is data science / big data / why is it important?        |                                                                                                                                |
| Jan 18 | Th  | Git, GitHub, computing environment, and Coding best practices | Read Gentzkow & Shapiro's [handbook](https://web.stanford.edu/~gentzkow/research/CodeAndData.pdf); register for GitHub account |
| Jan 23 | T   | Linux command line, SSH, accessing OSCER                      | PS 1                                                                                                                           |
| Jan 25 | Th  | Overview of Data Scientists' tools                            |                                                                                                                                |
| Jan 30 | T   | Using data: data types, storage                               | PS 2                                                                                                                           |
| Feb 1  | Th  | Big Data: SQL & RDDs                                          |                                                                                                                                |
| Feb 6  | T   | Sampling & storing Big Data                                   | PS 3                                                                                                                           |
| Feb 8  | Th  | Web scraping/APIs to gather data                              |                                                                                                                                |
| Feb 13 | T   | Web scraping/APIs to gather data                              | PS 4                                                                                                                           |
| Feb 15 | Th  | Data exploration, descriptive stats                           |                                                                                                                                |
| Feb 20 | T   | Data cleaning, transformations                                | PS 5                                                                                                                           |
| Feb 22 | Th  | Data visualization                                            |                                                                                                                                |
| Feb 27 | T   | Modeling continuous variables                                 | PS 6                                                                                                                           |
| Mar 1  | Th  | Modeling discrete variables                                   |                                                                                                                                |
| Mar 6  | T   | Functions, Optimizers, Root-Finders                           | PS 7                                                                                                                           |
| Mar 8  | Th  | Functions, Optimizers, Root-Finders                           |                                                                                                                                |
| Mar 13 | T   | Functions, Optimizers, Root-Finders                           | PS 8                                                                                                                           |
| Mar 15 | Th  | Debugging strategies and simulations                          |                                                                                                                                |
| Mar 20 | T   | No class (Spring break)                                       |                                                                                                                                |
| Mar 22 | Th  | No class (Spring break)                                       |                                                                                                                                |
| Mar 27 | T   | Intro to Machine Learning                                     | PS 9                                                                                                                           |
| Mar 29 | Th  | Supervised ML                                                 |                                                                                                                                |
| Apr 3  | T   | Unsupervised ML                                               | PS 10                                                                                                                          |
| Apr 5  | Th  | Unsupervised ML                                               |                                                                                                                                |
| Apr 10 | T   | Machine learning vs. econometrics                             | PS 11                                                                                                                          |
| Apr 12 | Th  | Evaluating ML model performance                               |                                                                                                                                |
| Apr 17 | T   | Structural modeling                                           | PS 12                                                                                                                          |
| Apr 19 | Th  | Structural modeling                                           |                                                                                                                                |
| Apr 24 | T   | Structural modeling                                           | PS 13                                                                                                                          |
| Apr 26 | Th  | Final Project presentations                                   |                                                                                                                                |
| May 1  | T   | Final Project presentations                                   |                                                                                                                                |
| May 3  | Th  | Final Project presentations                                   |                                                                                                                                |
| May 8  | T   | Final Exam (in class, 1:30-3:30pm)                            | Final project due                                                                                                              |


## Helpful Links ##

* [QuantEcon](https://quantecon.org)
* [Notes on Machine Learning & Artificial Intelligence](https://chrisalbon.com) by Chris Albon

## Books ##

* The Master Algorithm ([Amazon link](https://www.amazon.com/Master-Algorithm-Ultimate-Learning-Machine-ebook/dp/B012271YB2))
* Julia for Data Science ([Amazon link](https://www.amazon.com/Julia-Data-Science-Zacharias-Voulgaris/dp/1634621301))

## Academic Integrity: ##

I do not tolerate academic misconduct, [and neither does the University of Oklahoma](http://integrity.ou.edu/files/nine_things_you_should_know.pdf). I will not hesitate to fail students who do not fully comply with the University's academic misconduct policy. If you find yourself contemplating cheating, plagiarism, or other forms of academic misconduct, please come see me first. Help is available if you are struggling. I want everyone in the class to try their best and to do their own work. Please be advised that I reserve the right to utilize anti-plagiarism resources such as TurnItIn when grading assignments.

## Reasonable Accommodations for Students with Disabilities: ##

If a student requires an accommodation based on disability, the student should meet with me in my office during the first week of the semester. Student responsibility primarily rests with informing faculty at the beginning of the semester and in providing authorized documentation through designated administrative channels. The Disability Resource Center is located in Goddard Hall (405-325-3852).
