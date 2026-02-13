# 🍕 ReactJS Basics -- Learning README

This repository contains my learning and implementation of core ReactJS
concepts while building a Pizza Menu UI.

------------------------------------------------------------------------

## 📌 Topics Covered

-   Component
-   Props
-   React Fragment
-   Basic React Structure
-   Ternary Operator

------------------------------------------------------------------------

## ⚛️ 1. Component in React

Components are the building blocks of a React application.\
They allow us to split the UI into independent, reusable pieces.

### Example:

``` jsx
function Pizza() {
  return <h2>Margherita Pizza</h2>;
}

export default Pizza;
```

### Types of Components

-   Functional Components (Modern & recommended)
-   Class Components (Legacy)

------------------------------------------------------------------------

## 📦 2. Props (Properties)

Props are used to pass data from parent component to child component.

### Example:

``` jsx
function Pizza(props) {
  return <h2>{props.name}</h2>;
}

function App() {
  return <Pizza name="Pepperoni" />;
}
```

Props are: - Read-only - Used for data sharing - Passed from parent →
child

------------------------------------------------------------------------

## 🧩 3. React Fragment

React Fragment allows grouping multiple elements without adding extra
DOM nodes.

### Example:

``` jsx
import React from "react";

function Menu() {
  return (
    <>
      <h1>Pizza Menu</h1>
      <p>Choose your favorite pizza</p>
    </>
  );
}
```

It works like Angular's ng-container.

------------------------------------------------------------------------

## 🏗️ 4. Basic React Structure

Basic structure of a React application:

    src/
     ├── index.js
   
### index.js

``` jsx
import React from "react";
import ReactDOM from "react-dom/client";
import App from "./App";

const root = ReactDOM.createRoot(document.getElementById("root"));
root.render(<App />);
```

### App.js

``` jsx
function App() {
  return <h1>Welcome to Pizza App</h1>;
}

export default App;
```

------------------------------------------------------------------------

## ❓ 5. Ternary Operator in React

Used for conditional rendering inside JSX.

### Syntax:

``` jsx
condition ? trueValue : falseValue
```

### Example:

``` jsx
function Menu({ isOpen }) {
  return (
    <div>
      {isOpen ? (
        <p>We are open!</p>
      ) : (
        <p>Sorry, we are closed</p>
      )}
    </div>
  );
}
```

------------------------------------------------------------------------

## 🚀 What I Learned

-   How React components work
-   Data passing using props
-   Grouping JSX using Fragment
-   Understanding React project structure
-   Conditional rendering using ternary operator

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   ReactJS
-   JavaScript (ES6)
-   JSX
-   CSS

------------------------------------------------------------------------

## 📈 Next Learning Steps

-   State & useState
-   Event handling
-   Lists & keys
-   Forms in React
-   Hooks

------------------------------------------------------------------------

## 🙌 Author

Learning React step by step by building real UI components.

-----------------------------------------------------------------------

<img width="1919" height="1062" alt="Screenshot 2026-02-13 191521" src="https://github.com/user-attachments/assets/27f2c888-59ae-443e-8d70-0b242ddec9a8" />

