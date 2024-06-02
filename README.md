# APITestingPostman
### Overview
APITestingPostman is a learning project designed to demonstrate API testing using Postman. This repository contains Postman collections and scripts to automate and validate 2 main API endpoints:

1. **TRELLO REST APIs**: Trello provides a simple RESTful web API where each type of resource (e.g. a card, a board, or a member) has a URI that you can interact with. Full documentation found [here](https://developer.atlassian.com/cloud/trello/rest/api-group-boards/#api-boards-id-memberships-get).
2. **fakerestapi**: Simple collection of endpoints of a library-system. [swagger documentation here](https://fakerestapi.azurewebsites.net/index.html) and [source code here](https://github.com/kasuken/fakerestapi/tree/3da2fc66d9efed380ac5e80e51bb0503de23f91d).

### Features
- Comprehensive Postman collections for API testing.
- Environment configurations for different testing scenarios.
- Scripts for automated testing and validation.
# Getting Started
### Prerequisites
- Postman installed on your machine, or use web version.
- Basic understanding of API testing and Postman.
### Installation
- Clone the repository or download the ZIP file.
```sh
git clone <repo_name>
```
- Open Postman and import the collection and environment files from the repository.
- Click on Import, and select the collection and environment files from the APITestingPostman directory.
### Usage
- Load the appropriate environment in Postman.
- Select the collection and run the tests.
- Check the test results and validate the API responses.
### Project Structure
- collections: Contains Postman collections for different API testing scenarios.
- environments: Contains Postman environment files for different testing setups.
- scripts: Contains scripts for setting up and tearing down tests.
- README.md: Documentation for the project.
