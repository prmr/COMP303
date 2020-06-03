# COMP303 - Software Design (Fall 2020)

Provides an introduction to software design, with a focus on object-oriented design. 

| |  |
| --- |---|
|**Instructor:** |[Martin Robillard](http://www.cs.mcgill.ca/~martin)|
|**Time and place:** |Due to the Covid-19 pandemic, the course will exceptionally be offered on-line following an asychronous model. See [Course Work and Evaluation](#course-work-and-evaluation) for details. *Please not that the information provided here is preliminary and subject to modifications*.|

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

This course is divided into nine main modules which map to the chapters of the book. 

The material will be presented in the form of recorded coding demonstrations with separate live chat sessions. 

**Individual practice exercises** are organized in terms of the chapter structure and are available on the [companion website](https://github.com/prmr/DesignBook). The exercises are designed to help you learn as effectively as possible: you can do them at your own pace, individually or in a group, repeat what's necessary, seek advice from anyone, and make mistakes and learn from them. For these and other reasons, they would be a poor choice for *testing* your knowledge of the material, so they are not graded. 

**To be able to follow the pace of the course, the required reading must be done before the demonstrations and the exercises must be completed within one week of the end of the module.**

In adition to the *individual* practice exercises, you will be required to participate in **nine graded collaborative design activities**. In these design activities, you and nine randomly-assigned classmates will tackle a design problem by proposing solutions and discussing them. These activities will be graded based on *individual contributions* following a uniform grading scheme. The first eight activities will map to modules 2-9 of the book, and the last activity will be a final integration activity covering the entire course. You will have between one and two weeks to complete each activity. Groups will be shuffled for each activity, giving you a chance to collaborate with a maximum number of classmates. The first eight activities will be worth 10% each, with the lowest grade being replaced by the highest grade. The final activity will be worth 20% and its grade cannot be swapped.

All the material covered in the book, in the coding demonstrations, and the live chat sessions is subject to assessment. 

## Schedule

*Subject to adjustments*

### Topic Coverage

*The dates indicate when the corresponding learning material will be available. The dates correspond to the normal class schedule, but there is no requirement to attend an on-line meeting at a specific time.*

| Lecture | Date | Chapter |
| --- |---|---|
|1	|  2 Sep | 1-Introduction |
|  	|  7 Sep | Labour Day |
|2	|  9 Sep | 2-Encapsulation |
|3	|  14 Sep | 2-Encapsulation |
|4	|  16 Sep | 3-Types and Interfaces |
|5	|  21 Sep | 3-Types and Interfaces |
|6	|  23 Sep | 3-Types and Interfaces |
|7	|  28 Sep | 4-Object State |
|8	|  30 Sep | 4-Object State |
|9	|  05 Oct | 4-Object State |
|10  |  07 Oct | 5-Unit Testing |
|    | 12 Oct | Thanksgiving | |
|11	|  14 Oct | 5-Unit Testing |
|12	|  19 Oct | 6-Composition |
|13	|  21 Oct | 6-Composition | |
|14	|  26 Oct | 6-Composition |
|15	|  28 Oct | 7-Inheritancen |
|16 |  02 Nov | 7-Inheritance |
|17	|  04 Nov | 8-Inversion of Control |
|18	|  09 Nov | 8-Inversion of Control |
|19	|  11 Nov | 8-Inversion of Control |
|20	|  16 Nov | 8-Inversion of Control |
|21 |  18 Nov | 9-Functional Design |
|22 |  23 Nov | 9-Functional Design |
|23 |  25 Nov | 9-Functional Design |
|24 |  30 Nov | Putting it all together |
|25 |  02 Dec | Putting it all together |
|26 |  03 Dec | Putting it all together |

### Design Activities

| Topic | Starts | Ends |
| --- |---|---|---|
| 1-Chapter 2 | 14 Sep | 25 Sep |
| 2-Chapter 3 | 28 Sep | 06 Oct |
| 3-Chapter 4 | 07 Oct | 16 Oct |
| 4-Chapter 5 | 19 Oct | 23 Oct  |
| 5-Chapter 6 | 26 Oct | 30 Oct |
| 6-Chapter 7 | 02 Nov | 06 Nov |
| 7-Chapter 8 | 09 Nov | 13 Nov |
| 8-Chapter 9 | 16 Nov | 20 Nov |
| 9-Integration | 23 Nov | 03 Dec |


## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a>

Unless otherwise noted, the content of this repository is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>. 

Copyright Martin P. Robillard 2020
