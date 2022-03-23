# tutorial-app
tutorial from 

https://realpython.com/python-git-github-intro/

https://www.jcchouinard.com/deploy-a-flask-app-on-heroku/

# this is my own takeaway on the instructions, i.e.: what worked for me
1. create repo on github
2. clone repo to folder on machine ($ git clone <copied url>)
3. set up virtual environment ($ virtualenv venv)
4. activate virtual environment ($ . venv/Scripts/activate)
5. install requests, flask and gunicorn ($ pip install requests[security] flask gunicorn)
6. add flask file to repo folder, <app name>.py
7. create requirements.txt ($ pip freeze > requirements.txt)
8. create Procfile ($ echo web: gunicorn <app name>:app >> Procfile
9. deploy app to heroku ($ heroku login)
10. press any key, click login on new window, close window
11. create heroku app ($ heroku create <app name>'
12. add heroku app to remote
13. ($ heroku git:remote -a <heroku app name>
14. ($ git remote -v)
15. deploy the flask app to heroku
16. ($ git add .)
17. ($ git commit -m "")
18. git push
19. git push heroku main
