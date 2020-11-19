## Create a new repository on the command line

```
echo "# GitLab Setup" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://gitlab.com/ekaone3033/react-app.git
git push -u origin main
```

## Push an existing repository from the command line
```
git remote add origin https://gitlab.com/ekaone3033/react-app.git
git branch -M main
git push -u origin main
```