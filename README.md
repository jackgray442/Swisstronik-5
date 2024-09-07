# Swisstronik Deploy Proxy Quest


# push to github
```
git remote remove origin
```
```
git remote add origin https://yourGitHubRepoLink
```
```
git checkout --orphan new-main
git add -A
git commit -m "Initial commit"
git branch -D main
git branch -m main
git push -f origin main
```
