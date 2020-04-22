# Account Password Locker
## description
This is a project made in python knowledge to create a site where people with sepatete account are able to solve there password and user name problems
## User Stories
As a user I would like:

To create an account with my details - log in and password
Store my existing login credentials
Generate a password for a new credential/account
Specifications
* Behaviour	Input	Output
Display guides for navigation	In terminal: $./run.py	Hello Welcome to your Pass Word Locker. What is your name? (once you enter your nname):Use these known short codes to operate : SU -> SIGN UP. DA -> Display your account. LN ->LOGIN. ex ->exit Pass Word Locker.
Display prompt for creating an account	Enter: SU	Enter account name, user name password and email .
Display prompt for login in	Enter: LN	Enter your account password to login
Once logged in	You are now logged in to your account	Use these short codes:CA -> Create new credential.DC -> Display your credentials list. ex ->Log out your credentials account.
Display prompt for creating a credential	Enter: CA	Create new credential, Credential name: and password
Display a list of credentials	Enter: DC	Prints a list of saved credentials
Log out account	Enter: ex	You have logged out your account
To completely interact with this application,you will need to sign up to have an account,then login to your account and work in there.
## SetUp / Installation Requirement
python3.6
Good internet connection

## For linux/ubuntu users : Git
## Running the Application
To run the application, in your terminal:

  $ ./run.py
## Testing the Application
To run the tests for the class file and check if it functions well:

  $ python3.6 credentials_test.py
## Technologies Used
Python3.6
## License
MIT