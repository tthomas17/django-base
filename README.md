# django-base

django starter project setup with static and template files. Includes first view, urlpattern, and custom css file. 

1. Navigate to the directory where you want to keep your project (i.e Desktop)
2. Setup a new Virtual Environment     ``` virtualenv <envName> ```
3. Change into your Virtual Environment Directory   ``` cd <envName> ```
4. Activate your Virtual Environment   ``` source bin/activate ```
5. Clone the git repository > ``` git clone https://github.com/tthomas17/django-base ```
6. List Directories >  ``` ls ```
7. Rename main Directory to src  ``` mv django-base src ```
8. Change into src directory ``` cd src ```
9. List All files including hidden files/directories such as .git using ``` ls -a ```
10. Remove .git directory using ``` rm -fr .git ```
11. confirm it worked  ``` ls -a ```
12. Rename project ``` mv django-base <newProject> ```
13. Install django >  ``` pip install django ```
14. go back to parent directory ``` cd .. ```
15. open project in sublime (if setup) sublime src
16. In Sublime Find and replace djangoBase with your preferred project name  > ** Command + Shift + F **
17. Open README.md and update to reflect your new project
18. Using Terminal  navigate back into src directory  ``` cd src ```
19. Setup git:
    1. ```git init```
    2. ```git add .```
    3. ```git status```
    4. ```git commit -m “initial commit" ```
20. Add New Repository to Github
    1.  ``` git remote add origin https://github.com/yourUserName/yourRepoName ```
    2. ``` git push -u origin master ```