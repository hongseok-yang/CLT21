# CS492(F), Computational Learning Theory, Fall 2021, KAIST

This is a webpage of the course "CS492(F) Computational Learning Theory", which is offered at the KAIST CS department in the fall of 2021. The webpage will contain links to course-related materials and announcements.

The goal of this course is to expose students to the mathematical techniques for proving the guarantees of machine-learning algorithms. The main theme of the course is to find a mathematical guarantee of inductive generalisation used by machine learning algorithms: when a learning algorithm returns a classifier based on a given training data, what can we say about the real error of the classifier mathematically? We will study concepts designed to measure the complexity of the hypothesis space considered by a machine learning algorithm, such as Rademacher complexity, growth function and VC dimension, and discuss mathematical techniques for assessing the qualities of inductive generalisations used by different machine learning algorithms.

The course will be highly mathematical. Explaining lemmas, propositions and theorems and their proofs will form the main part of each lecture. We use multiple mathematical tools, such as concentration inequalities and Fenchel duality, throughout the course. We assume that students do not have any issue in understanding complex mathematical formalisms and proofs, and can construct proofs.

This course is not about state-of-the-art machine learning algorithms and popular recent deep learning models. It is more about well-developed mathematical foundations, which deal mostly with basic traditional machine learning algorithms and concepts. So, if a student is interested in deep learning or other fashionable machine-learning techniques, we advise the student to take a different course targeted at such topics.

## 1. Important Announcements

#### [28 August] Policy for handling late submissions.

We will adopt the following scheme for handling late submissions for homework assignments and two reports for the critical-survey assignment. The scheme assumes that the total marks are 100.

1. <= One day late (by the midnight of the next day): -10
2. <= Two days late: -20
3. <= Three days late: -30
4. <= Four days late: -40
5. More than four days late: -100.

#### [28 August] Honour code.

We adopt a very strict policy for handling dishonest behaviours. If a student is found to copy answers from peers or other sources in her or his submission for any assignment, he or she will get F.

## 2. Logistics

#### Evaluation

* Homework (40%). Final exam (40%). Critical survey (20%).

#### Teaching Staffs

* Lecturer: [Prof Hongseok Yang](https://cs.kaist.ac.kr/people/view?idx=552&kind=faculty&menu=160) (email: hongseok00@gmail.com, office hour: 6:00pm - 7:00pm Monday in ZOOM. You can find more information about it in KLMS.)
* TA: Sangho Lim (email: lim.sang@kaist.ac.kr, office hour: to be announced. You can find more information about it in KLMS.)

#### Place and Time

* Place: ZOOM.
* Lectures: 9:00am - 10:15am on Tuesday and Thursday.

#### Online Discussion

* We will use KLMS.

## 3. Homework

## 4. Tentative Plan

For each chapter we cover in the course, except the last, we plan to have one Q&A session where we discuss questions from students and solve exercise problems in the textbook together. However, if we are far behind the schedule, we may skip some of these Q&A sessions.

* 08/31(Tue) - Introduction ([video](https://youtu.be/Lpks1MCvIv0), [note](https://github.com/hongseok-yang/CLT21/blob/master/Lectures/Lecture1/CLT21-L1-Introduction.pdf), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L1/L1-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L1/L1-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L1/L1-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L1/L1-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L1/L1-board5.png), [board6](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L1/L1-board6.png), [board7](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L1/L1-board7.png)). 
* 09/02(Thu) - The PAC learning framework (Ch2). ([video](https://youtu.be/Y9U7eu6zFx8), [note](https://github.com/hongseok-yang/CLT21/blob/master/Lectures/Lecture2/CLT21-L2-PAC.pdf), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L2/L2-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L2/L2-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L2/L2-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L2/L2-board4.png)).
* 09/07(Tue) - The PAC learning framework (Ch2). ([video](https://youtu.be/Y9U7eu6zFx8), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L3/L3-board1.pdf), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L3/L3-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L3/L3-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L3/L3-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L3/L3-board5.png), [board6](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L3/L3-board6.png), [board7](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L3/L3-board7.png)).
* 09/09(Thu) - __**[Q&A]**__ The PAC learning framework (Ch2).
* 09/14(Tue) - Rademacher complexity and VC dimension (Ch3).
* 09/16(Thu) - Rademacher complexity and VC dimension (Ch3).
* 09/21(Tue) - __**NO ZOOM MEETING.**__ National holiday (Chuseok).
* 09/23(Thu) - Rademacher complexity and VC dimension (Ch3).
* 09/28(Tue) - __**[Q&A]**__ Rademacher complexity and VC dimension (Ch3).
* 09/30(Thu) - Model selection (Ch4).
* 10/05(Tue) - Model selection (Ch4).
* 10/07(Thu) - __**[Q&A]**__ Model selection (Ch4).
* 10/12(Tue) - Support vector machine (Ch5).
* 10/14(Thu) - Support vector machine (Ch5).
* 10/19(Tue), 10/21(Thu) - __**NO ZOOM MEETING.**__ Midterm exam period.
* 10/26(Tue) - Support vector machine (Ch5).
* 10/28(Thu) - __**[Q&A]**__ Support vector machine (Ch5).
* 11/02(Tue) - Kernel methods (Ch6).
* 11/04(Thu) - Kernel methods (Ch6).
* 11/09(Tue) - Kernel methods (Ch6).
* 11/11(Thu) - __**[Q&A]**__ Kernel methods (Ch6).
* 11/16(Tue) - Regression (Ch11).
* 11/18(Thu) - Regression (Ch11).
* 11/23(Tue) - Regression (Ch11).
* 11/25(Thu) - __**[Q&A]**__ Regression (Ch11).
* 11/30(Tue) - Maximum entropy models (Ch12).
* 12/02(Thu) - __**NO ZOOM MEETING.**__ Undergraduate interview.
* 12/07(Thu) - Maximum entropy models (Ch12).
* 12/09(Thu) - Maximum entropy models (Ch12).
* 12/14(Thu), 12/16(Thu) - __**NO ZOOM MEETING.**__ Final exam period.

## 5. Critical Survey

One important part of this course is to do an in-depth self study on a research-level topic on a theoretical aspect of machine learning, and write a survey article on the topic. The task accounts for the 20% of the total marks of this course. It consists of two reports, a proposal on what and how a student will study and a final survey that describes what the student learns from the study. In order to get full marks, a student has to show in his or her write-up that she or he has understood the chosen topic well, carried out in-depth study on the topic, and thought hard and originally about it. Our evaluation adopts the following criterion: the clarity of writing (20%), the level of understanding a topic and existing work about it (60%), and the demonstration of original thoughts and insights (20%). Here are the details of this assignment.

1. Task description.
   * Select a paper in COLT'18, COLT'19, COLT'20, and COLT'21, study a research topic or a problem of the paper, and write a survey on the topic. We encourage the students to go beyond a simple summary of the results of the paper, and write an in-depth and comprehensive survey on the topic itself. Ideally, the survey explains the background and importance of the topic, the existing results about it, and the contribution of the paper, and describes the student's view on why or why not the results of the paper are significant. Looking at the related-work section of the paper will help a student to navigate the existing literature. COLT is one of the best international conferences on the theoretical aspect of machine learning.

2. Two reports to submit.
   1. Proposal.
      * Description about which paper a student picks and why, and also about how the student plans to complete this survey-writing project, such as what other papers to look at and what questions to think about while writing the survey.
      * Deadline: __**23:59 of the 29th of October in 2021 (Friday). Submit in KLMS.**__
      * Maximum 1 page not including bibliography.
      * 5% of the total marks of the course.
   2. Final survey.
      * Deadline: __**23:59 of the 3rd of December in 2021 (Friday). Submit in KLMS.**__
      * Maximum 4 pages not including bibliography.
      * 15% of the total marks of the course.

3. Warning on plagiarism.
   * A student should not copy texts from other sources in her or his report. If the student has to use such texts, he or she has to rephrase them in her or his own words and state the source of those texts explicitly. Ideally, a student's write-up should mostly consist of the student's own phrases and expressions, and use such borrowed and rephrased sentences only when they are absolutely needed. Copying texts from other sources is an instance of plagiarism, and if it happens to an academic, it can destroy his or her research career. If a student is found to plagiarise, he or she will get F.

## 6. Study Materials

We will closely follow the textbook "Foundations of Machine Learning" (second edition) by Mohri, Rostamizadeh, and Talwalkar. The webpage of the textbook contains many useful materials, including the HTML version of the book and the list of typos.

* Main Textbook: [Foundations of Machine Learning (2nd edition)](https://cs.nyu.edu/~mohri/mlbook/).

