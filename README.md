## Students Registry Demo App

This is a simple web application built with Node.js and Express.js. It allows you to register students and view the list of registered students.

### Getting Started

These instructions will guide you on how to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

To run this project, you need to have the following installed on your machine:

-   Node.js
-   npm

### Installation

-   Clone the repository

```bash
git clone https://github.com/georgiev8/rs-app.git
```

-   Install dependencies in project root directory

```bash
npm install
```

### Building the App

You can build the app locally by running the following command:

```bash
npm start
```

### Running the Tests

This project uses Mocha for testing. Execute the tests with the following command:

```bash
npm test
```

### Deployment

The app is configured with a simple GitHub Actions workflow. The CI/CD pipeline is triggered on every push or pull request to the main branch. It installs the dependencies, builds the app, and runs the tests across multiple Node.js versions.
