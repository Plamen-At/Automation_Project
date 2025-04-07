Automation-Test-Project

This is a Java-based UI test automation framework developed using Maven, Selenium WebDriver, and TestNG. The framework is designed to automate UI testing for the Skillo Training Platform.

Design Pattern
This project follows the Page Object Model (POM) with PageFactory, ensuring better maintainability and scalability of test scripts.

Features
Automates five separated test scenarios for Skillo Automation QA course.
Test execution is managed by testng.xml file.
All tests run in Google Chrome web browser.
On failure, test reports are generated and stored in the reports/ directory.
Screenshots of failed tests are automatically saved in the screenshots/ directory.


The framework includes automated test cases for the following functionalities:
SignUpTests – Verifies the user registration process.

LoginTests – Ensures login and authentication work as expected.

UserEditTests – Tests profile information editing capabilities.

FollowTests – Validates follow/unfollow user functionality.

LogOutTests – Confirms successful user logout.

How to Run the Tests

Install dependencies:

mvn clean install

Execute the tests:

mvn test -DsuiteXmlFile=testng.xml

License

This project is licensed under the MIT License.