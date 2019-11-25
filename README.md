# UE_Test1 How to clone a repository containing a UE4 Project from GitHub Instructions: 

The purpose of this is to teach you how to view and edit another persons UE4 scene via Github. To do this you will practise cloning a repository which contains a UE4 project from Github, creating and naming your own branch, make changes to the scene you just cloned and lastly pushing your branch with your own edits made to the scene back up to Github for someone else to view.


### Getting setup:
Before even opening UE4, start by creating a GitHub account at https://github.com/ and downloading the Github Desktop app here https://desktop.github.com/.
Then link your Github account to your Epic games Account, here are some instructions on how to do it. Follow it from steps 2 to 7 https://www.unrealengine.com/en-US/ue4-on-github. Afterwards you will receive an email to confirm you have successfully linked your Github account with your Epic Games account. Make sure your Epic games account is the same one you are logged in with when you work with Unreal or the Epic Games launcher.


### Getting started:
Now that you've followed the above steps on getting setup you can now follow the numbered instructions below to practise cloning this Unreal project. These same instructions are also on Github when you select the first link below and will be the first thing you see, it's also titled as README.md.

1: Follow this link to the practice repository https://github.com/Xjana/UE_Test1 and select the clone button and copy the URL or copy it from here. (https://github.com/Xjana/UE_Test1.git)

2: Open your Github Desktop and select clone this repository either by selecting 'clone repository from the internet' and make sure you are on the URL TAB. Paste the URL link from Github from step 1 into the “Repository URL” Section. Before selecting clone to navigate to the Local Path section at the bottom selecting your local path folder, clone this repo into a new empty folder. Cloning a repository cannot be done in folders that already contain items or other files. If ready CLONE. This will take a few minutes as it is downloading onto your Drive.

3: In the Github Desktop select the ‘Fetch Origin’ with the 2 arrows. This grabs the latest version of your current branch from Github. Origin contains all the project files on the Master branch and any other branches and it’s associated files which are all stored on Github’s servers. The Master branch is essentially the master project files. A Master branch must also be a working version of the project at all times! A branch is a copy of the project’s files. People can create their own branches of a Master branch and edit the project files as much or as little as they want without affecting the Master. The next step is important as you will be moving off the Master branch and instead creating your own branch where you will also name it.

4: Create a new branch and name it. To do this, select the ‘Current branch’ button which will bring up a dropdown and select the ‘New Branch’ button. Name your new branch and select ‘Create branch’.

5: Go to the folder where you cloned UE_Test1 (this will be the same place you selected in Local path folder in Step 2) and select the UE4 project called 'Github_Test2' this will also have the UE4 icon. After executing this file, the Unreal Editor should open of a 3rd person level with a sphere and triangle on top in the level.

6: Make a change to the level and save it. Then check your Github Desktop and all your changes to the files should come upon the left-hand side. You also have to add a summary of your changes (it’s good to practise to add a comprehensive description of any changes made) Then select the commit and then ‘publish branch’ now highlighted in Blue or the  Publish Branch Menu icon or Ctrl+P. This pushes your branch to Github and is stored on the repository where you or anyone working on the project can later clone down again or view. You can now check your branch under branches next to commits on Github or the Desktop app.
