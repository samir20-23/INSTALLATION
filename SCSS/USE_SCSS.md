 
1. `node -v` (to check if Node.js is installed).
2. `npm init -y` (to initialize a new Node.js project).
3. `npm install -g sass` (to install Sass globally).
4. `npm install sass` (to install Sass locally).
5. Create a file named `style.scss` (to write your SCSS code).
6. Open VSCode terminal: `Terminal -> New Terminal`.
7. `sass style.scss style.css` (to compile SCSS to CSS).
8. `sass --watch style.scss:style.css` (to automatically recompile on file changes).
9. Add `<link rel="stylesheet" href="style.css">` (to link the generated CSS in your HTML file).
10. `npm install -g http-server` (to install HTTP server globally).
11. Run `http-server` in the project directory (to start a local server).
12. Open the browser and go to `http://localhost:8080` (to view your app).
13. Create partial files like `_variables.scss` (to organize SCSS code).
14. Import partials using `@import 'variables';` (in your main SCSS file).
15. Install **Live Sass Compiler** extension in VSCode (for automatic SCSS compilation).