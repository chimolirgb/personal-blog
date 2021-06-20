## PERSONAL-BLOG

## Author
Lucy Chimoli

## Description
This project is about createing a personal blogging website where you can create and share your opinions and other users can read and comment on them. Additionally, their is a feature that displays random quotes to inspire  users.
 
## User view
1. User can view the blog posts on the site.
2. User sees random quotes on the site.
3. User can view the most recent posts.
4. User can subscribe to blog maililng list and receive an email alert when a new     post  is made.
5. User can comment on blog posts.

## Writer view
1. sign in to the blog.
2. create a blog from the application.
3. delete comments that i find insulting or degrading.
4. update or delete blogs i have created.

## Technologies Used
1. Python 3.7.4
2. Flask 1.1.1
3. PostgreSQL 11.5
4. SQLAlchemy
5. HTML5
6. CSS3
7. Javascript
8. Bootstrap 4.0.0 beta
9. Font Awesome 5.8.2
10. jQuery 3.4.1
11. Google Font API

## Requirements
. This program requires python3.+ (and pip) installed, a guide on how to install python on various platforms can be found here
. Once python is installed, install the folowing external libraries provided in the requirements.txt file using pip
Example:
pip install flask


## Installation and Set-up
1. To view the app, open the live site link provided below on the README. Here is a run through of how to set up the application:

Step 1 : Clone this repository using git clone https://github.com/chimolirgb/personal-blog.git, or downloading a ZIP file of the code.
2. Step 2 : The repository, if downloaded as a .zip file will need to be extracted to your preferred location and opened
3. Step 3 : Go to the project root directory and install the virtualenv library using pip an afterwards create a virtual environment. Run the following commands respectively:
. pip install virtualenv
. virtualenv venv
. source venv/bin/activate
Note that you can exit the virtual environment by running the command deactivate
4. Step 4 : Go to config.py and set the SQLALCHEMY_DATABASE_URI to your own, you may use Postgres or any other SQL databse client.
5. Step 5 : Download the all dependencies in the requirements.txt using pip install -r requirements.txt
Create a file in your root directory called start.sh and store a generated SECRET key like so export SECRET_KEY="<your-key>"
On the same file write down the command python3 manage.py server
6. Step 6 : On your terminal, run the following command, chmod a+x start.sh
7. You can now launch the application locally by running the command ./start.sh
8. Open your preferred browser and view the app by opening the link http://127.0.0.1:5000/.

## License
MTN License @lucychimoli2021