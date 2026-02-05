# To-Do List

## Project Description
A simple and interactive **To-Do List web application** built with HTML, CSS, and JavaScript.  
This project allows users to add, check/uncheck, and delete tasks. Tasks are saved in the browser's **localStorage**, so they persist even after refreshing or closing the page.

## Features
- Add new tasks to the list
- Mark tasks as completed (toggle check/uncheck)
- Delete tasks individually
- Persistent storage using **localStorage**
- Responsive and clean UI with gradient background

## Tech Stack
- **HTML5** – Structure of the application  
- **CSS3** – Styling and layout  
- **JavaScript (ES6)** – Functionality and interactivity  
- **LocalStorage** – Data persistence  

## Project Structure
├── index.html # Main HTML file

├── style.css # Styling for the application

├── script.js # JavaScript logic

└── images/

└── .png # Placeholder image (optional)
## How It Works
1. User enters a task in the input box and clicks **Add**.
2. The task is appended to the list with a delete button (`×`).
3. Clicking on a task toggles its "checked" state (completed).
4. Clicking on the delete button removes the task.
5. All changes are saved in **localStorage** automatically.
6. On page load, tasks are retrieved from localStorage and displayed.

## Setup / Installation Instructions
1. Clone or download this repository.
2. Ensure the following files are in the same directory:
   - `index.html`
   - `style.css`
   - `script.js`
   - `images/` folder (optional for icons)
3. Open `index.html` in any modern web browser.

No additional installation or backend setup is required.

## Usage
- Type a task in the input field.
- Click the **Add** button to add it to the list.
- Click on a task to mark it as completed.
- Click the `×` button to delete a task.
- Refresh or reopen the page — tasks remain saved.

## Screenshots
*(Placeholder — add actual screenshots here)*

![App Screenshot](screenshots/todo-app.png)

## Future Enhancements
Based on the current code, possible improvements include:
- Add an **edit task** feature.
- Implement **categories** or **priority levels** for tasks.
- Add a **clear all tasks** button.
- Improve accessibility (keyboard navigation, ARIA labels).
- Enhance UI with animations or icons.

## License
This project is licensed under the **MIT License**.
