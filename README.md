README
Taskmaster
Taskmaster is a task management app where users can create and view tasks. This app is built with a Node.js backend using Express and MongoDB, with a React frontend for the user interface. The frontend communicates with the backend via REST API endpoints to manage tasks.

Technologies Used
Backend:
Node.js
Express
MongoDB
Mongoose (for MongoDB object modeling)
CORS (for enabling cross-origin requests)
Body-Parser (to parse incoming JSON requests)


Frontend:
React.js
Axios (for making HTTP requests)
Features
Task Creation: Users can add tasks by providing a title and description.
Task Listing: Users can view all the tasks that have been created.
Task Status: Tasks are stored with a default status of 'pending' (this can be expanded later to include features like updating status).

Contributing
Contributions to the Taskmaster project are welcome! If you have any suggestions or improvements, feel free to fork the repository and create a pull request.

Notes for Future Improvements
Implement user authentication (sign up/login).
Add task status updates (e.g., from "pending" to "completed").
Implement task editing and deletion.
Deploy the app using services like Heroku for the backend and Netlify or Vercel for the frontend.


