# TASK:
Create pretty users table with Bootstrap framework.
[http://getbootstrap.com/](http://getbootstrap.com/)
[http://www.w3schools.com/bootstrap/bootstrap_tables.asp](http://www.w3schools.com/bootstrap/bootstrap_tables.asp)

For admin purpose. 
With button "Get all user's" - which will refresh table on page.
Table must be dynamically rendered by JS.

### Additional task (Part 2):
Familiarize with jwt tokens and add to AJAX request header "Authorization" 
token obtained by login to system. 
Admin account fields:
    
    {
        "login":"admin",
        "password":"admin"
    }
[https://wm-task-tracker.herokuapp.com/doc/#api-Auth-PostSignIn](https://wm-task-tracker.herokuapp.com/doc/#api-Auth-PostSignIn)

## Documentation:
[https://wm-task-tracker.herokuapp.com/doc](https://wm-task-tracker.herokuapp.com/doc)

Documentation about users:
[https://wm-task-tracker.herokuapp.com/doc/#api-User-GetApiUsers](https://wm-task-tracker.herokuapp.com/doc/#api-User-GetApiUsers)

Example for get all users:
GET request to https://wm-task-tracker.herokuapp.com//api/users/