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
