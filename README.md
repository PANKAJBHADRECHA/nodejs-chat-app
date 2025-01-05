# Node.js Chat App
This is a simple chat application built using Node.js, Express.js, and Socket.io, designed to demonstrate basic real-time communication capabilities.

## Installation Instructions
To set up the chat app locally, you can download the source code from the GitHub repository. Follow these steps:

1. Visit the repository at [GitHub: nodejs-chat-app]([https://github.com/PANKAJBHADRECHA/nodejs-chat-app]).
2. Clone the repository to your local machine using Git, or download the ZIP file and extract it.
3. Open your command line interface (CLI), navigate to the project directory, and run the following command to install all necessary Node modules:

    ```bash
    npm install
    ```

## Running the App in Development Mode
To run the app in development mode, execute the following command after installation:

    ```bash
    npm run dev
    ```

This command starts the server on port 3000 and monitors for any file changes in your project, automatically restarting the server thanks to `nodemon`.

Open your web browser and go to [http://localhost:3000/](http://localhost:3000/) to view and interact with the chat application.

## Customizing the Listening Port
If you need to change the port on which the app listens, perform the following steps:

1. Copy the `.env.example` file in the root directory of the project and rename it to `.env`.
2. Open the `.env` file and change the value of the `PORT` variable to your preferred port number.
3. Save the changes and restart the app if it's running.

By following these steps, you can easily set up and customize the Node.js Chat App on your local machine.
