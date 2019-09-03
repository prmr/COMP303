# COMP303 - Software Design (Fall 2019)

Provides an introduction to software design, with a focus on object-oriented design. 

| |  |
| --- |---|
|**Instructor:** |[Martin Robillard](http://www.cs.mcgill.ca/~martin)|
|**Time and place:** |Monday and Wednesday 16:00-17:30 [BRONF 151](http://virtualcampustour.mcgill.ca/en/details/20/bronfman-building)|
|**Lectures Recorded?:**|No|
|**Instructor Office hours:** | Wednesday 11am or by appointment in MC 114N|
|**TA Office Hours:** | [See below](#office-hours-and-labs-schedule)|

## Course Topics
* **Concepts and Principles:** Encapsulation, information hiding, abstraction, immutability, interface, reference sharing, escaping references, polymorphism, loose coupling, reusability, extensibility, separation of concerns, interface segregation, concrete and abstract object states, object life cycle, object identity, object equality, object uniqueness, state space minimization, unit testing, regression testing, quality attributes of unit tests, test suites, test coverage, divide and conquer, law of Demeter, code reuse, extensibility, Liskov substitution principle, inversion of control, model–view–controller
(MVC) decomposition, callback method, behavior parameterization, first-class functions, higher-order functions, functional programming.
* **Programming Mechanisms:** Typing, enumerated types, scopes, access modifiers, assertions, Java interfaces, interface implementation, null references, final variables, optional types, nested classes, closures, unit testing frameworks, JUnit, metaprogramming, annotations, aggregation, delegation, cloning, inheritance, subtyping, downcasting, object initialization, super calls, overriding, overloading, abstract classes, abstract methods, final classes, final methods, application framework, event loop, graphical user interface (GUI) component graph, functional interfaces, lambda expressions, method references, streams.
* **Design Techniques:** Class definition, object diagrams, immutable wrappers, reference copying, copy constructors, design by contract, decoupling behavior from implementation, interface-based behavior specification, class diagrams, function objects, iterators, state diagrams, test suite organization, use of test fixtures, testing with stubs, testing private structures, use of test coverage metrics, testing exceptional conditions, sequence diagrams, combining design patterns, inheritance-base reuse, class hierarchy design, adapter inheritance, event handling, GUI design, behavior composition, functions as data sources, interface segregation with first-class functions, pipelining, map–reduce.
* **Patterns and Antipatterns:** Primitive Obsession*, Inappropriate Intimacy*, Iterator, Strategy, Switch Statement*, Speculative Generality*, Temporary Field*, Long Method*, Null Object, Flyweight, Singleton, Duplicated Code*, God Class*, Message Chain*, Composite, Decorator, Prototype, Command, Template Method, Pairwise Dependencies*, Observer, Visitor. 

## Prerequisites
The official prerequisites are COMP206 and COMP250. However, this assumes active participation in these courses and the accumulation of **a minimum level of Java programming experience**. It is difficult to learn software design while still getting familiar with basic programming idioms. It would be a bit like attempting to study literature in an unfamiliar language. This means that students registering to take COMP 303 should be able to, with a minimum of hesitation, write Java programs to solve small and well-defined problems, use a revision control system to organize their work, and use a debugger to trace through the execution of the code and inspect run-time values. Students who feel they could use additional programming experience are encouraged to take a few more COMP courses or undertake a pratice project or two before taking COMP303.

Not sure where you stand? Try the [self-assessment question](Assessment.md).

## Learning Outcomes
After this course, you should be able to... 

* *Name, using the proper terminology:* The important principles, programming techniques, and tools of object-oriented software design;
* *Describe and explain:* The important important principles, mechanisms, techniques, and patterns of software design;
* *Apply:* The important principles, mechanisms, techniques, and patterns of software design to provide effective solutions to realistic design problems;
* *Evaluate:* The quality of design solutions
* *Write:* well-designed, correct, and easily understandable software.

## Reference Material

* **Required Textbook**: [Introduction to Software Design with Java](https://link.springer.com/book/10.1007/978-3-030-24094-3). The electronic version of this book is **free** for McGill users with library access. For those who optionally want a print version, the [Paragraph Bookstore](http://paragraphbooks.com/) will stock a limited number of copies. 
* **Companion Website**: [DesignBook @ GitHub](https://github.com/prmr/DesignBook)
* **Recommended Reference:** [Java: The Complete Reference](https://learning.oreilly.com/library/view/java-the-complete/9781260440249/?ar), also available at no cost from the McGill library.
* **Sample Projects:** [Minesweeper](https://github.com/prmr/Minesweeper); [Solitaire](https://github.com/prmr/Solitaire)
* **Diagramming Tool (and Sample Project):** [JetUML](http://cs.mcgill.ca/~martin/jetuml/)

## Course Work and Evaluation

This course is divided into nine main modules which map to the chapters of the book. Except for the introduction, chapters are spread over two or three lectures and involve mandatory reading and practice exercises. **To be able to follow the pace of the course, the reading must be done before the chapter lectures and the exercises must be completed within one week of the end of the second lecture of the chapter.**

**It's very hard to get good at anything without practice, and software design is no exception.** Practice exercises are organized in terms of the chapter structure and are available on the [companion website](https://github.com/prmr/DesignBook). The exercises are designed to help you learn as effectively as possible: you can do them at your own pace, individually or in a group, repeat what's necessary, seek advice from anyone, and make mistakes and learn from them. For these and other reasons, they would be a poor choice for *testing* your knowledge of the material, so they are not graded. Instead, your practical skills will be evaluated through *lab tests*.

**The recipe for success** in COMP 303 is to regularly prepare for lectures by doing the required readings in advance, attending the lectures and participating in the design and coding walk-throughs, then completing the related exercises as soon as possible. If you do this you may be pleased to discover that the material will grow on you almost subconsciously. **The recipe for failure** is to await the midterms and final, then furiously attempt to memorize the book and lecture material. 

| Evaluation Activity | Weight |
| --- |---:|
|Lab tests	|20%|
|Midterm exam 1	|30%/20%/0%|
|Midterm exam 2	|30%/20%/0%|
|Final exam	    |40%/50%|

**Important Notes:**
* Midterm exams are normally worth 20%, but the grade of the lowest midterm can be replaced by 10% each of the final exam and other midterm. Missing one midterm automaticall selects this option.
* Missing both midterm exams results in a grade of 0% (on 30% of the total grade) unless original, independently-verifiable documentation justifying the absence to both midterm exams can be provided. Valid causes are limited to *unforseeable* circumstances.
* All material covered in class and in the practice exercises is subject to examination.
* **Midterm 1:** Thursday, October 3, 2019, 18:00-20:00
* **Midterm 2:** Wednesday, November 6, 2019 18:00-20:00

## Lectures

General philosophy of the role of lectures, and related policies:

* The lectures are not recorded. **No audio or video recording of any kind is allowed in class**, with the one exception that you can take pictures of the projection screen (only) if you can do so in a non-disruptive manner. Note, however, that practically all lecture material will be available on-line.
* Lectures **complement** the course material with demonstrations, examples, discussions, and class activities: they do **not replace** individual reading and practice.
* **The reading should be done in advance** to be able to follow the lecture. For example, I will not use the class time to read basic definitions of terms and go over the details of notation, because this is both boring and ineffective. However, coming to the lectures without having gone over the reading will be confusing, because terms will seem to come out of nowhere. Please do the reading in advance, and everything will be fine.
* The lectures will **not** be [Power Pointless](http://www.slate.com/articles/life/education/2014/03/powerpoint_in_higher_education_is_ruining_teaching.html). I will occasionally use slides to provide visual support for the material, and post the slides after the lecture. The slides should not be expected to constitute a self-contained study document. I must emphatically warn anyone against attempting to pass the course by memorizing slides.
* Although attendance is not monitored, I strongly recommend [attending lectures](http://www.cs.mcgill.ca/~martin/blog/2015-12-27.html). Lectures will feature walk-throughs of design and implementation tasks that will help you understand the reasoning behind certain design decisions as the decisions are being made. I will also go through multiple variants design solutions for various problems, which is extremely tedious to capture in writing (and read, for that matter).
* If you do decide to attend lectures, please refrain from using your computing devices in a distracting or disruptive manner. This includes **watching videos, playing games**, etc. 

## Lecture Schedule

*Subject to minor adjustments*

| Lecture | Date | Chapter |Lab|
| --- |---|---|---|
|1	|  4 Sep | 1-Introduction | |
|2	|  9 Sep | 2-Encapsulation | |
|3	|  11 Sep | 2-Encapsulation | |
|4	|  16 Sep | 3-Types and Interfaces | |
|5	|  18 Sep | 3-Types and Interfaces | |
|6	|  23 Sep | 3-Types and Interfaces | |
|7	|  25 Sep | 4-Object State | |
|8	|  30 Sep | 4-Object State | Lab 1 (C2-3)|
|9	|  02 Oct | 4-Object State | Lab 1 (C2-3)|
|M  |  03 Oct | Midterm 1 18:00 | Lab 1 (C2-3)|
|10	|  07 Oct | 5-Unit Testing | Lab 1 (C2-3)|
|11	|  09 Oct | 5-Unit Testing | Lab 1 (C2-3)|
|X	|  14 Oct | Thanksgiving | Lab 2 (C2-3)|
|12	|  16 Oct | 5-Unit Testing | Lab 2 (C2-3)|
|13	|  21 Oct | 6-Composition | Lab 2 (C2-3)|
|14	|  23 Oct | 6-Composition | Lab 2 (C2-3)|
|15	|  28 Oct | 6-Composition | |
|16	|  30 Oct | 7-Inheritance | |
|17	|  04 Nov | 7-Inheritance | |
|18	|  06 Nov | Midterm 2 18:00 - no class | |

*To be continued*

## Office Hours and Labs Schedule

TA office hours and labs are in TR 3120.

*To be completed

| Time | TA |
| --- |---|
| Monday 10 am to noon | Srinivas | 
| Tuesday 9 to 11 am | Aaron |
| Wednesday 1:30 to 3:30 pm | David |
| Thursday 2 to 4 pm | Mathieu |
| Friday 8:30 to 10:30 am | Deeksha |

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a>

Unless otherwise noted, the content of this repository is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>. 

Copyright Martin P. Robillard 2019
