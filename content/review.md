Title: Site generation using pelican
Date: 2019-03-11 10:20
Category: Review

Following is a review of my first experience with pelican.
I am new to this technology I only knew some python basics. Eventhough  
i am a beginner it is fun to work with pelican.

Site generation using pelican
 
1. Create a new virtual environment
2. Then run "**pip install pelican markdown”** 
3. Create a Project and choose a directory for your site with suitable names “**mkdir -p ~/projects/yoursite” and "cd ~/projects/yoursite"**
4. To create a skelton project we have to run ”**pelican-quickstart”**, this will follow to a few questions tat helps to build the site.
5. Next we have to add some contents using any text editor and save  as .md file. We cannot run Pelican without creating some contents.
6. From the site directory, to generate our site  run “**pelican content”**.
7. To preview our site “**pelican —listen**” (The default port for the site is 8000, if it is already taken we can run “pelican -p  8003 --listen”. That will choose the new port)

Steps to push the code into Github

1. Create a new repository to add the web page
2. Change the directory into the output which includes all html files
3. From there initialise the directory using **git init**
4. Then follow **git remote add origin git@github.com:username/newrepo.git** and **git commits -m "initial commit"****
5. Finally **git push -u origin master**