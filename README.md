# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
This project aims to create a simple web application that generates random passwords using React.js and styling with Tailwind CSS. The application utilizes React hooks such as useState, useCallback, useEffect, and useRef for managing state, side effects, and references.

React Hooks Used :
useState: Used for managing state variables such as the generated password.
useCallback: Used to memoize functions to prevent unnecessary re-renders.
useEffect: Used for performing side effects such as generating the initial random password.
useRef: Used for creating a reference to the password input field.

Technologies Used :
React.js: A JavaScript library for building user interfaces.
Tailwind CSS: A utility-first CSS framework for styling web applications.

Usage :
Upon opening the application, a random password will be generated and displayed.
You can copy the generated password by clicking the "Copy" button next to it.
