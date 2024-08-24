# Automated Testing Project for prom.ua

This repository contains an automated testing project for the prom.ua website, aimed at ensuring its functionality and reliability. The testing framework is developed in Java, leveraging Selenium WebDriver for web automation, TestNG for test management, Allure for comprehensive test reporting, and Jenkins for continuous integration.

## Project Structure

### `src/main/...`
- **BasePage**: Base class for all page objects, providing common functionality.
- **FavoritePage**: Page object representing the Favorites feature on the site.
- **FilterPage**: Page object for handling filter functionalities.
- **LoginPage**: Page object for the login functionality.
- **LogoutPage**: Page object for the logout functionality.
- **MenuPage**: Page object for the site’s main menu navigation.
- **SearchPage**: Page object for the search functionality.

### `src/test/...`
- **BaseTest**: Base class for all test cases, setting up common test configurations.
- **FavoriteTest**: Test cases for the Favorites feature.
- **FilterTest**: Test cases for the filtering functionality.
- **LoginTest**: Test cases for login functionality.
- **LogoutTest**: Test cases for logout functionality.
- **MenuTest**: Test cases for main menu navigation.
- **SearchTest**: Test cases for search functionality.

### Configuration Files
- **`allure.properties`**: Configuration for Allure reporting.
- **`testNG.xml`**: Configuration file for organizing and executing TestNG test suites.
- **`pom.xml`**: Maven configuration file for managing project dependencies and build settings.

## Key Technologies Used

- **Selenium WebDriver**: Utilized for browser automation, enabling seamless interaction with web elements on the prom.ua website.
- **TestNG**: Employed for organizing test suites, executing tests, and generating detailed test reports.
- **Allure**: Integrated for enhanced test reporting, providing detailed insights into test execution and results visualization.
- **Jenkins**: Implemented for continuous integration, automating the build and test execution processes for streamlined development workflows.
- **Java**: The primary programming language for developing test scripts, offering robustness, scalability, and cross-platform compatibility.
- **Maven**: Used as the project management and build automation tool, simplifying dependency management and project configuration.

## Features

- **Test Suites**: Organized test suites covering various functionalities of the prom.ua website, including user registration, product search, checkout process, and more.
- **Cross-Browser Testing**: Supports testing across multiple browsers, ensuring compatibility and consistency across different environments.
- **Comprehensive Reporting**: Generates detailed test reports using Allure, providing stakeholders with clear insights into test execution, results, and any encountered issues.
- **Continuous Integration**: Integrated with Jenkins for automated builds and test executions upon code changes, facilitating early detection of defects and ensuring code quality.

## How to Use

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/MACaron99/test-prom-ua
2. **Build and Run:**
   - Open the project in your preferred IDE.
   - Build the project using Maven:
     ```bash
     mvn clean install
   - Run the application:
     ```bash
     mvn spring-boot:run
