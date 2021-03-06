Comp 124 - Homework #0
===

# Overview

The goal of this homework is to familiarize you with the development environment you will be using in this class, including IntelliJ, JUnit, Git and GitHub.
You will correct a simple class that calculates the area of two shapes: a square and a circle.
Although the programming in this project is not challenging, the setup of your development tools may be.
You will often encounter an unexpected challenge or two when learning a new technology!

### Preparing Your Workspace

1. If you haven't already done so, begin by following the instructions in part one of the Google Doc to [set up your IntelliJ project on your laptop](https://docs.google.com/a/macalester.edu/document/d/1raRHiB6uUe8Yor05b5bS7LM0Q-wRzumbXiBIVUrhe98/edit?usp=sharing).
2. Follow the instructions in part two of the same document to clone https://github.com/mac-comp124-s16/124-hw0. After you fork the repo it will be available at https://github.com/your-github-username/124-hw0.

### Setup the assignment

1. Open the AreaTest file. The @Test annotation may appear in red. If so, this means that there is a compilation error, and it is occurring because we need to add the junit library to the project. Click on the red @Test, and wait for the red light bulb to pop up. Click the red light bulb and select "Add junit.jar to classpath." The red statements should turn black.
2. Run the tests. Right click on the class name AreaTest. Select Run -> AreaTest. 
3. IntellIj will run the tests, but they will fail. Each test has an orange exclamation points and error messages appear in the console when they are complete.

### Complete the assignment.

1. Open Area.java
2. Fix the two lines marked "TODO" in Area.java.   You may **not** change AreaTest.java.
3. Rerun the unit test AreaTest.java. Look for a green "OK" next to each test.
4. If (unit tests do not pass) goto step 2.

### Submit your asssignment.
1. Commit your changes: Select the hw0 module, right click, and select Git -> Commit Directory.
2. You should see all the source files you changed (which is only Area.java) with a checkmark in the popup.
3. Change the "commit" button to "commit and push" in the lower righthand corner.
4. Write an appropriate message in the comment box.
5. IMPORTANT: Select *"commit and push"* (not just commit) in the lower right.
6. Select "push" to send your changes to GitHub.
7. IntelliJ should say "push successful"
8. Visit your github site in your web browser to make sure the changes you made were pushed correctly.
9. Proclaim victory!  You've finished your first homework assignment!
