# daikuanzj

1.create a empty repository on github;
2.init local project as a git;
3.git remote add origin https://[user]@github.com/[user]/[reponame].git
4.git push -u origin master

github给的默认的uri没有在github.com前加上user的，这可能导致push时403 Forbidden，且不会提示你输入密码。
