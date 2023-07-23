# ToDo-List

The Todolist is a simple web application built using Node.js, Express.js, and MongoDB. It allows users to create and manage their to-do lists with features like adding new items, checking them off, and deleting completed tasks.

Features:

✅ Create and Manage Lists: Users can create and manage multiple to-do lists with custom names.

✅ Add and Check Items: Users can add new tasks to their lists and mark them as completed by checking off the checkboxes.

✅ Dynamic Routing: The application uses dynamic routing to handle different to-do lists based on their custom names.

Setup Instructions:

1. Install MongoDB and ensure it's running.
2. Clone the project and navigate to the project folder.
3. Run `npm install` to install dependencies.
4. Start the server with `node app.js` or `nodemon app.js`.
5. Access the Todolist at `http://localhost:4000` in your browser.

Usage:

- The homepage displays the default "Today" list with pre-defined items.
- To create a new list, add its name to the URL (e.g., `http://localhost:4000/Work`).
- Add new tasks to the list by typing in the input field and clicking the "+" button.
- Check off tasks by clicking on the checkboxes.
- Delete completed tasks by clicking on the "Delete" button.

Customization:

Modify EJS templates (list.ejs, header.ejs, footer.ejs) and CSS (styles.css) to customize the Todolist's appearance.

Author: Developed with ❤️ by Haniya.

Stay organized and manage your tasks efficiently with the Todolist app!
