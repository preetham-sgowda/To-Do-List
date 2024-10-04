# To-Do List Web Application

This project is a simple, responsive to-do list application built using HTML, CSS, and JavaScript. It allows users to add, mark as complete, and remove tasks. The tasks are saved in the browser's local storage, so they persist even after a page refresh.

## Features

- **Add Tasks**: Users can add new tasks using the input field and "Add" button.
- **Mark as Complete**: Clicking on a task will mark it as complete (strikethrough).
- **Remove Tasks**: Clicking the "×" next to a task will remove it from the list.
- **Persistent Storage**: Tasks are saved in the browser's local storage, so they remain even after the page is reloaded.

## File Structure

- **index.html**: The main structure of the web page, which includes a form to input tasks and a list to display them.
- **style.css**: Contains the styling for the to-do list, including responsiveness, fonts, and hover effects.
- **script.js**: Manages the functionality of the to-do list, such as adding, deleting, marking tasks, and saving them to local storage.

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/todo-list-app.git
   ```

2. Open the `index.html` file in a web browser.

3. Start adding tasks using the input field. Click on a task to mark it as complete or click the "×" to remove it.

## Local Storage

This application uses local storage to save tasks. If you add tasks, they will persist even if you refresh the page or close the browser. Tasks are stored as HTML in local storage and retrieved upon page load.

## Screenshots

![to1](https://github.com/user-attachments/assets/d384feb7-467b-4423-9e3a-b57dd11fecb1)

![to2](https://github.com/user-attachments/assets/23e676be-bcf3-4cfb-97a3-d87756f91a6f)



## Technologies Used

- HTML
- CSS (with Flexbox for layout and basic responsiveness)
- JavaScript (with local storage for persistence)

## Future Enhancements

- Add task categories.
- Implement drag-and-drop to rearrange tasks.
- Add a feature to set due dates and reminders.
