Day 1 – Automation Testing: Learning & Setup Report
Date: 20 November 2026
Project: QX Automation – OrangeHRM
Task: Automation Strategy and Framework Setup
1. Topics Learned
Today, I learned the fundamentals of automation testing, including:
•	Meaning and importance of automation testing.
•	Difference between manual testing and automation testing.
•	When automation testing is beneficial.
•	Software Testing Pyramid: Unit Testing, API Testing and UI Testing.
•	Introduction to Selenium, Playwright, REST Assured and Cucumber.
•	Maven project structure and dependency management.
•	Basics of Git and GitHub for version control.
2. Tools and Technologies
I understood the purpose of the following tools:
Tool	Purpose
Java 17	Programming language
Selenium	Browser automation
Playwright	Modern browser automation
Maven	Build and dependency management
JUnit 5	Test case execution
REST Assured	API automation
Cucumber	Behaviour-Driven Development
Git & GitHub	Version control and repository hosting
3. Practical Work Completed
1.	Installed and configured Java JDK 17.
2.	Installed and configured Apache Maven 3.10.1.
3.	Created the qx-automation Maven project.
4.	Created the basic automation framework folder structure.
5.	Configured pom.xml with Selenium, JUnit 5, REST Assured and Cucumber dependencies.
6.	Executed mvn clean install successfully and verified the Maven build.
7.	Reviewed the purpose of each folder in the automation framework.
4. OrangeHRM Automation Strategy
Prepared an initial automation strategy based on the Test Pyramid.
Unit Testing – JUnit 5
•	Input validation.
•	Employee data validation.
•	Date validation.
•	Reusable utility methods.
API Testing – REST Assured
•	Login API validation.
•	Employee creation and retrieval.
•	Employee search.
•	Authentication and invalid request scenarios.
UI Testing – Selenium
•	Valid and invalid login.
•	Logout functionality.
•	Employee search.
•	Add employee workflow.
•	Employee information verification.
•	Leave management navigation.
The strategy prioritises more unit tests, followed by API tests and fewer critical end-to-end UI tests.
5. Framework Folder Structure
Created the following structure:
qx-automation/
│
├── src/
│   ├── main/java/com/qx/
│   │   ├── config/
│   │   ├── drivers/
│   │   └── utils/
│   │
│   └── test/
│       ├── java/com/qx/
│       │   ├── tests/
│       │   ├── pages/
│       │   ├── api/
│       │   └── runners/
│       │
│       └── resources/
│           ├── features/
│           └── testdata/
│
├── pom.xml
├── README.md
└── .gitignore
6. Current Status and Next Steps
•	Maven project setup: Completed.
•	Framework folder structure: Completed.
•	Dependency configuration: Completed.
•	Maven build verification: Successful.
•	Git installation and GitHub repository setup: Pending.
•	First Selenium test execution: Pending.
7. Learning Outcome
I gained a basic understanding of automation testing concepts, the Test Pyramid, automation tools and Maven project management. I also learned how to establish a Java-based automation framework and prepare an automation strategy for the OrangeHRM application.
Next Plan: Complete Git and GitHub configuration, push the project repository, and start implementing Selenium test cases using JUnit 5 and Page Object Model.

