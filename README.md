# EmployeeHub Front-End

This is the front-end for the EmployeeHub application, a web interface for managing employee data. It is built with React and designed to communicate with a backend Web API.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Key Features

-   View a list of all employees.
-   Add, edit, and delete employee records.
-   View department information.
-   A responsive user interface built with Material-UI and React-Bootstrap.
-   Client-side routing handled by React Router.

## Technologies Used

-   **Framework/Library:** [React](https://reactjs.org/)
-   **UI Components:**
    -   [Material-UI](https://material-ui.com/)
    -   [React-Bootstrap](https://react-bootstrap.github.io/) & [Bootstrap 4](https://getbootstrap.com/)
-   **Routing:** [React Router](https://reactrouter.com/)
-   **Build Tool:** [Create React App](https://create-react-app.dev/) (react-scripts)
-   **Package Manager:** [npm](https://www.npmjs.com/)

---

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You need to have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/get-npm) installed on your machine.

### Installation

1.  Clone the repository:
    ```sh
    git clone https://github.com/your-username/EmployeeHub-Front-End.git
    ```
2.  Navigate into the project directory:
    ```sh
    cd EmployeeHub-Front-End-main
    ```
3.  Install the NPM packages:
    ```sh
    npm install
    ```

### Configuration

This front-end application is designed to connect to a backend API. You will need to create a `.env` file in the root of the project to specify the API's base URL.

1.  Create a new file named `.env` in the project root.
2.  Add the following line, replacing the URL with the actual address of your backend API.

    ```env
    REACT_APP_API_URL=http://localhost:5000/api
    ```

---

## Available Scripts

In the project directory, you can run the following commands:

### `npm start`

Runs the app in development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project. Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them.
