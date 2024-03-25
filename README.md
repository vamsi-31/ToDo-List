
# MERN Stack Todo App

This project is a simple todo app built using the MERN stack, which includes:  
MongoDB: For storing todo data.  
Express.js: For creating the backend API.  
React.js: For building the user interface.  
Node.js: For running the server.  
Features  
Add new todos.  
Mark todos as done/undone.  
Edit existing todos.  
Delete todos.  
Filter todos by All, Active, and Done.  
Remove all done todos at once.  
## Installation and Setup

Prerequisites:
Node.js and npm installed on your machine.  
MongoDB installed and running.

```bash
  git clone https://github.com/vamsi-31/ToDo-List
```

Go to the project directory

```bash
  cd ToDo-List
```

Install dependencies

```bash
  npm install
```
```bash
  cd FrontEnd
  npm start
```
Create a .env file in the root directory and add the following variables:  
```bash  
DB_USERNAME=your_mongodb_username  
DB_PASSWORD=your_mongodb_password
```  
Start the server

```bash
  cd BackEnd
  npm run start
```

This will open the app in your browser, typically at http://localhost:3000.

## Tech Stack

**FrontEnd:** React, Redux, CSS

**Server:** Node, Express

**Database:** MongoDb

Usage
Add new todos by typing in the input field and pressing Enter.
Click on a todo to mark it as done/undone.
Double-click on a todo to edit its text.
Click the trash icon to delete a todo.
Use the filter buttons to show All, Active, or Done todos.
Click the "Remove Done Todos" button to delete all completed tasks.
## Contributing

Contributions are highly valued! If you have ideas for new features, bug fixes, or enhancements, please feel free to submit a pull request.
License
This project is licensed under the MIT License.
Known Issues and Limitations
Mobile Device Compatibility: The application may not be fully functional on mobile devices due to limitations in touch input and screen size.
Performance on Large Canvases: Performance may be impacted when working with very large canvases.

## Additional Notes
For optimal performance, it is recommended to use the application on a desktop or laptop computer.
If you encounter any issues or have any questions, please feel free to create an issue on the GitHub repository.

