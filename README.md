# Kanban Board Task Management Application

This is a Kanban board-inspired task management application that allows users to efficiently manage tasks across different stages of completion. The application provides a seamless and intuitive interface for users to organize their tasks and keep track of their progress.


## Features

- **Homepage**: The homepage displays all tasks, categorized into different status groups: To Do, Doing, and Done.

- **Task Card**: Each task is presented as a card, showing the task title and description for quick reference.

- **Add Task**: Users can easily create a new task by filling out a form that prompts them for the task title and description.

- **Edit Task**: The application enables users to edit the title and description of an existing task, allowing for updates as needed.

- **Delete Task**: Users have the option to permanently remove a task, providing a comprehensive task management experience.

- **Task Status**: With a user-friendly drag-and-drop functionality, tasks can be effortlessly moved between the To Do, Doing, and Done categories to reflect their current status.

- **Responsive Design**: The application is fully responsive and functional on mobile devices, ensuring a consistent user experience across different screen sizes.

## Technologies Used

- Front-end: **ReactJS, Tailwind CSS**
- Back-end: **Node.js, Express.js**
- Database: **MongoDB**
- Version Control: **Git, Github**



## Installation and Usage


1. Navigate to the `Backend` directory:
   ```
   cd Backend
   ```

2. Install the required dependencies by running the following command:
   ```
   npm install
   ```
3. Set up the environment variables in a .env file like this :
   ```
   MONGODB_URI = <Your Mongodb connection uri>
   ```
   Add this file in the root of Backend directory

4. Start the Backend Server by running the following command:
   ```
   npm run dev
   ```

5. Navigate to the `Frontend` directory:
   ```
   cd Frontend
   ```

6. Install the required dependencies by running the following command:
   ```
   npm install
   ```
7. Set up the environment variables in a .env file like this:
   ```
   REACT_APP_BACKEND_URL=<Your local or deployed backend url>
   ```
    Add this file in the root of Frontend directory 
   
8. Finally, start the Frontend of the Application:
   ```
   npm start
   ```

9. Open your browser and visit `http://localhost:3000` to access the captivating world of TravelDiary.


## API Endpoints

- GET /projects: Get a list of all projects with minimal details.
- GET /project/:id: Get details of a specific project.
- POST /project: Create a new project.
- PUT /project/:id: Update details of a project.
- DELETE /project/:id: Delete a project.
- POST /project/:id/task: Create a new task within a project.
- GET /project/:id/task/:taskId: Get details of a specific task within a project.
- PUT /project/:id/task/:taskId: Update details of a task within a project.
- DELETE /project/:id/task/:taskId: Delete a task within a project.
- PUT /project/:id/todo: Update the order and stage of tasks within a project for task management.

