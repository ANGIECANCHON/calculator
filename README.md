# test calculator

## Description

Test automation on the android calculator in which the sum of two numbers
going to be validated, in this case 2 + 4, it's validated that the result is 6

## To Compile project

In this project I used:
- IDE intelliJ IDEA 
- SDK Java 1.8
- Maven to build the project
- Modules: Selenium, appium, testng (these are defined in the pom.xml)

## To build project 

If you don not use intelliJ IDEA, you have to install maven and excecute
```
mvn clean
mvn verify
mvn test -e
```

If you use intelliJ just click in build project

##How to improve the test?

- generate an ordered structure of all the code layers under a test methodology such as BDD or TDD
- Make a cleaner code out of comments with impressions to the log
- Move selectors away from class logic and capabilities
- Do not use literal text within the code, move everything to constants
- More base information could be generated within the tutorial, such as documentation on capabilities and libraries to use
