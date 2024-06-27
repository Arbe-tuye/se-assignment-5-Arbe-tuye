[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15265850&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
	prerequisites are stable internet connection, 
•	First step is to search Visual Studio Code on your favourite browser.
•	Choose the visual studio depending on your Operating system. if it's windows click on download for windows and it will start downloading the vs code installer.
•	once the download is complete, locate the downloaded installer file, which is typically in downloads folder.
•	Double click on installer file and run as administrator.
•	The installer will prompt setup options. choose the installation location and whether to add shortcuts to the Start Menu and desktop. Click on the "Next" button to proceed.
•	Select additional tasks, such as associating file types with VS Code, depending on preference and click "next"
•	click on the "Install" button to begin the installation process.
•	After the installation is complete. Click on the "Finish" button to exit the installer.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
Theme: Set your preferred font and theme by navigating to File > Preferences > themes > colour theme. In my case I selected dark (visual studio) 
Auto Save: Enable auto save to ensure that your changes are automatically saved. Go to files then click "auto save".
Extensions: Install essential extensions for your programming language or framework to enhance your coding experience. This includes code runner, Matplotlib, prettier, pylance and intellisense.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
Activity Bar:
Provides quick access to different views like Explorer, Search, Source Control, Run and Debug, and Extensions.
Explorer: View and manage files and folders.
Search: Perform text searches within your project.
Source Control: Manage version control operations (e.g., Git).
Run and Debug: Start debugging and run configurations.
Extensions: Browse, install and uninstall extension.
Side Bar
 Displays content and controls related to the currently selected Activity Bar icon.
Uses:
Displays the file and folder structure of your project.
Shows search results and options.
Lists changes, commits, branches, and more.
Displays debug information, breakpoints, and call stack.
Editor bar
The main area where you make changes to your files.
Features:
Tabs: Each open file is represented by a tab at the top.
Multiple Editors: You can split the editor into multiple groups to view and edit files side by side.
Syntax Highlighting: Provides language-specific syntax highlighting.
IntelliSense: Offers code completions, parameter info, quick info, and member lists.
Code Navigation: Allows you to navigate to definitions, declarations, references, etc.
Status Bar
Purpose: Displays information about the current state of the editor and the project.
Information Provided:
Current Branch: The active Git branch.
File Encoding: Shows the encoding of the current file.
Line and Column Numbers: Indicates the cursor's position in the file.
Language Mode: Shows the programming language of the current file.
Feedback and Notifications: Displays messages, warnings, and errors.
Extension Status: Some extensions show status information here.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
Command Palette Provides access to all commands and functions in VS Code. It allows you to execute tasks without navigating through menus, making it an efficient tool for enhancing productivity.
To access command pallette press (ctrl+shift+p) on windows OS.
Examples of common task that can be performed using command palette are:
Open File: Type >Open File
Open Folder: Type >Open Folder to open a folder in the editor.
Find in Files: Type >Find in Files to search across all files in your project.
Replace in Files: Type >Replace in Files to perform search and replace operations across multiple files.
Git Clone: Type >Git: Clone to clone a repository from a remote URL.
Commit Changes: Type >Git: Commit to commit staged changes.
Install Extension: Type >Extensions: Install Extension to browse and install extensions.
Disable Extension: Type >Extensions: Disable to disable a specific extension.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
Extensions are found in the activity bar, which is located on the far left side of the windows, the last icon at the bottom. 
Examples of essential extensions for web development are:
HTML CSS Support (ecmel.vscode-html-css): Provides CSS class and ID completion for HTML.
JavaScript (ES6) code snippets (xabikos.JavaScriptSnippets): Offers a collection of JavaScript snippets.
Prettier - Code formatter (esbenp.prettier-vscode): Formats your code consistently.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
 using the menu, go to view then terminal.
Creating New Terminals: Click the + icon in the terminal panel to create a new terminal. 
Navigating Between Terminals: Use the drop-down menu in the terminal panel to switch between different terminal instances.
Running Commands: Type your commands directly into the terminal and press Enter to execute them
Click the split terminal icon in the terminal panel to split the current terminal into multiple panes.

Advantages of using intergrated terminal as compared to an external terminal are:
Convenience and Efficiency: Remain in the same window, reducing the need to switch applications.
Context Awareness: Starts in the project root directory and inherits project-specific environment variables.
Integration with Editor Features: Provides code snippets, IntelliSense, and seamless integration with tasks and extensions.
Synchronization: Reflects code changes immediately and allows for side-by-side viewing.
Customization: Matches the editor's appearance and supports multiple terminal instances.
Debugging: Integrates with debugging tools and allows direct navigation to error lines in the code.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   Using the Explorer:
Creating a New File:
•	Open the Explorer by clicking the Explorer icon in the Activity Bar or by pressing Ctrl+Shift+E.
•	Right-click on the folder where you want to create a new file.
•	Select New File from the context menu.
•	Enter the name of the new file and press Enter.
Create a New Folder:
•	Right-click on the parent folder.
•	Select New Folder from the context menu.
•	Enter the name of the new folder and press Enter.
Opening Files and Folders
Using the Explorer:
•	Click on a file in the Explorer to open it in the editor.
•	Double-click on a file to keep it open while you navigate to other files.
•	To open a folder, right-click the Explorer pane and select Open Folder, then browse to the desired folder
Deleting:
Right-click on a file or folder in the Explorer and select Delete.
Confirm the deletion when prompted.
Moving:
Alternatively, right-click the file or folder, select Cut, navigate to the desired location, right-click, and select Paste.
Navigating Between Files and Directories Efficiently
Quick Open:
Press Ctrl+P to bring up the Quick Open dialog.
Start typing the name of the file you want to open and select it from the list. This is a fast way to open files without browsing through directories.
Go to Symbol:
Press Ctrl+Shift+O to navigate to symbols within the current file, such as functions or classes.
Go to Definition:
Right-click on a variable, function, or class name and select Go to Definition, or press F12. This navigates to the location where the symbol is defined.
File Tabs:
Open multiple files in tabs and switch between them by clicking the tab headers.
Use Ctrl+Tab to cycle through open tabs.
Explorer Pane:
Use the Explorer pane to navigate your project’s file structure.
Collapse and expand directories by clicking the arrow next to the folder name.
Integrated Terminal:
Use the integrated terminal to navigate directories using command-line commands (cd, ls, etc.)
Side-by-Side Editing:
Split the editor to view multiple files side by side by right-clicking a tab and selecting Split Right or Split Down.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   via menu go to File>preferences>settings.
Theme change:
Open Settings: As mentioned above, In the search bar, type “theme”, Click on Colour Theme and choose your preferred theme from the dropdown list.
Font change:
Open Settings: search for Font Size, in the search bar, type “font size”.
Set Font Size to your preferred value.
Changing Key bindings:
Open Keybindings: Go to File > Preferences > Keyboard Shortcuts 
Search for Command: Use the search bar to find the command you want to change.
Change Keybinding: Click on the command and press the new key combination you want to assign.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
Create a new file or open an existing one. For example, main.py for Python
Click on the Debug icon in the Activity Bar on the side of the window.
Click on the gear icon to open the launch.json file.
Select the appropriate environment (e.g., Python, Node.js). VS Code will generate a basic configuration for you.
Add a Configuration:
In the launch.json file, ensure you have a configuration that points to your main file. Example for Python:
Set Breakpoints:
Open your program file and click in the gutter next to the line number where you want to set a breakpoint. A red dot will appear indicating the breakpoint.
Start Debugging:
Go to the Debug view (click the Debug icon in the Activity Bar).
Select the appropriate configuration and click the green play button to start debugging.
Key debugging features in VS code:
Breakpoints:
Set and remove breakpoints by clicking in the gutter next to the line numbers.
Conditional breakpoints: Right-click on a breakpoint to add conditions or hit counts.
Watch Variables: add variables to the Watch panel to monitor their values as you step through your code.
Call Stack: View the call stack to see the sequence of function calls that led to the current point in the program.
Step Through Code: Use the debugging toolbar to step over, step into, and step out of functions.
Continue execution or restart debugging.
Variable Inspection: Hover over variables in the code to see their current values.
The Variables panel shows the current values of all local and global variables.
Debug Console: Use the Debug Console to execute commands and evaluate expressions in the context of the debugged program.
Exception Handling: Configure how VS Code handles exceptions and whether it should break on caught or uncaught exceptions.
Debugging Configurations: Customize multiple debug configurations in the launch.json file to suit different scenarios and environments.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
 Run git --version in your terminal, to make sure Git is available in system's path
Launch VS Code and open your project folder by navigating to File > Open Folder.
Initializing a Repository:
Open the integrated terminal in VS Code by clicking on view > terminal
Initialize a Git Repository:
In the terminal run git init, this initializes a new Git repository in your project directory.
In the Source Control view, you will see all the changes in your project.
Stage changes by clicking the + icon next to the file or by selecting Stage All Changes.
After staging the changes, enter a commit message in the input box at the top of the Source Control view.
Click the checkmark icon to commit the changes.
Pushing Changes to GitHub, go to GitHub and create a new repository.
Add Remote Repository, In the integrated terminal, add the URL of the GitHub repository as a remote and run git remote add origin <repository-url>
NB: Replace <repository-url> with the URL of your GitHub repository (e.g., https://github.com/username/repo.git).
Push Changes to GitHub, push your committed changes to the remote repository by running git push -u origin master
This command pushes your changes to the master branch on GitHub and sets the remote branch as the default upstream branch.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers. geeks for geeks, Software engineering 9th edition by Ian Sommerville
- Submit your completed assignment by 1st July 

