# COMP303 - Software Design (Fall 2021)

**Update (31 Aug 2021): It will not be possible to do the course purely remotely. However, no in-person activity will take place before the week of 27 Sep.**

**Update (23 Aug 2021): I have just received confirmation that the course can proceed with in-person exams and labs**

Provides an introduction to software design, with a focus on object-oriented design. 

| |  |
| --- |---|
|**Instructor:** |[Martin Robillard](http://www.cs.mcgill.ca/~martin)|
|**Time and Place:** |The lectures will be delivered via video on myCourses; Interactive office hours will take place Tuesday 9-10am and, as necessary,  Thursdays, 9-10am. Labs will take place in person in TR3120.|
|**Contact:** |For general questions about the course, use the myCourses **discussion board**. The instructor will be available via Zoom during **office hours**, also accessible via myCourses. Please resort to **email** only for confidential administrative matters (response delays are inevitable for email). The email addresses of the TAs will be available through myCourses.|

## Course Topics
* **Concepts and Principles:** Encapsulation, information hiding, abstraction, immutability, interface, reference sharing, escaping references, polymorphism, loose coupling, reusability, extensibility, separation of concerns, interface segregation, concrete and abstract object states, object life cycle, object identity, object equality, object uniqueness, state space minimization, unit testing, regression testing, quality attributes of unit tests, test suites, test coverage, divide and conquer, law of Demeter, code reuse, extensibility, Liskov substitution principle, inversion of control, model–view–controller
(MVC) decomposition, callback method, behavior parameterization, first-class functions, higher-order functions, functional programming.
* **Programming Mechanisms:** Typing, enumerated types, scopes, access modifiers, assertions, Java interfaces, interface implementation, null references, final variables, optional types, nested classes, closures, unit testing frameworks, JUnit, metaprogramming, annotations, aggregation, delegation, cloning, inheritance, subtyping, downcasting, object initialization, super calls, overriding, overloading, abstract classes, abstract methods, final classes, final methods, application framework, event loop, graphical user interface (GUI) component graph, functional interfaces, lambda expressions, method references, streams.
* **Design Techniques:** Class definition, object diagrams, immutable wrappers, reference copying, copy constructors, design by contract, decoupling behavior from implementation, interface-based behavior specification, class diagrams, function objects, iterators, state diagrams, test suite organization, use of test fixtures, testing with stubs, testing private structures, use of test coverage metrics, testing exceptional conditions, sequence diagrams, combining design patterns, inheritance-base reuse, class hierarchy design, adapter inheritance, event handling, GUI design, behavior composition, functions as data sources, interface segregation with first-class functions, pipelining, map–reduce.
* **Patterns and Antipatterns:** Primitive Obsession*, Inappropriate Intimacy*, Iterator, Strategy, Switch Statement*, Speculative Generality*, Temporary Field*, Long Method*, Null Object, Flyweight, Singleton, Duplicated Code*, God Class*, Message Chain*, Composite, Decorator, Prototype, Command, Template Method, Pairwise Dependencies*, Observer, Visitor. 

## Prerequisites
The official prerequisites are COMP206 and COMP250. However, this assumes active participation in these courses and the accumulation of **a minimum level of Java programming experience**. This means that students registering to take COMP 303 should be able to, with a minimum of hesitation, write Java programs to solve small and well-defined problems, use Git to organize their work, and use a debugger to trace through the execution of the code and inspect run-time values. Students who feel they could use additional programming experience are encouraged to take a few more COMP courses or undertake a pratice project or two before taking COMP303.

Not sure where you stand? Try the [self-assessment question](Assessment.md).

## Learning Outcomes
After this course, you should be able to... 

* *Name, using the proper terminology:* The important principles, programming techniques, and tools of object-oriented software design;
* *Describe and explain:* The important important principles, mechanisms, techniques, and patterns of software design;
* *Apply:* The important principles, mechanisms, techniques, and patterns of software design to provide effective solutions to realistic design problems;
* *Evaluate:* The quality of design solutions
* *Write:* well-designed, correct, and easily understandable software.

## Reference Material

* **Required Textbook**: [Introduction to Software Design with Java](https://link.springer.com/book/10.1007/978-3-030-24094-3). The electronic version of this book is **free** for McGill users with library access. 
* **Companion Website**: [DesignBook @ GitHub](https://github.com/prmr/DesignBook)
* **Recommended Reference:** [Java: The Complete Reference](https://learning.oreilly.com/library/view/java-the-complete/9781260440249/?ar), also available at no cost from the McGill library.
* **Sample Project:** [Minesweeper](https://github.com/prmr/Minesweeper), [Solitaire](https://github.com/prmr/Solitaire)
* **Diagramming Tool (and Sample Project):** [JetUML](http://cs.mcgill.ca/~martin/jetuml/)

## Course Work and Evaluation

*This section is subject to final adjustments.*

This course is divided into nine main modules which map to the chapters of the book. The material will be presented in the form of **recorded coding demonstrations**. 

**Individual practice exercises** are organized in terms of the chapter structure and are available on the [companion website](https://github.com/prmr/DesignBook). The exercises are designed to help you learn as effectively as possible: you can do them at your own pace, individually or in a group, repeat what's necessary, seek advice from anyone, and make mistakes and learn from them. For these and other reasons, they would be a poor choice for *testing* your knowledge of the material, so they are not graded. 

**To be able to follow the pace of the course, the required reading must be done before the demonstrations and the exercises must be completed before the corresponding lab test.**

**The recipe for success** in COMP 303 is to regularly do the required readings in advance, completing the related exercises as soon as  possible, and asking questions when stuck. If you do this you may be pleased to discover that the  material will grow on you almost subconsciously. **The recipe for failure** is to await the midterm and final, then furiously attempt to memorize the book and lecture material. 

| Evaluation Activity                        | Weight |
| ------------------------------------------ | ------ |
| In-person lab tests (4, with equal weight) | 25%    |
| Midterm exam                               | 25%    |
| Final exam                                 | 50%    |

**Important Notes:**

- **Accommodation 1**: If the grade of the final exam exceeds that of the midterm, the  grade of the final exam will replace the grade of the midterm. This accommodation includes the case where students are unable to write the midterm.
- **Accommodation 2:** The grade of the lab tests will be the average of the grades of the best three lab tests. This accommodation includes the case where students are unable to complete a lab test.
- **Date and place of the in-person midterm:** Tuesday Oct 26, 6-9pm,  STBIO S1/4, MAASS 112
- All material covered in videos and in the practice exercises is subject to assessment.
- Here is a [sample midterm](https://github.com/prmr/COMP303/blob/2019F/Sample-Midterm.pdf). This sample is provided so that you can familiarize yourself in advance with the *exam style*. **However**, the course schedule varies slightly from section to section so **the topics covered in the sample midterm are not necessarily representative of what will be evaluated in your own midterm**.

## Schedule

To be determined. 

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a>

Unless otherwise noted, the content of this repository is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>. 

Copyright Martin P. Robillard 2021