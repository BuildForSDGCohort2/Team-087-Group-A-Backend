# How to Make Contributions to this Repo

1.  Fork the repo
2.  Clone the forked repo to your local machine
3.  Add the original repo as a remote called upstream
4.  Create a new branch to work (e.g. `git checkout -b ft-resources-rest-endpoints`)
5.  Implement your feature on the branch you created
6.  After you have implemented your feature, run the following in your terminal:

-   `git add .`
-   `git commit -m "your commit message goes here.."`
-   git push (e.g. `git push origin ft-resources-rest-endpoints`)

7.  Go to github and create a pull request from your fork

## Branch Naming Convention

All contributors should adhere to the following branch naming format: 

```{story type prefix}-{2-3 word summary}
```

### Story type prefixes are one of the following

-   ft == feature
-   bg === bug
-   rf == refactor
-   ch == chore

Example: 

```ft-facebook-auth
```
```bg-facebook-auth-timeouts
```

### Note
Always ensure to pull upstream changes into your local repo. e.g. `git pull upstream develop`