# Test Automation University - Exploring Service APIs through Test Automation

This repository contains resources related to the "Exploring Service APIs through Test Automation" course at Test Automation University (TAU). Here, you'll find Postman collections and environments, along with my solutions to the course quizzes.

## Table of Contents

- [Introduction](#introduction)
- [Topics Covered](#topics-covered)
- [Directory Structure](#directory-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributions](#contributions)
- [Disclaimer](#disclaimer)

## Introduction

The "[Exploring Service APIs through Test Automation](https://testautomationu.applitools.com/exploring-service-apis-through-test-automation/)" course on Test Automation University is a great resource for learning and mastering service APIs. It equips you with the skills to build robust automated tests using industry-standard tools like Postman. This repository contains the test collection I created during the course and my solutions to the quizzes presented at the end of every chapter throughout the course.

## Topics Covered
- Basic Requests
- Importing Requests
- Creating Collections
- POISED API Testing Strategy
  - Parameters
  - Output
  - Interoperability
  - Security
  - Exceptions
  - Data
- Data-driven tests
- Advanced Tests
- Continuous Integration with Newman

## Directory Structure

The repository is organized as follows:

- `Chapter X/`: Each lecture from the course has its own directory.
  - `Chapter X Quiz.txt`: A text file corresponding to the quiz for the lecture. These files contain my solutions to the quiz questions.
- `RestfulBookerBVT.postman_collection.json`: This file contains a collection of API requests, organized and grouped for testing the Restful-Booker API. It is used to perform various API tests.
- `Local.postman_environment.json`: This file stores the environment-specific variables and configurations used for the local testing environment.
- `Production.postman_environment.json`: This file stores the environment-specific variables and configurations used for the production testing environment.

## Getting Started

1. Install Postman: [https://www.postman.com/downloads/](https://www.postman.com/downloads/)
2. Import Collections:
    - Download the entire repository or specific files.
    - In Postman, open `"File"` -> `"Import"` -> `"Select Files"` and choose the downloaded files.
3. Configure Environments:
    - Choose the appropriate environment file for your testing environment (e.g., "Local.postman_environment.json").
    - Go to `"File"` -> `"Import"` -> `"Select Files"` and select the chosen file.
4. Run Tests:
    - Within the collection, you can run individual requests or the entire collection.
    - For detailed instructions on test execution, refer to the TAU course materials.

## Usage

You can go ahead and explore my collection and quiz solutions by navigating to the specific chapter and associated directories within the repository. Each quiz text file contains my quiz answers.

Feel free to use these collections as reference code, study materials, or review materials to enhance your understanding of Postman. Additionally, you can review my quiz solutions to reinforce your knowledge of the course content.

## Contributions

Contributions to this repository are welcome. If you have alternative code implementations, suggestions for improvements, or corrections to my answers, please consider submitting a pull request. If you encounter any issues with my solutions or have additional insights to share, please open an issue.

## Disclaimer
> This is not the official implementation. The official implementation may be found [here](https://github.com/ambertests/explore-with-postman/tree/master/tau).
