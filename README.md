[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15281974&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

Windows Update in Settings (recommended)
If you’re upgrading from Windows 10, we recommend you wait until you're notified through Windows Update that the upgrade is ready for your device. To check if Windows 11 is ready for your device, select Start  > Settings  > Update & Security  > Windows Update  > Check for updates.
![screenshot](<Screenshot (2908).png>)

Download and Install Windows 11: Step-by-Step Guide
Prerequisites
Ensure your computer meets the minimum system requirements for Windows 11.
Prepare a USB flash drive with at least 8GB of space (if creating a bootable installation media).
Secure a stable internet connection.
Backup your important files.
Step 1: Download Windows 11 Installation Media
Visit the Official Download Page:

Open your web browser and go to the Windows 11 download page(https://www.microsoft.com/software-download/windows11)
![screenshot](<Screenshot (2904).png>)

Download the Media Creation Tool:

Scroll down to the "Create Windows 11 Installation Media" section and click on Download now.
![screenshot](<Screenshot (2909).png>)

Step 2: Create Installation Media
Run the Media Creation Tool:

After downloading, run the Media Creation Tool. You might need to grant administrative permissions to proceed.

Accept License Terms:
Read and accept the license terms.

Choose Your Preferences:
Select your preferred language and edition (ensure they match the version you are licensed for).

Select Media Type:
Choose USB flash drive and click Next. Ensure your USB drive is connected to your computer.

Create Bootable USB Drive:
Select your USB drive from the list and click Next. The tool will download and copy the Windows 11 installation files to the USB drive.

Step 3: Install Windows 11
Boot from USB Drive:
Insert the bootable USB drive into the computer where you want to install Windows 11.
Restart the computer and enter the BIOS/UEFI settings (usually by pressing F2, F12, Delete, or Esc during startup).
Change the boot order to prioritize the USB drive and save the changes.

Start the Installation:
The computer will boot from the USB drive and display the Windows Setup screen.
Select your language, time, and keyboard preferences, then click Next.

Install Now:
Click Install now.

Enter Product Key:
Enter your Windows 11 product key or click I don’t have a product key to enter it later.

Accept License Terms:
Read and accept the license terms, then click Next.

Choose Installation Type:
Select Custom: Install Windows only (advanced) for a clean installation.

Select Partition:
Choose the partition where you want to install Windows 11. If necessary, delete existing partitions and create new ones. Be aware that this will erase all data on the selected drive.

Install Windows 11:
The setup process will begin copying files and installing Windows 11. This may take some time, and the computer may restart several times.

Step 4: Initial Setup and Configuration
Configure Windows:
After installation, Windows 11 will guide you through the initial setup process, including setting up your region, keyboard layout, and connecting to a network.

Sign In:
You will be prompted to sign in with a Microsoft account or create a local account.

Complete Setup:
Follow the remaining prompts to configure privacy settings, set up a PIN, and customize your Windows 11 experience.
By following these steps, you will have successfully installed Windows 11 on your computer

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
. Download Visual Studio Code
Visit the VS Code Download Page:
Open your web browser and go to the Visual Studio Code Download page.(https://code.visualstudio.com/Download)
![screenshot](<Screenshot (2874).png>)

Select the Windows Version:
Click on the Windows download link to download the installer.
![screenshot](<Screenshot (1951).png1.png>)

2. Install Visual Studio Code
Run the Installer:
Once the download is complete, run the installer by double-clicking the downloaded file (VSCodeSetup-x64-<version>.exe).
![screenshot](<Screenshot (2888)1.png>)

Accept the License Agreement:
Review and accept the license agreement. Click "Next".
![screenshot](<Screenshot (2893).png>)

Choose Installation Location:
Choose the installation location. The default location is usually fine. Click "Next".

Select Additional Tasks:
Choose any additional tasks you would like the installer to perform. It is recommended to create a desktop icon and add VS Code to the PATH. Click "Next".
![screenshot](<Screenshot (2894).png>)

Install VS Code:
Click "Install" to begin the installation process. This may take a few minutes.
![screenshot](<Screenshot (2895).png>)

Complete Installation:
Once the installation is complete, click "Finish" to close the installer. You can choose to launch VS Code immediately.

3. Initial Configuration
Launch Visual Studio Code:
Open VS Code from the Start menu or desktop icon.
Select a Theme:
Upon first launch, you may be prompted to select a theme. Choose your preferred theme.
![screenshot](<Screenshot (2934).png>)

Install Recommended Extensions:
VS Code may suggest some recommended extensions based on your detected programming languages. You can choose to install these extensions.
![alt text](<Screenshot (2933)-1.png>)

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

Step 1: Install Git
Download Git:

Go to the official Git website: Git Downloads.(https://git-scm.com/downloads)
Select your operating system (Windows, macOS, or Linux) and download the installer.
![screenshot](<Screenshot (2910).png>)

Install Git on Windows:
Run the downloaded installer.
Follow the installation wizard, choosing the default options unless you have specific preferences.
![screenshot](<Screenshot (2912).png>)

Step 2: Configure Git
Open Terminal (Command Prompt on Windows): and run the git bash as an administrator.
Run the following commands to set your username and email. These details will be associated with your commits.
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
![screenshot](<Screenshot (2914).png>)

Verify Configuration:
You can verify your configuration by running:
git config --list

Step 3: Create a GitHub Account
Sign Up for GitHub:
Go to the GitHub website and click Sign up.
Follow the prompts to create a new account.
![screenshot](<Screenshot (2915).png>)

![screenshot](<Screenshot (2916).png>)
![screenshot](<Screenshot (2917).png>)
Step 4: Initialize a Git Repository
Create a Project Folder:
Create a new folder for your project or navigate to your existing project folder.

Initialize Git Repository:
Open Terminal (or Command Prompt) and navigate to your project folder using cd command.
![screenshot](<Screenshot (2919).png>)

Run the following command to initialize a Git repository:
git init
![screenshot](<Screenshot (2918).png>)

Add Files to Repository:
Add your project files to the repository using:
git add .
![screenshot](<Screenshot (2920).png>)

Make First Commit:
Commit the files with a message:
git commit -m "Initial commit"

Step 5: Push to GitHub
Create a New Repository on GitHub:
Go to GitHub and click the + icon in the top right corner, then select New repository.
Fill in the repository name and description, and click Create repository.
![screenshot](<Screenshot (2921).png>)
![screenshot](<Screenshot (2922).png>)

Link Local Repository to GitHub:
Copy the repository URL from GitHub.
In your terminal, run:
git remote add origin https://github.com/your-username/your-repository.git

Push Local Changes to GitHub:
Push your changes to GitHub
git push -u origin master

- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
![screenshot](<Screenshot (2923).png>)


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
1. Download Python
Visit the Official Python Website:
Go to Python Downloads.(https://www.python.org/downloads/)
![screenshot](<Screenshot (2925).png>)

Download the Installer:
Click on the "Download Python [version]" button. This button will display the latest stable version of Python available.
![screenshot](<Screenshot (2926).png>)

2. Install Python
Run the Installer:
Open the downloaded installer file to start the Python installation process.
![screenshot](<Screenshot (2928).png>)

Add Python to PATH:
Ensure you check the box that says "Add Python to PATH". This makes it easier to run Python from the command line.

Choose Installation Type:
You can choose "Install Now" for the default installation or "Customize Installation" if you need specific options.

Install:
Click "Install" to start the installation process. You may need to approve any prompts for administrator permissions.

Complete Installation:
Once the installation is complete, you should see a success message. Click "Close" to finish

Verify Python Installation
Open Command Prompt or Terminal:
Open your command line interface (Command Prompt on Windows, Terminal on macOS/Linux).
Check Python Version:
Run the following command to check that Python is installed correctly
python --version
![screenshot](<Screenshot (2930).png>)

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   Check pip Version:
Run the following command to check if pip is already installed:
pip --version
If pip is installed, you should see output showing the version of pip and the Python version it is associated with. For example:
pip 21.0.1 from /usr/local/lib/python3.9/site-packages/pip (python 3.9)
![screenshot](<Screenshot (2932).png>)

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
Step-by-Step Instructions
1. Download MySQL Installer
Visit the MySQL Download Page:
Open your web browser and go to the MySQL Installer for Windows(https://dev.mysql.com/downloads/windows/installer/5.7.html) download page.
![screenshot](<Screenshot (2935).png>)
In this example, we selected the Full MySQL Package (B).
![screenshot](<Screenshot (2936).png>)

After selecting a version, you are provided with the option of signing up for a MySQL Community account. If you are not interested, select the No thanks, just start my download option at the bottom of the page.
![screenshot](<Screenshot (2937).png>)
By selecting this option, the download process starts immediately. Once the download is complete, you can execute the MySQL Installer file from the download folder.
![screenshot](<Screenshot (2888)2.png>)

After accepting the Oracle license agreement terms, the first screen you encounter allows you to define which MySQL products are going to be installed. You can choose between several predefined options or create your custom setup type.
Developer Default --installs all the tools you need to develop and micromanage your MySQL databases effectively.
Server Only-- is used to install an instance of the MySQL Server and forgo other MySQL products.
Client Only-- installs all products except the MySQL Server and associated tools.
The Full --configuration installs all available MySQL products.

A Custom setup allows you to select the individual elements that are to be installed and alter predefined default settings.

In the example below, we select the Server Only option and click Next.
![screenshot](<Screenshot (2938).png>)

At this point, the system tries to resolve possible inconsistencies. It might inform you that additional packages need to be installed for the process to continue (e.g., Microsoft Visual C++ 2019 Redistributable Package)
Luckily the MySQL Installer auto-resolves issues and installs the latest binary compatible version of missing software. You are now ready to start the installation process in earnest. Click Execute to begin the installation process.
![screenshot](<Screenshot (2939).png>)

Once the status of the installation status is labeled as Complete, you are ready to configure the MySQL database.
The MySQL Server 8.0.19 is now ready to be configured. Initiate the process by clicking Next.
![screenshot](<Screenshot (2940).png>)

The first configuration option affects database availability. It allows you to decide if you want to set up a Standalone MySQL Server or an InnoDB server cluster to improve availability. In this instance, we selected the classic, single server option.
![screenshot](<Screenshot (2941).png>)

The Type and Networking section is used to define several essential features.

The Config Type option lets you choose between three server configuration types. Development Computer, Server Computer, and Dedicated Computer define whether the server is dedicated solely to running your MySQL database or is going to share the underlying system with other applications.
In this example, we decided to create a dedicated MySQL server.
![screenshot](<Screenshot (2942).png>)

The Type and Networking tab can also define the port the MySQL server is listening on. The default setting is port number 3306 and can be changed to suit your needs.

By checking the Show Advanced and Logging Option box, you can set additional logging options at a later stage.
Click Next once you’ve selected the options you feel meet your requirements.
![screenshot](<Screenshot (2943).png>)

It is possible to choose between two authentication methods, the recommended Strong Password Encryption, and the Legacy Authentication Method. Select the recommended Use Strong Password Authentication option.
![screenshot](<Screenshot (2945).png>)

You are now prompted to enter a password for your MySQL root user. You can also create additional roles for various users and purposes.
This is only an initial setup, and credentials can be edited once the installation is complete.
![screenshot](<Screenshot (2946).png>)

By defining MySQL as a Windows Service, it can now start automatically whenever the Windows system boots.
If you decide to start MySQL as an executable application, you would need to configure it manually.
![screenshot](<Screenshot (2947).png>)

If you have selected the Show Advanced Logging option in the Type and Networking tab, you are now able to set up MySQL log preferences.
Logging options let you select the types of logs you want to activate and define the log directories.
![screenshot](<Screenshot (2948).png>)

Click Next to reach the Advanced Options section.
Advanced Options include setting a unique server identifier, and the type of case (Lower/Upper) to be used for Table Names.
These settings are only available if you have checked the Show Advanced Options box in the Type and Networking tab.

Apply Configuration
You have successfully configured the MySQL server and need to confirm for the MySQL Installer to apply the configuration.
An overview of the configurations steps appears on the screen. Click Execute to apply the configuration.
![screenshot](<Screenshot (2949).png>)

The system informs once the configuration process is completed. Select Next to continue the installation process.
![screenshot](<Screenshot (2950).png>)

Complete MySQL Installation on Windows Server
After clicking Next, you are given the option to copy the installation process log to the Windows Clipboard.
![screenshot](<Screenshot (2951).png>)

Click Finish to complete the MySQL server installation on Windows.

Start MySQL Server on Windows
If you need to start the MySQL Server on Windows for the first time enter the following command in the Windows Command Prompt:
"C:\Program Files\MySQL\MySQL Server 8.0\bin\mysqld" --console

The path in this command is the default installation folder. In case you have installed MySQL in a different folder, the command needs to reflect that to launch the mysqld executable file successfully.

The --console option displays output directly on your console. Omitting this option sends the output directly to the MySQL logs.

Stop MySQL Server on Windows
To shut down MySQL Server in Windows, type the following command in the Windows Command Prompt:
"C:\Program Files\MySQL\MySQL Server 8.0\bin\mysqladmin" -u root shutdown
The mysqladmin tool performs the shutdown command and fully stops the MySQL server. The system does not provide output as confirmation.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
Step-by-Step Instructions
1. Open the Extensions View
Launch VS Code:
Open Visual Studio Code on your machine.
Open Extensions View:
Click on the Extensions icon in the Activity Bar on the side of the window. Alternatively, you can use the keyboard shortcut Ctrl+Shift+X (Windows/Linux) or Cmd+Shift+X (macOS).
![screenshot](<Screenshot (2933).png>)
9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 


Key References:
How to install Windows 11 safely? – guide by Linus Tech & Acronis. (2023, August 25). [Video]. Acronis. https://www.acronis.com/en-gb/blog/posts/steps-before-installing-windows-11/

Ways to install Windows 11 - Microsoft Support. (n.d.-b). https://support.microsoft.com/en-us/windows/ways-to-install-windows-11-e0edbbfb-cfc5-4011-868b-2ce77ac7c70e

https://git-scm.com/downloads

https://github.com/

https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup

https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-new-repository

https://www.python.org/downloads/

https://pip.pypa.io/en/stable/installing/

https://pip.pypa.io/en/stable/user_guide/

https://bootstrap.pypa.io/get-pip.py

https://code.visualstudio.com/docs/editor/extension-gallery

https://code.visualstudio.com/docs/editor/extension-marketplace

https://marketplace.visualstudio.com/vscode

https://dev.mysql.com/doc/workbench/en/

https://dev.mysql.com/doc/refman/5.7/en/windows-installation.html

https://dev.mysql.com/downloads/installer/

https://code.visualstudio.com/docs/setup/setup-overview

https://code.visualstudio.com/docs/python/python-tutorial

https://phoenixnap.com/kb/install-mysql-on-windows

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.
MySQL Installation

Challenges:
Dependency Issues: Missing prerequisites stopped the installation.
Complex Configuration: Setting root passwords and network settings was confusing.
MySQL 8.0 Command Line client setup- configuring Mysql was challenging as it required me to add path of Mysql into my local machine and then enter the password to prompt the Mysql platform

Strategies:
Install Dependencies: Following prompts carefully to ensure all prerequisites are installed.
Guided Steps: Using MySQL’s step-by-step installer to avoid errors.
Run as Administrator: Executing the installer with administrative privileges to fix permission issues.

Git Setup
Challenges:
SSH Key Configuration: Setting up SSH keys can be complex.
Repository Initialization: Initializing and configuring a Git repository was confusing to me.
Commit Management: Understanding Git workflows like branching and merging were a bit  challenging.

Strategies:
Use Tutorials: Following detailed guides for SSH key setup and Git configurations.
GUI Tools: Using tools like GitHub Desktop to simplify operations.
Practice: Regularly using Git commands and referring to documentation for complex tasks.


#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
