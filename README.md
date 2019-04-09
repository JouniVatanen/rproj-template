# Rproj template
Custom template for an R project

## Instructions

1. [Create R project](https://support.rstudio.com/hc/en-us/articles/200526207-Using-Projects)
2. [Initialise git](https://git-scm.com/docs/git-init)
3. Download template from github using
- [https-connection, recommended](https://help.github.com/articles/which-remote-url-should-i-use/#cloning-with-https-urls-recommended)
- [SSH-connection](https://help.github.com/articles/connecting-to-github-with-ssh/)

### Git commands

Add a remote repository and pull. You might need to delete .gitignore from your own R project before pulling.

```
git remote add origin git@github.com:JouniVatanen/rproj-template.git
git pull origin master
```

If you need to overwrite all existing files like .gitignore then instead of pull
```
git fetch --all
git reset --hard origin/master
```

Change the url to your own project.

```
git remote set-url origin git@github.com:JouniVatanen/my-project.git
```

Commit to the new repository.

```
git add -A
git commit -m "first commit"
git push --set-upstream origin master
```

## Info template

### Folder structure

- data/
- doc/
- output/
- posted/
- R/
- work/
