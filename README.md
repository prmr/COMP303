# COMP303 - Software Design (Fall 2017)

## Basic Information
| |  |
| --- |---|
|**Instructor:** |[Martin Robillard](http://www.cs.mcgill.ca/~martin)|
|**Email:** |For your own protection, I only respond to student inquiries that originate from official McGill email accounts |
|**Time and place:** |Tuesdays and Thursdays 16:00-17:30 [ENGMC 204](http://maps.mcgill.ca)|
|**Office hours:** | Instructor: TBD in MC 114N. For TA Office Hours [see below](#office-hours-and-labs-schedule)  |

## Description
This course provides an in-depth introduction to the discipline of software design, with a focus on object-oriented design. Software design can easily be discounted as a secondary concern when solving small computing problems such as assignments and scripts. However, it assumes a critical role when attempting to build realistic and high-quality software applications. The course 
combines rigorous foundations (guiding principles, precise terminology, well-defined techniques) with extensive opportunities for the development of practical skills using state-of-the art tools and techniques based on the latest research and practice in software engineering. 

### Sample Course Topics
* General Design Principles (separation of concerns, encapsulation, substitutablity, interface segregation, etc.);
* Design patterns and design smells;
* Design techniques such as Design by Contract and Refactoring;
* Effective use of programming language mechanisms (exception handling, serialization, concurrency and synchronization, reflection, etc.);
* Software development tools such as automatic testing tools, coverage analyzers, static checkers. 

### Prerequisites
The official prerequisites are COMP 206 and COMP 250. However, this course targets students who have reached at least a working level of Java programming fluency. In practice, it is very difficult to learn software design when still getting familiar with basic programming idioms. This means that students registering to take COMP 303 should be able to, with a minimum of hesitation, write Java programs to solve small and well-defined problems, use a revision control system to organize their work, and use a debugger to trace through execution and inspect run-time values. This requirement cannot be neatly captured by any specific combination of courses, but students who feel they could use additional programming experience are encouraged to take COMP 302 before or during the term in which they take COMP 303.

### Learning Outcomes
After this course, you should be able to... 

* *Name, using the proper terminology:* The important first principles, techniques, and tools of object-oriented software design;
* *Describe and explain:* The important principles, techniques, and tools of object-oriented software design;
* *Apply:* The important principles, techniques, and tools of object-oriented software design to provide effective solutions to realistic design problems;
* *Evaluate:* The quality of design solutions
* *Write:* well-designed, error-free, and easily understandable software.

## Reference Material

* **Course Notes:** [Introduction to Software Design with Java.](https://github.com/prmr/SoftwareDesign/) This textbook-style set of notes is intended to be a one-stop-shop for this course. It is, however, a work in progress. 
* **Design Pattern Reference:** [http://java-design-patterns.com/](http://java-design-patterns.com/)
* **Recommended Textbook:** [Object-oriented Design and Patterns](http://www.bookdepository.com/Object-oriented-Design-Patterns-Cay-Horstmann/9780471744870). Now out of print, this was the former textbook for the course and may provide some useful insights if you can find it. The programming examples will be a bit dated.
* **Complementary Resource:** [Clean Code: A Handbook of Agile Software Craftmanship. Prentice-Hall, 2008.](http://proquest.safaribooksonline.com/9780136083238?tocview=true). Available on-line from the McGill domain. 
* **Recommended Reference:** A Java 8 Programming reference of your choice.
* **Sample Project:** [Solitaire](https://github.com/prmr/Solitaire)
* **Diagramming Tool (and Sample Project):** [JetUML](http://cs.mcgill.ca/~martin/jetuml/)

## Course Work and Evaluation

This course is divided into [ten main modules](https://github.com/prmr/SoftwareDesign/blob/master/Overview.md), each addressing a major topic in object-oriented software design. Modules are spread over two lectures and involve mandatory reading and practice exercises. To be able to follow the pace of the course, the reading must be done before the module lectures and the exercises must be completed within one week of the end of the second lecture of the module.

It's very hard to get good at anything without practice, and software design is no exception. *Practice exercises* are organized in terms of the module structure and are available on their individual pages. The exercises are designed to help you learn as effectively as possible: you can do them at your own pace, individually or in a group, repeat what's necessary, seek advice from anyone, and make mistakes and learn from them. For these and other reasons, they would be a poor choice for *testing* your knowledge of the material, so they are not graded. Instead, your practical skills will be evaluated through *lab tests*.

Software design is a naturally abstract topic that needs to be applied to make any sense. The **recipe for success** in COMP 303 is to regularly prepare for lectures by doing the required readings in advance, attending the lectures and participating in the design and coding walk-throughs, then completing the related exercises as soon as possible. If you do this you may be pleased to discover that the material will grow on you almost subconsciously. The **recipe for failure** is to await the midterms and final, then furiously attempt to memorize the book and lecture material. Please opt for success.

| Evaluation Activity | Weight |
| --- |---:|
|Lab tests	|20%|
|Midterm exam 1	|30%/20%/0%|
|Midterm exam 2	|30%/20%/0%|
|Final exam	    |40%/50%|

**Important Notes:**
* Midterm exams are normally worth 20%, but the grade of the lowest midterm can be replaced by 10% each of the final exam and other midterm. Missing one midterm automaticall selects this option.
* Missing both midterm exams results in a grade of 0% unless original, independently-verifiable documentation justifying the absence to both midterm exams can be provided. Valid causes are limited to *unforseeable* circumstances.
* All material covered in class and in the practice exercises is subject to examination.

## Lectures

General philosophy of the role of lectures, and related policies:

* Lectures **complement** the course material with
  demonstrations, examples, discussions, and class
  activities: they do **not replace** individual reading and practice.
* The reading should be done in advance to be able to follow the lecture. For example, I will not use the class time to read basic definitions of terms and go over the details of notation, because this is both boring and ineffective. However, coming to the lectures without having gone over the reading will be confusing, because terms will seem to come out of nowhere. Please do the reading in advance, and everything will be fine.
* The lectures will **not** be [Power Pointless](http://www.slate.com/articles/life/education/2014/03/powerpoint_in_higher_education_is_ruining_teaching.html). I will occasionally use slides to provide visual support for the material, and post the slides after the lecture. The slides should not be expected to constitute a self-contained study document. I must emphatically warn anyone against attempting to pass the course by memorizing the slides.
* Although attendance is not monitored, I strongly recommend [attending lectures](http://www.cs.mcgill.ca/~martin/blog/2015-12-27.html). Lectures will feature walk-throughs of design and implementation tasks that will help you understand the reasoning behind certain design decisions as the decisions are being made. I will also go through multiple variants design solutions for various problems, which is extremely tedious to capture in writing (and read, for that matter).
* If you decide to attend lectures, you are asked to refrain from using your computing devices in a distracting or disruptive manner. This includes **watching videos, playing games**, etc. 
* The lectures are not recorded. **No audio or video recording of any kind is allowed in class**, with the one exception that you can take pictures of the projection screen (only) if you can do so in a non-disruptive manner. Note, however, that practically all lecture material will be available on-line.

These policies are subject to revision at any point during the term.

## Lecture Schedule

| Lecture | Date | Module |Lab|
| --- |---|---|---|
|1	|  5 Sep | [M0 - Preparation](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-00.md) | |
|2	|  7 Sep | [M1 - Encapsulation](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-01.md) | |
|3	| 12 Sep | [M1 - Encapsulation](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-01.md) | |
|4	| 14 Sep | [M2 - Types and Polymorphism](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-02.md) | |
|5	| 19 Sep | [M2 - Types and Polymorphism](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-02.md) | |
|6	| 21 Sep | [M2 - Types and Polymorphism](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-02.md) | |
|7	| 26 Sep | [M3 - Object State](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-03.md) | |
|8	| 28 Oct | [M3 - Object State](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-03.md) | |
|9	|  3 Oct | [M4 - Unit Testing](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-04.md) | Lab Test 1 (M1-3)|
|10	|  5 Oct | [M4 - Unit Testing](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-04.md) | Lab Test 1 (M1-3)|
|11	| 10 Oct | Review Session | Lab Test 1 (M1-3)|
|12	| 12 Oct | Midterm 1 | Lab Test 1 (M1-3)|
|13	| 17 Oct | [M5 - Composition](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-05.md) | Lab Test 2 (M4-5)|
|14	| 19 Oct | [M5 - Composition](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-05.md) | Lab Test 2 (M4-5)|
|15	| 24 Oct | [M6 - Inversion of Control](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-06.md) | Lab Test 2 (M4-5)|
|16	| 26 Oct | [M6 - Inversion of Control](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-06.md) | Lab Test 2 (M4-5)|
|17	| 31 Oct | Review Session | |
|18	|  2 Nov | Midterm 2 | |
|19	|  7 Nov | [M6 - M7 - Inheritance](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-07.md) | Lab Test 3 (M6-7) |
|20	|  9 Nov | [M6 - M7 - Inheritance](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-07.md) | Lab Test 3 (M6-7) |
|21 | 14 Nov | [M8 - Design Patterns](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-08.md) | Lab Test 3 (M6-7)|
|22	| 16 Nov | [M8 - Design Patterns](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-08.md) | Lab Test 3 (M6-7)|
|23	| 21 Nov | [M9 - Concurrency](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-09.md) | Lab Test 4 (M6-7)|
|24	| 23 Nov | [M9 - Concurrency](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-09.md) | Lab Test 4 (M6-7)|
|25	| 28 Nov | [M10 - Topics in Software Design](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-10.md) | Lab Test 4 (M8-9)|
|26	| 30 Nov | [M10 - Topics in Software Design](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-10.md) | Lab Test 4 (M8-9)|

## Office Hours and Labs Schedule

TA office hours and labs are in TR 3120.

| Time | TA |
| --- |---|
| TBD | TBD | 

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a>

Unless otherwise noted, the content of this repository is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>. 

Copyright Martin P. Robillard 2017
