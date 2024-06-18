Assignment DEV_SET UP

Setting up development environment

Windows operating system setup

#### Task1 setting up operating system

Visual studio code setup

#### Task2 setting up Visual studio code IDE on windows

1. Open any web browser, such as Google Chrome or Microsoft Edge, and go to the Official Website of Visual Studio Code at this [vscode](https://code.visualstudio.com/docs/?dv=win) <br><br>

2. Click the “Download” button on the website to initiate the download of the Visual Studio Code application, on the next page click on the windows download icon, this should start the download.<br><br>

3. Once the download is complete, the Visual Studio Code icon will appear in your downloads folder.<br><br>

4. Double-click the installer icon to begin the installation process of Visual Studio Code.<br><br>

5. When the installer opens, you will need to accept the terms and conditions of Visual Studio Code. Select "I accept the agreement" and then click the Next button.<br><br>

6. Choose the installation location for Visual Studio Code. Browse to the desired location and then click Next.<br><br>

7. To start the installation setup, click the Install button.<br><br>

8. After clicking Install, the installation process will take about one minute to complete.<br><br>

9.  Once the installation is finished, a window will appear. Check the "Launch Visual Studio Code" checkbox and then click Finish.<br><br>

10. Following the previous step, the Visual Studio Code window will open successfully.
---
Version control using git and github

#### Task 2 setting up version control using git and github on windows

1. Go to [git](https://git-scm.com/download/win) <br><br>

2. Download the latest version of Git and choose the windows 64/32 bit version. <br><br>

3. After the file is downloaded, install it in the system. <br><br>

4. Once installed, select Launch the Git Bash, then click on finish. <br><br>

5. Once git bash is launched type the command git <span style="color:red">git --version </span> to check the installation <br><br>

6. For any help, use the command: <span style="color:red">git config --help </span> <br>

##### The next step is to initialize a new repository

1. first the new repository will be initialized in a new directory. the  command below will be used to make a new directory <br><br>

	- mkdir test <span style="color:red">this command makes a new directory or folder into which a new repository will be initialized </span> <br><br>

	- cd test <span style="color:red">this command navigates inside the directory</span><br><br>

    <div style="width:100vw; height:8vh; border:1px solid black;background-color:#505050; color:white; ">
    C:\ mkdir test <br> C:\ cd test
     </div><br>


8. Once inside the directory use the command git init (this command initiates a new repository)
    <br>
    <div style="width:100vw; height:8vh; border:1px solid black;background-color:#505050; color:white; display:flex; justify-content:center; align-items:center;">
     git init
     </div><br>

9. Navigate / go to the folder where "test" is created and create a text document named "demo." Open "demo" and put any content, like "Hello powerlearn." Save and close the file.<br><br>

10. in git bash enter the command <span style="color:red">"git status"</span> to check the status:<br><br>

11. Add the "demo" to the current directory using the following command: <span style="color:red">"git add demo.txt"</span><br><br>

12. Next, make a commit using the following command: <span style="color:red">git commit -m "committing a new file"</span><br>
	
##### To link the local repository to a remote repository, you need to open a github account and create a remote repository, to do this follow the steps below

13. Go to your browser and paste the link [github](https://github.com/)<br><br>

14. To get started you'll need to create a free personal account on GitHub.com and verify your email address. follow the prompts to register for an account and create a password<br><br>

15. A verification email will be sent to your email address with the necessary login details for you to log in to your github account.<br><br>

16. Once logged in you can create a new repository by first clicking on Repositories (this will take you to the repository page). You can then click on the new button on the repository page, this will create a new repository <br><br>

17. Once clicked, you will be taken to a new page where you will need to enter a name for the repository,once entered, click on create repository, which will send you to a new page displaying your created repository<br><br>

18. For you to now link the local repository to your newly created remote repository,first go to `git bash`<br><br>

19. since this is the first time you want to link a new local repository to a remote repository you will enter the command <br><br>

	- git config --global user.name: "your github username"
	- git config --global user.email: "your github email"

*N/B you may be prompted to enter your password to verify your identity if it is the first time your are linking your local repository to your remote repository, if so, just enter your credentials i.e your username and password on the github logi popup that appears*

*Once you have logged in and git hub has verfied your login details, check on git bash to confirm login status, if ok proceed with the commands below*

	git remote add origin https://github.com/"your user name"/"your repository".git
	git push -u origin main

20. once done you should see an updated version of your local repository appearing in your remote repository in your github account (this is your local repository data and or files uploaded to your remote github account)
---
Python installation

#### Task 3 Steps to downloading and installing python 

1.  Navigate to the Python download page:

	Open your web browser.
	Go to https://www.python.org/downloads/ <br><br>
	
2.  Locate the Download button:

	On the webpage, find the "Download Python 3.12.4" button and click on it.<br><br>
3.  Download the installer:

	 A file named `python-3.12.4.exe` will be downloaded to your computer, typically in the "Downloads" folder.<br><br>

4. Open the installer:

	- Navigate to your "Downloads" folder.
	- Double-click on `python-3.12.4.exe` to start the installer.<br><br>

5. Installer window - Add to PATH:

	- The Python installer window will open.
	- Check the box that says `Add Python 3.12 to PATH` at the bottom.<br><br>

6. Start the installation:

	Click on the "Install Now" button.<br><br>

7. User Account Control (UAC):

	If prompted by UAC, click "Yes" to allow the installer to make changes to your device.<br><br>

8. Wait for the installation to complete:

	The installation progress will be shown, and it may take a few minutes.<br><br>

9. Installation complete:

	- Once the installation is finished, you will see a "Setup was successful" message.
	- Click the "Close" button.<br><br>

10. Verify installation:

	- Open a command prompt or terminal window.
	- Type python --version and press Enter.
	- You should see Python 3.12.4 displayed.
---

PIP package manager for python

#### Task 4 steps for setting up the pip package manager for python

pip is a package manager for python that can be installed using get-pip.py

1. Open a web browser and navigate to https://bootstrap.pypa.io/get-pip.py.<br><br>

2. Download the get-pip.py script:

	Right-click on the page and select "Save as..." to save the file as get-pip.py in your desired 	location (e.g., the "Downloads" folder).<br><br>

3. Open Command Prompt:

	Press `Win + R`, type cmd, and press Enter to open the Command Prompt.<br><br>

4. Navigate to the directory where you saved get-pip.py:

	Use the cd command to change the directory. For example, if you saved the file in the 	"Downloads" folder, type cd Downloads and press Enter.<br><br>

5. Run the get-pip.py script:
   Type python get-pip.py and press Enter. This will download and install pip.<br><br>

6. Verify the installation:

	After the installation completes, type pip --version and press Enter. You should see the 	version of pip installed.
---
MySQL Database

#### Task 5 Steps to download, configure, and install MySQL on Windows

1. Open a web browser and navigate to https://dev.mysql.com/downloads/windows/installer/5.7.html.<br><br>

2. Download the MySQL Installer:

	- Click on the "Download" button for the MySQL Installer (choose either the web installer or the 	full installer, depending on your preference).<br><br>

	- On the next page, you may be prompted to login or sign up for an Oracle Web account. You can 	        click on "No thanks, just start my download" to skip this step and start the download.<br><br>

3. Run the MySQL Installer:
	
	- Once the download is complete, navigate to the location where the installer file (mysql-		installer-community-<version>.msi) is saved.

	- Double-click on the installer file to run it.<br><br>

4. Choose Setup Type:

	- In the MySQL Installer window, select the setup type that best suits your needs (Developer 	        Default, Server only, etc.). 
	- Click "Next" to proceed.<br><br>

5. Check for Requirements:
	
	The installer will check for any requirements. If any components are missing, follow the               instructions to install them. Click "Next" when all requirements are met.<br><br>

6. Select Products and Features:

	Ensure the necessary MySQL products and features are selected. Click "Next" to proceed.<br><br>

7. Installation:

	- Click "Execute" to start the installation of the selected products. Wait for the installation to complete. 
	- Click "Next" when done.<br><br>

8. Product Configuration:

	 After installation, you will be prompted to configure MySQL Server and other products. Click "Next" to start the configuration process.<br><br>

9. MySQL Server Configuration:

	- Choose the configuration type (Standalone MySQL Server or InnoDB Cluster).
	- Set the MySQL root password and optionally create additional user accounts.
	- Configure other settings such as server name, port number, and MySQL as a Windows Service.
	- Click "Next" to proceed through each configuration step.<br><br>

10. Apply Configuration:

	Click "Execute" to apply the configuration settings. Wait for the process to complete and click "Finish".<br><br>

11. Complete the Installation:

        Once all configurations are applied, click "Next" and then "Finish" to complete the                    installation process.<br><br>

12. Verify Installation:
        
	Open a command prompt and type `mysql -u root -p`, then enter the root password you set during         configuration.
    If you see the MySQL prompt, the installation was successful.<br><br>
---

Extensions and Plugins

#### Task 6 Steps to install the Python extension in Visual Studio Code (VS Code) to enhance Python development:

1. Open Visual Studio Code:
   Launch VS Code on your computer<br><br>

2. Access the Extensions View:
   Click on the Extensions icon in the Activity Bar on the side of the window (or press Ctrl+Shif+X).<br><br>

3. Search for the Python Extension:
   In the Extensions view search bar, type "Python".<br><br>

4. Select the Official Python Extension:
   Look for the extension named "Python" published by Microsoft and select it.<br><br>

5. Install the Extension:
   Click the "Install" button on the extension's details page.<br><br>

6. Verify the Installation:
   Once the installation is complete, you should see the Python extension listed under "Installed"      extensions.<br><br>

7. Configure Python Interpreter:
   - Open the Command Palette by pressing Ctrl+Shift+P.
   - Type "Python: Select Interpreter" and select it.
   - Choose the Python interpreter you want to use from the list.<br><br>

8. Reload or Restart VS Code (if necessary):
   
   Sometimes, you might need to reload the VS Code window for the extension to be fully activated.       Click the reload button if prompted, or restart VS Code manually.<br><br>