# Python for text analysis
*As taught at the Vrije Universiteit Amsterdam in the Research MA Linguistics, track [Linguistic Engineering](http://www.cltl.nl/teaching/research-master-linguistic-engineering/).*

This is a practical course in Python, geared towards those who want to get some hands-on experience working with language data.
No knowledge of programming is required or presupposed.
We will work with Python 3. If you haven't worked with Python before, we recommend that you install [Anaconda](https://www.continuum.io/downloads).

(If you have worked with Python 3 before, be sure to check if Jupyter Notebook
is installed on your machine. We will work extensively with notebooks.)

## Goals

After this course you will know the basics of the Python programming language, and you will be familiar with several external libraries that are commonly used to analyze text. Our goal is for you to become an independent programmer, who is able to find solutions to new problems. You will..

*	Learn how to deal with structured and unstructured (text) data (reading, representing, and analyzing).
*	Learn how to get the data you want (through APIs or using a script).
*	Learn how to deal with large amounts of (text) data.
*	Learn how to share your code and results.

This course is very pragmatic and hands-on. We focus on *understandability* and *re-usability* of the code above all (so that Future You will also be able to use the code that you've written).

## Core principles

Every course has a set of core principles that its teachers adhere to.
We strongly believe in the principles outlined by Mike Bostock in his article
[What makes software good?](https://medium.com/@mbostock/what-makes-software-good-943557f8a488) Here they are:

* **Good software is approachable**. It can be understood completely in independent, easy pieces. You don’t need to understand everything before you can understand anything.

* **Good software is consistent**. It lets you take what you’ve learned about one part and extrapolate it to the rest. It doesn’t self-contradict. It is parsimonious, avoiding superfluous elements.

* **Good software explains itself**. It has affordances for learning and discovery. It is role-expressive and minimizes hidden magic.

* **Good software teaches**. It doesn’t just automate an existing task, but provides insight or imparts knowledge, such as a best practice or a new perspective on a problem.

* **Good software is for humans**. It is cognizant of people and the reality in which they live. It does not expect elaborate and arbitrary rules to be memorized. It anticipates the need for learning and debugging.

## The 15 minute rule

When you are just learning how to program, it sometimes happens that you get stuck and you don't know what to do next. This is normal.
There are many fantastic resources online that we encourage you to use to solve your problem on your own. But we don't want this to be a frustrating experience for you. So if you're stuck for more than 15 minutes: please contact us! No matter how small the problem. If you're stuck, you're stuck.

In our experience it does help to solve the exercises together with a classmate. (See [pair programming](https://en.wikipedia.org/wiki/Pair_programming) and [rubber duck debugging](https://en.wikipedia.org/wiki/Rubber_duck_debugging).) If either one of you gets stuck, try to explain the thought process behind your program, and go through the lines step by step. Making your thought process explicit is a great way to find bugs in your code!

## Courseware structure

Our materials are structured as follows:

* Notebooks can be found in the `Notebooks` folder. This is our primary teaching material. You will work through an interactive notebook every week.

* Chapters on Python can be found in the `Python-chapters` folder. You can use these chapters for future reference.

* Other topics, related to natural language processing and 'everyday work' are covered
  in the `NLP-topics` folder. So if you're just here to learn Python, you can skip these
  notebooks. You may still find them useful, however!
  
* The `Data` folder contains all data used in this course, and scripts used to obtain
  this data. (So you can see what techniques we used.)

This file serves as the syllabus and a general reference for this course.

## Assignments and Grading

There will be weekly assignments, a midterm exam, and a final assignment.
These are weighted as follows.

| Part    | weight % | | Part    | weight % |
|---------|---------|---|---------|---------|
|Assignment 1|	 4  | | Total Assignments |	35 |
|Assignment 2|	 4  | | Exam	            |	20 |
|Assignment 3|	 9  | | Final assignment  |	45 |
|Assignment 4|	 9  | | **Total**         |	100 |
|Assignment 5|	 9  | | | |
|**Total Assignments** |	35 | | | |

### Planning
The schedule for the entire course follows the same structure, illustrated below.
Our philosophy is that programming should be taught in a hands-on manner, so we tried
to reduce 'powerpoint time' to a minimum. Most theory is mainly taught through the
notebooks, but we'll also address the major topics in class.

After the introductory session, assignments will be given on Thursday. You can
work on these assignments in class and at home. We'll have a Q&A session on Monday,
along with additional theory. We'll also work on the assignments in class. Assignments
are handed in on Tuesday, so we can check everything in time for Thursday where you
will receive feedback and get the new assignment.

| Week | Day    | Activities                         |
|------|--------|------------------------------------|
| 1    | Monday |Practical matters + getting started |
| 1    | Thursday | Theory + give assignment 1       |
| 2    | Monday | Theory + Work on assignment        |
| 2    | Tuesday | Hand in assignment 1              |
| 2    | Thursday | Feedback + Give assignment 2     |
| 3    | Monday | Theory + Work on assignment        |
| 3    | Tuesday | Hand in assignment 2              |
| ...  | ...     | ...                               |

### Weekly assignments
Every week you are asked to hand in an assignment. We use these assignments to keep
track of your progress in the course, and to address misunderstandings when they arise.
As practice is essential to learn how to program, and since these assignments also serve
as a feedback mechanism in the course (keeping track of your progress), the assignments
are **mandatory.**

### Midterm exam
The midterm exam tests your knowledge of the syntax of Python, and your knowledge
of the standard library. It also tests whether you are able to write simple functions
in Python. This knowledge is fundamental to the rest of the course. As such, you cannot
pass the course without a passing grade on the midterm. But don't worry: if you are able
to finish the assignments, you will be fine on the exam.

### The final assignment
The exact details of the final assignment are to be determined. If you come up with
an interesting task of your own, we are happy to turn that into an assignment as well.

You can expect a project in which you are asked to:

1. process a number of files;
2. extract relevant information from those files;
3. present that information to the user;
4. store the information in a useful format

We will consider the following questions (along with the core principles) to evaluate your final assignment:

* Does the code work?
* Does the code fulfill the requirements?
* Is the code well-documented?
* Is the code clear and understandable?
* Is the code modular?
* Is the code easily extensible?
* How scalable is the solution?
* Is the code written in accordance with [the community standards](http://pep8.org/)? (That is: PEP8)
* Are there tests to ensure that the code works?

-----------------------------

**Note**
This course is a work-in-progress. The first full draft should be finished by September 2016 (at the start of the academic year).
If you have any questions or comments, please email me at [emiel.van.miltenburg@vu.nl](mailto:emiel.van.miltenburg@vu.nl).
