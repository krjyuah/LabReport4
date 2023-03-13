# Reproduce the Task From the Competition

1. **Setup** Delete any existing forks of the repository you have on your account

![Image](Screenshot_20230224_113057.png)

![Image](Screenshot_20230224_113550.png)

2. **Setup** Fork the repository

![Image](Screenshot_20230224_113716.png)

3. **The real deal** Start the timer!

4. Log into ieng6

![Image](Screenshot_20230224_113951.png)

```
# code block
type in 'cs15lwi23xxx@ieng6.ucsd.edu' and password
```
Then **Enter**


5. Clone your fork of the repository from your github account

![Image](Screenshot_20230224_114212.png)

click git clone, then **ctrl-c** from github, back to vistual studio, **ctrl-v** to the command line
then **enter**

6. Run the tests, demonstrating they they fail

![Image](Screenshot_20230227_091638.png)
type in the Junit test code so I cd into lab7, ctrl-v from the week 3 meterial **crtl-c**, and **ctrl-v** the test code to the command line, for the end of java part, change the  to ListExamplesTests

```
# code block
javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests
```


7. Edit the code file to fix the failing test

![Image](Screenshot_20230224_124500.png)

type nano ListExamples.java get into the nano system, and 44 times **down** and 12 times **right** to find the error lines, which is the last while loop,
it is index2 +=1 and not index1 +=1. After change it, type in **ctrl-o** to save the files,, **enter**, **ctrl-x** to exit the sysytem

8. Run the tests, demonstrating that they now succeed

![Image](Screenshot_20230224_125511.png)

**Up** **Up** **Up** **Up** which is 4 times up then **Enter** to find the Junit javac test code, then **Up** **Up** **Up** **Up** 4 times up and then click **Enter** to find the Junit java test code

9. Commit and push kthe resulting change to your Github account(you can pick any cimmit message!)

![Image](Screenshot_20230224_125511.png)

First type in git add List **tab** (which will fill out the compelete word automatic).java, **enter**, then git commit -m "Updated", **enter** , then git push, **enter** to push the save file to github page
