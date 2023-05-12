Backend

* The backend folder contains the Node.js server-side code that handles the chatbot logic.
* The main file is index.js, which sets up the server and establishes a connection to the OpenAI API.
* The index.js file also creates a function to handle user input and utilizes the Readline module to read user input from the console.
* The backend code is responsible for processing the user input, sending the input to the OpenAI API, and returning the response back to the front-end.
* The index.js file contains the OpenAI API key(https://platform.openai.com/account/api-keys) and organization key (https://platform.openai.com/account/org-settings) that needs to be replaced with the user's own key.

Frontend

* The frontend folder contains the React code that handles the user interface of the chatbot.
* The main file is App.jsx, which contains the state and functions to handle user input and responses.
* The App.jsx file also utilizes the Vite module to run the local development server.
* The front-end code is responsible for rendering the chat interface, sending user input to the backend, and displaying responses from the backend.
* The App.jsx file contains a placeholder for the backend URL that needs to be replaced with the URL of the running backend server.

Dependencies

* The project has several dependencies that need to be installed.
* The backend dependencies include the OpenAI API, ChatGPT, Node.js, and the Readline module.
* The frontend dependencies include React and Vite.

Installation

* Navigate into the backend folder using cd backend.
* Install the backend dependencies using npm install.
* Replace the placeholder for the OpenAI API key with your own key in the index.js file.
* Start the backend server using npm start.

* Navigate into the frontend folder using cd ../frontend.
* Install the frontend dependencies using npm install.
* Replace the placeholder for the backend URL with the URL of the running backend server in the App.jsx file.
* Start the frontend server using npm run dev.
* Access the chatbot interface from your browser at http://localhost:5173.