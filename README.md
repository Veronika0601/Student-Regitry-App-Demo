# Student Registry App

This project is a **Student Registry** application where users can view and manage registered students.

## Features
- Displays the number of registered students.
- Lists students with their details.

## Prerequisites

Before begin, ensure you have met the following requirements:
- **Node.js** installed on your local machine.
- **npm** (Node Package Manager) for installing dependencies.

## Installation

To get started with this project locally, follow these steps:

1. Clone the repository:
    git clone https://github.com/Veronika0601/StudentRegistryApp.git
    

2. Navigate to the project folder:
    
    cd StudentRegistryApp

3. Install the dependencies:
    npm install

## Usage

1. To start the application, run the following command:
    npm start

2. The application should now be running on `http://localhost:8888`.

3. Open your browser and go to `http://localhost:8888` to see the application in action.

## Running Tests

To ensure the application works as expected, we have written tests using **Mocha** and **Node Fetch**.

1. Install testing dependencies (if not already installed):
    npm install --save-dev mocha node-fetch

2. To run the tests, use the following command:
    npx mocha

3. The tests will check:
   - **Page title**: Verifies that the page contains the `<h1>Students Registry</h1>` tag.
   - **Students count**: Verifies that the page shows the correct number of registered students (`<b>2</b>`).

## Contributing

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push your branch to your forked repository.
5. Open a pull request with a description of your changes.

## Acknowledgements

- Node.js
- Mocha testing framework
- Node Fetch for HTTP requests
