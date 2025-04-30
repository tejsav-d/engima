# ng-training-assignment-1


### 1. Project Overview
   - Project Name: ng-training-assignment-1
   - Description: A simple task management application built with Angular. Users can create, view, and delete tasks.
   - Features:
     - Task creation
     - Task deletion
     - Task listing
   - Technologies Used: Angular, TypeScript, HTML, CSS, Angular CLI

### 2. **Installation Guide**
   - Prerequisites:
     - Node.js and npm installed
     - Angular CLI installed globally
   - Steps to Install:
     ```bash
     # Clone the repository 
     git clone https://gitlab.com/enzigma-assignment-1/ng-training-assignment-1.git
     
     # Navigate to the project directory
     cd ng-training-assignment-1/client-side

     # Install dependencies
     npm install
     ```

### 3. Running the Application
   - Development Server:
     - Start the development server:
       ```bash
       ng serve
       ```
     - Open a browser and navigate to `http://localhost:3000/`.
     - The application will automatically reload if you change any of the source files.
   
### 4. Project Structure
   - src/app: Contains all Angular components, services, and modules.
     - app.component.ts: The root component of the application.
     - app/app.module.ts: A feature module for task-related components.
     - app/task-list/task-list.component.ts: Component for displaying and managing the list of tasks.
   - src/styles.css: Global styles for the application.
   - src/index.html: The main HTML file that includes the root component.
   - angular.json: Angular CLI configuration file.
   - package.json: Contains metadata about the project and dependencies.

### 5. **Components Documentation**
   - **AppComponent:**
     - Selector: `app-root`
     - Description: The root component that bootstraps the application.
   - **TaskListComponent:**
     - Selector: `app-task-list`
     - Description: Displays the list of tasks and provides options to add or delete tasks.

### 6. **Services Documentation**
   - TaskService:
     - Description: Manages the CRUD operations for tasks. Interacts with a backend or local storage to fetch, add, or delete tasks.
     - **Methods:**
       - `getTasks(): Observable<Task[]>`: Fetches the list of tasks.
       - `addTask(task: Task): Observable<Task>`: Adds a new task.
       - `deleteTask(id: string): Observable<void>`: Deletes a task by ID.

### 7. **Usage Instructions**
   - Adding a Task:
     - Enter the task name in the input field and click the "Add Task" button.
   - Deleting a Task:
     - Click the "Delete" button next to the task you want to remove.
  


