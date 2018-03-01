###Java TDD manual: 
Goal: setting up Junit 

1.	Right click project name, click on Build Path -> Configure Build Path


2.	Add Junit Libraries 


3.	Create a Source Folder named as test

4.	Create a Junit test class 
5.	Use annotations and create method 
@BeforeClass/@AfterClass: ---- public static void methodName(){};

@Before/@Test/@Aftrer: ---- public void methodName(){};

6.	Use Assert to test each condition:
Assert. assertEquals()
Assert.assertTrue()
Assert. assertNull()
Assert. assertFalse()
Assert.assertNotNull()

7.	Running test: 


Goal: setting up Mockito

1: Complete step 1 to 2 of setting up Junit

2: Download .jar file >>>mockito-all-x.x.x.jar

3: use Configure Build Path to Add External JARs

4: Create mocked object:


5: Setup Mockito test for Verify Behaviour:

line73-74: used to setup the mock object 

line 76: initialize objectForOutterClass with Mocked object

line 78: call outterMathod, which will invoke innerMathoud

line 80: verify invoking of innerMathod

*****:   