#GIT COURSE
This is a training repository I use for git-course on platform [Яндекс.Практикум]https://practicum.yandex.ru

##Starting
1. Initialize repository locally
```git init```
2. Go to github and create a remote repository
3. On github find a Quick setup section and choose SSH, you are looking for a link that looks like this:
```git@github.com:Lulufox/git_course.git```
4. Locally enter the repository folder and run:
```git remote add origin *link from previous step*```
5. Run `git status` to check the status

##First commit
1. `git status` to check status.
2. `git add .` to add everything to index.
3. `git commit -m 'Text'` to create a commit with a message
4. `git push --set-upstream origin master` to push to remote repo.