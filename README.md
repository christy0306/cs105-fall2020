# A01 - HelloWorld

## Pre-requisites
Ensure you have completed the tutorials linked from the Canvas homepage on command line (if you are unfamiliar), git/github, and Visual Studio Code.  You will find it easier to understand if you do.

## Overview
Note that all assignments must be able to run in the lab. If you do your assignment from home then it must run as if it was done in the lab. Assignments that are not compatible recieve no credit and you will not be allowed to resubmit. Please test your code in the lab before submitting it.

This is your first assignment and this assignment's purpose is to give you some practice using the tools that we will be involved with all semester.

This exercise should help you adapt to the class' workflow.The basic project name of this exercise is HelloWorld, but the project should be created using the full project name.  To understand how to create and name your projects, you should first read Canvas web page titled **How to Start Every Project in this Class**. You can find this page by looking on the class home page. It should be in the first block.

After you have read that page follow the instructions. The ProjectName mentioned on the page is called HelloWorld for this assignment. All assignments start with a sentence giving you the name of the project. You can see this above in the yellow highlighted word.

Adding and Running Java Code
Once you have followed the instructions shown on the "How to Start Every Project in this Class" web page you should have a file called Program.java. Replace all of the code present in that file with the code shown below. It is **critical** that the folder structure match the instructions in that document. Otherwise, Java won't find your code and you won't be able to compile, run, or test it.  This includes spelling and case sensitivity. To be more precise, your code should be in the following path {project-root}\src\main\java\edu\sbcc\cs105 where {project-root} is a placeholder for the name of the project folder on disk.


```Java
package edu.sbcc.cs105;

public class Program {

    public static void main(String[] args) {
	    System.out.println("Hello, World");
    }

}
```

You can simply copy the code from the grey box and paste it into the Program.java file. Save it. Now run the file by choosing Debug -> Start Debugging or Start Without Debugging.  You should have the Program.java file open and be the active document when you execute the Start command

## Run Unit Tests

In the Visual Studio Code Activity Bar (docked on the left edge of the applicatoin), select the Beaker icon (Unit Tests). To run the unit test, select the item that starts with the word Test (in this case TestHelloWorld) and click the run button.  If it succeeds, you should see an All and a green Passed status indicator with the number of tests in each. Hopefully, the number passed equals the total number.  If something fails, you'll see a red Failed status indicator. To see what went wrong, expand the Test method

**Unit Test Runner**

![run unit tests](images/RunUnitTest.png?raw=true)

**Failed Test Run**

![failed test run summary](images/FailedUnitTestRun.png)

**Failed Test Run Details**

![failed test run details](images/FailedUnitTestRunDetail.png)

**Successful Test Run** 

![successful unit test run](/images/SuccessfulTestRun.png)

## How to turn in this exercise ##
Follow the instructions in Canvas on "How to Submit Assignments"

