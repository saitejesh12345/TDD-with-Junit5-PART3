# TDD-with-Junit5-PART3
You can check out information regarding  TDD-with-Junit5-PART2 in Wiki pages of that repository and you can check clear description and what we are going to implement in part3 i have mention clearly in README File please go through it.

 **we will add extra features to the application like adding Premium flight and write effectively J-unit test cases**
 1. one of feature and Annotation we are using is @Nested class to be applied in inner test classes.
 
 2.we already have 4 testing methods we already know what  they are intend to do by checking their names.But we can do STill better **The Logic of testing may be seperated at the level of inner classes.
 
 3.In order to better and control the logic and prove important information to the ones running the tests.we will use** @DisplayName and @BeforeEach Annotations**
 
 4. Lets have a quick look of **TDD-with-Junit5-PART2** of current state of AirportTest class.It contains Two test for EconomyFlight and Two tests for Business Fligt.
 
 5.Junit5 Provides the possibility to use Nested Test so we can Introdue a Minor economyFlight test class,annotate it as nested,and move here testing logic for the economy flight

6.And we can introduce an inner businessFlight test class annotate it as nested
and move here the testing logic for business flight.

7.we can also reduce code application and have a economyFlight and businessFlight as fields into the new inner classes and reinitialize the objects before each test.

8. use @DisplayName annotation and we can explain what we are doing in plane english.

9.we can also use TDD related to given,when then it helps us to understand the logic,when some particular condition are given when we do action,then we are expecting some results.

**we will add extra features to the application like adding Premium flight  and we will write test cases for new functionality we will add the code to implement new functionality** on next ** PART4 now in this PART3 we have wrote effective  test cases.**

**...........................................................................................................................................................**

 


