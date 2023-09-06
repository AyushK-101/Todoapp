# Instructions to run this on your local

1. Download the code zip
2. Open the folder in your code editor (e.g VS Code)
3. Open terminal and run "npm install"
4. Now open a new terminal and run "npx json-server --watch data/db.json --port 8000" (This will allow us to make HTTP CRUD requests to the db.json file, we watch port 8000 because default 3000 or 5173 will be in use)
5. Return to the previous terminal and run "npm run dev". This will start the app on localhost:5173
6. Go to the page and explore the options there.
