Heroku url
https://dashboard.heroku.com/apps

Steps to clone this app in heroku

Open git bash in command prompt
login using below command
	$ heroku login
clone the project
	$ git clone https://github.com/GnanaprakashKaruthan/TomcatHelloWorld.git
Navigate to directory
	$ cd TomcatHelloWorld
	
create repository in heroku
	$ heroku create tomcatapp1
	
Push the changes in heroku and start the application
	$ git push heroku master

Make sure at least one instance is running, use scale command
	$ heroku ps:scale web=1

Open the application in web browser
	$ heroku open

To check the logs, to display 100 lines of logs
	$ heroku logs -n 100

Make sure that you have installed heroku CLI in your machine before you do deploy app.

Steps to install heroku in windows
Download heroku and install it (05-December-2019)
https://cli-assets.heroku.com/heroku-x64.exe
Below path will be set automaticall in environement variable if you install with admin rights
C:\Program Files\heroku\bin

Also make sure you have installed and set git variable in environement path.
To verify git version via command prompt
	$ git -v



Steps to commit the changes in GitHub
Create empty repository
clone it in local via git command prompt
	$ git clone https://github.com/GnanaprakashKaruthan/TomcatHelloWorld.git
Do your changes and add the files to github
	$ git add . (please note the dot at end of the command)
Commit the changes
	$ git commit -m 'init'
Push the changes
	$ git push origin master
	

	