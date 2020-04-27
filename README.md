https://morning-wildwood-72184.herokuapp.com/api/notes
Steps to deploy:

1. heroku login, heroku create

2. add `Procfile` to backend root, add `app.use(express.static("build"))` to `index.js`

3. copy `build` directory from frontend to root of backend

4. create/commit to my regular git repo - `git push -u origin master`

5. push to heroku - `git push heroku master`
