---
layout: page
title: Syllabus
professor: Dr. Alex White (he/him)
email: whiteae@si.edu
schedule: ['Fridays, 8-9:30 (PDT)']
location: Zoom

---

## Course

{{ site.title }}


### Instructor

{{ page.professor }}


### Course Communications

If you need to contact me for any reason, please send me an email.
Email: [{{ page.email }}](mailto:{{ page.email }})

### Location

{{location}}

### Times

{% for class in page.schedule %}
  {{ class }}
{% endfor %}


### Website

The syllabus and other relevant class information and resources will be posted
at [{{ site.url}}]({{ site.baseurl }}/). Changes to the schedule will be posted to this 
site so please try to check it periodically for updates.


### Required Texts

There is no required text book for this class.

All needed material is openly available on the course website. If you are
interested in additional reading on the topics we are covering I highly
recommend [R for Data Science](https://r4ds.had.co.nz/), which is freely
available on the web.


### Course Description

An introduction to data management, manipulation, and analysis, with an emphasis
on biological problems. Class consists of short introductions to new concepts
followed by hands on computing exercises using R, but the concepts
apply to programming languages more generally. No background in
computing is required.


### Prerequisite Knowledge and Skills

Knowledge of basic biology to provide context for exercises.


### Purpose of Course

In this course you will learn all of the fundamental aspects of computer
programming that are necessary for conducting biological research. By the end of
the course you will be able to use these tools to import data into R, perform
analysis on that data, and export the results to graphs and text files. By learning how to get the computer to do your work for you, you will be able to do more science faster.


### Course Objectives and Goals

Students completing this course will be able to:

* Create well structured databases
* Write computer programs in R
* Automate data analysis
* Apply these tools to address biological questions
* Apply general data management and analysis concepts to other programming
  languages


### Teaching Philosophy

This class is taught using a flipped, learner-centered, approach, because
learning to program and work with data requires actively working on
computers. Flipped classes work well for all kinds of content, but they
work particularly well for computer oriented classes. If you're interested in
knowing more take a look at this great
[info-graphic](https://www.knewton.com/flipped-classroom-2/).


### Instructional Methods

As a flipped classroom, students are provided with either reading or video
material that they are expected to view/read prior to class. Classes will
involve brief refreshers on new concepts followed by working on exercises in
class that cover that concept. While students are working on exercises the
instructor will actively engage with students to help them understand material
they find confusing, explain misunderstandings and help identify mistakes that
are preventing students from completing the exercises, and discuss novel
applications and alternative approaches to the data analysis challenges students
are attempting to solve. For more challenging topics class may start with 20-30
minute demonstrations on the concepts followed by time to work on exercises.


## Course Policies


### Attendance Policy

Attendance will not be taken. However, experience suggests that students who regularly 
miss class struggle to learn the material.


### Quiz/Exam Policy

There are no quizzes or exams in this course.


### Assignment policy

Assignments are due Monday night by 11:59 pm Eastern Time. Assignments should be
submitted via Goucho Space. This timing allows you to be finished with one week's material before starting the next week's material.


### Course Technology

Students are required to provide their own laptops. Students will connect to a cloud 
computing environment via their web browser to access software for their coursework. 
Students that would like to install software on their own laptops can follow [Setup]({{ site.baseurl }}/computer-setup) for installation instructions (not required). 


### Netiquette and Communication Courtesy

All members of the class are expected to follow rules of common
courtesy in all email messages, threaded discussions and chats.


## Course Schedule

The detailed course schedule is available on the course website at:
[{{ site.url }}/schedule]({{ site.baseurl }}/schedule).

