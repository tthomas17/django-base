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

3. Personalize project

    ```
    $ mv django-base src && cd src  #changes main directory to src
    $ mv djangoBase <newProject> #renames project
    $ sublime . #opens project in sublime (if setup)
    ```
4. In Sublime Find and replace djangoBase with your preferred project name
    ```Command + Shift + F```

5. Open README.md and update to reflect your new project


6. Install Requirements
``` $ pip install -r requirements.txt ```

7. Remove old git repository and setup new git repository
    ```
    $ rm -fr .git  #remove old repo
    $ git init   #setup new repo
    $ git add .
    $ git status
    $ git commit -m “initial commit"

    ```

8. Add New Repository to Github
    ```
    $ git remote add origin https://github.com/yourUserName/yourRepoName
    $ git push -u origin master

     ```

9. Add Datebase

    ```
    $ python manage.py migrate
    $ python manage.py createsuperuser

    ```


