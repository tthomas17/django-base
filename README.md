# django-base

django starter project setup with static and template files. Includes first view, urlpattern, and custom css file.


##Steps to clone django-base and setup a new repo on GitHub using the Terminal on Mac

1. Create and activate new Virtual Environment
```
cd ~/desktop
virtualenv <envName>
source bin/activate

```
2. Clone the git repository > ``` git clone https://github.com/tthomas17/django-base ```
3. List Directories >  ``` ls ```
4. Rename main Directory to src  ``` mv django-base src ```
5. Change into src directory ``` cd src ```
6. Remove .git directory using ``` rm -fr .git ```
7. Rename project ``` mv djangoBase <newProject> ```
8. Install django >  ``` pip install django ```
9. go back to parent directory ``` cd .. ```
10. open project in sublime (if setup) ```sublime src```
11. In Sublime Find and replace djangoBase with your preferred project name  > ```Command + Shift + F```
12. Open README.md and update to reflect your new project
13. Using Terminal  navigate back into src directory  ``` cd src ```
14. Setup git:
    ```
    git init
    git add .
    git status
    git commit -m “initial commit"

    ```
15. Add New Repository to Github
    ```
    git remote add origin https://github.com/yourUserName/yourRepoName
    git push -u origin master

     ```