Assignment DEV_SET UP

Setting up development environment


#### Task1 setting up operating system

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

#### Task 2 setting up version control using git and github on windows

1. Go to [git](https://git-scm.com/download/win) <br><br>

2. Download the latest version of Git and choose the windows 64/32 bit version. <br><br>

3. After the file is downloaded, install it in the system. <br><br>

4. Once installed, select Launch the Git Bash, then click on finish. <br><br>

5. Once git bash is launched type the command git <span style="color:red">git --version </span> to check the installation <br><br>

6. For any help, use the command: <span style="color:red">git config --help </span> <br>

##### The next step is to initialize a new repository

1. first the new repository will be initialized in a new directory. the  command below will be used to make a new directory <br><br>

	i. mkdir test <span style="color:red">this command makes a new directory or folder into which a new repository will be initialized </span> <br><br>

	ii. cd test <span style="color:red">this command navigates inside the directory</span><br><br>

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

18. For you to now link the local repository to your newly created remote repository,first go to git bash<br><br>

19. since this is the first time you want to link a new local repository to a remote repository you will enter the command <br><br>

	1. git config --global user.name: "your github username"
	2. git config --global user.email: "your github email"

*N/B you may be prompted to enter your password to verify your identity if it i the firs time your are linking your local repository to your remote repository, if so, just enter your credentials i.e your username and password on the github logi popup that appears*

*Once you have logged in and git hub has verfied your login details, check on git bash to confirm login status, if ok proceed with the commands below*

	git remote add origin https://github.com/"your user name"/"your repository".git
	git push -u origin main

20. once done you should see an updated version of your local repository appearing in your remote repository in your github account (this is your local repository data and or files uploaded to your remote github account)
---