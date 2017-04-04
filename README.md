# django-base

django starter project setup with static and template files. Includes first view, urlpattern, and custom css file.


## Steps to clone django-base and setup a new repo on GitHub using the Terminal on Mac

1. Create and activate new Virtual Environment
```
$ cd ~/desktop
$ virtualenv <envName> && cd <envName>
$ source bin/activate
```
2. Clone the git repository
 ``` $ git clone https://github.com/tthomas17/django-base ```
3. Rename main Directory to src and change into src
``` $ mv django-base src && cd src ```
4. Remove .git directory using
``` $ rm -fr .git ```
5. Rename project
 ``` $ mv djangoBase <newProject> ```
6. Install Requirements
``` $ pip install -r requirements.txt ```
7. go back to parent directory
``` $ cd .. ```
8. open project in sublime (if setup)
```$ sublime src```
9. In Sublime Find and replace djangoBase with your preferred project name
 ```Command + Shift + F```
10. Open README.md and update to reflect your new project
11. Using Terminal  navigate back into src directory
``` $ cd src ```

12. Add Datebase

    ```
    $ python manage.py migrate
    $ python manage.py createsuperuser
     ```

13. Setup git:
    ```
    $ git init
    $ git add .
    $ git status
    $ git commit -m “initial commit"

    ```
14. Add New Repository to Github
    ```
    $ git remote add origin https://github.com/yourUserName/yourRepoName
    $ git push -u origin master

     ```