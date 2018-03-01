# Java TDD manual for Eclipse: 
## Goal: setting up Junit 

1.	Right click project name, click on Build Path -> Configure Build Path
![](https://github.com/KaiTang26/Java_testing_framework_notes/blob/master/documents/1.png)

2.	Add Junit Libraries 
![](https://github.com/KaiTang26/Java_testing_framework_notes/blob/master/documents/2.png)


3.	Create a Source Folder named as test
![](https://github.com/KaiTang26/Java_testing_framework_notes/blob/master/documents/3.png)


4.	Create a Junit test class 
5.	Use annotations and create method 
- @BeforeClass/@AfterClass: ---- public static void methodName(){};

- @Before/@Test/@Aftrer: ---- public void methodName(){};

6.	Use Assert to test each condition:
- Assert. assertEquals()
- Assert.assertTrue()
- Assert. assertNull()
- Assert. assertFalse()
- Assert.assertNotNull()

7.	Running test: 
![](https://github.com/KaiTang26/Java_testing_framework_notes/blob/master/documents/4.png)



## Goal: setting up Mockito

1: Complete step 1 to 2 of setting up Junit

2: Download .jar file >>> **mockito-all-x.x.x.jar**

3: use Configure Build Path to Add External JARs
![](https://github.com/KaiTang26/Java_testing_framework_notes/blob/master/documents/5.png)


4: Create mocked object:
![](https://github.com/KaiTang26/Java_testing_framework_notes/blob/master/documents/6.png)



5: Setup Mockito test for Verify Behaviour:
![](https://github.com/KaiTang26/Java_testing_framework_notes/blob/master/documents/7.png)


line73-74: used to setup the mock object 

line 76: initialize objectForOutterClass with Mocked object

line 78: call outterMathod, which will invoke innerMathoud

line 80: verify invoking of innerMathod

*****:   
![](https://github.com/KaiTang26/Java_testing_framework_notes/blob/master/documents/8.png)
