# Native Playwright Test Project

This project is designed to run UI automation tests using Playwright.

## Pages Under Test:
- <URL_1>
- <URL_2>

## Prerequisites

Make sure you have the following installed:

1. [Node.js](https://nodejs.org/)  
   - You can install Node.js by running:
     ```bash
     brew install node
     ```

2. Playwright
   - Install Playwright via npm:
     ```bash
     npm install -D playwright
     ```
   - Install browsers:
     ```bash
     npx playwright install
     ```

## How to Run Tests

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run Playwright tests:
   ```bash
   npx playwright test
   ```

4. Run Playwright tests in Playwright Test UI:
   ```bash
   npx playwright test --ui
   ```

## Writing and Running Tests
All test cases will be created inside the tests folder using Playwright's test runner. For more details on writing tests with Playwright, refer to the official [Playwright Documentation](https://playwright.dev/docs/intro).


This provides basic information on setting up and running the project. Adjust the page URLs and repository details as necessary.