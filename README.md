# COMP303 - Software Design (Fall 2023)

Provides an introduction to software design, with a focus on object-oriented design. 

| |  |
| --- |---|
|**Instructor:** |[Martin Robillard](http://www.cs.mcgill.ca/~martin)|
|**Time and Place:** |Mondays and Wednesdays, 8:35-9:55 in [ENGMC 304](https://maps.mcgill.ca/?cmp=1&txt=EN&id=McConnellEng).|
|**Policy on lectures:**| Lectures are designed as an interactive in-person activity during which anyone should feel comfortable to participate. Lectures are therefore **not recorded** and may not be independently audio- or video-recorded. It is permitted to take pictures of the presentation screen for _private study_ if the picture does not include the instructor or other students. Attendance is recommended but not mandatory. |
|**Contact:** | The fastest way to get answers to questions about the course is to use the course's **discussion board**. The instructor and TAs will also be available in person during **office hours** (times and place posted on myCourses). Please resort to **email** only for exceptional and confidential administrative matters (note that response delays are inevitable due to email volume). The email addresses of the TAs will be available through myCourses.|

## Course Topics
* **Concepts and Principles:** Encapsulation, information hiding, abstraction, immutability, interface, reference sharing, escaping references, polymorphism, loose coupling, reusability, extensibility, separation of concerns, interface segregation, concrete and abstract object states, object life cycle, object identity, object equality, object uniqueness, state space minimization, unit testing, regression testing, quality attributes of unit tests, test suites, test coverage, divide and conquer, law of Demeter, code reuse, extensibility, Liskov substitution principle, inversion of control, model–view–controller
(MVC) decomposition, callback method, behavior parameterization, first-class functions, higher-order functions, functional programming.
* **Programming Mechanisms:** Typing, enumerated types, scopes, access modifiers, assertions, Java interfaces, interface implementation, null references, final variables, optional types, nested classes, closures, unit testing frameworks, JUnit, metaprogramming, annotations, aggregation, delegation, cloning, inheritance, subtyping, downcasting, object initialization, super calls, overriding, overloading, abstract classes, abstract methods, final classes, final methods, application framework, event loop, graphical user interface (GUI) component graph, functional interfaces, lambda expressions, method references, streams.
* **Design Techniques:** Class definition, object diagrams, immutable wrappers, reference copying, copy constructors, design by contract, decoupling behavior from implementation, interface-based behavior specification, class diagrams, function objects, iterators, state diagrams, test suite organization, use of test fixtures, testing with stubs, testing private structures, use of test coverage metrics, testing exceptional conditions, sequence diagrams, combining design patterns, inheritance-base reuse, class hierarchy design, adapter inheritance, event handling, GUI design, behavior composition, functions as data sources, interface segregation with first-class functions, pipelining, map–reduce.
* **Patterns and Antipatterns:** Primitive Obsession*, Inappropriate Intimacy*, Iterator, Strategy, Switch Statement*, Speculative Generality*, Temporary Field*, Long Method*, Null Object, Flyweight, Singleton, Duplicated Code*, God Class*, Message Chain*, Composite, Decorator, Prototype, Command, Template Method, Pairwise Dependencies*, Observer, Visitor. 

## Prerequisites
The official prerequisites are COMP206 and COMP250. This assumes active participation in these courses and the accumulation of **a minimum level of Java programming experience**. This means that students registering to take COMP 303 should be able to write Java programs to solve small and well-defined problems, use Git to organize their work, and use a debugger to trace through the execution of the code and inspect run-time values. Students who feel they could use additional programming experience are encouraged to take a few more COMP courses or undertake a practice project or two before taking COMP303.

The [self-assessment question](Assessment.md) will help you gauge your level of preparation for the course.

## Learning Outcomes
After this course, you should be able to... 

* *Name, using the proper terminology:* The important principles, programming techniques, and tools of object-oriented software design;
* *Describe and explain:* The important important principles, mechanisms, techniques, and patterns of software design;
* *Apply:* The important principles, mechanisms, techniques, and patterns of software design to provide effective solutions to realistic design problems;
* *Evaluate:* The quality of design solutions
* *Write:* well-designed, correct, and easily understandable software.

## Reference Material

* **Required Textbook**: [Introduction to Software Design with Java, 2nd edition](https://link.springer.com/book/10.1007/978-3-030-97899-0). The electronic version of this book is **free** for McGill users with library access. 
* **Companion Website**: [DesignBook @ GitHub](https://github.com/prmr/DesignBook)
* **Recommended Reference:** [Java: The Complete Reference](https://learning.oreilly.com/library/view/java-the-complete/9781260440249/?ar), also available at no cost from the McGill library.
* **Sample Projects:** [COMP303 Starter](https://github.com/prmr/COMP303Starter), [Minesweeper](https://github.com/prmr/Minesweeper), [Solitaire](https://github.com/prmr/Solitaire)
* **Diagramming Tool:** [JetUML](https://www.jetuml.org/)

## Course Work and Evaluation

This course is divided into nine modules that map to the chapters of the book. Except for the introduction, chapters are spread over two or three lectures and involve required reading and practice exercises. 

**The lectures are designed to complement and enrich the required reading, not repeat it.** To get the most of the lectures, the corresponding reading should be done _before_ the lecture. Without the required preparation, the lectures will appear confusing.

Practice exercises are organized in terms of the chapter structure and are available on the [companion website](https://github.com/prmr/DesignBook). The exercises are designed to help you learn as effectively as possible: you can do them at your own pace, individually or in a group, repeat what's necessary, seek advice from anyone, and make mistakes and learn from them. For these and other reasons, they would be a poor choice for *testing* your knowledge of the material, so they are not graded. Instead, your practical skills will be evaluated through *lab tests*.

**To be able to follow the pace of the course, the reading should be done before the chapter lectures and the exercises completed within one week of the end of the second lecture of the chapter.**

**The recipe for success** in COMP 303 is to prepare for lectures by regularly doing the required readings in advance, attending the lectures, then completing the related exercises as soon as possible. If you do this you may be pleased to discover that the material will grow on you almost subconsciously. In contrast, **attempting to memorize the book and lecture material before exams is likely to result in some disappointment**.

| Evaluation Activity                        | Weight |
| ------------------------------------------ | ------ |
| Lab tests (4, with equal weight)           | 25%    |
| Midterm exam                               | 25%    |
| Final exam                                 | 50%    |

**Important Notes:**

- **Accommodation 1 (exams)**: If the grade of the final exam exceeds that of the midterm, the  grade of the final exam will replace the grade of the midterm. This accommodation covers the case where students are unable to write the midterm.
- **Accommodation 2 (labs):** The grade of the lab tests will be the average of the grades of the best three lab tests. This accommodation covers the case where students are unable to complete a lab test.
- **Date and place of the in-person midterm:** Thursday October 20th 6pm in ENGMC 204 (A-R incl.) and SADB M-1 (S-Z).
- All material covered in the textbook, lectures, and in the practice exercises is subject to assessment.
- Here is a [sample midterm](https://github.com/prmr/COMP303/blob/2019F/Sample-Midterm.pdf). This sample is provided so that you can familiarize yourself in advance with the *exam style*. **However**, the course schedule varies slightly from section to section so **the topics covered in the sample midterm are not necessarily representative of what will be evaluated in your own midterm**.

## Schedule

See myCourses for a detailed schedule and the lab sign-up sheet.

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a>

Unless otherwise noted, the content of this repository is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>. 

Copyright Martin P. Robillard 2023
