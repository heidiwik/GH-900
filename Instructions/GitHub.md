# 1. Create a GitHub account

Go to: https://github.com

Create an account and choose your username carefully, as it will be visible throughout GitHub.


# 2. Create a new repository

1. Go to your GitHub profile:

   ```
   https://github.com/<username>
   ```

2. Click the **+** button in the top-right corner.
3. Select **New repository**. Use the following settings:
    - **Repository name:** Any name is fine for now. For a real project, use a meaningful name such as `my-recipe-book`.
    - **Description:** Optional.
    - **Visibility:** Public.
    - Enable **Add a README file**.
    - Click **Create repository**.

# 3. Clone a repository

1. Navigate to the repository on GitHub you just created
2. Click the green **Code** button.
3. Copy the repository URL.
4. Open Visual Studio Code in an empty folder where you want to work.
5. Open a terminal.
6. Run:

```bash
git clone <repository-url>
```

After the clone is complete, you should see the project files in Visual Studio Code.

---

# Connect to GitHub using the command line

Install **GitHub CLI**: https://cli.github.com/

Open **PowerShell** and run:

```bash
gh auth login --web --clipboard
```

GitHub will open in your browser.

Go back to the command line. You will see a code similar to: ```XXXX-XXXX```

Enter the code when prompted and complete the login process.

You should now be connected to GitHub from your computer.