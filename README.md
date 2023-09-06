# simple-report-system
Computer problem reporting page - /v1/reporter
Provide basic error reporting functions
Reporters do not need to register to report anonymously
Software delivery request page - /v1/delivery
When classroom users (e.g. teachers) need to request new software installation and delivery services, they can apply online to the PC Management Teaching Assistant here.
Administrator page (login required) - /v1/login
Register/Login Manager
Manage report records, make repairs to report records, and troubleshoot problems
Registration requires key provided by PC Assistant
Development
The source code can be used only by adding the model/.dbconfig.json file (including database-related settings and the secret key used by the administrator for registration). If you want to use it in your own field, simply add this file setting That’s it.
The current development environment uses MySQL
.dbconfig.json format:
{
    "db_schema": "name of Database",
    "db_username": "owner of Database",
    "db_userpasswd": "Owner's password",
    "db_host": "Host IP address",
    "secret_key": "your secret key shared among administrators"
}
If you are interested in maintaining this heroku distribution of Chengda Information, please email me (kevinbird61@gmail.com) to get the .dbconfig.json configuration file!
Misc
A few things about deploying on Heroku


