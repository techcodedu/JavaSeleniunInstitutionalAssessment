# GitHub Users Search Functional Testing

## Test Description
In this test, you will create an automated test suite using Selenium WebDriver in Java, TestNG, and the Page Object Model (POM) design pattern. Your test suite will cover the functionality of the GitHub Users Search website (https://gh-users-search.netlify.app/). You will create a test suite that includes tests for user search functionality, user details, and user repositories. You will also need to generate a test report using TestNG's `MySuite`.

## Requirements
1. Open the GitHub Users Search website in a browser.
2. On the homepage, search for a GitHub user using the search functionality.
3. Verify that the search results are relevant to the search query.
4. Click on a user from the search results.
5. On the user details page, verify that the user details such as name, location, and bio are displayed correctly.
6. Navigate to the user's repositories tab and verify that the repositories are listed correctly with their names and descriptions.
7. Use TestNG annotations such as `@BeforeTest`, `@Test`, and `@AfterTest` to structure your tests.
8. Apply the Page Object Model (POM) design pattern to organize your code.
9. Use assertions to validate the data displayed on the pages.
10. Generate a test report using TestNG's `MySuite`.

## Steps
### Setup
- Follow the same setup process as mentioned in your previous test description.

### Create Page Objects
- Create separate Java classes for each page of the GitHub Users Search website that you will be interacting with: `HomePage`, `UserDetailsPage`, and `UserRepositoriesPage`.
- In each class, create methods for the actions that can be performed on the page, such as searching for a user, viewing user details, and viewing user repositories.

### Create Test Cases
- Create a Java class called `GitHubUsersSearchTest`.
- In this class, create methods for each of the test cases mentioned in the 'Requirements' section above. Use the `@Test` annotation for each test case method.

### Generate Test Report
- Follow the same process as mentioned in your previous test description.

### Run the Test Suite
- Follow the same process as mentioned in your previous test description.

## Deliverables
1. The complete source code of your automated test suite.
2. The generated test report.

## Evaluation Criteria
1. Your test suite should cover all the requirements mentioned above.
2. Your code should be well-structured and well-commented.
3. You should use the Page Object Model (POM) design pattern correctly.
4. Your test report should be comprehensive and should include details of each test case execution.

## Additional Requirements
1. Implement data-driven testing by using a data provider to test the search functionality with different search queries.
2. Implement a test case to verify that an error message is displayed when searching for a non-existing user.
3. Implement a test case to verify that the 'Load more' button in the repositories tab works correctly and loads more repositories.

## Submission
1. Push the complete source code of your automated test suite to your GitHub account.
2. Submit the link to your GitHub repository and the generated test report via this [Google Form](https://forms.gle/eP382LbM3Y5uTBEd7).
