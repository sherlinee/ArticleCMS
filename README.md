# Article CMS (FlaskWebProject)

This project is a Python web application built using Flask. The user can log in and out and create/edit articles. An article consists of a title, author, and body of text stored in an Azure SQL Server along with an image that is stored in Azure Blob Storage. You will also implement OAuth2 with Sign in with Microsoft using the `msal` library, along with app logging.

## Log In Credentials for FlaskWebProject

- Username: admin
- Password: pass

Or, once the MS Login button is implemented, it will automatically log into the `admin` account.

## Steps Taken in Azure (screenshots attached as resource group is deleted to avoid any costs)

1. Created a Resource Group in Azure.
2. Created an SQL Server and Database in Azure that contains a user table, an article table, and data in each table (populated with the scripts provided in the SQL Scripts folder).
3. Created a Storage Container in Azure for `images` to be stored in a container.
4. Completed TODOs in `views.py`.
5. Created an App Service to deploy the application and enabled app registration in azure directory then redirected Uris to the app service.
6. Deloyed the app service and linked to my Github
7. Tested the blog
## Dependancies
 Python 3.7 or later
