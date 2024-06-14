[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15278095&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   Download Windows 11
Check System Requirements: Ensure your PC meets the minimum system requirements for Windows 11.
Backup Your Data: It's always a good idea to back up your important files before upgrading.
Download the Windows 11 Installation Media:
Download the Windows 11 Installation Assistant or create a bootable USB using the Media Creation Tool.
Create a Bootable USB Drive
Insert a USB Flash Drive: Ensure it has at least 8GB of free space.
Run the Media Creation Tool:
Choose "Create installation media USB flash for another PC".
Select the language, edition, and architecture (64-bit).
Choose "USB flash drive" and select your USB drive from the list.
Follow the prompts to create the bootable USB drive.
Install Windows 11
Prepare Your PC:

Connect the bootable USB drive to your PC.
Restart your PC and enter the BIOS/UEFI settings (usually by pressing F2, F12, DEL, or ESC during startup).
Change the boot order to boot from the USB drive.
Begin Installation:

Save and exit the BIOS/UEFI settings. Your PC will restart and boot from the USB drive.
Follow the on-screen prompts to start the Windows 11 installation.
Select your language, time, and keyboard preferences, then click "Next".
Click "Install Now".
Enter your product key or choose "I don't have a product key" if you're doing a clean installation or upgrading from a genuine copy of Windows 10.
Accept the license terms and click "Next".
Choose Installation Type:

Select "Custom: Install Windows only (advanced)" for a clean installation, or "Upgrade: Install Windows and keep files, settings, and applications" if upgrading.
Select the Partition:

Choose the partition where you want to install Windows 11. If you're doing a clean install, you may need to delete the existing partitions and create a new one.
Click "Next" to start the installation. Your PC will restart several times during this process.
Set Up Windows 11:

After installation, follow the on-screen instructions to personalize your settings.
Sign in with your Microsoft account or create a new account.
Set up a PIN if prompted.
Configure your privacy settings and preferences.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download


To download Visual Studio Code:

Visit the Visual Studio Code website:

Go to code.visualstudio.com.
Download the installer:

Click on the "Download" button for your operating system (Windows, macOS, or Linux).
Run the installer:

Once the download is complete, open the installer file and follow the installation instructions specific to your operating system.
Launch Visual Studio Code:

After installation, open Visual Studio Code from your applications or start menu.

Go to environment variables,then go to path and copy the location of the visual studio


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   a). Install Git
Windows
Download Git:

Go to the Git for Windows download page.
Click on "Download" to get the latest version.
Install Git:

Run the downloaded installer and follow the setup instructions.
Use the default settings unless you have specific preferences.

  b).Configure Git
  Open CMD and configure Git using username and email for example git config --global user.name "Xavier" git config --global user.email "noreply@gmail.com"

  c). Create a GitHub account
  Sign up for GitHub:
Go to github.com.
Click on "Sign up" and follow the instructions to create a new account.

  d).Initialize Git repository
  open cmd and run  "mkdir my-plpproject" "cd my-plpproject" "git init"

  e). Commit
  "git commit -m "initial commit"

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  Download and Install Python;
Visit the Python website:

Go to the official Python download page.
Download the installer:

Click on the "Download Python 3.x.x" button to download the latest version of Python.
Run the installer:

Open the downloaded installer.
Check the box that says "Add Python to PATH".
Click "Install Now".

Then copy the path of downloaded python . 
Open edit system environment variables and copy the path of python on the path prtion in the environment variables.

Then confirm python by running "python --version" on command prompt.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).


   Install pip
Download get-pip.py:

Go to the get-pip.py script page.
Right-click on the page and select "Save as..." to download the get-pip.py file.
Run get-pip.py:

Open Command Prompt and navigate to the directory where you downloaded get-pip.py. For example:

cd Downloads

Run the script by typing:
python get-pip.py

Verify pip Installation
Check pip version again:
Type the following command and press Enter:
pip --version
You should now see the pip version number, confirming the installation

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

Download MySQL Installer
Visit the MySQL website:

Go to the MySQL Downloads page.
Download the MySQL Installer:

Click on "Download" under "MySQL Installer for Windows".
Choose the "Windows (x86, 32-bit), MSI Installer" if you're unsure which version to get.
Select the "No thanks, just start my download" link to start downloading the installer.
Install MySQL
Run the MySQL Installer:

Locate the downloaded MSI file and double-click it to run the installer.
Select Setup Type:

Choose the setup type that suits your needs. For most users, the "Developer Default" is recommended. Click "Next".
Check Requirements:

The installer will check for requirements. If any are missing, the installer will prompt you to install them. Click "Execute" to install the required components. Click "Next" when done.
Choose Products and Features:

The default selection should be fine. Click "Next".
Installation:

Click "Execute" to start the installation of MySQL products. Once complete, click "Next".
Apply Configuration:

The installer will guide you through the configuration steps:
High Availability: Select "Standalone MySQL Server / Classic MySQL Replication".
Type and Networking: Choose "Development Computer" for Config Type, and ensure "TCP/IP" is checked with default port 3306. Click "Next".
Authentication Method: Choose "Use Strong Password Encryption" unless you have specific needs. Click "Next".
Accounts and Roles: Set a root password and optionally create a user. Click "Next".
Windows Service: Check "Configure MySQL Server as a Windows Service", and leave the default settings. Click "Next".
Apply Configuration: Click "Execute" to apply the configuration.
Complete Installation:

Click "Finish" once the installation is complete.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   Open Visual Studio Code:

Launch Visual Studio Code from your Start menu or desktop shortcut.
Open Extensions View:

Press Ctrl+Shift+X on your keyboard or click on the Extensions icon in the Activity Bar on the side of the window.
Search for the Extension:

In the Extensions view search box, type Python Extension Pack.
Install the Extension Pack:

Find the "Python Extension Pack" in the search results.
Click the Install button next to the extension pack name.
Reload/Restart Visual Studio Code (if prompted):

Some extensions may require you to reload or restart VS Code. Follow any on-screen instructions to complete the installation.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

    My GitHub repository:
    https://paw0rd.github.io/inifinteuni/
    This project was build on vs code using html and css.
    I then pushed it to Github using git committ
    I used extensions like intellicode, HTML CSS supporter and Live server

    Challenges faced:

   Anti-virus warning when trying to install some softwares from unknown authors
   This is solved by giving permission to the softwares

   Installing some softwares when you already have one in the pc poses a challenge
   This is solved by unistalling or updating the previous versions

   Compatibility is a serious issue
   This is solved by downloading softwares that meet the required standard of your pc


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
