**What is JUnit?**
  - JUnit is a testing framework for Java.<br />
  - It is used to write and run repeatable tests.<br />
  - Junit helps verify that individual code units work as expected.<br />
  - Write tests using @Test Annotation.<br />
  - Junit annotations make test management easy.<br />
  - Assertions are used to check if the results are expected.<br />
  - Junit has test runners execute tests and report results.<br />
  - JUnit can integrated with IDEs and build tools(Maven, Gradle) for easy execution.<br />

**Junit Basics**
- The class we want to test is called a Class under test.
- The method we want to test is called a Method under test.
- A test class in JUnit is a regular Java class that contains one or more test methods. These test methods are annotated with @Test and contain the 
  logic to test a specific code.
- A test method is a method within a test class that is annotated with @Test. This method contains assertions that check the expected outcomes of the 
  code being tested
- Assertions are used to check whether the code under test behaves as expected. Junit provides several assertion methods, such as 
  assertEquals,assertFalse,assertTrue,assertNotNull and assertThrows.
- The test runner is responsible for executing the test methods in a test class and reporting the results. In Junit,the test runner is typically 
  provided by an IDE or build tool, such as Eclipse, IntelliJ IDEA, Maven or Gradle.



