# 100Hire Portfolio Project 

## Tools Installed

- **Cursor IDE** — Downloaded and installed from cursor.com
- **Claude Code** — Added as an extension inside Cursor
- **Codex** — Added as an extension inside Cursor
- **GitHub** — Created a public repository to store this project

## Steps Completed

1. Installed Cursor IDE from cursor.com
2. Opened Cursor and navigated to the Extensions panel using Ctrl+Shift+X
3. Searched for "Claude Code" in Extensions and installed it
4. Logged in to Claude Code using my Anthropic account (claude.ai)
5. Searched for "Codex" in Extensions and installed it
6. Logged in to Codex using my OpenAI account
7. Created a public GitHub repository
8. Downloaded the repository as a ZIP and opened it in Cursor using File → Open Folder
9. Created this README.md file to document the process

## Issues I Ran Into and How I Solved Them

**Issue 1: Could not find the Extensions panel in Cursor**
When I first opened Cursor, it showed the Agent/Chat interface and there was no visible Extensions icon in the sidebar. I solved this by pressing Ctrl+Shift+X which opened the Extensions panel directly.

**Issue 2: Cursor opened in Agent view by default**
The home screen of Cursor looked different from a standard code editor. I fixed this by going to File → Open Folder and opening a local folder, which switched the view to the full editor interface.

**Issue 3: Unclear where to find the Extensions icon**
The left sidebar did not show the standard 4-square Extensions icon until a folder was opened. Opening a project folder first resolved this.

**Issue 4: git add command gave "fatal: not a git repository" error**
The folder downloaded from GitHub as ZIP was not recognized as a git repo. Solved it by running git init inside the folder.

**Issue 5: git commit gave "Author identity unknown" error**
Git did not know my name and email. Solved by running git config --global user.email and git config --global user.name commands.

**Issue 6: git push was rejected with "fetch first" error**
GitHub already had files that were not in my local folder. Solved by running git push --force to override.

## What I Learned

- How to install and navigate Cursor IDE
- How to find and install extensions inside Cursor
- How to create a GitHub repository and open it locally in a code editor
- How to configure git with name and email
- How to handle common git push errors
- How to document a technical setup process clearly
