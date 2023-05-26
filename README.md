
Note- I've barely begun to actually play around with these so I am not sufficiently comfortable enough to make any sort of technical tutorial. My Sun-Wed is completly blocked off to work with this. 


GET STARTED WITH GIT, GITHUB AND WEBSTORM

installation instructions-

Webstorm- start with this because you may need to submit an ID picture and approval can take a day or two

go to- jetbrains.com

create account-

register- click on student tools and fill out the application. you may be prompted to upload a picture ID. once you submit your registration it may take a day or two for it to be approved

download- Once the approval email is recieved, click the link to "link your free license" to your account. From there, click WebStorm from the list of downloadable products.

Git-

go to- git-scm.com

download- click 'download' inside computer screen graphic on right side of screen(or click below that for Mac) . Then click on the the top link to download the latest version of the Git software

Install- once downloaded, open the installer and follow it's instructions

Github- 

go to- github.com

create account- in the top right corner click "sign up" and follow the instructions. A code will be sent to verify your email address. input the code and you will be taken to the github home page which will now include your projects and a "create repository" on the left side of the page. 

Now that you have installed Webstorm and Git, as well as made a Github account, you're ready to learn about some of its features and commands. 

The first thing youll want to do is create a **repository**. This is where your project will be stored. To do this open your **Git** command shell and either create a new folder or send to a folder you already made

command for new folder-  mkdir myproject

Now that you have a repository, you can choose to create a new file, or upload an existing one. For the sake of this tutorial we will assume you are starting from scratch. Open up your favorite text editor and and save it to the folder you created. once you've named your new file and start adding things to it, you'll want to **commit** them, which is what will actually make the changes and update the file. ***This isn't a relationship, you dont have to be afraid of commitment here

to add file- git add your_filename

This main file can also be called your master **branch**, and anywhere in that file you can branch off to create another version of your project from that point. Now that you can create branches, you'll also need to learn to **merge** them, which will is exactly what it sounds like. However, if your branch cannot be merged, you will recieve a **merge conflict**

Now that you have some things in your file, you need to know how to send and recieve things between your local and remote. To send things to Github(your remote) you use the **push** command. Note that Git does not automatically push when you commit your changes. push just sends all your recent commitments to the remote server. With bringing from the remote to your local, you have a few more options. First, you can **fetch** things from the remote server, which simply downloads any changes and new files. going a step further you can also **pull** from the remote which will also automatically merge whats being pulled. 

**Glossery of Terms**
Repository- root folder to contain all project files 
Github- Used alongside Git as a hosting platform to write and edit code, both individually and collaborativly.
Remote- the remote server is where projects and stored outside your local server and can be accessed by others if working collaborativly. 
Git- "Global Information Tracker" used to track changes in a codebase. Everytime an update is made, it makes a whole new copy of your file, as well as keeps evey old copy.
Commit-this command adds changes and updates to a project
Clone- this command makes a copy of a repository
Branch- a version of your project. there will always be a Master branch but when creating a new branch, it starts from its creation point
Merge- this command brings together multiple branches
Merge Conflict- Git is unable to successfully merge branches
Fetch- this command downloads new changes and files from the remote to local server
Push- this command sends content to the remote server from the local
Pull- this both downloads and merges changes from the remote to local server


**Resources**
https://www.w3schools.com/git/git_intro.asp?remote=github
https://njit.instructure.com/courses/28777/files/5112257?module_item_id=1105219
https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners
