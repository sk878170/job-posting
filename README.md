# job-posting

### Software requiremenets for backend
- Tailwind
- Firebase
- react js
- express js
- node js
- mongo DB

### Resources for CSS and Responsiveness
- Tailwind CSS
- Bootstrap

### Steps to backend
1. open a terminal in vs
2. type: npx create-react-app client
3. now goto a folder and type:
   - cd _location of file_
   -  npm init
4. Enter program name (backend), version (ignore), description, entry point (ignore), {test command, git repository,keywords-(ignore)}, author name(your name)
5. now install major files using
   - npm i nodemon
   - npm i express
   - npm i cors
   - npm i mongoose
6. Now goto location client (cd client)
7. npm run start

### Tailwind CSS
1. In VS code terminal run the commands:
   - npm install -D tailwindcss
   - npx tailwindcss init
2. Add this to tailwind.config.js (in src)
  - content: [
    "./src/**/*.{js,jsx,ts,tsx}",
    ],
3. And this to index.css file (in src)
   - @tailwind base;
   - @tailwind components;
   - @tailwind utilities;

#### To check whether it's working or not 

1. open file explorer
2. Go to client under the project folder
3. Tap on file location and type cmd
4. write '_code ._' in cmd
5. It will open VS code in the specific location
6. open terminal
7. type '_npm start_'
8. Check whether your changes in code is updated or not

### Now you can start designing

- Create 2 folders in src Components & Assets to store photos/videos etc.
- Under Components create _Navbar_ and _Home_ folder.
- Create 2 files with _.jsx_ and _.css_ extensions under both the folders.
  
