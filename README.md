**1. What’s your experience with JavaScript code?**

I have extensive experience with JavaScript, having worked with both vanilla JavaScript and frameworks like Angular and React. I am proficient in writing maintainable and scalable code, leveraging modern JavaScript features such as ES6+ syntax, asynchronous programming, and functional programming paradigms.

**Sample questions:**

- **Explain the difference between synchronous and asynchronous functions.**\
  Synchronous functions execute sequentially, blocking further execution until the current function completes. Asynchronous functions, on the other hand, allow the program to continue execution while waiting for an operation (e.g., fetching data) to complete.

- **Why is fetch the preferred way to send a network request via the web browser?**\
  `fetch()` is preferred because it returns Promises, making asynchronous code easier to handle. It also provides better error handling and is more flexible than the older `XMLHttpRequest`.

- **If the browser encounters malformed HTML, what happens?**\
  The browser attempts to interpret the malformed HTML as best as it can, often using error recovery mechanisms. However, unexpected behavior or rendering issues may occur.

- **Is there another option, besides explicit promises, to handle asynchronous code in JavaScript?**\
  Yes, JavaScript provides `async/await`, which simplifies working with asynchronous code by allowing asynchronous operations to be written in a synchronous style.

- **Explain the function and syntax of the array forEach() method.**\
  The `forEach()` method executes a provided function once for each array element. Example:

  ```javascript
  [1, 2, 3].forEach(num => console.log(num));
  ```

- **Explain the function and syntax of the function bind() method.**\
  The `bind()` method creates a new function with a specified `this` value and arguments. Example:

  ```javascript
  const obj = { name: 'Gustavo' };
  function greet() { console.log(`Hello, ${this.name}`); }
  const boundGreet = greet.bind(obj);
  boundGreet(); // Hello, Gustavo
  ```

- **Is there a way to stop an event from bubbling up?**\
  Yes, using `event.stopPropagation()`. Example:

  ```javascript
  element.addEventListener('click', event => event.stopPropagation());
  ```

- **How is the event loop defined in the JavaScript engine?**\
  The event loop is a mechanism that handles execution of JavaScript code, events, and asynchronous tasks, ensuring non-blocking behavior.

- **How do callbacks work in JavaScript?**\
  Callbacks are functions passed as arguments to other functions and executed later. Example:

  ```javascript
  function fetchData(callback) {
    setTimeout(() => { callback('data loaded'); }, 1000);
  }
  fetchData(console.log);
  ```

- **Have you worked with jQuery or other JS libraries actively?**\
  Yes, I have experience with jQuery, though I primarily work with modern frameworks like React and Angular.

- **What design patterns do you know?**\
  I am familiar with patterns such as MVC (Model-View-Controller) and Component-Based Architecture: Usado em frameworks como React, Vue e Angular, onde a interface é dividida em componentes reutilizáveis.

---

**2. Are you familiar with ECMAScript?**\
Yes, I keep up-to-date with ECMAScript standards and features.

- **What are the differences between arrow functions and function expressions?**\
  Arrow functions have a lexical `this`, meaning they do not bind their own `this`. Function expressions, on the other hand, have their own `this` context.

- **Are there any language structures that implement strict mode by default?**\
  Yes, ES6 modules automatically enable strict mode.

---

**3. Can you describe TypeScript essentials?**\
TypeScript provides static typing, interfaces, and other features that enhance JavaScript development.

- **Is static typing faster than dynamic typing?**\
  Yes, static typing helps catch errors at compile time, making development more efficient.

- **What is the difference between a type and an interface in TypeScript?**\
  `interface` is used for defining object shapes and supports extension, while `type` can define primitives, unions, and intersections.

- **What is the difference between “Unknown,” “Any” and “Never” in TypeScript?**\
  `Any` disables type checking, `Unknown` requires type checking before usage, and `Never` represents a value that never occurs.

- **What are the five key data structures?**\
  Arrays, Objects, Maps, Sets, and Tuples.

- **What are the advantages and disadvantages of generics?**\
  Generics provide type safety and code reusability but increase complexity.

---

**4. Can you write SQL queries?**\
Yes, I have experience writing SQL queries for CRUD operations.

---

**5. How does REST API work?**\
REST APIs follow stateless client-server architecture, using HTTP methods (GET, POST, PUT, DELETE) to communicate between clients and servers.

- **What is the difference between API and REST API?**\
  API is a broader term for interfaces enabling communication between systems. REST API follows REST principles, ensuring stateless communication over HTTP.

---

**6. Why do we need virtualization services?**\
Virtualization services like Docker provide isolated environments, making deployment and scalability easier.

- **What is Docker, and how can it be useful for a front-end developer?**\
  Docker allows developers to create portable development environments, ensuring consistency across machines and simplifying dependency management.

---

**7. Can you describe your process of working in the terminal?**\
I am comfortable using Bash, ZSH, and CLI tools for tasks like Git operations, managing processes, connecting to containers, and package management.

---

**8. Can you name version control systems and their differences?**\
I primarily use Git for version control.

- **What is the difference between Git's “push” and “pull” requests?**\
  `push` uploads local commits to a remote repository, while `pull` fetches and merges changes from the remote repository.

- **What is the difference between Rebase and Merge in Git?**\
  `merge` creates a new commit combining branches, while `rebase` integrates changes linearly by rewriting commit history.

- **How do you squash already pushed commits?**\
  Using interactive rebase: `git rebase -i HEAD~n`.

- **Which branching workflows for Git do you know?**\
  Git Flow, GitHub Flow, Trunk-based development.

- **What version control system providers did you work with?**\
  GitHub, GitLab, BitBucket, Azure DevOps.

---

**9. How do you manage software development?**\
I follow Agile methodologies and best practices to ensure software quality.

- **How would you define Kanban?**\
  A visual workflow management method for continuous delivery.

- **Why do agile teams need daily stand-up meetings?**\
  To align team members, discuss progress, and address blockers.

- **What are sprint planning, review, and sprint retrospective meetings?**\
  They define work scope, evaluate progress, and improve future sprints.

- **What is the purpose of decomposition in programming?**\
  Breaking complex problems into smaller, manageable parts.

**10. What task tracking systems do you use?**

Task management is crucial for organizing and tracking project progress. I have experience using Jira, Trello, Azure DevOps, and GitHub Projects for managing tasks, sprints, and tracking bugs.

- **What project management tools have you used?**  
  I have used Jira for Agile workflows, Trello for lightweight task management, Azure DevOps for development lifecycle management, and GitHub Projects for repository-specific task tracking.

---

**11. How are tasks evaluated?**

Tasks are evaluated based on their complexity, dependencies, and estimated effort required for completion. Agile methodologies often use techniques such as story points and planning poker to assess effort collaboratively.

- **What is the planning poker technique?**  
  Planning poker is a consensus-based estimation technique where team members use a deck of cards to assign story points to a task. It helps ensure a balanced and agreed-upon estimation.

- **How do you define story points?**  
  Story points represent an abstract measure of effort required to complete a task, considering complexity, uncertainty, and effort.

---

**12. What is object-oriented programming?**

Object-oriented programming (OOP) is a programming paradigm that organizes code around objects, which encapsulate data and behavior.

- **What is a class in programming? Can you give an example?**  
  A class is a blueprint for creating objects. Example in JavaScript:
  
  ```javascript
  class Car {
    constructor(brand, model) {
      this.brand = brand;
      this.model = model;
    }
    getDetails() {
      return `${this.brand} ${this.model}`;
    }
  }
  ```

- **What is the benefit of interfaces?**  
  Interfaces define a contract that classes must adhere to, ensuring consistency and maintainability in codebases.

- **What is inheritance in OOP?**  
  Inheritance allows a class to inherit properties and methods from another class, promoting code reusability.

- **What is meant by polymorphism in OOP?**  
  Polymorphism allows a single interface to be used for different data types. Example: method overloading and method overriding.

- **Why is encapsulation important in programming?**  
  Encapsulation restricts direct access to an object's data and only exposes necessary functionality, improving security and modularity.

- **Why do we use abstraction in programming?**  
  Abstraction hides implementation details and exposes only essential features, reducing complexity.

- **What is the difference between a function and a constructor?**  
  A function performs a specific task, whereas a constructor initializes objects when a class is instantiated.

- **What is the difference between prototype inheritance and classical inheritance?**  
  Classical inheritance (as in Java or C#) uses classes, while prototype inheritance (JavaScript) allows objects to inherit properties directly from other objects via the prototype chain.

**13. What is functional programming?**
Functional programming is a programming paradigm that treats computation as the evaluation of mathematical functions and avoids changing state or mutable data. It emphasizes the use of pure functions, higher-order functions, and immutable data structures.

**Sample questions:**

- **What does closure mean in programming?**
  A closure is a function that retains access to its lexical scope even when executed outside of its original context. This allows functions to maintain state between executions.

- **What is a higher-order function in functional programming?**
  A higher-order function is a function that takes another function as an argument or returns a function as its result. Examples include `map`, `filter`, and `reduce` in JavaScript.

- **What are pure and impure functions?**
  - Pure functions always return the same output for the same input and do not cause side effects.
  - Impure functions may depend on external state or cause side effects like modifying a variable outside their scope.

- **What is idempotency, and where is it used?**
  Idempotency means that performing an operation multiple times produces the same result as performing it once. It is often used in APIs to ensure safe retries without unintended side effects.

- **What is a monad in programming?**
  A monad is a design pattern that allows for chaining operations while managing side effects. It is commonly used in functional programming for handling asynchronous operations, optional values, or state management.

- **How do you know if a function is composite?**
  A composite function is a function that is created by combining multiple functions, where the output of one function serves as the input to another.

- **When is function currying used?**
  Currying is used when a function is broken down into multiple functions, each taking a single argument. This technique enhances reusability and functional composition.

---

**14. What frameworks do you work with?**
Frameworks provide structure and enforce design patterns in software development. In front-end development, frameworks help manage UI complexity and maintainability.

**Sample questions:**

- **What is React used for?**
  React is a JavaScript library used for building interactive user interfaces, particularly single-page applications (SPAs).

- **What are the advantages and disadvantages of Virtual DOM?**
  - Advantages: Improves performance by minimizing direct manipulation of the DOM, enables efficient updates, and provides a declarative UI approach.
  - Disadvantages: Increased memory usage and abstraction complexity.

- **Are TSX and JSX the same?**
  No. JSX is used in React to write HTML-like syntax in JavaScript, while TSX is the TypeScript version of JSX, adding type safety.

- **How do props work in React?**
  Props (short for properties) are read-only data passed from a parent component to a child component in React.

- **What are Hooks in React?**
  Hooks are functions that allow functional components to use state and lifecycle methods without converting them into class components.

- **What is NextJS used for?**
  Next.js is a React framework for building server-side rendered (SSR) applications, static websites, and hybrid applications with optimized performance.

---

**15. What’s your experience with styling tools?**
Styling tools help developers implement designs efficiently, ensuring consistency and responsiveness.

**Sample questions:**

- **Which is more responsive, Grid or Flex?**
  CSS Grid is more suitable for complex layouts, while Flexbox is better for aligning elements in a single direction (row or column).

- **What are the most popular UI frameworks?**
  Bootstrap, Material UI, Tailwind CSS, and Ant Design.

- **What are the advantages and disadvantages of using CSS preprocessors?**
  - Advantages: Variables, mixins, nested rules, and better organization.
  - Disadvantages: Additional compilation step, learning curve, and potential performance issues.

- **Name common CSS selectors that use the `div` tag and their purpose.**
  - `.className`: Targets elements with a specific class.
  - `#idName`: Targets a specific element with an ID.
  - `div > p`: Targets direct child `p` elements inside a `div`.
  - `div + p`: Targets the immediate `p` element following a `div`.

---

**16. How do you test an application?**
Testing ensures software quality by catching bugs and verifying functionality before deployment.

**Sample questions:**

- **Which software is used for manual testing?**
  Tools like Selenium, Postman, and Cypress are used for manual testing.

- **What is unit testing, and why is it important?**
  Unit testing tests individual components or functions to ensure they work as expected, reducing bugs early in development.

- **What is the primary purpose of integration testing?**
  Integration testing checks how different modules or components work together.

- **What is E2E testing, and why do we need it?**
  End-to-end (E2E) testing simulates real user interactions to validate the entire application flow.

- **What is the difference between debugging in the browser and in an IDE?**
  - Browser debugging: Uses developer tools like Chrome DevTools to inspect elements, network requests, and console logs.
  - IDE debugging: Uses built-in tools like breakpoints and variable inspection to analyze code execution.


