[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15281852&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.
answer
1. Install Visual Studio Code
Visual Studio Code (VS Code) is a powerful IDE for coding across various languages.

Download VS Code from Visual Studio Code website.
Run the downloaded installer.
Follow the installation wizard instructions.
Launch VS Code after installation.

2. Set Up Git
Git is essential for version control and collaboration.

Download Git from git-scm.com.
Run the downloaded installer.
Follow the installation wizard instructions.
Open a Command Prompt or Git Bash to verify installation:
bash
Copy code
git --version
Configure Git with your name and email:
bash
Copy code
git config --global user.name "daslime"
git config --global user.email "brianmutugidev@gmail.com"
3. Create a GitHub Account
GitHub hosts your Git repositories and facilitates collaboration.

Visit github.com.
Sign up for a free account if you haven't already.
4. Initialize Git Repository
Let’s set up a sample project with Git.

Open VS Code.
Create a new directory for your project.
Open this directory in VS Code (File -> Open Folder).
Initialize a Git repository from VS Code's integrated terminal:
bash
Copy code
git init
Create a README file:
bash
Copy code
echo "# My Project" >> README.md
git add README.md
git commit -m "Initial commit"
5. Install Python
Python is a widely-used programming language.

Download Python from python.org.
Run the downloaded installer.
During installation, check the box "Add Python to PATH".
Follow the installation wizard instructions.
6. Install MySQL
MySQL is a relational database management system.

Download MySQL Installer from dev.mysql.com.
Run the downloaded installer.
Choose "Custom" setup type.
Select MySQL Server and MySQL Workbench for installation.
Follow the installation wizard instructions. Set a root password during setup.
7. Optional: Set Up Docker
Docker simplifies the setup of development environments.

Download Docker Desktop for Windows from docker.com.
Run the downloaded installer.
Follow the installation wizard instructions.
8. Configure Visual Studio Code Extensions
Explore and install useful VS Code extensions.

Open VS Code.
Navigate to Extensions (Ctrl+Shift+X).
Search for extensions like Python, GitLens, Docker (if using Docker), etc.
Install desired extensions to enhance functionality.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
