# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

## Project: Pass
### Step 1: Setup GitHub, Heroku, and then Run.
1. Setup GitHub.
    1.	Download to zip given from the professor
    2.	Create new repository and then publish
    3.	Upload given zip file and then publish.
2. Setup Heroku
    1. Signup to Heroku
	2.  Login to Heroku
	3. Connect uploaded git
	3. Enable automatic deploy 
	4.  Then deploy
	5. But fail to push error will occur
	6. To solve this error change the gem file.
    7. Change verison of 2.7.0 to 2.6.6.
    8. Then do deploy again
3. Run Code.
    1. open console after going into more
    2. Run the command: heroku run rake db:migrate to migrate database
    3. Run command: heroku run rake db:seed which featch 
    4. After this commoands open app
    5. This is the Link: https://passass.herokuapp.com/articles



