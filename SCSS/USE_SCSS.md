Here are all the steps to set up and work with SCSS in your project:

1. **Check if Node.js is installed:**
   ```bash
   node -v
   ```

2. **Initialize a new Node.js project:**
   ```bash
   npm init -y
   ```

3. **Install Sass globally:**
   ```bash
   npm install -g sass
   ```

4. **Install Sass locally:**
   ```bash
   npm install sass
   ```

5. **Create a file named `style.scss`:**
   Write your SCSS code in this file.

6. **Open VSCode terminal:**
   Go to `Terminal -> New Terminal` in VSCode.

7. **Compile SCSS to CSS:**
   ```bash
   sass style.scss style.css
   ```

8. **Automatically recompile SCSS on file changes:**
   ```bash
   sass --watch style.scss:style.css
   ```

9. **Link the generated CSS file in your HTML file:**
   ```html
   <link rel="stylesheet" href="style.css">
   ```

10. **Install HTTP server globally:**
    ```bash
    npm install -g http-server
    ```

11. **Run the HTTP server in the project directory:**
    ```bash
    http-server
    ```

12. **Open the browser and go to `http://localhost:8080`:**
    This will open your app in the browser.

13. **Create partial SCSS files (e.g., `_variables.scss`) to organize your SCSS code:**
    Partial files allow you to split your SCSS code into manageable pieces.

14. **Import partial files into your main SCSS file:**
    In `style.scss`, import partials like this:
    ```scss
    @import 'variables';
    ```

15. **Install the **Live Sass Compiler** extension in VSCode:**
    This extension will automatically compile your SCSS files as you make changes.

By following these steps, you'll have SCSS set up in your project, and you can easily compile and manage your stylesheets.
