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

Over the course of the semester, we tentatively plan to cover the following topics (in this general order):
1. Discrete Time (DT) signals: Impulse and step functions in discrete time
2. Linearity, time-invariance, discrete time linear time invariance (DT-LTI) properties, convolution, LCCDE and block diagrams:
Delay-Adder-Gain (DAG) blocks
3. Complex exponentials, eigenfunctions of LTI systems, frequency response, plots of
magnitude and phase response
4. BIBO stability, causality, state-space representation
5. Continuous time (CT) signals: Dirac Delta, CT-LTI systems, frequency response, BIBO stability, LCCDE and
block diagrams: Integrate-Adder-Gain (IAG) blocks, feedback systems
6. Vector space representation basics: gentle introduction to Hilbert space of functions
7. Fourier analysis for DT and CT for periodic (FS) and aperiodic (FT) signals: stress vector
space viewpoint, FFT and time-frequency uncertainty theorem
8. Sampling theorem: bridging CT and DT; reconstruction, interpolation, oversampling,
subsampling, gentle introduction to multi-rate processing systems
9. Z transform
10. Laplace transform


## Communication

All official course communication will be through Ed and email. BCourses and Gradescope are for resource storage and assignment submission. We will also maintain the course website for your convenience.

To contact staff admin directly (Professor Dimakis and Chaoying), please send an email to [ee120-fa25-admin@lists.berkeley.edu](mailto:ee120-fa25-admin@lists.berkeley.edu).


## Lecture

**Time**: Mon/Wed 2 PM - 4 PM

**Location**: Physics Building 4

**Recordings**: Lecture recordings will be posted to the Media Gallery on bCourses. However, we reserve the right to withold recordings if attendance drops too low.

**Lecture Threads**: There will be an Ed thread for each lecture where you can ask questions about lecture topics.


## Discussion

There are three discussion sections, all on Friday. **You can attend any discussion time you would like as long as there's enough room for everyone to sit comfortably.**

Discussions will be in-person, but we will post worksheet walkthrough videos after the discussion. Walkthrough videos will be available in the Media Gallery on bCourses. The videos are not a substitute for the active learning that takes place in class. 

We will post the worksheet to bCourses and Ed on Friday mornings.

### Times and Locations

* Cory 540AB @ 11:00am - 12:00pm
* Cory 540AB @ 12:00pm - 1:00pm
* Dwinelle 182 @ 1:00pm - 2:00pm


### Attendance

Attendance for discussion is not required. However, you will receive one bonus point (on the scale of 100) if you attend at least 7 discussions.

Nevertheless, we highly recommend that you attend lecture and discussion as frequently as possible to stay caught up with the material, and also for the staff to get to know you. At the end of the semester, when we decide on final grades, intense discussions take place about students who fall near grade boundaries. If you're in that situation, it's of potential benefit to you if at least one member of the staff knows you enough to advocate for you and comment on your classroom performance.


**The first discussion is Friday Jan 31st**.


### COVID Reminder

**If at any time you feel ill or need to isolate yourself due to close contact with someone who tests positive for COVID, please do NOT come to live lecture or discussion**. You can watch the lecture recordings and discussion walkthrough videos instead, and let us know promptly if you would like further support.

## Assignments

All assignments will be submitted through Gradescope. **Students who enroll or join the class late will be expected to keep up with material and will not be provided extra accommodations for this reason alone.**

## Homework

To enhance and gauge your fluency with the course content, we will have two types of homework assignments: problem sets and labs ([Jupyter notebook](https://jupyter.org/)-based coding assignments). You can expect **approximately one problem set per week**, and **five labs** throughout the semester.


### Problem Set Logistics

**Release**: Problem sets will typically be released on Wednesday via bCourses. We will also announce on Ed when problem sets are released.

**Submission**: Problem sets will be due the following **Monday at 11:59pm, with a one day grace period until Tuesday at 11:59pm (see the grace period section below)** (you have **one week** to complete the assignment).

You will submit your work through **Gradescope**. You have several options for scanning and submitting your work:

1. Print out the homework document and write your solutions on the printout. Then upload a PDF file of the scan.
2. Write your solutions on this PDF file using a tablet device. Then upload a PDF file.
3. Use your own sheets of paper, but demarcate clearly the space for each problem, part, and subpart. You must not exceed the amount of space allotted in this official problem set document. Then upload a PDF file.

**The first problem set will be released on Wednesday Aug 27th and will be due on Monday Sep 1st at 11:59pm, with grace period until Tuesday Sep 2nd at 11:59pm.**

### Lab Logistics

Labs are interactive assignments that utilize Jupyter notebooks, an interactive web-based tool for running Python code. Labs provide an opportunity to see real-world applications of EE 120 material.

**Release**: Typically, labs will be released on Saturdays via Ed. They will be released on **Datahub**, an online platform for running Jupyter notebooks; we will provide a Datahub link for each lab.

We will also provide zip files of lab materials via bCourses if you want to work locally. Please note that we will have limited support for technical issues that arise while running labs locally.

**Submission**:

1. Run all cells before the grader.export() cell
2. Save the notebook (ctrl-s or cmd-s should work)
3. Run the grader.export() cell
4. Download the zip file produced by grader.export()
5. Upload the zip file to the Gradescope.

As we cannot avoid releasing problem sets and labs in concurrent weeks, labs will be due **two weeks after they are released, on Thursday at 11:59pm, with a one day grace period until Friday at 11:59pm.**


**Notes on Autograding**:

* You will be able to see whether you passed the public tests, but not your full score, directly after the autograder finishes running.
* **If tests pass locally but not on Gradescope:**
    * _Double-check that you saved the notebook._
    * _Make sure you did not add any print statements that we did not ask you to add. This interferes with the autograder._
    * Due to a bug, you might see "Failed Tests: Public Tests" in red on the right-hand side of the screen. **Disregard this; you're fine as long as you see "All test cases passed!" for each public test** on the autograder output.
* There may be private tests. You will not see your grade for the private tests until after scores are released. _We will, however, do our best to make public tests comprehensive._
* We'll release full autograder scores during the week after the lab is due.

### Drops

**We will automatically drop the lowest problem set score and the lowest lab score from your final grade**. We will also drop an additional problem set score if you fill out the midsemester feedback form. Note that these drops are provided in case of emergencies such as illnesses.

### Grace Period

Although problem sets and labs are due on Mondays and Thursdays respectively, **you can submit, with no penalty, each of your assignments (problem sets and labs) one day after the official due date of that assignment at 11:59 PM**. This comes with four important caveats:

1. This grace period is meant to account for technical issues.
1. Staff support will be limited during the grace period.
1. Barring exceptional circumstances and DSP accommodations, we will not be accepting any late assignments (_i.e._, they will automatically earn a 0). 
1. There will be no extensions on deadlines outside of DSP-related reasons -- these are meant to be covered by the drop policy.

### Collaboration

We encourage you to collaborate with up to five other current EE 120 students on each assignment, but each person must submit their own work. For problem sets, please write down the names of your collaborators on the appropriate location on the first page of the assignment. You need not indicate your collaborators for labs.


## Self-Grades

You will self-grade your problem sets. Labs will have both autograded and self-graded components. **Warning: Not submitting a self-grade will result in a 0 on the corresponding self-graded portion of the assignment.**

As assignments exist to encourage learning, not to punish small mistakes, the self-graded portion of each assignment will be scaled up by 1.25 and capped out at full credit. This means an 8/10 on a self-grade will be scaled up to a 10/10.

You may submit a self-grade up to **two days** late for **50% credit**. **No self-grades will be accepted after this late deadline (outside of DSP-related accommodations).**

The purpose of the self-grade assignments strategy is to encourage you to look over the solutions and use it to check your answers.  We hope it offers a chance to self-assess your understanding of the class content to prepare better for exams. As an oversight measure against inflationary self-grading, we conduct random checks at our discretion, and without notice.

### Timeline

Self grades will be released, along with assignment solutions, when the grace period for the assignment ends. **Self-grades for both homeworks and labs will be due a week after the end after the corresponding assignment grace period.** Homework self-grades will usually be due on Tuesdays and lab self-grades will usually be due on Fridays. Self-grades will be accepted up to **two days** after this deadline for **50% credit**.

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

## Exams

We will have 2 midterms and a final this semester. These midterms will be held **in-person** on the following dates:

**Midterm 1 Exam Time:** Wednesday October 1st 2 - 4 PM @ TBA

**Midterm 2 Exam Time:** Wednesday November 12th 2 - 4 PM @ TBA

**Final Exam Time:** Tuesday December 18th 3 - 6 PM @ TBA

We will release more exam logistics in Ed posts before each exam.

### Clobber Policy

We have a clobber policy where your final can replace your grade for either MT1 or MT2, but not both. Your lower midterm score in terms of z-score will be clobbered by the final based on z-score, allowing you to miss a midterm. This policy is meant to cover conflicts such as medical emergencies or exam conflicts.

You will be eligible for the clobber policy if you complete both of the clobber assignments, which entails completing the exam again without time constraint. More information will be provided on Ed on its release.

## Office Hours
These hours are subject to change. The most up-to-date office hour times and locations are available on the Calendar page of the course website. We have a combination of in-person and remote options: each office hour will have a room number, Zoom link, or both listed.

* Homework Party: Mondays 5 PM - 7 PM @ Cory 400
* Professor Dimakis: 


## Homework Party
We offer homework party on Mondays 5 PM - 7 PM in Cory 400 where you can ask questions about the problem sets and labs. Typically, two TAs will staff homework party each week. Homework party will start on September 1st.


## Grading

* **Midterms**: 20% each (40% total)
* **Final**: 35%
* **Problem Sets**: 15% (We drop the lowest score + another for filling out the midsemester feedback form)
* **Labs**: 10% (We drop the lowest score)

## DSP
UC Berkeley is committed to creating a learning environment that meets the needs of its diverse student body including students with disabilities. If you anticipate or experience any barriers to learning in this course, please feel welcome to discuss your concerns by emailing [ee120-fa25-admin@lists.berkeley.edu](mailto:ee120-fa25-admin@lists.berkeley.edu). If you have a disability, or think you may have a disability, you can work with the Disabled Students' Program (DSP) to determine any accommodations you may need to have equal access in this course. The Disabled Students' Program (DSP) is the campus office responsible for authorizing disability-related academic accommodations, in cooperation with the students themselves and their instructors. You can find more information about the DSP application process [here](https://dsp.berkeley.edu/students/new-students/application-process). We are available if you have any questions or concerns about your accommodations, but in the event of a disagreement, the proper procedure is for you to work with your DSP Specialist and your DSP Specialist to work with us toward a resolution.

Please submit your DSP letters of accommodation through email to [ee120-fa25-admin@lists.berkeley.edu](mailto:ee120-fa25-admin@lists.berkeley.edu) as soon as possible. If you are uncertain as to whether you will use the accommodation, it is much better to have the accommodation in place than to scramble at the last minute should you need it. Accommodations are not retroactive, so course staff is not responsible for providing accommodations prior to the receipt of an accommodation letter (although if you have extenuating circumstances, we may be able to make temporary adjustments). The more lead time that you provide admin staff, the easier it is for us to arrange your accommodations. Contact us through the admin email for any DSP-related concerns, including but not limited to assignments and exams. Be mindful that it might not be possible to accommodate last-minute requests, depending on your accommodation needs.


## Optional Course Materials

There is no official textbook or set of course notes for EE 120. EE 120 is a self-contained course in that the lectures, discussions, and labs contain all of the material you are responsible for knowing. However, if you would like additional information beyond what is covered in lectures, homeworks, and labs, you can look at these two textbooks:


* [Signals and Systems by Oppenheim and Willsky](https://github.com/gigahidjrikaaa/Engineering-Books/blob/main/Signals%20and%20Systems/Oppenheim%2C%20Willsky%2C%20Nawab%20-%20Signals%20%26%20Systems%20%5B2nd%20Edition%5D.pdf)
* [Signals and Systems, Theory and Applications by Fawwaz T. Ulaby, Andrew E. Yagle](https://ss2-2e.eecs.umich.edu)
* [Signals and Systems by Hwei P Hsu](https://electronicsbookcafe.files.wordpress.com/2015/08/signals-and-systems-2nd-edition-schaums-outline-series-hwei-hsu.pdf)

As a disclaimer, EE 120 does not directly follow these textbooks, so they will differ from the course material in terms of content, emphasis, notation, scope, and order. We may provide associated readings for each lecture, but these do not necessarily directly correspond to the topic being taught. Nothing is a substitute for attending lecture and discussion, and watching (and rewatching) the videos. 
