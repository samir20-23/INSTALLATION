

**hi this installation Kotlin in VSCode:**

### Steps to Set Up Kotlin in Visual Studio Code

#### File: `kotlin_vscode.md`

---

### **1. Download Kotlin Compiler:**
- Visit the [official Kotlin website](https://kotlinlang.org/docs/command-line.html#install-the-compiler).
- Download the latest Kotlin Compiler release.
- Extract the downloaded ZIP to `C:\kotlin` (or your preferred directory).

---

### **2. Add Kotlin to System Environment Variables:**
1. Open **Start Menu** and search for **Environment Variables**.
2. Click on **Edit the system environment variables**.
3. In the **System Properties** window, click **Environment Variables**.
4. Under **System variables**, locate and select the `Path` variable, then click **Edit**.
5. Click **New** and add:
   ```
   C:\kotlin\bin
   ```
6. Click **OK** to save changes.

---

### **3. Verify Kotlin Installation:**
1. Open a new **Command Prompt** window.
2. Type:
   ```bash
   kotlinc
   ```
3. If Kotlin is set up correctly, you should see the Kotlin compiler prompt.

---

### **4. Configure Visual Studio Code (VSCode):**
1. Open **VSCode**.
2. Go to **Extensions** and search for **Kotlin**.
3. Install the **Kotlin Language** extension.
4. Restart VSCode.

---

### **5. Run Kotlin Code in VSCode:**
- Open your Kotlin file (`.kt`).
- Right-click inside the editor and select **Run Code**.

---

Now, you can compile and run Kotlin code directly from Visual Studio Code!