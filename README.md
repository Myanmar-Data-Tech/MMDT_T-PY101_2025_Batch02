### 📁 Assignment Submission on GitHub

All homework assignments for this course must be submitted via a **GitHub Pull Request**. This process ensures that your submissions are tracked, organized, and provides a clear way for the instructor to review your work.

You have two options for submitting your work, depending on your comfort level with Git.

---

### **Option 1: Web-Based Submission (Recommended for Beginners)** 🌐

This method allows you to submit your homework directly through the GitHub website without needing to install Git on your computer.

**Step 1: Fork the Homework Repository**
* Navigate to the class's **homework repository** on GitHub.
* Click the **'Fork'** button in the top-right corner. This will create a personal copy of the repository in your GitHub account.

**Step 2: Create Your Submission Folder**
* In your forked repository, click on the **'Add file'** button and then select **'Create new file'**.
* In the filename field, type your name followed by a forward slash, for example: `jane-doe/`.
* This will automatically create a new folder. After the slash, type the name of your homework file, like `jane-doe/Ex01_Homework.txt`.

**Step 3: Upload Your Homework Files**
* Navigate into the folder you just created.
* Click **'Add file'** and then **'Upload files'**.
* Drag and drop all your completed homework files directly into the browser window.

**Step 4: Commit and Submit**
* At the bottom of the page, add a clear and descriptive commit message, such as: `Submit Homework 1 - [Your Name]`.
* Click the **'Commit changes'** button.
* Go back to the main page of your forked repository. You should see a banner indicating that your changes are ready to be submitted. Click **'Contribute'** and then **'Open pull request'**.
* On the next screen, give your pull request a clear title and description, and then click **'Create pull request'** to submit.

---

### **Option 2: Local Machine Submission (Advanced Users)** 💻

This is the standard, professional method for using Git. It requires you to have Git installed on your computer.

**Step 1: Fork and Clone the Repository**
* **Fork:** First, fork the main homework repository on GitHub, just like in the web-based method.
* **Clone:** Open your terminal or command prompt. Clone your forked repository to your local machine:
    ```
    git clone [https://github.com/](https://github.com/)<your-name>/MMDT_T-PY101_2025_Batch[02]
    ```
* **Navigate:** Change into the repository folder:
    ```
    cd [name of the repo]
    ```

**Step 2: Create a Branch and a Folder**
* To keep your work organized, create a new branch with your name:
    ```
    git checkout -b [your-name]
    ```
* Then, create a dedicated folder for all your homework submissions:
    ```
    mkdir [your-name]
    ```

**Step 3: Add, Commit, and Push Your Homework**
* **Navigate:** Change into your folder:
    ```
    cd [your-name]
    ```
* Move your completed homework files into the folder you created.
* Stage the new files to be tracked by Git:
    ```
    git add .
    ```
* Commit your changes with a clear message:
    ```
    git commit -m "Submit Homework [Number] - [Your Name]"
    ```
* Push your changes to your forked repository on GitHub:
    ```
    git push origin [your-name-or-id]
    ```

**Step 4: Create a Pull Request**
* Go to your forked repository on GitHub.
* A banner will appear at the top, prompting you to create a pull request from your new branch. Click **'Compare & pull request'**.
* Write a clear title and description for your submission and click **'Create pull request'**.
