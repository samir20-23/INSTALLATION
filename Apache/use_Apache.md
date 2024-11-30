To install MySQL and Apache separately without XAMPP:

### 1. **Install Apache:**
   - Download the Apache installer from [Apache Lounge](https://www.apachelounge.com/download/).
   - Extract the downloaded zip file.
   - Copy the folder to `C:\Apache24`.
   - Open `httpd.conf` inside the `conf` folder.
   - Edit the `ServerRoot` and `DocumentRoot` to match your folder location.
   - Open Command Prompt as Administrator and run:
     ```bash
     cd C:\Apache24\bin
     httpd.exe -k install
     ```
   - Start Apache with:
     ```bash
     httpd.exe -k start
     ```

### 2. **Install MySQL:**
   - Download MySQL from the [official website](https://dev.mysql.com/downloads/mysql/).
   - Run the installer and follow the setup wizard.
   - Choose **Server Only** installation type.
   - Set the root password during installation.
   - After installation, start MySQL from the Services panel.

Now, you have Apache and MySQL installed separately!