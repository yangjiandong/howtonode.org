# howtonode.org

## 2012.04.07

> install, http://cloudcelebrity.wordpress.com/2012/01/22/steps-by-step-guide-to-clone-howtonode-node-js-git-repo-and-run-locally/ 

```
npm install -d
```

> run

```
cd server
node server.js
http://localhost:8080
```

> git remote yh

```
git branch yang
git co yang
--github create repo
git remote add yh git@github.com:yangjiandong/howtonode.org.git
git push -u yh master

--git remote rename yang yh
--远程更新
git pull yh
or
git fetch yh

git merge yh/master

```
