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

## Tentative List of Topics

Over the course of the semester, we plan to cover the following topics (in this general order):
1. DT signals: Impulse and step functions in discrete time
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
10. Laplace transform


## Communication

All official course communication will be through Ed and bCourses. We will also maintain the course website for your convenience.

You may contact the staff at **[ee120-fa23-admin@lists.berkeley.edu](mailto:ee120-fa23-admin@lists.berkeley.edu)**. This reaches both head TAs and Professor Ramchandran.

## Gradescope

All assignments will be submitted through Gradescope. The code to join can be found on Ed.


## Lecture

**Time**: Mon/Wed 3-5pm

**Location**: Physics Building 4 (directly east of the Campanile; the room should be near the entrance to the building)

**Recordings**: Lecture recordings will be posted to the course website and the individual lecture threads on Ed. However, we reserve the right to withhold recordings if lecture attendance is too low.

**Lecture Threads**: There will be an Ed thread for each lecture where you can ask questions about lecture topics.


## Discussion

There are 4 discussion sections, all on Friday. **You can attend any discussion time you would like as long as there's enough room for everyone to sit comfortably.**

Discussions will be in-person, but we will post worksheet walkthrough videos after the discussion. Walkthrough videos will be available in the Media Gallery on bCourses. The videos are not a substitute for the active learning that takes place in class. 

We will post the worksheet to bCourses and Ed on Friday mornings.

### Times and Locations

* Fri 10-11am in Cory 540AB
* Fri 1-2pm in Wheeler 130
* Fri 2-3pm in Evans 3
* Fri 3-4pm in Evans 3

### Attendance

Attendance for lecture and discussion is not required. However, if you attend at least 7 discussions, **we will add 1% to your final grade**.

Nevertheless, we highly recommend that you attend lecture and discussion as frequently as possible to stay caught up with the material, and also for the staff to get to know you. At the end of the semester, when we decide on final grades, intense discussions take place about students who fall near grade boundaries. If you're in that situation, it's of potential benefit to you if at least one member of the staff knows you enough to advocate for you and comment on your classroom performance. 


**The first discussion is Friday, September 1st**.


### COVID Reminder

**If at any time you feel ill or need to isolate yourself due to close contact with someone who tests positive for COVID, please do NOT come to live lecture or discussion**. You can watch the lecture recordings and discussion walkthrough videos instead, and let us know promptly if you would like further support.


## Homework

To enhance and gauge your fluency with the course content, we will have two types of homework assignments: problem sets and labs ([Jupyter notebook](https://jupyter.org/)-based coding assignments). You can expect **approximately one problem set per week**, and **six labs** throughout the semester.


### Problem Set Logistics

**Release**: Problem sets will typically be released on **Tuesdays** via bCourses. We will also announce on Ed when problem sets are released.

**Submission**: Problem sets will be due the following **Monday at 11:59pm, with a 24hr grace period until Tuesday at 11:59pm (see the grace period section below)** (you have **one week** to complete the assignment).

You will submit your work through **Gradescope**. You have several options for scanning and submitting your work:

1. Print out the homework document and write your solutions on the printout. Then upload a PDF file of the scan.
2. Write your solutions on this PDF file using a tablet device. Then upload a PDF file.
3. Use your own sheets of paper, but demarcate clearly the space for each problem, part, and subpart. You must not exceed the amount of space allotted in this official problem set document. Then upload a PDF file.


### Lab Logistics

Labs are interactive assignments that utilize Jupyter notebooks, an interactive web-based tool for running Python code. Labs provide an opportunity to see real-world applications of EE 120 material.

**Release**: Typically, labs will be released on **Fridays via Ed**. They will be released on **Datahub**, an online platform for running Jupyter notebooks; we will provide a Datahub link for each lab.

We will also provide .zip files of lab materials via bCourses if you want to work locally. Please note that we will have limited support for technical issues that arise while running labs locally.

**Submission**:

1. Run all cells before the grader.export() cell
2. Save the notebook (ctrl-s or cmd-s should work)
3. Run the grader.export() cell
4. Download the zip file produced by grader.export()
5. Upload the zip file to the Gradescope.

As we cannot avoid releasing problem sets and labs in concurrent weeks, labs will be due **two weeks after they are released, on Thursday at 11:59pm, with a 24hr grace period until Friday at 11:59pm.**

**Notes on Autograding**:



* You will be able to see whether you passed the public tests, but not your full score, directly after the autograder finishes running.
* **If tests pass locally but not on Gradescope:**
    * _Double-check that you saved the notebook._
    * _Make sure you did not add any print statements that we did not ask you to add. This interferes with the autograder._
    * Due to a bug, you might see "Failed Tests: Public Tests" in red on the right-hand side of the screen. **Disregard this; you're fine as long as you see "All test cases passed!" for each public test** on the autograder output.
* There may be private tests. You will not see your grade for the private tests until after scores are released. _We will, however, do our best to make public tests comprehensive._
* We'll release full autograder scores during the week after the lab is due.


### Drops

**We will automatically drop the lowest problem set score and the lowest lab score, excluding lab 5, from your final grade**. There will be a chance to get one more problem set drop by filling out the mid-semester feedback form.


### Grace Period

Although problem sets are due on Mondays and labs are due on Thursdays, **you can submit, with no penalty, each of your assignments (problem sets and labs) until 11:59pm, one day after the official due date of that assignment**. This comes with two important caveats:



1. Staff support will be limited during the grace period.
2. Barring exceptional circumstances and DSP accommodations, we will not be accepting any late assignments (_i.e._, they will automatically earn a 0).


### Collaboration

We encourage you to collaborate with up to 5 other current EE 120 students on each assignment, but each person must submit their own work. For problem sets, please write down the names of your collaborators on the appropriate location on the first page of the assignment. You need not indicate your collaborators for labs.


## Self Grades

You will self-grade your problem sets. Labs will have both autograded and self-graded components. **_Warning: Not submitting a self-grade will result in a 0 on the corresponding assignment._**

The purpose of the self-grade assignments strategy is to encourage you to look over the solutions and use it to check your answers.  We hope it offers a chance to self-assess your understanding of the class content to prepare better for exams. As an oversight measure against inflationary self-grading, we conduct random checks at our discretion, and without notice.


### Timeline

Self grades will be released, along with assignment solutions, when the grace period for the assignment ends. **Self grades will be due typically one week after the assignment was due at 11:59pm, with a 24hr grace period until the next day at 11:59pm.** To clarify, problem set self grades will be due on the immediate following Monday at 11:59pm, with a grace period until the following Tuesday at 11:59pm. Lab self grades will be due on the immediate following Thursday at 11:59pm, with a grace period until the following Friday at 11:59pm.


### Instructions



1. When we release solutions for each assignment, we will post a link to a form in which you can input your self grades. You can find this link on the “Solutions Released” Ed post.
    1. This form produces a JSON file, which you will then upload to gradescope.
    2. For transparency, we will release the number of points associated with each problem. This should not influence your self grades.
2. Using the rubric below, give each problem a score from 0 to 5 and input your scores into the form.
3. Download the file generated by pressing the button at the bottom of the form, and upload that file to the self-grade assignment on Gradescope.
    3. Ensure that the autograder runs properly. Contact course staff through a private post on Ed if you are having issues.
4. In the week after self grades are due, we will check a subset of self-graded problems.
    4. If there is a **large discrepancy** found between your self grade and the course staff-determined score, you run the risk of having that homework rescored, and having your other self grades reviewed as well.


### Rubric

* 5: At least 80% of the problem is correct, with full effort and work shown. Complete work must be shown for full credit!
    * For example:
        * You completed 80+% of the sub-parts (if applicable), and each was fully correct, or had minor arithmetic errors that did not impact the form of the final solution.
        * You attempted all of the sub-parts, and your work was almost fully correct with minor errors.

* 4: At least 60% … 
    * Your work was in the right direction, but missing one or a few critical steps.

* 3: At least 40% … 
    * You made about half (or a little less) of the progress required for a correct solution.

* 2: At least 20% … 
    * You made initial progress but proceeded in the wrong direction.

* 1: At least 5% …
    * Minimal progress; almost fully incorrect.

* 0: Blank or did not attempt.

## Office Hours
Office hour times and locations are available on the Calendar page of the course website. We have a combination of in-person and remote options: each office hour will have a room number, Zoom link, or both listed.

## Homework Party
We offer a two-hour homework party on TBD from TBD where you can ask questions about the problem sets and labs. The location and Zoom information is listed on the Calendar page of the website. Typically, two TAs will staff homework party each week.


## Exams

We will have 2 midterms and 1 final this semester.

**Midterm Exam Dates:** Thursday September 28th @ 7-9pm and Thursday November 2nd @ 7-9pm

**Final Exam Date:** Tuesday December 12th @ 7-10pm

We will release more exam logistics in Ed posts before each exam.


### Clobber
We will be using a clobber policy where your final can replace your grade for either MT1 or MT2, but not both. Your lower midterm score in terms of z-score will be clobbered by the final based on z-score, allowing you to miss a midterm.

## Grading

* **Midterms**: 20% each (40% total)
* **Final**: 35%
* **Labs**: 10% (We drop the lowest score)
* **Problem Sets**: 15% (We drop the lowest score)


## Optional Course Materials

There is no official textbook or set of course notes for EE120. However, if you would like additional information beyond what is covered in lectures, homeworks, and labs, you can look at these two textbooks:



* [Signals and Systems by Hwei P Hsu](https://electronicsbookcafe.files.wordpress.com/2015/08/signals-and-systems-2nd-edition-schaums-outline-series-hwei-hsu.pdf)
* [Signals and Systems by Oppenheim and Willsky](https://eee.guc.edu.eg/Courses/Communications/COMM401%20Signal%20&%20System%20Theory/Alan%20V.%20Oppenheim,%20Alan%20S.%20Willsky,%20with%20S.%20Hamid-Signals%20and%20Systems-Prentice%20Hall%20(1996).pdf)

As a disclaimer, EE 120 does not directly follow these textbooks, so they will differ from the course material in terms of content, emphasis, notation, scope, and order. We provide associated readings for each lecture, but these do not necessarily directly correspond to the topic being taught. Nothing is a substitute for attending lecture and discussion, and watching (and rewatching) the videos. 
