# JavaSeleniunInstitutionalAssessment

## Test Description
In this test, you will create an automated test suite using Selenium WebDriver in Java, TestNG, and the Page Object Model (POM) design pattern. Your test suite will cover the functionality of one of the following e-commerce websites: Alibaba, Lazada, or Shopee. You will be responsible for choosing one of these websites and creating a test suite that includes tests for product search, product details, and adding a product to the cart. You will also need to generate a test report using TestNG's `MySuite`.

## Requirements
1. Open the selected e-commerce website in a browser.
2. On the homepage, search for a product using the search functionality.
3. Verify that the search results are relevant to the search query.
4. Click on a product from the search results.
5. On the product details page, verify that the product details such as name, price, and description are displayed correctly.
6. Add the product to the cart.
7. Navigate to the cart page and verify that the product has been added to the cart correctly.
8. Use TestNG annotations such as `@BeforeTest`, `@Test`, and `@AfterTest` to structure your tests.
9. Apply the Page Object Model (POM) design pattern to organize your code.
10. Use assertions to validate the data displayed on the pages.
11. Generate a test report using TestNG's `MySuite`.

## Steps
### Setup
- Create a new Java project in your IDE.
- Add the Selenium WebDriver and TestNG dependencies to your project.
- Use WebDriverManager to handle driver instantiation.
# Project Structure

The project is organized into different folders for better structure and maintainability. 

- `src/test/java`: This is the source folder where all the test code resides.
    - `pages`: This folder contains the Page Object Model (POM) classes for the Home page, Product page, and Cart page.
        - `HomePage.java`: This is the POM class for the Home page.
        - `ProductPage.java`: This is the POM class for the Product page.
        - `CartPage.java`: This is the POM class for the Cart page.
    - `tests`: This folder contains the actual test classes where the test methods are written.
        - `ECommerceTest.java`: This is the test class that contains the test methods.

- `pom.xml`: This file contains the project configurations and dependencies needed for the project.


### Create Page Objects
- Create separate Java classes for each page of the e-commerce website that you will be interacting with: `HomePage`, `SearchResultsPage`, `ProductDetailsPage`, and `CartPage`.
- In each class, create methods for the actions that can be performed on the page, such as searching for a product, viewing product details, and adding a product to the cart.

### Create Test Cases
- Create a Java class called `ECommerceTest`.
- In this class, create methods for each of the test cases mentioned in the 'Requirements' section above. Use the `@Test` annotation for each test case method.

### Generate Test Report
- Configure TestNG to generate a test report using `MySuite`.
- Run your test suite and verify that the test report is generated correctly.

### Run the Test Suite
- Run your test suite and verify that all the test cases pass.
- Check the generated test report for details of the test execution.

## Deliverables
1. The complete source code of your automated test suite.
2. The generated test report.

## Evaluation Criteria
1. Your test suite should cover all the requirements mentioned above.
2. Your code should be well-structured and well-commented.
3. You should use the Page Object Model (POM) design pattern correctly.
4. Your test report should be comprehensive and should include details of each test case execution.

## Submission
1. Push your complete solution to your GitHub account. Make sure your repository is public so that it can be accessed for evaluation.
2. Copy the link of your GitHub repository.
3. Submit the link of your GitHub repository via this [Google Form](https://forms.gle/rRJwKHTMZyKfnki58).

Your submission will be evaluated based on the criteria mentioned in the 'Evaluation Criteria' section. Make sure to test your solution thoroughly before submitting.

Good luck!


> **Note:** Be mindful of the terms of use of the e-commerce website you choose. Some websites prohibit automated access or have strict rate limits. It is always best practice to check the website's terms of use and to test responsibly.
