[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15259271&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   1.	Download Visual Studio Code:
o	Visit the official Visual Studio Code download page: Visual Studio Code Download.
o	Click on the Windows download button to download the installer.
2.	Run the Installer:
o	Once the download is complete, locate the downloaded file (VSCodeSetup.exe) in your Downloads folder or the location where you saved the file.
o	Double-click on the VSCodeSetup.exe file to start the installation process.
3.	Accept the License Agreement:
o	Read the license agreement.
o	Check the box to accept the agreement and click Next.
4.	Select Destination Location:
o	Choose the destination folder where you want to install Visual Studio Code.
o	You can accept the default location or choose a different location by clicking Browse.
o	Click Next to continue.
5.	Select Additional Tasks:
o	You can select additional tasks to perform during the installation. These are optional but recommended:
	Create a desktop icon: Check this box if you want a shortcut on your desktop.
	Add to PATH (recommended): Check this box to add Visual Studio Code to your system PATH for easy access from the command line.
	Register Code as an editor for supported file types: This option allows Visual Studio Code to be the default editor for file types it supports.
o	After selecting the desired options, click Next.
6.	Install:
o	Click the Install button to begin the installation. This might take a few minutes.
7.	Launch Visual Studio Code:
o	Once the installation is complete, you can choose to launch Visual Studio Code immediately by checking the box Launch Visual Studio Code and then click Finish.
8.	First Launch and Initial Setup:
o	Welcome Screen: On first launch, you will see the Welcome screen, where you can:
	Get Started: Access tutorials and documentation to help you get started.
	Customize VS Code: Install extensions and configure settings to personalize your development environment.
	Open Folder: Start working on your project by opening a folder.
9.	Install Extensions (Optional but Recommended):
o	Open Extensions View:
	Click on the Extensions icon in the Activity Bar on the side of the window or press Ctrl+Shift+X to open the Extensions view.
o	Search and Install Extensions:
	Search for extensions you need (e.g., Python, GitLens, Prettier) and click Install.
o	Recommended Extensions:
	Python: Provides IntelliSense, linting, and debugging support for Python.
	GitLens: Enhances the Git capabilities built into VS Code.
	Prettier: Code formatter for consistent code style.
	ESLint: Integrates ESLint JavaScript into VS Code.


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   Configure Settings
General Settings
•	Theme: Choose a theme that is easy on your eyes. Go to File > Preferences > Color Theme and select one.
•	Font Size and Family: Set a comfortable font size and typeface. Adjust in File > Preferences > Settings (search for Font Size and Font Family).
•	Line Numbers: Make sure line numbers are visible. Set "editor.lineNumbers": "on".
•	Tab Size and Spaces: Customize your tab size and whether to use spaces or tabs. Example: "editor.tabSize": 4 and "editor.insertSpaces": true.
•	Auto Save: Enable auto-saving of files to avoid losing work. Set "files.autoSave": "afterDelay".
Coding Assistance
•	IntelliSense: Ensure IntelliSense is enabled for code completion suggestions.
•	Format on Save: Automatically format your code when you save. Set "editor.formatOnSave": true.
•	Linting: Enable linting to catch errors and enforce coding standards.
3. Install Extensions
Extensions can significantly enhance your development experience. Here are some essential ones:
General Extensions
•	Prettier - Code Formatter: Automatically format your code.
•	ESLint: Integrate ESLint for JavaScript and TypeScript linting.
•	GitLens: Enhance Git capabilities within VS Code.
•	Path Intellisense: Auto-complete file names.
•	Live Server: Launch a local development server with live reload.
Language-Specific Extensions
•	Python: Essential for Python development (provided by Microsoft).
•	Pylance: Fast, feature-rich language support for Python.
•	JavaScript (ES6) Code Snippets: Useful snippets for JavaScript development.
•	Jupyter: Support for Jupyter notebooks.
•	C/C++: Microsoft’s C/C++ extension for code editing, navigation, and debugging.
•	Java Extension Pack: Essential extensions for Java development.


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
    Activity Bar
The Activity Bar is located on the far left side of the VS Code window. It provides quick access to different views and features within the editor.
•	Icons: The Activity Bar contains a set of icons that represent different views. These typically include:
o	Explorer: Shows the file and folder structure of your workspace.
o	Search: Allows you to search for files and text within your project.
o	Source Control: Integrates version control systems like Git.
o	Run and Debug: Accesses debugging features and configurations.
o	Extensions: Manages extensions and plugins.
•	Purpose: The Activity Bar allows you to switch between these different views quickly, helping you navigate your project and tools efficiently.
2. Side Bar
The Side Bar is adjacent to the Activity Bar and changes its content based on the selected Activity Bar icon.
•	Explorer View: Displays the folder and file structure of the current workspace, allowing you to open and manage files.
•	Search View: Provides a comprehensive search tool for finding and replacing text within your files.
•	Source Control View: Shows version control information, such as changes, branches, and commit history.
•	Run and Debug View: Displays debugging configurations and controls for running and managing debugging sessions.
•	Extensions View: Lists installed extensions and provides a marketplace for finding new extensions.
•	Purpose: The Side Bar provides a detailed and interactive interface for managing different aspects of your project, from files and version control to debugging and extensions.
3. Editor Group
The Editor Group is the main area where you edit your files. It can contain multiple editors in separate tabs and can be split into multiple groups.
•	Tabs: Each open file is represented by a tab in the editor. You can switch between tabs to edit different files.
•	Split Editors: You can split the editor horizontally or vertically to view and edit multiple files side by side.
•	Editor Layout: Customize the layout to suit your workflow, allowing you to compare files or view multiple files at once.
•	Purpose: The Editor Group is the central area for writing and editing code. It provides a flexible and customizable space for working on multiple files simultaneously.
4. Status Bar
The Status Bar is located at the bottom of the VS Code window and provides information and shortcuts related to the current context and workspace.
•	Information Display: Displays information such as the current branch in version control, the selected encoding, line and column numbers, file type, and any running processes or tasks.
•	Interactive Elements: Some elements in the Status Bar are interactive and provide quick access to settings and commands. For example, clicking on the branch name might open the Source Control view, and clicking on the encoding might allow you to change it.
•	Purpose: The Status Bar provides at-a-glance information about the current file and workspace state, and offers quick access to important settings and commands.


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   The most important key combination to is Ctrl+Shift+P, which brings up the Command Palette. This gives access to all functionality within VS Code, including keyboard shortcuts for the most common operations.
 
The Command Palette provides access to many commands. You can run editor commands, open files, search for symbols, and see a quick outline of a file, all using the same interactive window. Here are a few tips:
•	Ctrl+P enables you to navigate to any file or symbol by typing its name
•	Ctrl+Tab cycles you through the last set of files opened
•	Ctrl+Shift+P brings you directly to the editor commands
•	Ctrl+Shift+O enables you to navigate to a specific symbol in a file
•	Ctrl+G enables you to navigate to a specific line in a file
Type ? in the input field to get a list of available commands that you can run from the Command Palette.
 


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   Extensions play a crucial role in Visual Studio Code (VS Code), significantly enhancing its functionality and allowing developers to tailor their coding environment to their specific needs. Here’s a comprehensive look at the role of extensions, how to find, install, and manage them, and examples of essential extensions for web development.
Role of Extensions in VS Code
Extensions in VS Code extend the editor’s capabilities by adding features, tools, and functionalities that are not available out-of-the-box. They can improve productivity, facilitate integration with other tools and services, and provide language-specific support, among other benefits. Examples include:
•	Language Support: Syntax highlighting, IntelliSense, and debugging for different programming languages.
•	Linting and Formatting: Code linters and formatters to enforce coding standards.
•	Version Control Integration: Enhanced Git support and integrations with other version control systems.
•	Framework and Library Support: Tools specific to frameworks like React, Angular, and Vue.js.
•	Themes and Visual Customizations: Custom themes to change the editor’s appearance.
Finding, Installing, and Managing Extensions
Finding Extensions
1.	Extensions View: Open the Extensions view by clicking the Extensions icon in the Activity Bar .
2.	Search Bar: Use the search bar in the Extensions view to find specific extensions by name, keyword, or category.
Installing Extensions
1.	Browse and Select: Browse through the list of extensions. Each extension has an "Install" button.
2.	Install: Click the "Install" button. Once installed, the extension might prompt you to reload VS Code to activate it.
3.	Recommended Extensions: VS Code might suggest recommended extensions based on the type of files in your project or workspace.
Managing Extensions
1.	Installed Extensions: View and manage your installed extensions in the Extensions view under the "Installed" section.
2.	Disable/Enable: Disable or enable extensions as needed. Right-click on an extension and select "Disable" or "Enable".
3.	Uninstall: Uninstall extensions that you no longer need by right-clicking and selecting "Uninstall".
4.	Settings and Configurations: Some extensions have settings that can be configured. Access these through the gear icon next to the extension or through the global settings (File > Preferences > Settings).
Essential Extensions for Web Development
Here are some must-have extensions for web developers:
General Extensions
•	Prettier - Code Formatter: An opinionated code formatter that supports many languages.
•	ESLint: Integrates ESLint into VS Code, providing real-time linting for JavaScript and TypeScript.
•	GitLens: Supercharges the built-in Git capabilities with additional features like blame annotations and repository insights.
HTML/CSS
•	HTML Snippets: Provides a set of useful HTML snippets.
•	CSS Peek: Allows you to quickly see which CSS rules are affecting an HTML element.
•	IntelliSense for CSS class names in HTML: Autocompletes CSS class names in HTML files.
JavaScript/TypeScript
•	JavaScript (ES6) Code Snippets: A collection of ES6 code snippets.
•	npm Intellisense: Autocompletes npm modules in import statements.
•	Path Intellisense: Autocompletes file paths in your projects.
Framework-Specific Extensions
Tools and Utilities
•	Live Server: Launch a local development server with live reload capability for static and dynamic pages.
•	Debugger for Chrome: Debug your JavaScript code running in the Google Chrome browser directly from VS Code.
•	REST Client: Send HTTP requests and view responses directly in VS Code, useful for testing APIs.
By leveraging these extensions, web developers can create a powerful and efficient development environment within VS Code, tailored to their specific workflow and technology stack.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   Opening the Integrated Terminal
1.	Via Menu:
o	Navigate to the top menu bar and select View > Terminal.
2.	Using Keyboard Shortcut:
o	On Windows/Linux: Press Ctrl + (backtick)`.
o	On macOS: Press Cmd + (backtick)`.
3.	Activity Bar:
o	Click the terminal icon if it is available in the Activity Bar (depending on your configuration).
Once opened, the terminal will appear at the bottom of the VS Code window. You can open multiple terminal sessions, split them, or navigate between them using the icons in the terminal panel or keyboard shortcuts.
Using the Integrated Terminal
•	Basic Commands: You can run any command that you would in a standalone terminal, such as ls, cd, npm install, git status, etc.
•	Multiple Terminals: Click the + icon in the terminal panel to open multiple terminal instances. You can switch between them using the dropdown menu or by clicking on the terminal tabs.
•	Split Terminals: Click the split terminal icon to create side-by-side terminal instances.
•	Customization:
o	Right-click the terminal tab and choose Rename to give your terminal sessions custom names.
o	Change the default shell by navigating to File > Preferences > Settings, then search for terminal.integrated.shell. Set the path for your preferred shell (e.g., PowerShell, Git Bash, Zsh).
Advantages of Using the Integrated Terminal Compared to an External Terminal
1. Contextual Relevance
•	Project Integration: The integrated terminal opens in the context of your current project directory, eliminating the need to navigate to your project folder manually.
•	Environment Consistency: Shares the same environment and settings as your VS Code workspace, ensuring consistency in environment variables and configurations.
2. Workflow Efficiency
•	Single Interface: You can perform terminal operations alongside coding, debugging, and file management without switching between different applications.
•	Quick Commands: Quickly run build scripts, execute code, and manage version control directly from the same interface you are coding in.
3. Enhanced Productivity
•	Integrated Tools: Extensions and tools within VS Code can interact with the terminal, offering features like debugging, running tests, and handling commands through integrated UI elements.
•	Synchronization: Actions in the terminal (like navigating directories) are synchronized with the Explorer view in VS Code.
4. Customizability and Flexibility
•	Multiple Terminals: Open multiple terminal instances and organize them in a single window.
•	Terminal Splitting: Split terminals for side-by-side command executions.
•	Customization: Customize the appearance, shell, and behavior of the integrated terminal to match your preferences and needs.
5. Convenience Features
•	Integrated Output: Errors and outputs from the terminal can directly link to the editor, allowing quick navigation to relevant parts of the code.
•	Terminal History and Shortcuts: Access terminal history, use shortcuts, and benefit from terminal-based features like quick access to previously run commands.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   Creating Files and Folders. This can be achieved by using the explorer pane, the keyboard shortcuts or opening recent files and folders.
1.	Using the Explorer Pane:
o	Create a File:
	Open the Explorer pane by clicking the Explorer icon in the Activity Bar.
	Right-click on a folder in the Explorer pane or the workspace root.
	Select New File, then enter the file name and press Enter.
o	Create a Folder:
	Right-click on the workspace root or an existing folder.
	Select New Folder, then enter the folder name and press Enter.
2.	Using Keyboard Shortcuts:
o	Create a File: To create a new untitled file. Save and specifying the desired location and file name.
o	Create a Folder: Use the Explorer pane as mentioned above.
Opening Files and Folders
1.	Opening a Single File:
o	Use Ctrl+O to open a file dialog. Navigate to the file you want to open and select it.
o	Alternatively, double-click a file in the Explorer pane to open it.
2.	Opening a Folder:
o	Use Ctrl+K, Ctrl+O  to open a folder dialog. Navigate to and select the folder you want to open.
o	Alternatively, drag and drop a folder from your file system into the VS Code window.
3.	Opening Recent Files and Folders:
o	Use Ctrl+R to bring up a list of recently opened files and folders. Select from the list to quickly reopen them.
Managing Files and Folders
1.	Renaming:
o	Right-click on a file or folder in the Explorer pane and select Rename.
o	Alternatively, select the file or folder and press F2 to rename.
2.	Deleting:
o	Right-click on a file or folder in the Explorer pane and select Delete.
o	Confirm the deletion in the prompt that appears.
3.	Moving:
o	Drag and drop files or folders within the Explorer pane to move them to a new location.
o	Alternatively, cut (Ctrl+X or Cmd+X) and paste (Ctrl+V or Cmd+V) files and folders to move them.
Navigating Between Files and Directories Efficiently
Using the Explorer Pane
•	File Navigation: Double-click a file to open it. Single-click to preview it without opening a new tab.
•	Folder Navigation: Expand and collapse folders to quickly access nested files and subfolders.
Using the Command Palette
•	Press Ctrl+Shift+P to open the Command Palette.
•	Type commands like Open File, Open Folder, or Recent Files to quickly access files and folders.
Quick Open
•	Press Ctrl+P to open the Quick Open dialog.
•	Start typing the name of the file you want to open. Quick Open will filter and display matching files. Press Enter to open the selected file.
Keyboard Shortcuts
•	Navigate Between Open Files: Use Ctrl+Tab to cycle through open files.
•	Navigate Between Editor Groups: Use Ctrl+1, Ctrl+2, etc to switch between editor groups.
•	Move Between Open Tabs: Use Ctrl+Page Up and Ctrl+Page to move between tabs.
File Tabs
•	Open Tabs: Use the tabs at the top of the editor to switch between open files.
•	Close Tabs: Click the X on a tab to close it or use Ctrl+W.
Integrated Terminal
•	Use the integrated terminal to navigate and manage files using command-line tools like ls, cd, mkdir, and rm.


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   1.	Settings Interface:
o	Via Menu: Go to File > Preferences > Settings or Code > Preferences > 
o	Using Keyboard Shortcut: Press Ctrl +.
2.	Settings JSON File:
o	Open the Command Palette with Ctrl + Shift + P.
o	Type Preferences: Open Settings (JSON) and select it to open the settings JSON file directly.
Customizing Settings
Changing the Theme
1.	Via Settings Interface:
o	Open the settings interface.
o	In the search bar at the top, type theme.
o	Under Color Theme, click on the drop-down menu to see a list of available themes.
o	Select your desired theme from the list. The change will apply immediately.
2.	Via Command Palette:
o	Open the Command Palette with Ctrl + Shift + P.
o	Type Preferences: Color Theme and select it.
o	Choose a theme from the list that appears.
Changing the Font Size
1.	Via Settings Interface:
o	Open the settings interface.
o	In the search bar, type font size.
o	Under Editor: Font Size, adjust the font size by entering a new value. The default is typically 14.
o	The font size will change immediately in the editor.
2.	Via Settings JSON File:
o	Open the settings JSON file.
o	Add or modify the following line:
json
Copy code
"editor.fontSize": 16
o	Save the file to apply the change.
Changing Keybindings
1.	Via Keybindings Interface:
o	Open the Command Palette with Ctrl + Shift + P.
o	Type Preferences: Open Keyboard Shortcuts and select it.
o	This will open the keybindings editor where you can search for and modify keybindings.
o	To change a keybinding, find the command you want to change, click on the pencil icon next to it, and press the new key combination.
2.	Via Keybindings JSON File:
o	Open the Command Palette with Ctrl + Shift + P.
o	Type Preferences: Open Keyboard Shortcuts (JSON) and select it.
o	Add a new keybinding or modify an existing one. For example:
json
Copy code
[
    {
        "key": "ctrl+k ctrl+c",
        "command": "editor.action.addCommentLine",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+k ctrl+u",
        "command": "editor.action.removeCommentLine",
        "when": "editorTextFocus"
    }
]
o	Save the file to apply the changes.
Examples of Customizations
1.	Changing the Theme to Dark+:
o	Open the Command Palette with Ctrl + Shift + P.
o	Type Preferences: Color Theme and select Dark+ (default dark) from the list.
2.	Setting the Font Size to 18:
o	Open the settings interface.
o	Search for font size and set the Editor: Font Size to 18.
3.	Customizing Keybindings for Commenting Code:
o	Open the keybindings editor (Preferences: Open Keyboard Shortcuts from the Command Palette).
o	Search for Toggle Line Comment.
o	Click the pencil icon next to Toggle Line Comment and press the desired key combination (e.g., Ctrl + / or Cmd + /).


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
   To bring up the Run and Debug view, select the Run and Debug icon in the Activity Bar on the side of VS Code. You can also use the keyboard shortcut Ctrl+Shift+D.
 
The Run and Debug view displays all information related to running and debugging and has a top bar with debugging commands and configuration settings.
If running and debugging is not yet configured (no launch.json has been created), VS Code shows the Run start view.
 
Run menu
The top-level Run menu has the most common run and debug commands:
 

To run or debug a simple app in VS Code, select Run and Debug on the Debug start view or press F5 and VS Code will try to run your currently active file.
However, for most debugging scenarios, creating a launch configuration file is beneficial because it allows you to configure and save debugging setup details. VS Code keeps debugging configuration information in a launch.json file located in a .vscode folder in your workspace (project root folder) or in your user settings or workspace settings.
To create a launch.json file, select create a launch.json file in the Run start view.
 
VS Code will try to automatically detect your debug environment, but if this fails, you will have to choose it manually:
Debug actions
Once a debug session starts, the Debug toolbar will appear on the top of the editor.
 
Action	Explanation
Continue / Pause
F5	Continue: Resume normal program/script execution (up to the next breakpoint).
Pause: Inspect code executing at the current line and debug line-by-line.
Step Over
F10	Execute the next method as a single command without inspecting or following its component steps.
Step Into
F11	Enter the next method to follow its execution line-by-line.
Step Out
Shift+F11	When inside a method or subroutine, return to the earlier execution context by completing remaining lines of the current method as though it were a single command.
Restart
Ctrl+Shift+F5	Terminate the current program execution and start debugging again using the current run configuration.
Stop
Shift+F5	Terminate the current program execution.
Tip: Use the setting debug.toolBarLocation to control the location of the debug toolbar. It can be the default floating, docked to the Run and Debug view, or hidden. A floating debug toolbar can be dragged horizontally and also down to the editor area.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    •	Git: Ensure Git is installed on your system. Download it from git-scm.com.
•	GitHub Account: Ensure you have a GitHub account. Sign up at github.com if you don't have one.
•	VS Code: Ensure Visual Studio Code is installed on your system. Download it from code.visualstudio.com.
Step-by-Step Guide
Step 1: Install Git on Your System
1.	Download Git: Visit git-scm.com and download the installer for your operating system.
2.	Install Git: Run the installer and follow the setup instructions, ensuring you select options to add Git to your system PATH.
Step 2: Open Your Project in VS Code
1.	Open VS Code: Launch VS Code.
2.	Open Folder: Go to File > Open Folder... and select the folder containing your project files. If you don't have a project yet, you can create a new folder and add some files to it.
Step 3: Initialize a Git Repository
1.	Open Source Control View: Click the Source Control icon in the Activity Bar on the left side of VS Code or press Ctrl+Shift+G.
2.	Initialize Repository: Click the "Initialize Repository" button. This creates a .git folder in your project directory, initializing it as a Git repository.
Step 4: Make Changes and Commit
1.	Make Changes: Edit or create files in your project.
2.	Stage Changes: In the Source Control view, you will see a list of modified files under "Changes". Hover over the files you want to stage and click the + icon next to them. Alternatively, you can click the + icon at the top of the "Changes" section to stage all changes.
3.	Commit Changes:
o	Write a commit message in the input box labeled "Message" at the top of the Source Control view.
o	Click the checkmark icon at the top to commit the staged changes.
Step 5: Create a GitHub Repository
1.	Create Repository on GitHub:
o	Go to github.com and sign in to your account.
o	Click the + icon in the top-right corner and select "New repository".
o	Name your repository and configure its visibility (public or private).
o	Click "Create repository".
o	Copy the repository URL (e.g., https://github.com/username/repository.git).
Step 6: Add GitHub Remote
1.	Open Terminal in VS Code: Open the integrated terminal in VS Code by going to View > Terminal or pressing Ctrl+ (backtick).
2.	Add Remote Repository:
o	In the terminal, run the following command:
sh
Copy code
git remote add origin https://github.com/username/repository.git
o	Replace username and repository with your GitHub username and repository name.
Step 7: Push Changes to GitHub
1.	Push to GitHub:
o	In the terminal, run:
sh
Copy code
git push -u origin master
o	This command pushes your local commits to the master branch on GitHub and sets origin as the default remote repository.
Key Git Features in VS Code
Source Control View
•	Changes: See a list of all changes in your working directory.
•	Staged Changes: See a list of all changes that have been staged for commit.
•	Commit Message: Input box for writing commit messages.
•	Actions: Buttons for staging all changes, committing, and more.
Diff Viewing
•	Click on a file in the Source Control view to see a side-by-side comparison of the current and previous versions.
Branch Management
•	Create, switch, and delete branches using the branch icon in the Source Control view or the Git commands in the Command Palette.
Merge and Rebase
•	Handle merge conflicts and perform rebase operations directly within VS Code.
Example Workflow
1.	Open Project:
o	Open your project folder in VS Code.
2.	Initialize Git:
o	Go to the Source Control view and initialize the repository.
3.	Make Edits:
o	Edit or create files in your project.
4.	Stage and Commit:
o	Stage the changes and commit them with a message.
5.	Create GitHub Repo:
o	Create a new repository on GitHub and copy its URL.
6.	Add Remote and Push:
o	Add the GitHub repository as a remote and push your local commits to GitHub.

References
1.	https://code.visualstudio.com/docs/copilot/setup#_step-3-sign-in-to-github
2.	https://chatgpt.com/c/bc147bbb-9cb2-4197-94fa-a736fe357be3


 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

