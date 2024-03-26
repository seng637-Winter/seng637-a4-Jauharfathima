**SENG 637 - Dependability and Reliability of Software Systems**

**Lab. Report \#4 – Mutation Testing and Web app testing**

| Group \#:      |     |
| -------------- | --- |
| Student Names: |     |
|                |     |
|                |     |
|                |     |

# Introduction

# Analysis of 10 Mutants of the Range class 

# 3. Report all the statistics and the mutation score for each test class

# *Statistics and Mutation score for DataUtilities test classes before updation*

* (1) DataUtilitiesCalculateColumnTotal

* (2) DataUtilitiesCalculateColumnTotal2

* (3) DataUtilitiesClone

* (4) DataUtilitiesCreateNumberArray

* (5) DataUtilitiesCreateNumberArray2D

* (6) DataUtilitiesCumulativePercentageTest

* (7) DataUtilitiesEqual

* (8) DataUtilitiesTest1

* (9) DataUtilitiesTest2

# *Statistics and Mutation score for DataUtilities test classes after updation*

* (1) DataUtilitiesCalculateColumnTotal

* (2) DataUtilitiesCalculateColumnTotal2

* (3) DataUtilitiesClone

* (4) DataUtilitiesCreateNumberArray

* (5) DataUtilitiesCreateNumberArray2D

* (6) DataUtilitiesCumulativePercentageTest

* (7) DataUtilitiesEqual

* (8) DataUtilitiesTest1

* (9) DataUtilitiesTest2

# 4. Analysis drawn on the effectiveness of each of the test classes


| Test SUT       |  Updation  |  Line Coverage   |  Mutation Coverage   |  Test Strength   |
| -------------- | -----------| -----------------| ---------------------| -----------------| 
| CalculateColumnTotal  |  Before    | 95% (20/21)  | 47% (43/92)   | 47% (43/92)      |
|                       |  After     | 100% (25/25) | 58% (67/116)  | 58% (67/116)     |     
| CalculateColumnTotal2 | Before     | 100% (15/15) | 39% (26/66)   | 39% (26/66)      |    
|                       |  After     | 100% (60/60) | 55% (192/346) | 55% (192/346)    |  
| Clone                 |  Before    | 96% (23/24)  | 30% (130/428)   | 30% (130/428)   |
|                       |  After     | 100% (92/92) | 41% (498/1224)  | 41% (498/1224)  | 
| CreateNumberArray     |  Before    | 92% (11/12)  | 72% (169/234)   | 72% (169/234)|
|                       |  After     | 99% (67/68)  | 83% (1077/1299) | 83% (1077/1299) | 
| CreateNumberArray2D   |  Before    | 95% (19/20)  | 69% (204/296)   |  69% (204/296)  |
|                       |  After     | 99% (95/96)  | 81% (1257/1554) |  81% (1257/1554)| 
| CumulativePercentageTest |  Before    |            |                    |                  |
|                          |  After     |            |                    |                  | 
| Equal                    |  Before    | 100% (41/41) | 45% (945/2079)   | 45% (945/2079)   |
|                          |  After     | 100% (99/99) | 74% (3215/4337)  | 74% (3215/4337)  | 
| Test1                    |  Before    | 100% (28/28) | 45% (61/135)   | 45% (61/135)  |
|                          |  After     | 100% (64/64) | 53% (205/387)  | 53% (205/387) | 
| Test2                    |  Before    | 98% (59/60)  | 55% (260/471)  | 55% (260/470) |
|                          |  After     | 97% (36/37)  | 65% (180/278)  | 65% (180/277) | 

- From the above table we can analze that the Statistics of Line Coverage, Mutation Coverage and Test Strength.
- It is seen that the Mutation test scores of the DataUtilities Test classes have increased consistently after adding new test cases.
- When compared to the intial values before adding mutants the new Test suites have improved in overall quality.

# A discussion on the effect of equivalent mutants on mutation score accuracy

- In Part-1 of this Assignmet we have created mutants (faulty versions) of the SUIT, and then run the test suite against the mutants to determine if their test suite can accurately Kill the introduced mutants.
- The more mutants killed with resspect to the introduced mutants gives us the Mutation score percentage.
- A test SUIT with higher Mutation score after introducing equivalent mutants is said to have higher ability to detect coding errors.

# A discussion of what could have been done to improve the mutation score of the test suites

# Why do we need mutation testing? Advantages and disadvantages of mutation testing

# Explain your SELENUIM test case design process

# Explain the use of assertions and checkpoints

# how did you test each functionaity with different test data

# How the team work/effort was divided and managed

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the assignment itself
