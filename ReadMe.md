# Tabibi Frontend - Developer Documentation

Welcome to the Tabibi Frontend repository! This document serves as a guide for developers looking to understand and contribute to the codebase.

## Repository Overview

Tabibi Frontend is a React-based web application designed for managing medical appointments and interactions between patients and healthcare providers. The application is structured with a focus on modularity and maintainability.

### Key Directories and Files

- [`src/App.js`](https://github.com/CodeMongerrr/Tabibi_Frontend/blob/master/src/App.js): The main application component that sets up routing and global state.
- [`src/index.js`](https://github.com/CodeMongerrr/Tabibi_Frontend/blob/master/src/index.js): Entry point for the application. It renders the `App` component.
- [`src/redux/store.js`](https://github.com/CodeMongerrr/Tabibi_Frontend/blob/master/src/redux/store.js): Configuration of the Redux store.
- [`src/redux/reducers/rootSlice.js`](https://github.com/CodeMongerrr/Tabibi_Frontend/blob/master/src/redux/reducers/rootSlice.js): Root reducer containing the global state logic.
- [`src/components`](https://github.com/CodeMongerrr/Tabibi_Frontend/tree/master/src/components): Directory containing reusable React components like `Navbar`, `Footer`, etc.
- [`src/pages`](https://github.com/CodeMongerrr/Tabibi_Frontend/tree/master/src/pages): Contains the main pages of the application like `Home`, `Login`, `Register`, etc.
- [`src/styles`](https://github.com/CodeMongerrr/Tabibi_Frontend/tree/master/src/styles): CSS files for styling the application.

### Installation and Setup

1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Start the development server with `npm start`.

### Dependencies

- React and ReactDOM for UI.
- Redux Toolkit for state management.
- React Router for navigation.
- Axios for HTTP requests.
- Other UI libraries (e.g., `react-icons`, `react-hot-toast`).

See [`package.json`](https://github.com/CodeMongerrr/Tabibi_Frontend/blob/master/package.json) for a complete list of dependencies.

### Contributing

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Write code and add tests if applicable.
4. Commit your changes with a clear commit message.
5. Open a pull request against the main branch.

### Code Style and Standards

- Follow React best practices.
- Use functional components with hooks.
- Ensure code readability and maintainability.
- Write meaningful comments where necessary.

### Testing

- Write unit tests for new components and utilities.
- Ensure that existing tests pass before making a pull request.

### Reporting Issues

Use the GitHub Issues tab to report bugs and suggest enhancements.

---

This documentation provides a basic overview of the Tabibi Frontend repository. For more detailed information, refer to the specific files and code within the repository.

---

**Note:** You are currently using the free plan of AskTheCode, which has limited requests. To increase your quota and access more features, consider checking out the [available plans](https://c7d59216ee8ec59bda5e51ffc17a994d.auth.portal-pluginlab.ai/pricing).

Also, AskTheCode is now available as a custom GPT! Your active subscription will be valid for this GPT as well. Try it out [here](https://chat.openai.com/g/g-3s6SJ5V7S-askthecode).
