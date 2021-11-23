# CS492(F), Computational Learning Theory, Fall 2021, KAIST

This is a webpage of the course "CS492(F) Computational Learning Theory", which is offered at the KAIST CS department in the fall of 2021. The webpage will contain links to course-related materials and announcements.

The goal of this course is to expose students to the mathematical techniques for proving the guarantees of machine-learning algorithms. The main theme of the course is to find a mathematical guarantee of inductive generalisation used by machine learning algorithms: when a learning algorithm returns a classifier based on a given training data, what can we say about the real error of the classifier mathematically? We will study concepts designed to measure the complexity of the hypothesis space considered by a machine learning algorithm, such as Rademacher complexity, growth function and VC dimension, and discuss mathematical techniques for assessing the qualities of inductive generalisations used by different machine learning algorithms.

The course will be highly mathematical. Explaining lemmas, propositions and theorems and their proofs will form the main part of each lecture. We use multiple mathematical tools, such as concentration inequalities and Fenchel duality, throughout the course. We assume that students do not have any issue in understanding complex mathematical formalisms and proofs, and can construct proofs.

This course is not about state-of-the-art machine learning algorithms and popular recent deep learning models. It is more about well-developed mathematical foundations, which deal mostly with basic traditional machine learning algorithms and concepts. So, if a student is interested in deep learning or other fashionable machine-learning techniques, we advise the student to take a different course targeted at such topics.

## 1. Important Announcements

#### [23 November] Final exam.

The final exam will be a take-home exam. Here is information about it.

1. The exam paper will be available at 9:00am on the 14th of December (Tuesday), and students will be given 24 hours to prepare their answers. That is, the deadline is 9:00am on the 15th of December (Wednesday). No late submissions will be accepted.
2. Questions will be based on Chapters 6 and 11.
3. As in other homework submissions, we will adopt a very strict policy for handling dishonest behaviours. If a student is found to violate the honour code, he or she will get F. Also, because of the new rule in the department, we will have to report the case to the department.

#### [8 November] [Homework2](https://github.com/hongseok-yang/CLT21/blob/master/Homework/homework2.pdf) is out.
The homework assignment 2 is out. Submit your solutions in KLMS by 6:00pm on 24 November 2021 (Wednesday).

We remind the students that we adopt a very strict policy for handling dishonest behaviours. If a student is found to copy answers from peers or other sources in her or his submission for this homework assignment, he or she will get F.

#### [2 October] [Homework1](https://github.com/hongseok-yang/CLT21/blob/master/Homework/homework1.pdf) is out.

The homework assignment 1 is out. Submit your solutions in KLMS by 6:00pm on 15 October 2021 (Friday).

We remind the students that we adopt a very strict policy for handling dishonest behaviours. If a student is found to copy answers from peers or other sources in her or his submission for this homework assignment, he or she will get F.

#### [16 September] No lecture on 23 September.

Following the university's policy related to COVID-19, we will cancel our online class on 23 September.

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
* TA: Sangho Lim (email: lim.sang@kaist.ac.kr, office hour: 6:00pm - 7:00pm Tuesday in ZOOM. You can find more information about it in KLMS.)

#### Place and Time

* Place: ZOOM.
* Lectures: 9:00am - 10:15am on Tuesday and Thursday.

#### Online Discussion

* We will use KLMS.

## 3. Homework

Submit your solutions in KLMS. We will create submission folders for all the homework assignments in KLMS.

* [Homework2](https://github.com/hongseok-yang/CLT21/blob/master/Homework/homework2.pdf) - Deadline: 6:00pm on 24 November 2021 (Wednesday).
* [Homework1](https://github.com/hongseok-yang/CLT21/blob/master/Homework/homework1.pdf) - Deadline: 6:00pm on 15 October 2021 (Friday).

## 4. Tentative Plan

For each chapter we cover in the course, except the last, we plan to have one Q&A session where we discuss questions from students and solve exercise problems in the textbook together. However, if we are far behind the schedule, we may skip some of these Q&A sessions.

* 08/31(Tue) - Introduction ([video](https://youtu.be/Lpks1MCvIv0), [note](https://github.com/hongseok-yang/CLT21/blob/master/Lectures/Lecture1/CLT21-L1-Introduction.pdf), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L1/L1-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L1/L1-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L1/L1-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L1/L1-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L1/L1-board5.png), [board6](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L1/L1-board6.png), [board7](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L1/L1-board7.png)). 
* 09/02(Thu) - The PAC learning framework (Ch2). ([video](https://youtu.be/Y9U7eu6zFx8), [note](https://github.com/hongseok-yang/CLT21/blob/master/Lectures/Lecture2/CLT21-L2-PAC.pdf), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L2/L2-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L2/L2-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L2/L2-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L2/L2-board4.png)).
* 09/07(Tue) - The PAC learning framework (Ch2). ([video](https://youtu.be/Wj13XVwpVbA), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L3/L3-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L3/L3-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L3/L3-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L3/L3-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L3/L3-board5.png), [board6](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L3/L3-board6.png), [board7](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L3/L3-board7.png)).
* 09/09(Thu) - __**[Q&A]**__ The PAC learning framework (Ch2). ([video](https://youtu.be/sDDFNAC-Vso), [note](https://github.com/hongseok-yang/CLT21/blob/master/Lectures/Lecture2/CLT21-L2-PAC-exercises.pdf), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L4/L4-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L4/L4-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L4/L4-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L4/L4-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L4/L4-board5.png), [board6](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L4/L4-board6.png)).
* 09/14(Tue) - Rademacher complexity and VC dimension (Ch3). ([video](https://youtu.be/3t5HS5ppG6A), [note](https://github.com/hongseok-yang/CLT21/blob/master/Lectures/Lecture3/CLT21-L3-Rademacher.pdf), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L5/L5-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L5/L5-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L5/L5-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L5/L5-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L5/L5-board5.png)).
* 09/16(Thu) - Rademacher complexity and VC dimension (Ch3). ([video](https://youtu.be/TtNP8pmDiRM), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L6/L6-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L6/L6-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L6/L6-board3.png)).
* 09/21(Tue) - __**NO ZOOM MEETING.**__ National holiday (Chuseok).
* 09/23(Thu) - __**NO ZOOM MEETING.**__ Due to the university's action on COVID-19.
* 09/28(Tue) - Rademacher complexity and VC dimension (Ch3). ([video](https://youtu.be/o5cSywRACUI)).
* 09/30(Thu) - __**[Q&A]**__ Rademacher complexity and VC dimension (Ch3). ([video](https://youtu.be/NhJKwmvM--k), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L8/L8-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L8/L8-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L8/L8-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L8/L8-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L8/L8-board5.png)).
* 10/05(Tue) - Model selection (Ch4). ([video](https://youtu.be/mI0W8tiERfA), [note](https://github.com/hongseok-yang/CLT21/blob/master/Lectures/Lecture4/CLT21-L4-ModelSelection.pdf), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L9/L9-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L9/L9-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L9/L9-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L9/L9-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L9/L9-board5.png)).
* 10/07(Thu) - Model selection (Ch4). ([video](https://youtu.be/0wopM8uM5JA)).
* 10/12(Tue) - Model selection (Ch4). ([video](https://youtu.be/_xRvICGvg5s), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L11/L11-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L11/L11-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L11/L11-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L11/L11-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L11/L11-board5.png)).
* 10/14(Thu) - __**[Q&A]**__ Model selection (Ch4). ([video](https://youtu.be/7huA2BF-tgs), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L12/L12-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L12/L12-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L12/L12-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L12/L12-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L12/L12-board5.png)).
* 10/19(Tue), 10/21(Thu) - __**NO ZOOM MEETING.**__ Midterm exam period.
* 10/26(Tue) - Support vector machine (Ch5). ([video](https://youtu.be/kWiexRg4kF4), [note](https://github.com/hongseok-yang/CLT21/blob/master/Lectures/Lecture5/CLT21-L5-SVM.pdf), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L13/L13-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L13/L13-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L13/L13-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L13/L13-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L13/L13-board5.png)).
* 10/28(Thu) - Support vector machine (Ch5). ([video](https://youtu.be/6CuzWJ9eonY), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L14/L14-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L14/L14-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L14/L14-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L14/L14-board4.png))
* 11/02(Tue) - Support vector machine (Ch5). ([video](https://youtu.be/yR4fAj5oV2Y)).
* 11/04(Thu) - __**[Q&A]**__ Support vector machine (Ch5). ([video](https://youtu.be/mpvRkcz5nio), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L16/L16-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L16/L16-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L16/L16-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L16/L16-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L16/L16-board5.png))
* 11/09(Tue) - Kernel methods (Ch6). ([video](https://youtu.be/kTZNtfNLuI0), [note](https://github.com/hongseok-yang/CLT21/blob/master/Lectures/Lecture6/CLT21-L6-Kernel.pdf), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L17/L17-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L17/L17-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L17/L17-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L17/L17-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L17/L17-board5.png))
* 11/11(Thu) - Kernel methods (Ch6). ([video](https://youtu.be/Tr2WCRdchLg), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L18/L18-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L18/L18-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L18/L18-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L18/L18-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L18/L18-board5.png), [board6](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L18/L18-board6.png))
* 11/16(Tue) - Kernel methods (Ch6). ([video](https://youtu.be/fy4jKFlNQeI), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L19/L19-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L19/L19-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L19/L19-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L19/L19-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L19/L19-board5.png), [board6](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L19/L19-board6.png))
* 11/18(Thu) - __**[Q&A]**__ Kernel methods (Ch6). ([video](https://youtu.be/7as0DWn60ac), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L20/L20-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L20/L20-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L20/L20-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L20/L20-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L20/L20-board5.png), [board6](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L20/L20-board6.png), [board7](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L20/L20-board7.png))
* 11/23(Tue) - Regression (Ch11). ([video](https://youtu.be/olvYo6pZHug), [board1](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L21/L21-board1.png), [board2](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L21/L21-board2.png), [board3](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L21/L21-board3.png), [board4](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L21/L21-board4.png), [board5](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L21/L21-board5.png), [board6](https://github.com/hongseok-yang/CLT21/blob/master/Whiteboards/L21/L21-board6.png))
* 11/25(Thu) - Regression (Ch11).
* 11/30(Tue) - Regression (Ch11).
* 12/02(Thu) - __**NO ZOOM MEETING.**__ Undergraduate interview.
* 12/07(Thu) - __**[Q&A]**__ Regression (Ch11).
* 12/09(Thu) - Special topic.
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

