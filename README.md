<h1 align="center">Project Epsilon</h1>

## About the project
With project epsilon we aim to enable young african entrpeneurs to build companies using a marketplace platform. Making things such as hiring talent, applying for grants, and company management easy and accessible for those wanting to take the oppurtunity to create a successful business.

## Project setup
Follow these instructions to run the project after cloning locally:
1. Install [MySQL installer](https://dev.mysql.com/downloads/installer/) and install MySQL Server 8.0.25
    1. Set the MySQL root password as: 12345
    2. Create a DB Admin user with these credentials: u: epsilon p: 12345
2. At root, create a virtual environment with these commands on your terminal [instructions]:
    1. python3 -m venv venv
    2. source venv/bin/activate
    3. pip3 install -r requirements.txt
4. Run `mysql -u epsilon -p` and type in the password when prompted.
    1. Run `CREATE DATABASE epsilon_db CHARACTER SET utf8;` to create the local database.
    2. Run `exit`.
4. Run `python3 app.py` and go to the link provided in the terminal to view the webapp.

To manage the database use a third party GUI tool with the credentials above to view/edit.
(for now it is safe to put these credentials here since the repo is private to students in CSCC01)
  
For general flask inquiries and instructions follow [this](https://flask.palletsprojects.com/en/2.0.x/installation/) documentation.
For mysql connection follow [this](https://flask-mysqldb.readthedocs.io/en/latest/) documentation.

## Contributing to the project
For project epsilon we are using github as our version control. Whenever a change is made that is more than 10 lines or is not a bug fix, a pull request should be made. Branch names will be the same as their associated ticket on Jira.

All tickets will be created on Jira to assign work to any given member of the project.

Finally, members will use Figma to create all mockups

For team details, go to [doc/sprint0/team.md](doc/sprint0/team.md)
