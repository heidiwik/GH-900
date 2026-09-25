# Install Git

## Install Git on Windows

1. Download **Git for Windows**: https://git-scm.com/download/win

2. Run the installer and make sure to adjust these settings:
    - Default editor: Change to Notepad++ or the text editor of your choice
    - Name of initial branch: Change to **main**
    - Use the **default settings** for everything else.

3. After the installation is complete, open **Visual Studio Code**.

4. Open the terminal using **Ctrl + Ö** (or open it from **Terminal → New Terminal**).

5. Type the following command: 
```
git 
```

If Git is installed successfully, you should see a list of Git commands and usage instructions on the terminal

---

## 2. Configure your name and email

Your name and email address will be attached to your Git commits. Open 
Visual Studio Code terminal and execute following commands

Replace the placeholders with your own information:

```bash
git config --global user.name "<your-name>"
git config --global user.email "<your-email>"
```

You can verify the configuration with:

```bash
git config --global --list
```


### Using Git with Visual Studio Code


See quickstart for Visual Studio Code: https://code.visualstudio.com/docs/sourcecontrol/quickstart
