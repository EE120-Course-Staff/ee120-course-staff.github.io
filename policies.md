---
layout: page
title: Policies
nav_order: 2
description: >-
    Course policies and information.
---

{%- if site.under_construction -%}
<p class="warning">
This site is under construction. All dates and policies are tentative until this message goes away.
</p>
{%- endif -%}

# Policies
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

<!-----

Yay, no errors, warnings, or alerts!

Conversion time: 0.854 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β34
* Tue Jan 17 2023 10:48:16 GMT-0800 (PST)
* Source doc: Syllabus
----->

## Berkeley Honor Code
“As a member of the UC Berkeley community, I act with honesty, integrity, and respect
for others.”

## Tentative List of Topics

Over the course of the semester, we plan to cover the following topics (in this general order):
1. Signal and system representations
2. LTI systems, convolution, correlation
3. Continous and Discrete Fourier Transforms
4. 2D Fourier Transform and filtering
5. Sampling in 1D and 2D, the Nyquist Sampling Theorem, and interpolation
6. Deconvolution and image processing
7. Laplace and Z Transform

<!-- 1. DT signals: Impulse and step functions in discrete time
2. Linearity, time-invariance, DT-LTI properties, convolution, LCCDE and block diagrams:
Delay-Adder-Gain (DAG) blocks
3. Complex exponentials, eigenfunctions of LTI systems, frequency response, plots of
magnitude and phase response
4. BIBO stability, causality, state-space representation
5. CT signals: Dirac Delta, CT-LTI systems, frequency response, BIBO stability, LCCDE and
block diagrams: Integrate-Adder-Gain (IAG) blocks, feedback systems
6. Vector space representation basics: gentle introduction to Hilbert space of functions
7. Fourier analysis for DT and CT for periodic (FS) and aperiodic (FT) signals: stress vector
space viewpoint, FFT and time-frequency uncertainty theorem
8. Sampling theorem: bridging CT and DT; reconstruction, interpolation, oversampling,
subsampling, gentle introduction to multi-rate processing systems
9. Z transform
10. Laplace transform -->


## Communication

All official course communication will be through Ed and bCourses. We will also maintain the course website for your convenience.

To contact staff admin directly, please send an email through bCourses to Professor Liu and both head TAs.

## Gradescope

All assignments will be submitted through Gradescope.


## Lecture

**Time**: Mon/Wed 12:00pm - 2:00pm

**Location**: Genetics and Plant Biology 100

**Recordings**: Lecture recordings will be posted to bCourses and the individual lecture threads on Ed.

**Lecture Threads**: There will be an Ed thread for each lecture where you can ask questions about lecture topics.


## Discussion

There are four discussion sections, all on Friday. **You can attend any discussion time you would like as long as there's enough room for everyone to sit comfortably.**

Discussions will be in-person, but we will post worksheet walkthrough videos after the discussion. Walkthrough videos will be available in the Media Gallery on bCourses. The videos are not a substitute for the active learning that takes place in class. 

We will post the worksheet to bCourses and Ed on Friday mornings.

### Times and Locations

* Hearst Mining 310 @ 11:00am - 12:00pm
* Dwinelle 182 @ 12:00pm - 1:00pm
* Dwinelle 182 @ 1:00pm - 2:00pm
* Cory 289 @ 2:00pm - 3:00pm


### Attendance

Attendance for lecture and discussion is not required. However, you will receive one bonus point (on the scale of 100) if you attend at least one of Professor Liu’s office hours and at least 7 discussions. At Professor Liu’s office hours, you don’t need to ask any technical questions if you don’t have any -- if you wish, you can just simply tell Professor Liu something about yourself and course feedback. If you wish to talk to Professor Liu privately, please schedule separately.

Nevertheless, we highly recommend that you attend lecture and discussion as frequently as possible to stay caught up with the material, and also for the staff to get to know you. At the end of the semester, when we decide on final grades, intense discussions take place about students who fall near grade boundaries. If you're in that situation, it's of potential benefit to you if at least one member of the staff knows you enough to advocate for you and comment on your classroom performance.


**The first discussion is Friday January 26th**.


### COVID Reminder

**If at any time you feel ill or need to isolate yourself due to close contact with someone who tests positive for COVID, please do NOT come to live lecture or discussion**. You can watch the lecture recordings and discussion walkthrough videos instead, and let us know promptly if you would like further support.


## Homework

To enhance and gauge your fluency with the course content, we will have two types of homework assignments: problem sets and labs ([Jupyter notebook](https://jupyter.org/)-based coding assignments). You can expect **approximately one problem set per week**, and **five labs** throughout the semester.


### Problem Set Logistics

**Release**: Problem sets will typically be released on Fridays via bCourses. We will also announce on Ed when problem sets are released.

**Submission**: Problem sets will be due the following **Friday at 11:59pm, with a two day grace period until Sunday at 11:59pm (see the grace period section below)** (you have **one week** to complete the assignment).

You will submit your work through **Gradescope**. You have several options for scanning and submitting your work:

1. Print out the homework document and write your solutions on the printout. Then upload a PDF file of the scan.
2. Write your solutions on this PDF file using a tablet device. Then upload a PDF file.
3. Use your own sheets of paper, but demarcate clearly the space for each problem, part, and subpart. You must not exceed the amount of space allotted in this official problem set document. Then upload a PDF file.

**The first problem set will be released on Wednesday Jan 17th and will be due on Wednesday Jan 24th at 11:59pm, with a two day grace period until Friday at 11:59pm**

### Lab Logistics

Labs are interactive assignments that utilize Jupyter notebooks, an interactive web-based tool for running Python code. Labs provide an opportunity to see real-world applications of EE 120 material.

**Release**: Typically, labs will be released on **Fridays via Ed**. They will be released on **Datahub**, an online platform for running Jupyter notebooks; we will provide a Datahub link for each lab.

We will also provide zip files of lab materials via bCourses if you want to work locally. Please note that we will have limited support for technical issues that arise while running labs locally.

**Submission**:

1. Run all cells before the grader.export() cell
2. Save the notebook (ctrl-s or cmd-s should work)
3. Run the grader.export() cell
4. Download the zip file produced by grader.export()
5. Upload the zip file to the Gradescope.

As we cannot avoid releasing problem sets and labs in concurrent weeks, labs will be due **two weeks after they are released, on Friday at 11:59pm, with a two day grace period until Sunday at 11:59pm.**


**Notes on Autograding**:

* You will be able to see whether you passed the public tests, but not your full score, directly after the autograder finishes running.
* **If tests pass locally but not on Gradescope:**
    * _Double-check that you saved the notebook._
    * _Make sure you did not add any print statements that we did not ask you to add. This interferes with the autograder._
    * Due to a bug, you might see "Failed Tests: Public Tests" in red on the right-hand side of the screen. **Disregard this; you're fine as long as you see "All test cases passed!" for each public test** on the autograder output.
* There may be private tests. You will not see your grade for the private tests until after scores are released. _We will, however, do our best to make public tests comprehensive._
* We'll release full autograder scores during the week after the lab is due.

### Weekly Check-ins

Each week, we will release a Gradescope assignment with five multiple choice or True-False questions covering the content for the week. You are responsible for filling out the check-in form by the end of the weekend. These check-in forms will be autograded, and you will receive immediate feedback. While these will not count for course points, they are an important way for course staff to gauge how well the material is being understood, and they give us a chance to catch misconceptions early. Participation in these check-ins may be taken into consideration when bumping students on grade boundaries.


### Drops

**We will automatically drop the two lowest problem set scores and the lowest lab score from your final grade**. Note that these drops are provided in case of emergencies such as illnesses.


### Grace Period

Although problem sets and labs are due on Fridays, **you can submit, with no penalty, each of your assignments (problem sets and labs) until the following Sunday at 11:59pm, two days after the official due date of that assignment**. This comes with two important caveats:

1. Staff support will be limited during the grace period.
2. Barring exceptional circumstances and DSP accommodations, we will not be accepting any late assignments (_i.e._, they will automatically earn a 0).


### Collaboration

We encourage you to collaborate with up to five other current EE 120 students on each assignment, but each person must submit their own work. For problem sets, please write down the names of your collaborators on the appropriate location on the first page of the assignment. You need not indicate your collaborators for labs.


## Self-Grades

You will self-grade your problem sets. Labs will have both autograded and self-graded components. **_Warning: Not submitting a self-grade will result in a 0 on the corresponding self-graded portion of the assignment._**

As assignments exist to encourage learning, not to punish small mistakes, the self-graded portion of each assignment will be scaled up by 1.25 and capped out at full credit. This means an 8/10 on a self-grade will be scaled up to a 10/10.

We do accept late self-grades for up to two days after grace period. However, for each day past the grace period, 10% will be deducted from the self-grade after the 1.25 scaling, up to two days. Barring exceptional circumstances and DSP accommodations, self-grades will not be accepted past that point.

The purpose of the self-grade assignments strategy is to encourage you to look over the solutions and use it to check your answers.  We hope it offers a chance to self-assess your understanding of the class content to prepare better for exams. As an oversight measure against inflationary self-grading, we conduct random checks at our discretion, and without notice.


### Timeline

Self grades will be released, along with assignment solutions, when the grace period for the assignment ends. **Self grades will be due typically one week after the assignment was due on the following Friday at 11:59pm, with a two day grace period until the following Sunday at 11:59pm.**


### Instructions

1. When we release solutions for each assignment, we will post a link to a form in which you can input your self grades. You can find this link on the “Solutions Released” Ed post.
    1. This form produces a JSON file, which you will then upload to gradescope.
    2. For transparency, we will release the number of points associated with each problem. This should not influence your self grades.
2. Using the rubric below, give each problem a score from the choices and input your scores into the form. If you give yourself a 2, 5, or 8 for any subpart, provide reasoning why you gave yourself that score.
3. Download the file generated by pressing the button at the bottom of the form, and upload that file to the self-grade assignment on Gradescope.
    3. Ensure that the autograder runs properly. Contact course staff through a private post on Ed if you are having issues.
4. In the week after self grades are due, we will check a subset of self-graded problems.
    4. If there is a **large discrepancy** found between your self grade and the course staff-determined score, you run the risk of having that homework rescored, and having your other self grades reviewed as well.


### Rubric

* 0: Didn't attempt or very wrong
* 2: Got started and made some progress, but went off in the wrong direction or with no clear direction
* 5: Right direction and got halfway there
* 8: Mostly right but a minor thing missing or wrong
* 10: 100% correct, with full effort and work shown. Complete work must be shown for full credit!

**Note: If you give yourself a 2, 5, or 8 for any subpart, provide reasoning why you gave yourself that score.**

## Office Hours
Office hour times and locations are also available on the Calendar page of the course website. We have a combination of in-person and remote options: each office hour will have a room number, Zoom link, or both listed.

* Professor Chunlei Liu, Monday 3-4 PM
* TBA

## Homework Party
We offer homework party on TBA where you can ask questions about the problem sets and labs. The location and Zoom information is listed on the Calendar page of the website. Typically, two TAs will staff homework party each week.


## Exams

We will have 3 midterms and no final this semester. These midterms will be held remotely during class time on the following dates:

**Midterm 1 Exam Date:** Wednesday February 21st

**Midterm 2 Exam Date:** Wednesday March 20th

**Midterm 3 Exam Date:** Wednesday April 24th

### Exam Policy

Before the exam, we will post an answer template on bCourses, and we will post the exam questions once the exam period starts.
* You are responsible for printing out the answer sheet and filling out the honor code before the exam begins.
* If printing is non-trivial, you may either use a tablet to fill in the answer sheet OR use loose paper provided that you use roughly the same space as provided on the exam booklet.
* If you encounter technical issues during scanning or submitting your solutions, you need to alert the head TAs before the due time and take pictures of all your solutions to prove that you have finished the quiz or exam on time.

Late submissions: If a submission is late by $n$ minutes ($n \le 5$) for a quiz that has a normal duration of $N$ minutes (e.g. $N = 90$ for midterms), a penalty of $\frac{3n}{N}$ will be applied to the score of the particular exam. Any late submission exceeding five minutes will not be graded and a score of zero will be applied automatically. If Gradescope submission fails, email your solution to the head TA. This policy still applies to emailed solutions.

Exams will be open-book and open-notes (including digital books and notes). However, no internet (except for bCourses, Gradescope, and the course website) nor software use is permitted unless stated otherwise. You may not collaborate in any way with other students on exams. No public posts are allowed.

DSP students will start exams at the same time as other students, but will be allowed to submit to Gradescope late based on their time accommodation.

We will release more exam logistics in Ed posts before each exam.

## Grading

* **Midterms**: 25% each (75% total)
* **Problem Sets**: 15% (We drop the two lowest scores)
* **Labs**: 10% (We drop the lowest score)


## Optional Course Materials

There is no official textbook or set of course notes for EE 120. EE 120 is a self-contained course in that the lecture notes, lectures, discussions, and labs contain all of the material you are responsible for knowing. However, if you would like additional information beyond what is covered in lectures, homeworks, and labs, you can look at these two textbooks:



* [Signals and Systems by Oppenheim and Willsky](https://eee.guc.edu.eg/Courses/Communications/COMM401%20Signal%20&%20System%20Theory/Alan%20V.%20Oppenheim,%20Alan%20S.%20Willsky,%20with%20S.%20Hamid-Signals%20and%20Systems-Prentice%20Hall%20(1996).pdf)
* [Signals and Systems, Theory and Applications by Fawwaz T. Ulaby, Andrew E. Yagle](https://ss2.eecs.umich.edu)
* [Signals and Systems by Hwei P Hsu](https://electronicsbookcafe.files.wordpress.com/2015/08/signals-and-systems-2nd-edition-schaums-outline-series-hwei-hsu.pdf)

As a disclaimer, EE 120 does not directly follow these textbooks, so they will differ from the course material in terms of content, emphasis, notation, scope, and order. We provide associated readings for each lecture, but these do not necessarily directly correspond to the topic being taught. Nothing is a substitute for attending lecture and discussion, and watching (and rewatching) the videos. 