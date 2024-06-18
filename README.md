[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15233698&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
      Step 1: Backup Your Data
      Before installing Windows 11, it's crucial to back up all your important data to avoid any loss. You can use an external drive or a cloud storage service.

      Step 2: Create a Bootable USB Drive
      Download the Windows 11 ISO File:
      Go to the Microsoft website and download the Windows 11 ISO file.
      Create a Bootable USB Drive:
      Use a tool like Rufus to create a bootable USB drive.
      Insert a USB drive with at least 8 GB capacity.
      Open Rufus, select the USB drive, choose the downloaded ISO file, and start the process.
      Step 3: Install Windows 11
      Insert the Bootable USB Drive:
      Plug the USB drive into the PC where you want to install Windows 11.
      Boot from USB Drive:
      Restart the PC and enter the BIOS/UEFI settings. This is usually done by pressing a key like F2, F12, Delete, or Esc immediately after turning on your PC.
      Change the boot order to boot from the USB drive first.
      Save and exit the BIOS/UEFI settings.
      Start the Installation:
      The PC will boot from the USB drive and display the Windows Setup screen.
      Select your language, time, and keyboard preferences, then click "Next".
      Click "Install now".
      Enter the Product Key:
      Enter your Windows 11 product key if prompted, or click "I don't have a product key" to enter it later.
      Select the Installation Type:
      Choose "Custom: Install Windows only (advanced)".
      Select the partition where you want to install Windows 11. If you have a previous version of Windows, you might want to delete existing partitions and create a new one.
      Complete the Installation:
      The installation process will start, and your PC will restart several times.
      Follow the on-screen instructions to set up your region, keyboard layout, and account.
      Step 4: Post-Installation Setup
      Install Drivers and Updates:
      Once Windows 11 is installed, connect to the internet and download the latest updates and drivers. This can usually be done via Windows Update.
      Restore Your Data:
      Restore your backed-up data to the PC.
      Install Necessary Software:
      Reinstall your preferred applications and settings.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
      Step 1: Download Visual Studio Code
      - Open Your Web Browser:
      Launch your preferred web browser (e.g., Edge, Chrome, Firefox).
      Go to the Visual Studio Code Website:
      Visit the official Visual Studio Code download page at https://code.visualstudio.com/.
      - Download the Installer:
      Click the "Download for Windows" button. This will download the installer for the stable build of Visual Studio Code.
      Step 2: Install Visual Studio Code
      - Run the Installer:
      Once the download is complete, open the downloaded file (VSCodeSetup.exe).
      - Accept the License Agreement:
      In the setup wizard, read and accept the license agreement by checking the box and clicking "Next".
      - Choose the Installation Location:
      Select the destination folder for Visual Studio Code. The default location is usually fine, so click "Next".
      - Select Additional Tasks:
      You can select additional tasks such as:
      Creating a desktop icon.
      Adding "Open with Code" actions to the Windows Explorer file context menu.
      Adding "Open with Code" actions to the Windows Explorer directory context menu.
      Registering VS Code as the default editor for supported file types.
      Choose your preferred options and click "Next".
      - Install:
      Click the "Install" button to begin the installation process.
      - Complete the Installation:
      Once the installation is complete, you can choose to launch Visual Studio Code immediately by checking the box and clicking "Finish".
      Step 3: First Launch and Setup
      - Launch Visual Studio Code:
      If you didn't select the option to launch VS Code immediately after installation, you can open it by finding "Visual Studio Code" in the Start menu or by using the desktop shortcut if you created one.
      - Initial Setup:
      Upon first launch, you might see a welcome screen. You can explore the welcome guide, which provides helpful tips on getting started with VS Code.
      Step 4: Install Extensions (Optional but Recommended)
      - Open Extensions View:
      Click on the Extensions icon on the Activity Bar on the side of the window or press Ctrl+Shift+X.
      - Browse and Install Extensions:
      Search for popular extensions such as:
      Python
      Prettier - Code formatter
      Live Server
      GitLens
      Click the "Install" button for any extension you want to add to VS Code.
      Step 5: Configure Settings (Optional)
      - Open Settings:
      Go to File > Preferences > Settings or press Ctrl+,.
      - Adjust Settings:
      Customize various settings such as theme, font size, editor settings, and more according to your preferences.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

      a. Installing Git:
      Head to the official Git downloads page: Search for "Git SCM Downloads".
      - Download the installer: Choose the appropriate version (32-bit or 64-bit) for your system.
      - Run the installer: Follow the on-screen instructions. During installation, it's recommended to:
      Select "Use Git Bash as my default shell" (for Windows) to easily access Git commands.
      Choose your preferred text editor (optional).
      b. Configuring Git:
      Open a terminal window (Command Prompt on Windows, Terminal on Mac/Linux).
      - Verify Git installation: Type git --version and press Enter. It should display the installed Git version.
      - Set up your user name: Run the command: git config --global user.name "<Your Name>" (replace <Your Name> with your actual name).
      - Set up your email: Run the command: git config --global user.email "<your_email@example.com>" (replace with your email address).
      c. Creating a GitHub Account:
      Go to https://github.com/ and sign up for a free account.
      - Initializing a Git Repository and Making your First Commit:
      Open your terminal and navigate to your project directory. Use the cd command to change directories.
      - Initialize a Git repository: Run the command git init. This creates a hidden folder named .git in your project directory, which stores Git metadata.
      Create a file (if you don't have one already). This could be a text file, code file, etc.
      - Stage the file for commit: Use the command git add <filename>, replacing <filename> with the actual name of your file.
      Commit your changes: Run the command git commit -m "<commit message>". Replace <commit message> with a descriptive message about your changes.

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
      Step 1: Download Python Installer
      Open your web browser and go to the official Python website: python.org.
      Navigate to the Downloads section.
      Click on the Download Python 3.x.x button (the latest version will be displayed).
      Step 2: Run the Python Installer
      Locate the downloaded installer (typically in the Downloads folder).
      Double-click the installer to run it.
      Step 3: Customize the Installation
      Check the box that says "Add Python 3.x to PATH" at the bottom of the installer window. This is important as it adds Python to your system environment variables, allowing you to run Python from the command line.
      Click on "Customize installation" (optional but recommended for more control over the installation process).
      Step 4: Select Optional Features
      In the Optional Features screen, you can leave all default options selected, which include:
      Documentation
      pip (Python package manager)
      IDLE (Python Integrated Development and Learning Environment)
      etc.
      Click Next.
      Step 5: Advanced Options
      In the Advanced Options screen, you can select additional options:
      Install for all users (requires admin privileges)
      Add Python to environment variables (already checked if you selected it in the first step)
      Precompile standard library
      etc.
      Choose the installation location if you want to install Python in a specific directory.
      Click Install.
      Step 6: Complete the Installation
      The installation process will start and may take a few minutes.
      Once the installation is complete, you will see a "Setup was successful" message.
      Click Close to exit the installer.
      Step 7: Verify the Installation
      Open the Command Prompt (you can search for "cmd" in the Start menu).
      Type python --version and press Enter. This should display the version of Python that you installed.
      Type pip --version to ensure that pip (Python's package manager) is also installed correctly.
      Optional: Installing a Python Integrated Development Environment (IDE)
      For a better development experience, consider installing an IDE such as:
      PyCharm: A powerful IDE specifically for Python development. Download it from jetbrains.com/pycharm.
      Visual Studio Code (VS Code): A lightweight, versatile editor with Python support. Download it from code.visualstudio.com.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).
      Step 1: Check if Pip is Installed
      - Open the Command Prompt (search for "cmd" in the Start menu).
      Type the following command and press Enter:
      pip --version
      - If pip is installed, you will see something like pip x.x.x from .... If not, you will need to install it.
      Step 2: Download get-pip.py
      - Open your web browser and navigate to the get-pip.py script.
      - Right-click on the page and choose Save As to download the file to your computer. Save it in an easily accessible location, such as your Downloads folder.
      Step 3: Install Pip
      - Open the Command Prompt again.
      - Navigate to the directory where you saved get-pip.py. For example, if you saved it in the Downloads folder, type:
      cd Downloads
      - Run the following command to install pip:
      python get-pip.py
      - This will install pip and any necessary dependencies.
      Step 4: Verify the Installation
      - Once the installation is complete, verify that pip is installed correctly by typing:
      pip --version
      - You should see the pip version and the path where it is installed.
      Step 5: Upgrade Pip (Optional)
      - It is a good idea to ensure that you have the latest version of pip. To upgrade pip, use the following command:
      pip install --upgrade pip
      Step 6: Adding Pip to PATH (If Necessary)
      - If you encounter any issues running pip from the command line, it may be necessary to add it to your PATH manually.
      - Open File Explorer and navigate to the Python installation directory. This is typically located at C:\Users\<YourUsername>\AppData\Local\Programs\Python\Python3x\Scripts or C:\Python3x\Scripts.
      - Copy the full path to the Scripts directory.
      - Right-click on This PC or My Computer on the desktop or in File - - Explorer and select Properties.
      - Click on Advanced system settings.
      - Click the Environment Variables button.
      - In the System variables section, scroll down and find the Path variable, then click Edit.
      - In the Edit Environment Variable window, click New and paste the path to the Scripts directory.
      - Click OK to close all windows.
      Step 7: Verify Path Update
      - Open a new Command Prompt window.
      - Type pip --version again to confirm that pip is recognized in the command line.


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
      Step 1: Download MySQL Installer
      - Open your web browser and go to the official MySQL website: MySQL Downloads.
      - Click on the "MySQL Installer for Windows" link.
      - Choose the Windows (x86, 32-bit), MSI Installer and click on the Download button. You can select either the web installer or the full installer. The web installer is smaller and will download only the necessary files during installation.
      Step 2: Run the MySQL Installer
      - Locate the downloaded installer (typically in the Downloads folder).
      - Double-click the installer to run it.
      Step 3: Choose Setup Type
      - The MySQL Installer window will appear. Choose the setup type that best suits your needs:
      - Developer Default: Installs the MySQL server and other MySQL tools.
      - Server Only: Installs only the MySQL server.
      - Client Only: Installs only the MySQL client tools.
      - Full: Installs all MySQL products.
      - Custom: Allows you to select specific MySQL products to install.
      - For most users, the Developer Default option is recommended.Select it and click Next.
      Step 4: Check Requirements
      - The installer will check for any missing requirements. If any prerequisites are missing, the installer will prompt you to install them.
      - Click Execute to install the required software.
      Step 5: Select Products and Features
      - The installer will display a list of products and features to be installed. Review and click Next.
      Step 6: Installation Path
      - Choose the installation path or leave it as the default. Click Next.
      Step 7: Apply Configuration
      - Click Execute to start the installation. The installer will download and install the selected products.
      Step 8: Configure MySQL Server
      - High Availability: Choose the appropriate option (Standalone MySQL Server is recommended for most users).
      Type and Networking:
      - Choose the Config Type (Development Machine, Server Machine, or Dedicated Machine).
      - Set the MySQL port (default is 3306) and click Next.
      - Authentication Method: Choose the appropriate authentication method. The recommended option is "Use Strong Password Encryption (RECOMMENDED)".
      - Accounts and Roles: Set the root password and create any additional user accounts if necessary. Click Next.
      - Windows Service: Configure the MySQL Server as a Windows service and set it to start automatically. Click Next.
      - Apply Configuration: Review the settings and click Execute to apply the configuration.
      Step 9: Complete Installation
      - Once the configuration is applied, click Finish to complete the installation.
      Step 10: Verify Installation
      - Open the Command Prompt.
      - Type the following command and press Enter:
      mysql -u root -p
      - Enter the root password you set during the installation. If you see the MySQL prompt (mysql>), the installation was successful.
      - Optional: Install MySQL Workbench
      - MySQL Workbench is a visual tool for database management.
      - If you chose the Developer Default setup type, it should already be installed. If not, you can download it from the MySQL Workbench Download Page.


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
      Step 1: Open Visual Studio Code
      - Launch Visual Studio Code on your computer.
      Step 2: Open the Extensions View
      - On the Activity Bar on the side of the window, click the Extensions icon. It looks like a square with four squares inside.
      - Alternatively, you can open the Extensions view by pressing Ctrl+Shift+X on your keyboard.
      Step 3: Explore Extensions
      - The Extensions view will open in a new panel. Here, you can see a list of recommended and popular extensions.
      - You can use the Search Bar at the top to find specific extensions. Simply type in keywords or the name of the extension you are looking for.
      Step 4: Install Extensions
      - Browse the list of available extensions or use the search function to find an extension you want to install.
      - Click on the extension name to view more details about it, including a description, installation instructions, and user reviews.
      - To install an extension, click the Install button on the extension's detail page.
      Step 5: Manage Installed Extensions
      - After installing an extension, you might need to reload VS Code for the extension to activate. If so, you'll see a prompt to reload.
      - You can manage your installed extensions by clicking on the Installed tab in the Extensions view.
      - Here, you can enable, disable, or uninstall extensions.
      - You can also view the settings and configuration options for each extension by clicking on the gear icon next to the extension's name.
      Step 6: Explore Extension Packs and Themes
      - Extension Packs are collections of related extensions bundled together. You can find them by searching for "Extension Pack" in the Extensions view.
      - Themes change the visual appearance of VS Code. To explore themes, search for "Themes" or browse the "Themes" category in the Extensions view.
      Step 7: Configure Extensions
      - Some extensions require additional configuration. You can access an extension's settings by:
      - Clicking the gear icon next to the extension's name in the Installed tab and selecting Extension Settings.
      - Going to File > Preferences > Settings (or press Ctrl+,) and searching for the extension's settings.

There were various challenges that were met during the setup process but most of them were overcome through consultation with peers and also looking at package documentation on various websites online. 

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

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
