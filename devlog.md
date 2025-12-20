### 15.12.2025

- Learned Git + Github basics
- Branches, Commit and push workflow
- Difference between staging area, commits and pushes

<details>
<summary>Git(hub) basics Recap:</summary>

- `git init`  
  Creates a local Git repository so Git can track your folders.

- `git config --global user.name "Name"`  
  `git config --global user.email "Email"`  
  Sets your name and email for commits.

- `git status`  
  Shows which files are changed, staged, or untracked.

- `git add <file>` / `git add .`  
  Adds changes to the **staging area**, ready to commit.

- `git commit -m "Message"`  
  Creates a **local snapshot** of the staged changes.

- `git remote add origin <URL>`  
  Connects your local repo to a remote (e.g., GitHub).

- `git push -u origin main`  
  Pushes local commits to the remote and sets the upstream branch.

- `git pull --rebase`  
  Fetches changes from the remote and integrates them locally without merge commits.

- `git fetch`  
  Fetches info about remote changes only, does not merge anything automatically.

- `git branch -m master main`  
  Renames your local branch.

- `.gitignore`  
  Specifies files or folders that Git should ignore.

- `.gitkeep`  
  Allows tracking of empty folders.

**Workflow in short:**  
Edit changes → `git add` → `git commit` → `git push` → version tracked locally + remotely.

</details>

### 16.12.2025

- Learned basic HTML structure
- Used semantic elements (`header`, `section`, `footer`)
- Practiced headings, paragraphs, links, images, lists
- Built a simple form with inputs and textarea

<details>
<summary>HTML Basics Recap:</summary>

- Document structure

  - `<!DOCTYPE html>` → HTML5 declaration
  - `<html>`, `<head>`, `<body>` → page skeleton

- Text content

  - Headings `<h1>`–`<h6>`, paragraphs `<p>`
  - Links `<a>` with `href`, `target="_blank"`, `rel="noopener noreferrer"`
  - Horizontal rule `<hr>`

- Sections & semantic grouping

  - `<header>`, `<section>`, `<footer>`

- Lists

  - `<ul>` → unordered list
  - `<li>` → list items

- Media

  - `<img src="..." alt="...">`

- Forms

  - `<form>` container
  - `<label for="id">` for inputs
  - `<input>` types text/email
  - `<textarea>` for multi-line input
  - `<button type="submit">`

- Attributes
  - `id` → unique element reference
  - `name` → form element identifier
  - `placeholder` → hint text

**Overall:**  
Practiced structuring a webpage, using semantic elements, and creating basic forms for interaction.

</details>

### 17.12.2025

- Learned CSS Basics and Flexbox
- Starting with some JS
- Looked at fractures of React and Tailwind

<details>
<summary>CSS & JS Recap:</summary>

- CSS (Flexbox & Properties):

- Container display

  - `display: flex;` → defines a flex container
  - `flex-direction` → row or column layout
  - `flex-wrap` → whether items wrap onto multiple lines

- Alignment

  - `justify-content` → horizontal distribution along main axis (`flex-start`, `center`, `space-between`, `space-around`)
  - `align-items` → vertical alignment along cross axis (`flex-start`, `center`, `stretch`, `baseline`)
  - `align-self` → overrides `align-items` for a single item

- Spacing

  - `gap` → spacing between flex items
  - `margin` / `padding` → additional spacing inside and outside elements

- Flex sizing

  - `flex-grow` → how much an item can expand relative to siblings
  - `flex-shrink` → how much an item can shrink if needed
  - `flex-basis` → initial size of a flex item

- Other CSS Basics Practiced:

  - `min-width`, `height` → controlling element size
  - `border`, `border-radius` → element outlines and rounded corners
  - `padding` → spacing inside elements
  - `font-family`, `font-size`, `color` → text styling
  - `cursor` → pointer for interactive elements
  - `background-color` → visual grouping and section separation

- JavaScript Basics Practiced:

  - Selecting elements: `document.getElementById`
  - Handling events: `addEventListener("submit", ...)`
  - Preventing default browser behavior: `event.preventDefault()`
  - Reading form input values: `.elements["name"].value` etc.
  - Conditional logic to check for empty fields (`if ... else`)
  - Using `return` to stop function execution
  - Displaying output: `console.log` and `alert`
  - Template literals: `` `Data: ${name}` `` for dynamic strings

- Tailwind Basics (minimal, CSS equivalence):

- Layout / Flex:

  - `flex` → `display: flex;`
  - `flex-row` → `flex-direction: row;`
  - `justify-around` → `justify-content: space-around;`
  - `gap-8` → `gap: 2rem;` (spacing between flex items)

- Sizing / Spacing:

  - `p-2` → `padding: 0.5rem;`
  - `mx-[20vh]` → horizontal margin: `margin-left`/`margin-right: 20vh;`
  - `mt-5`, `mb-20` → `margin-top: 1.25rem;`, `margin-bottom: 5rem;`
  - `rounded-xl` → `border-radius: 1rem;`

- Visual / Effects:

  - `bg-white/5` → `background-color: rgba(255,255,255,0.05);`
  - `backdrop-blur-xl` → `backdrop-filter: blur(20px);`
  - `shadow-[0_0_20px_#3b82f6,0_0_40px_#3b82f6]` → `box-shadow: 0 0 20px #3b82f6, 0 0 40px #3b82f6;`

- Text:
  - `text-white` → `color: white;`

</details>

### 18.12.2025

* Focused mainly on JavaScript
* Worked with logic, data handling and user input
* Learned how different JS concepts interact in practice

<details>
<summary>JavaScript Basics Recap:</summary>

* Variables & data structures

  * Arrays to store multiple values in a defined order
  * Objects to bundle related values under named keys
  * Difference between changing an object vs reassigning a variable
  * Objects are passed by reference, not copied automatically

* Functions

  * Creating functions to reuse logic
  * Passing values and objects into functions
  * Changing object properties inside a function
  * Using `return` to immediately stop function execution

* Arrays & array methods

  * `push()` to add new entries to an array
  * `forEach()` to run code for every array entry
  * `some()` to check if at least one entry matches a condition
  * `find()` to get the first matching entry from an array
  * `filter()` to create a new array without certain entries

* Strings

  * `.replaceAll(old, new)` to remove or replace characters
  * `.slice(start, end)` to cut out parts of a string
  * Using string length and fixed offsets to extract data
  * Template literals `` `${value}` `` for dynamic string building

* Events

  * `addEventListener("submit", ...)` to react to form submits
  * `event.preventDefault()` to stop default browser behavior
  * `addEventListener("click", ...)` to react to clicks
  * `event.target` to identify the clicked element
  * `classList.contains()` to check element classes
  * Handling multiple buttons using one event listener (event delegation)

* Logic & control flow

  * `if` statements to validate conditions
  * Guard clauses to exit early on invalid states
  * Avoiding deeply nested `if` blocks
  * Ternary operator for simple value switching

* Debugging & inspection

  * `console.log()` to trace code execution
  * Logging objects and arrays with `JSON.stringify()`
  * Using logs to verify state changes step by step

**Overall:**
Focused on understanding how core JavaScript concepts work and how they affect each other during execution.

</details>

ah, got it. dann alles neutral und konzeptuell, englisch, mit generischen code-examples.

### 19.12.2025

* Started learning React basics
* Learned how React code is built into static HTML/CSS/JS files
* Explored hosting concepts like Cloudflare tunnels and Apache VirtualHosts

<details>
<summary>React & Hosting Concepts Recap:</summary>

* **React Components:**

  * Components are reusable UI units
  * A component can be defined in one file and imported into another:

    ```jsx
    import ComponentA from './ComponentA';
    ```
  * Multiple components can be rendered together inside a parent container:

    ```jsx
    <>
      <ComponentA />
      <ComponentB />
    </>
    ```
  * JSX allows writing HTML-like syntax directly in JavaScript

* **React Build:**

  * `npm run build` compiles the React app into static files
  * Output: `index.html` as a container, `assets/*.js` containing all components and logic, `assets/*.css` for styling
  * Browser loads HTML, JS renders components dynamically

* **Hosting Concepts:**

  * Cloudflare Tunnel exposes a local server to the internet
  * Apache VirtualHosts map domains to specific folders
  * Raspberry Pi hosting was briefly reviewed, mainly for serving static files

</details>

