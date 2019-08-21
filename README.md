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

## Learning Outcomes
After this course, you should be able to... 

* *Name, using the proper terminology:* The important principles, techniques, and tools of object-oriented software design;
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
|9	|  3 Oct | [M4 - Unit Testing](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-04.md) | Lab Test 1 (M1-2)|
|10	|  5 Oct | [M4 - Unit Testing](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-04.md) | Lab Test 1 (M1-2)|
|11	| 10 Oct | Review Session | Lab Test 1 (M1-2)|
|12	| 12 Oct | Midterm 1 | Lab Test 1 (M1-2)|
|13	| 17 Oct | [M5 - Composition](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-05.md) | Lab Test 2 (M3-4)|
|14	| 19 Oct | [M5 - Composition](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-05.md) | Lab Test 2 (M3-4)|
|15	| 24 Oct | [M6 - Inversion of Control](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-06.md) | Lab Test 2 (M3-4)|
|16	| 26 Oct | [M6 - Inversion of Control](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-06.md) | Lab Test 2 (M3-4)|
|17	| 31 Oct | Review Session | |
|18	|  2 Nov | Midterm 2 | |
|19	|  7 Nov | [M6 - M7 - Inheritance](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-07.md) | Lab Test 3 (M5-6) |
|20	|  9 Nov | [M6 - M7 - Inheritance](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-07.md) | Lab Test 3 (M5-6) |
|21 | 14 Nov | [M8 - Design Patterns](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-08.md) | Lab Test 3 (M5-6)|
|22	| 16 Nov | [M8 - Design Patterns](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-08.md) | Lab Test 3 (M5-6)|
|23	| 21 Nov | [M9 - Concurrency](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-09.md) | Lab Test 4 (M7-8)|
|24	| 23 Nov | [M9 - Concurrency](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-09.md) | Lab Test 4 (M7-8)|
|25	| 28 Nov | [M10 - Topics in Software Design](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-10.md) | Lab Test 4 (M7-8)|
|26	| 30 Nov | [M10 - Topics in Software Design](https://github.com/prmr/SoftwareDesign/blob/master/modules/Module-10.md) | Lab Test 4 (M7-8)|

## Office Hours and Labs Schedule

TA office hours and labs are in TR 3120.

*To be completed

| Time | TA |
| --- |---|
| Day Time | TAName | 

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a>

Unless otherwise noted, the content of this repository is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>. 

Copyright Martin P. Robillard 2019
