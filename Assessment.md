# Self-Assessment Questions

The following questions can be used as a guide to help assess your level of readiness to take COMP303. It is not a perfect instrument, and comes with no guarantee. However, if you are wondering whether you are ready to take the course, this is a good place to start. Once you are done (or have gone as far as you can), check your progress against the [self-evaluation grid](Evaluation.md).

## Question 1

Complete the following task using only the programming tools available in your IDE, the [Java API documentation](https://docs.oracle.com/javase/8/docs/api/), and one basic Java programming book (for example [ThinkJava](http://www.greenteapress.com/thinkapjava/thinkapjava.pdf)). This excludes looking for answers on forums and websites (which you won't have access to during the exam).

Given an input text string, find the word that occurs the most frequently, and retrieve this word along with its frequency. Ignore the capitalization when counting frequencies (e.g., "The" and "the" are the same). Consider a word to be any string of characters separated by one or more white space (return, tab, or space), comma (`,`), or period (`.`). If there are more than one word with equal maximum frequency, you can return any of them.

You can use the following code to get started:

```java
public class Test {

	private static final String TEXT = "Lorem ipsum dolor sit amet, "
			+ "consectetur adipiscing elit. Nunc quis tempor tellus. Nulla "
			+ "tincidunt pretium justo non finibus. Fusce quis bibendum ante. "
			+ "Vivamus a ex maximus, iaculis nunc eu, posuere augue. Vestibulum "
			+ "ante ipsum primis in faucibus orci luctus et ultrices posuere "
			+ "cubilia Curae; Nullam ut lorem metus. Vivamus consequat eros "
			+ "sed lorem rhoncus finibus. Sed porta euismod consequat. Etiam "
			+ "sodales accumsan nulla, non pretium ex tincidunt eget. Aliquam "
			+ "nibh erat, tristique vel augue sit amet, sodales sollicitudin leo. "
			+ "Mauris in arcu volutpat, efficitur erat imperdiet, finibus dolor. "
			+ "Vestibulum a dolor sed justo tempor elementum. Pellentesque eu "
			+ "tincidunt ex, et posuere orci. Phasellus non nibh non nibh pharetra "
			+ "lobortis. ";
}
```

For this input your program should return something like this:

```
Most frequent: "non" (4 occurrences)
```

## Lab Tests

The following questions can be used to assess your level of programming skills for lab tests. The three tasks ask you to modify the code located at
https://github.com/prmr/COMP303Starter/tree/master/labtest01/labtest01
You should be able to complete each of the three tasks in about 15 minutes.
A familiarity with the manipulation of the common data structure in Java (Map, List, Set) can help.

**Task 1:** Write a method `int countItems(Item target)` in the Corporation class that returns the total number of the `target` item in all inventories of the corporation.

**Task 2:** Add a `long lastModified()` method to the Inventory class that returns the time of last modification (last call to `stock()` or `dispose()`) of the inventory. Hint: Use `System.currentTimeMillis()` to get the current time.

**Task 3:** Add a `void clearCache()` method to the Inventory class that removes all items that are no longer available (quantity = 0) from the `aInventory` HashMap.

Each solution can give you up to 5 marks. To evaluate your solutions, we will use the following grid:

```
No code or has no idea what’s going on: 0
Is there a coherent solution that fulfills (at least partially) the requirement?
YES
	Perfect (optimal) solution: 5
	With minor design issues, typos, or non-directed hints: 4
	With major design flaws, compilation problems, or directed hints: 3
NO
	Missing only one key element: 3
	Coherent set of elements towards a complete solution: 2
	Confused set of elements related to the requirement: 1```
