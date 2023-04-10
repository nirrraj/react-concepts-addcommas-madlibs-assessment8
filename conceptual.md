### Conceptual Exercise

Answer the following questions below:

- What is React? When and why would you use it?

React is a library for front end development where elements on a page can be created in modular, reusable, inheritable ways. React also makes it much more possible for web apps to be dynamic -- tools like hooks enable states that can readily 'react' to user immediate user interactions with the elements on a web page.

- What is Babel?

Babel is a transpiler -- it compiles javascript and 'converts' it for compatibility across browsers.

- What is JSX?

JSX is an HTML notation in javascript that allows HTML to be written in plain text without causing an error for being unrecognizble javascript syntax.

- How is a Component created in React?

A component is created by saving a dedicated .js file for that component, exporting it, and importing it into the App.js file. In this way, the component can be inserted repeatedly with a simple pseudo-HTML element notation `<Component />`

- What are some difference between state and props?

Props are immutable, dedicated variables passed to a component, such as from parent to child component. State is a changeable, allocated memory that persists through re-renders within a component.

- What does "downward data flow" refer to in React?

It is the practice of passing data (i.e., props) down from parent components to child componenets.

- What is a controlled component?

In a controlled component, React can access and dictate the instantaneous value of the component via state. An common use would be a form input that displays dynamic searches, search suggestions, formatting, etc. instantaneously as the user types in the form, the contents of which are totally and always visible to React.

- What is an uncontrolled component?

An uncontrolled component is one which React does not control via state and does not have access to its data. Examples might include an embedded video or file upload element.

- What is the purpose of the `key` prop when rendering a list of components?

The purpose is for React to keep track of these elements behind the scenes. Keys must be totally unique otherwise unexpected, erroneous performance will occur as React mixes up what it is keeping track of.

- Why is using an array index a poor choice for a `key` prop when rendering a list of components?

Arrays are mutable; modifications such as insertions, deletions can result in inaccurate or duplicate keys.

- Describe useEffect.  What use cases is it used for in React components?

useEffect is a hook that can be used to run a 'side effect' upon change of certain conditions such as one time on page render, or whenever a component changes. It can be used for fetching data dynamically, reading from local storage, implementing and removing evenet listeners, etc.

- What does useRef do?  Does a change to a ref value cause a rerender of a component?

Use ref is a variable that persists through re-renders and a change in the ref does not cause a rerender of the component.

- When would you use a ref? When wouldn't you use one?

When you need to store dynamically defined data without inducing a re-rendering of a component upon every change. You wouldn't use one if you don't need persistence across changes

- What is a custom hook in React? When would you want to write one?

Custom hooks are customized functions, made up by the developer, that are designed to be reusable across components. You can reuse similar logic in multiple places without rewriting that workflow every time.
