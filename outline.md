Job : 
    - title
    - location
    - job type
    - description
    - published at
    - Vacancy
    - salary
    - category
    - experience 
    

    - apply job 
    - post job


Blog : 
    - title
    - description 
    - created_at
    - category
    - tags
    - author

    - search
    - comment
    - recent posts

contact
home


login 


Fix git
•	List remotes: git remote -v
•	Let's say your remote is named origin, then you can remove it with: git remote remove origin
•	Reinsert the origin and repo URL: git remote add origin git@github.com:{USER_NAME}/{REPO_NAME}.git
•	finally, push it to the server: git push -u origin main
•	git add .
•	git commit – m "add Django project structure"
•	git push



•	fromtend template
•	virtualenv:
    o	create
    o	activate
    o	pip install
    o	deactivate
    o	pip freeze > requirments.txt

- upload project on github
•	url: path
•	view: logic
•	model: DB
•	templates: frontend

py mange.py startapp blog

py mange.py startapp createsuperuser


realtions
- one to many   [author , posts]
- many to many  [users , groups]
- one to one     [user , profile]
