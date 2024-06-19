[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15301982&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11




Step 1: Check System Requirements
Before you begin, ensure your computer meets the minimum system requirements for Windows 11. You can find these requirements on the official Microsoft page or use the PC Health Check tool provided by Microsoft.

Step 2: Download Windows 11 Installation Media
Visit the Official Microsoft Windows 11 Download Page:

Open your web browser and go to Microsoft's Windows 11 download page.
Select the Installation Method:

On the download page, you have a few options:
Windows 11 Installation Assistant: This tool helps you upgrade from Windows 10 to Windows 11.
Create Windows 11 Installation Media: This option allows you to create a bootable USB drive or DVD to install Windows 11.
Download Windows 11 Disk Image (ISO): This option allows you to download an ISO file to create installation media manually.
Step 3: Create a Bootable USB Drive
Using the Media Creation Tool:

If you choose the "Create Windows 11 Installation Media" option, click on "Download now" under that section to download the Media Creation Tool.
Run the Media Creation Tool and follow the prompts to create a bootable USB drive. You'll need a USB flash drive with at least 8 GB of space.
Using the ISO File:

If you download the ISO file, you can use software like Rufus to create a bootable USB drive.
Download and install Rufus from here.
Open Rufus, select the downloaded ISO file, and create the bootable USB drive.
Step 4: Install Windows 11
Boot from the USB Drive:

Insert the bootable USB drive into your computer.
Restart your computer and enter the BIOS/UEFI settings (usually by pressing a key like F2, F12, Delete, or Esc during startup).
Change the boot order to boot from the USB drive first. Save the changes and exit the BIOS/UEFI settings.
Follow the Installation Prompts:

The Windows 11 installation process will begin.
Select your language, time, and keyboard preferences, and click "Next."
Click "Install now."
Enter your Windows 11 product key if prompted. If you don't have one, you can select "I don't have a product key" to continue.
Accept the license terms and click "Next."
Choose the type of installation you want (Upgrade or Custom). For a clean install, select "Custom."
Select the drive/partition where you want to install Windows 11 and click "Next."
Complete the Installation:

Windows 11 will start copying files and installing.
Your computer will restart several times during the process.
Follow the on-screen instructions to set up Windows 11, including creating or signing in with a Microsoft account, configuring privacy settings, and customizing your system.
Step 5: Post-Installation Setup
Install Drivers and Updates:

After installation, make sure to install any necessary drivers for your hardware.
Check for Windows updates by going to Settings > Windows Update and installing any available updates.
Install Applications:

Reinstall your applications and transfer your files if you performed a clean install.



2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download


   Step 1: Download Visual Studio Code
Visit the Official VS Code Download Page:

Open your web browser and go to Visual Studio Code Download Page.
Select Your Operating System:

Click on the Windows download button to download the installer for Windows.
Step 2: Install Visual Studio Code on Windows
Run the Installer:

Once the download is complete, locate the installer file (VSCodeUserSetup-<version>.exe) in your Downloads folder and double-click it to start the installation process.
Follow the Installation Prompts:

The Visual Studio Code Setup Wizard will open. Click Next to proceed.
Read and accept the license agreement, then click Next.
Choose the installation location (the default location is usually fine), then click Next.
Select additional tasks you want to perform, such as:
Creating a desktop icon.
Adding "Open with Code" action to Windows Explorer file context menu.
Adding "Open with Code" action to Windows Explorer directory context menu.
Registering Code as an editor for supported file types.
Adding to PATH (useful for command-line operations).
Click Next and then Install to begin the installation.
Complete the Installation:

Once the installation is complete, click Finish. You can choose to launch Visual Studio Code immediately by checking the box.
Step 3: Launch and Configure Visual Studio Code
Open Visual Studio Code:

If you didn’t launch VS Code immediately after installation, you can open it by finding the shortcut on your desktop or by searching for "Visual Studio Code" in the Start menu.
Install Extensions:

To enhance your development experience, install extensions for the programming languages you use.
Click on the Extensions icon in the Activity Bar on the side of the window or press Ctrl+Shift+X.
Search for and install the extensions you need (e.g., Python, JavaScript, C++, etc.).
Configure Settings:

Customize your VS Code settings by clicking on the gear icon in the lower-left corner and selecting Settings.
You can modify settings like themes, keybindings, and editor preferences.
Step 4: Start Coding
Create or Open a Project:

You can create a new project or open an existing one by selecting File > Open Folder and navigating to your project directory.
Begin Development:

Start writing and running your code using the powerful features of Visual Studio Code, such as IntelliSense, debugging, and integrated terminal.


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com


To install Git, configure it, create a GitHub account, initialize a Git repository, and make your first commit, follow these steps:

Step 1: Install Git
Visit the Official Git Website:

Go to the Git download page.
Download the Installer:

Click on the Windows download button to download the Git installer.
Run the Installer:

Once the download is complete, locate the installer file (Git-<version>-64-bit.exe) in your Downloads folder and double-click it to start the installation process.
Follow the installation prompts. The default settings are usually fine for most users.
Step 2: Configure Git
Open Git Bash:

After installation, open Git Bash (search for it in the Start menu).
Set Your Username and Email:

Run the following commands to set your Git username and email (replace "Your Name" and "your.email@example.com" with your actual name and email):

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Step 3: Create a GitHub Account
Visit GitHub:

Go to GitHub.
Sign Up for a New Account:

Click on Sign up and follow the instructions to create a new GitHub account.
Step 4: Initialize a Git Repository
Create a New Project Directory:

Open Git Bash and navigate to the directory where you want to create your project. For example:
cd /d/DjangoMayProject/mayplpdjango
Initialize a Git Repository:

Run the following command to initialize a new Git repository in your project directory:

git init
Step 5: Make Your First Commit
Create a README File:

Create a README.md file (you can use VS Code or any text editor):

echo "# My Project" > README.md
Add Files to the Staging Area:

Add the README.md file to the staging area:

git add README.md
Commit the Files:

Make your first commit:

git commit -m "Initial commit"
Step 6: Push Your Repository to GitHub
Create a New Repository on GitHub:

Go to your GitHub account, click on the + icon in the top right corner, and select New repository.
Give your repository a name, description (optional), and set the visibility (public or private). Click Create repository.
Add the Remote Repository URL:

Copy the repository URL from GitHub. In Git Bash, run the following command to add the remote repository (replace <repository-url> with the actual URL):

git remote add origin <repository-url>
Push Your Local Repository to GitHub:

Push your local commits to the remote repository:
git push -u origin master


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.



Step 1: Download and Install Python
Visit the Official Python Website:

Go to the Python download page.
Download the Installer:

Click on the Download Python button. This will download the latest version of Python.
Run the Installer:

Once the download is complete, locate the installer file (e.g., python-312.0.1-amd64.exe) in your Downloads folder and double-click it to start the installation process.
Make sure to check the box that says Add Python 3.0 to PATH at the bottom of the installer window.
Click on Install Now to proceed with the installation using default settings.
Step 2: Verify Python Installation
Open Command Prompt:

Press Win + R, type cmd, and press Enter to open Command Prompt.
Check Python Version:

In the Command Prompt, type the following command and press Enter:

python --version
You should see the version of Python you installed (e.g., Python 312.0).

Step 3: Install Required Python Packages
Install pip:

Pip is the package installer for Python. It should be installed automatically with Python. Verify pip installation by running:

pip --version
Install Packages:

Use pip to install any necessary packages for your project. For example, to install Django, run:

pip install django
Step 4: Install Additional Compilers, Interpreters, or Runtimes (if needed)
Check Project Requirements:

Review your project’s documentation or requirements file to identify any additional compilers, interpreters, or runtimes you need.
Install Additional Tools:

For example, if you need a specific compiler like GCC for C/C++ extensions, you can install MinGW (Minimalist GNU for Windows):

Download MinGW from MinGW download page.
Run the installer and follow the instructions to install MinGW.
Set Up Environment Variables (if needed):

If you install additional tools, you may need to add their paths to the system environment variables.
Step 5: Set Up a Virtual Environment (Optional)
Create a Virtual Environment:

Navigate to your project directory and run the following command to create a virtual environment:

python -m venv venv
Activate the Virtual Environment:

On Windows, activate the virtual environment with:

venv\Scripts\activate

Install Packages in the Virtual Environment:

With the virtual environment activated, use pip to install any required packages. For example:

pip install django
Step 6: Verify Installation of Tools
Test Your Installation:

Create a simple Python script to ensure that everything is working correctly. For example, create a file named test.py with the following content:

python
print("Hello, World!")
Run the Script:

In Command Prompt, navigate to the directory where test.py is located and run:

python test.py
You should see the output: Hello, World!


5. Install Package Managers:
   If applicable, install package managers like pip (Python).


Install Python Packages Using Pip
You can now use pip to install any Python package. For example, to install Django, run:

pip install django
 Verify Package Installation
After installing a package, you can verify its installation by running:

pip show django
This command will display information about the Django package, confirming that it has been installed.

 Use a Virtual Environment (Recommended)
Using virtual environments helps to manage dependencies for different projects separately.

Create a Virtual Environment:

Navigate to your project directory and run:

python -m venv myenv

Activate the Virtual Environment:

On Windows, activate the virtual environment with:
myenv\Scripts\activate
Install Packages in the Virtual Environment:

With the virtual environment activated, use pip to install packages. For example:

pip install django
Deactivate the Virtual Environment:

When you’re done working in the virtual environment, deactivate it by running:

deactivate


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html


Step 1: Download MySQL Installer
Visit the MySQL Downloads Page:

Go to the MySQL download page: MySQL Installer for Windows.
Select the Installer:

Click on the Download button for the "MySQL Installer 5.7 for Windows".
You can choose between the "Web Community" installer, which is smaller and downloads the required components during the installation process, or the "Offline" installer, which includes all components in a single package.
Step 2: Run the MySQL Installer
Launch the Installer:

Once the download is complete, run the installer file (mysql-installer-community-5.7.x.x.msi).
Choose Setup Type:

Select a setup type that best matches your needs. The options typically include:
Developer Default: Installs MySQL Server and other MySQL tools required for development.
Server only: Installs only the MySQL Server.
Client only: Installs only the MySQL client applications.
Full: Installs all MySQL products and features.
Custom: Allows you to choose specific products and features to install.
For most users, the Developer Default is the recommended option.

Step 3: Install MySQL Components
Download and Install:

The installer will check for prerequisites and download the required MySQL products. Ensure you have an internet connection for this step if you are using the "Web Community" installer.
Apply Configuration:

Once the products are installed, the installer will guide you through the configuration steps:
High Availability: Choose the stand-alone MySQL server option unless you need a more complex setup.
Type and Networking: Set the Config Type to Development Machine. Ensure the port number (default is 3306) is not blocked by your firewall.
Authentication Method: Choose the appropriate authentication method. The recommended option is the strong password encryption method.
Accounts and Roles: Set the root password and create additional user accounts if necessary.
Windows Service: Configure MySQL to run as a Windows service and choose a standard or custom name for the service.
Step 4: Complete Installation
Start MySQL Server:

The installer will start the MySQL server as part of the installation process.
Finish Setup:

Click Finish to complete the installation. Optionally, you can run MySQL Workbench or other installed MySQL tools to verify the installation.
Step 5: Verify Installation
Open Command Prompt:

Open a new Command Prompt window.
Connect to MySQL Server:

Connect to the MySQL server by typing the following command and entering the root password when prompted:

mysql -u root -p
Verify the MySQL Version:

Once connected, verify the installation by checking the MySQL version:

SELECT VERSION();


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.


   Visual Studio IntelliCode:

Uses AI to provide intelligent suggestions based on your code context.
Visual Studio IntelliCode
Settings Sync:

Syncs your VS Code settings, extensions, and configurations across multiple machines.
Settings Sync
Python:

Adds syntax highlighting, IntelliSense, linting, debugging, and more for Python development.
Python
GitHub Pull Requests and Issues:

Manage pull requests, issues, and code reviews directly from VS Code.
GitHub Pull Requests and Issues
Code Formatting:
Prettier - Code formatter:

Code formatter for JavaScript, TypeScript, CSS, JSON, and more.
Prettier - Code formatter
Python Docstring Generator:

Automatically generates Python docstrings.
Python Docstring Generator
Additional Tools:
Docker:

Adds syntax highlighting, commands, and IntelliSense for Dockerfiles.
Docker
Remote - SSH:

Open any folder on a remote machine using SSH and edit with VS Code.
Remote - SSH
Installation:
To install these extensions:

Open Visual Studio Code.
Go to the Extensions view by clicking on the square icon on the sidebar or pressing Ctrl+Shift+X.
Search for the extension by name.
Click Install to install the extension.



9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 


    Comprehensive Guide to Setting Up Your Developer Environment
This document outlines the steps taken to set up a developer environment, including configurations, customizations, and troubleshooting steps encountered during the process.

Table of Contents
Operating System Installation
Text Editor/IDE Installation
Git Installation and Configuration
Python Installation
MySQL Installation
Extensions and Plugins for Visual Studio Code
Common Issues and Troubleshooting
Operating System Installation
Step 1: Choose and Install Windows 11

Visit the Windows 11 download page.
Download the Windows 11 installation media.
Create a bootable USB drive using the downloaded media.
Boot from the USB drive and follow the on-screen instructions to install Windows 11.
Customizations:

Set up system preferences such as language, region, and privacy settings.
Install necessary drivers for your hardware components.
Text Editor/IDE Installation
Step 2: Download and Install Visual Studio Code

Visit the Visual Studio Code download page.
Download the installer for Windows and run it.
Follow the installation prompts to complete the installation.
Configurations:

Set up user settings by opening VS Code and navigating to File > Preferences > Settings.
Customize themes and layout according to your preferences.
Git Installation and Configuration
Step 3: Install Git

Visit the Git download page.
Download the installer for Windows and run it.
Follow the installation prompts, ensuring you select the options to enable Git from the command line.
Configuration:

Open Git Bash and set up your Git configuration:

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

Step 4: Create a GitHub Account

Visit GitHub and create a new account.


Step 5: Initialize a Git Repository

Navigate to your project directory and initialize a Git repository:
git init
git add .
git commit -m "Initial commit"
Python Installation
Step 6: Install Python

Visit the Python download page.
Download the latest version of Python and run the installer.
Ensure you check the option to add Python to your PATH during installation.
Step 7: Install pip

pip is included with Python, but you can ensure it's up to date by running:

python -m pip install --upgrade pip
MySQL Installation
Step 8: Install MySQL

Visit the MySQL Installer download page.
Download the installer and run it.
Follow the installation prompts to install the MySQL server and other necessary components.
Configuration:

Configure MySQL server settings such as root password, port number, and server configuration.
Ensure MySQL service is running.
Extensions and Plugins for Visual Studio Code
Step 9: Install Extensions

Open Visual Studio Code.

Go to the Extensions view by clicking on the square icon on the sidebar or pressing Ctrl+Shift+X.

Search for and install the following recommended extensions:

Visual Studio IntelliCode: AI-assisted code recommendations.
Settings Sync: Sync VS Code settings across machines.
Bracket Pair Colorizer 2: Color matches brackets.
Python: Python language support.
JavaScript (ES6) code snippets: ES6 syntax support.
ESLint: Integrates ESLint JavaScript linter.
Pylint: Python code analysis.
GitLens: Enhances Git capabilities.
GitHub Pull Requests and Issues: Manage GitHub PRs and issues.
Prettier - Code formatter: Code formatting for multiple languages.
Python Docstring Generator: Auto-generate Python docstrings.
Docker: Docker support.
Remote - SSH: Remote development via SSH.
Customization:

Customize each extension’s settings via the Extensions panel.
Common Issues and Troubleshooting
Issue 1: ImportError: cannot import name 'path' from 'django'

Solution: Ensure you are using the correct import statement in your Django project:
python

from django.urls import path
Issue 2: The included URLconf does not appear to have any patterns in it

Solution: Check your urls.py file to ensure urlpatterns is correctly defined:
python
from django.urls import path
from . import views

urlpatterns = [
    path('', views.index, name='index'),
]
Issue 3: MySQL service not starting

Solution: Verify MySQL service configuration, ensure no port conflicts, and check the MySQL error log for details.


#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
