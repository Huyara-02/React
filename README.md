# React
This Repo contains all the learning of react, from basics to advance
HTMl in js is called as JSX

Components : A component is a reusable, independent block of UI in React.
It’s like a JavaScript function that returns JSX (HTML + JS).

code </> :
function Welcome() {
  return <h1>Hello!</h1>;
}

Feature | Benefit
Reusability | Write once, use many times (by the help of props)
Readability | Smaller code chunks = easier to understand (building smaller functionalities)
Separation of concerns | UI is broken into logical, independent pieces
Maintainability | Easier to update or debug specific parts

Components Must:

Start with a capital letter
Return JSX
Be pure functions (given same input, return same output)
Use props to accept input

Props : 
Props (short for properties) are inputs to a React component.
They are used to pass data from one component (usually a parent) to another (usually a child).

Reusibility Example :

function Button({ label }) {
  return <button>{label}</button>;
}

<Button label="Login" />
<Button label="Sign Up" />

here two buttons woluld be created, one with label "login" and another with label "Sign Up".


