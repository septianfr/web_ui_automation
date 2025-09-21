# web_ui_automation

## Description

This repository contains a Web UI test automation framework built with:

- **Cucumber** for Behavior-Driven Development (BDD) using Gherkin syntax  
- **Java** as the programming language  
- **Selenium WebDriver** to automate browser interactions  
- **Gradle** for build and dependency management  
- **Page Object Model (POM)** design pattern to separate UI logic from test scripts  

## Project Structure

src/
├── test/java/page/loginPage.java
├── test/java/StepDefinitions/loginTest.java
├── test/java/runner/TestRunner.java
└── test/resources/features/login.feature

## Sample Test Case

This project includes 3 sample test cases for login functionality on the demo site https://www.saucedemo.com/:

1. Positive test case (valid credentials)
2. Negative test case (invalid credentials)
3. Edge test case (edge values)

## Dependencies

io.cucumber:cucumber-java — Cucumber framework for Java
io.cucumber:cucumber-junit — Cucumber and JUnit integration
org.seleniumhq.selenium:selenium-java — Selenium WebDriver
junit:junit — JUnit testing framework

All dependencies are managed through Gradle (see build.gradle).
