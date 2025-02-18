PART 1: Directions on Using Visual Studio Code/GIT/GitHub:

Set Up Git (MacOS; Homebrew):
1. Choose one of the following options for installing Git on macOS (Git, nd):

      a. Homebrew 

            i. URL: https://brew.sh/

      b. MacPorts

            i. URL: https://www.macports.org/install.php

      c. Xcode

            i. URL: https://developer.apple.com/xcode/

      d. Binary Installer

            i. URL: https://sourceforge.net/projects/git-osx-installer/

      e. Building from source

            i. URL: https://www.kernel.org/pub/software/scm/git/

      f. Installing git-gui

            i. URL: (use homebrew) https://brew.sh/

            ii. Prompt: brew install git-gui

2. Open MacOS terminal

3. (Using Homebrew) Copy, Paste, and Run prompt in MacOS terminal:

      a. Prompt: $ brew install git

4. Set username (GitHub, n.d., Set up Git)

      a. Prompt: $ git config --global user.name "Your Name"

5. Set email (GitHub, n.d., Set up Git)

      a. Prompt: $ git config --global user.email "your.email@example.com"

Set Up GitHub:

1. Go to the GitHub website

      a. URL: https://github.com/

2. Find the sign up button:

      a. URL: https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home

3. Create username

4. Enter email and password

5. Verify email

Set Up Visual Studio Code (Chinthala, 2024):

1. Go to the Visual Studio Code download website

      a. URL: https://code.visualstudio.com/download

2. Create a New Folder on your computer

3. Once created, open Visual Studio Code

4. Click the “Open Folder” button and find the folder you just created and open it

5. If needed, allow access and tell the system to trust authors

6. Once you’re back at the homepage, that new folder should appear on the left-hand side and you will select the “New File” button to the right of the new folder name

      a. It will be the first icon that looks like a piece of paper that is dog-eared with a plus, and when you hover over the icon, it will say “New File”

      b. Once created, it will immediately bring you into the new file

7. In the left-hand side bar, click on the Extensions icon

      a. It looks like a square broken into 4 pieces with the top left corner detached from it, and when you hover over the icon it will say “Extensions”

8. In the search bar in the top left corner, type “Code Runner”, and install it

      a. Identifier: formulahendry.code-runner

      b. URL: https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner

9. In the search bar, type “HTML CSS Support”, and install it

      a. Identifier: ecmel.vscode-html-css

      b. URL: https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css

10. In the search bar, type “JavaScript (ES6) code snippets”, and install it

      a. Identifier: xabikos.javascri

      b. URL: https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets

11. In the search bar, type “GitHub Pull Requests”, and install it

      a. Identifier: github.vscode-pull-request-github

      b. URL: https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github

12. You should be prompted to sign into GitHub, so sign in

      a. In the bottom left corner, a profile icon will have a notification pop-up to prompt you to sign into GitHub in order to use the last extension installed, GitHub Pull Requests

13. Select the green button that reads “Authorize Visual-Studio-Code”


PART 2: Glossary:

**Branch** - A **branch** is a parallel version of a **repository**. It is contained within the **repository**, but does not affect the primary or main **branch** allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can **merge** your **branch** back into the main **branch** to publish your changes (GitHub, n.d.). 

**Clone** - A **clone** is a copy of a **repository** that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a **clone**, you can edit the files in your preferred editor and use **Git** to keep track of your changes without having to be online. The **repository** you **cloned** is still connected to the **remote** version so that you can **push** your local changes to the **remote** to keep them synced when you're online (GitHub, n.d.).

**Commit** - A **commit**, or "revision", is an individual change to a file (or set of files). When you make a **commit** to save your work, **Git** creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes **committed** along with who made them and when. **Commits** usually contain a **commit** message which is a brief description of what changes were made (GitHub, n.d.).

**Fetch** - When you use **git** **fetch**, you're adding changes from the **remote** **repository** to your local working **branch** without **committing** them. Unlike **git** **pull**, **fetching** allows you to review changes before **committing** them to your local **branch** (GitHub, n.d.).

**GIT** - **GIT** is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that **GitHub**, the social and user interface, is built on top of (GitHub, n.d.).

**Github** - An open source version control system. Version control is the use of a system to keep track of changes to source code or other documents. Allows the ability for multiple people to work on the same document at the same time. Can revert to a previous version if serious bugs are introduced. (Powerpoint)

**Merge** - Merging takes the changes from one **branch** (in the same **repository** or from a fork), and applies them into another. This often happens as a "**pull** request" (which can be thought of as a request to **merge**), or via the command line. A **merge** can be done through a **pull** request via the **GitHub**.com web interface if there are no conflicting changes, or can always be done via the command line (GitHub, n.d.).

**Merge Conflict** - A difference that occurs between **merged** **branches**. **Merge conflicts** happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The **merge conflict** must be resolved before you can **merge** the **branches** (GitHub, n.d.).

**Push** - To **push** means to send your **committed** changes to a **remote** **repository** on **GitHub**.com. For instance, if you change something locally, you can **push** those changes so that others may access them (GitHub, n.d.).

**Pull** - **Pull** refers to when you are **fetching** in changes and merging them. For instance, if someone has edited the **remote** file you're both working on, you'll want to **pull** in those changes to your local copy so that it's up to date (GitHub, n.d.). 

**Remote** - This is the version of a **repository** or **branch** that is hosted on a server, most likely **GitHub**.com. **Remote** versions can be connected to local clones so that changes can be synced (GitHub, n.d.).

**Repository** - A **repository** is the most basic element of **GitHub**. They're easiest to imagine as a project's folder. A **repository** contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private (GitHub, n.d.).

References

Chinthala, L. A. (2024, October 19). How to setup VS Code IDE [Video]. Panopto. https://njit.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=c61f03ed-f0b0-4a74-b6f3-b1fd0004ac2a

Git. (n.d.). Git - Downloads. Git SCM. Retrieved February 18, 2025, from https://git-scm.com/downloads

GitHub. (n.d.). GitHub glossary. GitHub Docs. Retrieved February 17, 2025, from https://docs.github.com/en/get-started/learning-about-github/github-glossary

GitHub. (n.d.). Set up Git. GitHub Docs. Retrieved February 18, 2025, from https://docs.github.com/en/get-started/getting-started-with-git/set-up-git
