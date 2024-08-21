# How to Run the Code on Your PC

1. **Navigate to the Project Directory:**
   - Open your terminal or command prompt.
   - Navigate to the specific project folder within the `builds` directory. For example, to run the Infoboard     project, use:
     ```
     cd /path/to/builds/infoboard
     ```

2. **Install the `serve` Package:**
   - Run the following command to install the `serve` package globally on your machine (you only need to do this once):
     ```
     npm install -g serve
     ```

3. **Start the Server:**
   - Once you're in the project directory (e.g., `.../builds/infoboard`), start the server by running:
     ```
     serve -s .
     ```
   - This will create a server on your computer and serve the files in the current directory.

4. **Access the Application:**
   - Open your web browser and go to `http://localhost:3000` (or another port if specified) to view and interact with the project.
   - The application will remain accessible as long as the server is running, so do not close the terminal window.

*If you encounter any problems running the code on your computer, please contact me.*