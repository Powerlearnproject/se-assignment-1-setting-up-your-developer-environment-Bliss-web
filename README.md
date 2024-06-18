[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15288710&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:



1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
ANSWER
Here are the steps to download Windows 11:
Visit the Microsoft Website: Go to the Windows 11 download page.
Choose an Option:
Windows 11 Installation Assistant: Click "Download now" to upgrade your current PC.
Create Windows 11 Installation Media: Download the tool to create a bootable USB 
Download Windows 11 Disk Image (ISO): Select the ISO file for a custom installation or virtual machine.




2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
ANSWER
Here's a step-by-step guide to installing a text editor or Integrated Development Environment (IDE) suitable for my programming languages and workflow. I'll cover Visual Studio Code (VS Code), a popular and versatile choice.
#Installing Visual Studio Code
-Download VS Code:
-Visit the VS Code download page.
-Select the installer for your operating system (Windows, macOS, or Linu).
#Run the Installer:
-For Windows: Double-click the downloaded .exe file and follow the installation wizard.
#Launch VS Code:
-Open VS Code from your Start Menu (Windows).
#Install Extensions:
-Open the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or pressing Ctrl+Shift+X.
-Search for and install extensions relevant to your development needs, such as:
*Prettier for code formatting.
*ESLint for JavaScript linting.
*Python for Python support.
*GitLens for Git integration.
#Configure Settings:
-Go to File > Preferences > Settings or press Ctrl+, to customize your settings.
-Configure settings like editor font size, theme, and other preferences.
#Installing IntelliJ IDEA (for Java Development)
-Download IntelliJ IDEA:
-Visit the IntelliJ IDEA download page.
-Choose the Community (free) or Ultimate (paid) edition and download the installer.
#Run the Installer:
-For Windows: Double-click the downloaded .exe file and follow the installation wizard.
#Launch IntelliJ IDEA:
-Open IntelliJ IDEA from your Start Menu (Windows).
#Set Up Your First Project:
-On the Welcome screen, click "Create New Project" and follow the prompts to set up your project.
-Choose the relevant SDK and libraries for your project.
#Install Plugins:
-Go to File > Settings > Plugins or IntelliJ IDEA > Preferences > Plugins (macOS).
-Browse and install plugins relevant to your development needs, such as Lombok, CheckStyle, and others.




3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
ANSWER
Here's how to set up a version control system with Git and GitHub:
#Install Git
-Download Git: Go to the Git download page and select your operating system.
-Install Git: Follow the installation instructions for your OS.
-Windows: Run the installer and follow the prompts.
#Configure Git
1.Open a Terminal: (Command Prompt on Windows).
2.Set Your Username:
    git config --global user.name "Your Name"
3.Set Your Email:
   git config --global user.email "your.email@example.com"
#Create a GitHub Account
1.Sign Up: Go to GitHub and create an account.
#Initialize a Git Repository
1.Navigate to Your Project Directory:
  cd path/to/your/project
2.Initialize the Repository:
git init
3.Add Files:
  git add .
4.Make Your First Commit:
  git commit -m "Initial commit"
#Create a GitHub Repository
1.Create a New Repository: On GitHub, click "New" and fill in the details for your repository.
2.Push Your Local Repository to GitHub:
git remote add origin https://github.com/your-username/your-repo.git
git branch -M main
git push -u origin main




4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
ANSWER
#Installing Python
Download Python:
-Go to the Python download page.
-Click on the appropriate installer for your operating system (Windows, macOS, Linux).
#Install Python:
Windows: Run the downloaded .exe file and follow the installation prompts. Make sure to check "Add Python to PATH".
#Verify Installation:
-Open a terminal or command prompt.
-Type python --version or python3 --version to check the installed version.
#Installing Necessary Tools
1.pip: Python's package installer.
-Usually included with Python installation.
-Verify by typing pip --version or pip3 --version.
2.Virtual Environment:
-Install with pip install virtualenv.
-Create a virtual environment: virtualenv venv.
-Activate the virtual environment:
-Windows: venv\Scripts\activate
3.Install Project Dependencies:
-Inside the activated virtual environment, install necessary packages using:
*pip install package-name
-If you have a requirements.txt file, install all dependencies with:
*pip install -r requirements.txt
#Verify Everything is Set Up
1.Create a Simple Python Script:
*print("Hello, World!")
2.Run the Script:
*Save the script as hello.py.
*Run it with python hello.py or python3 hello.py.




5. Install Package Managers:
   If applicable, install package managers like pip (Python).
ANSWER
To install and set up package managers for Python, follow these steps:
#Install pip (Python)
1.Check if pip is installed:
 bash
 pip --version
If pip is not installed, you can install it by following the steps below.
2.Install pip:
*If you have Python 3.4+ installed, pip should come pre-installed. If not, you can manually install it.
*Download get-pip.py:
  bash
  curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
*Run the script:
 bash
 python get-pip.py
#Verify pip installation:
  bash
  pip --version
#Usage
1.Install a package:
  bash
  pip install package-name
*Upgrade a package:
 bash
 pip install --upgrade package-name
*Install packages from a requirements file:
 bash
 pip install -r requirements.txt




6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
ANSWER
Here are the steps to download, install, and configure MySQL:
#Download MySQL
1.Visit the Download Page: Go to the MySQL Installer for Windows.
2.Select the Installer: Choose between the "web" and "offline" installer. The web installer is smaller and downloads necessary files during installation.
#Install MySQL
1.Run the Installer: Double-click the downloaded .msi file to start the installation.
2.Choose Setup Type: Select a setup type (Developer Default, Server only, etc.) based on your needs.
3.Check Requirements: The installer will check for requirements. Install any missing prerequisites.
4.Installation: Proceed with the installation steps and wait for the process to complete.
#Configure MySQL
1.Launch MySQL Installer: Open the MySQL Installer after installation.
2.Server Configuration:
 *Choose "Standalone MySQL Server".
 *Set the configuration type (Development, Server, Dedicated).
 *Choose the port (default is 3306).
 *Configure networking (optional).
3.Authentication:
 *Set the root password.
 *(Optional) Create additional user accounts.
 *Apply Configuration: Click "Execute" to apply the configuration settings.
#Verify Installation
1.Open MySQL Command Line Client: Enter the root password set during configuration.
2.Run a Test Query:
  sql
  SHOW DATABASES;




7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
ANSWER
Setting up development environments and using virtualization tools like Docker or virtual machines can greatly enhance your development process by isolating project dependencies and ensuring consistency across different machines. Here’s how i did it:
USING DOCKER
Install Docker: Download and install Docker from the official Docker website.
-Create a Dockerfile: Define the environment with a Dockerfile.
-Build Image: Run docker build -t your-image-name . in the project directory.
-Run a Container: Use docker run -d -p 8000:8000 your-image-name to start the application.

USING VIRTUAL MACHINES
Install VirtualBox: Download and install VirtualBox from Oracle’s website.
-Create a New VM: Set up a new virtual machine with your preferred operating system.
-Install Dependencies: Configure the VM with all necessary development tools and libraries.
-Snapshot Your VM: Take snapshots to save the state of your VM at different points in time.

ADVANTAGE
-Isolation: Each project can run in its own environment without affecting others.
-Consistency: Ensures that your development environment is consistent across different machines.
-Reproducibility: Easily share environments with team members.

CONSIDERATION
-Performance: Virtual machines can be resource-intensive compared to Docker containers.
-Complexity: Setting up and managing these environments can require additional knowledge and setup time.



8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   ANSWER
 1. Visual Studio Code (VS Code)
 A. Prettier: Code formatter.
 B. ESLint: JavaScript linting.
 C. GitLens: Git integration.
 D. Python: Language support for Python.
 E. Bracket Pair Colorizer: Highlights matching brackets.

2. IntelliJ IDEA
A. CheckStyle-IDEA: Code linting.
B..ignore: Manage ignore files.
C. Lombok: Lombok support.
D. Rainbow Brackets: Highlights matching brackets.

3. Sublime Text
A. Package Control: Manage packages.
B. SublimeLinter: Linting framework.
C. Emmet: HTML and CSS shortcuts.
D. GitGutter: Git diff in the gutter.

4. Atom
A. Teletype: Real-time collaboration.
B. Linter: Base linter framework.
C. Minimap: Code overview.
D. Hydrogen: Run code interactively.


9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
ANSWER
Developer Environment Setup Documentation

Prepared by: [Blessing Agbo]
Date: [18 June 2024]
#Introduction
This document details the setup process for my developer environment, including configurations, customizations, and any troubleshooting encountered. The environment is primarily geared towards [describe your primary development focus, e.g., web development, data science, etc.].
#System Specifications
-Operating System: [Window 11 Pro Version 22H2]
-Processor: [Intel(R) Core(TM) i5-4300U CPU @ 1.90GHz   2.50 GHz]
-RAM: [8.00 GB ]
-Storage: [Local Disk(C:)-465GB]
#Development Tools
*Integrated Development Environment (IDE)*
-IDE: [Visual Studio Code]
-Version: [1.69.0 ]
-Plugins/Extensions: 
=Python (ms-python.python)
=Prettier - Code formatter (esbenp.prettier-vscode)
=Docker (vscode-docker)

*Version Control*
-Version Control System: [Git ]
-Client: GitHub Desktop 3.2.1
-Repositories:        
=Main Project Repository:
   *Name: MyProject
   *Location: https://github.com/username/MyProject
=Documentation Repository:
   *Name: MyProjectDocs
   *Location: https://github.com/username/MyProjectDocs
=Library Repository:
   *Name: MyLibrary
   *Location: https://github.com/username/MyLibrary

*Package Management*
-Package Manager: [pip ]
-Global Packages: [Pandas 1.5.0, Django 4.1.1]

*Virtualization/Containerization*
-Virtualization Tool: [VirtualBox ] 


*Languages and Frameworks*
-Primary Language: [Python ]
-Version: [3.12.4 ]
-Frameworks/Libraries: Web Development - Django 4.1.1


*Troubleshooting*
= Issues Encountered
1.Bootable USB Not Recognized
= Steps Taken to Resolve:
-Verified that the USB drive was correctly created by trying it on another computer.
-Reformatted the USB drive and recreated the bootable drive using a different tool.
-Used a different USB port on the computer.

2.Network Connectivity Problems Post-Installation
= Steps Taken to Resolve:
-Confirmed that the Wi-Fi adapter was recognized and working. 
-Restarted the network manager:

3.Conflicts between installed software packages prevented installation of necessary dependencies.
= Steps Taken to Resolve:
-Identified conflicting packages using the package manager logs.
-Removed conflicting packages:
-Cleared the package manager cache:
-Installed necessary dependencies:

4.Some Python packages failed to install due to missing dependencies.
= Steps Taken to Resolve:
-Installed system dependencies using the package manager:
-Used pip to install Python packages:

Conclusion
This setup documentation serves as a reference for maintaining and updating my development environment. It covers all necessary tools, configurations, troubleshooting and steps taken to resolve them.


Thank You.












