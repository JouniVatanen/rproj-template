# R project template

## Normal git workflow (DELETE THIS FROM YOUR PROJECT AFTER FIRST COMMIT)

```
## Change origin to project github page
git remote set-url origin git@github.com:JouniVatanen/MY-PROJECT.git
## Push to project github page
git add .
git commit -m "first commit"
git push --set-upstream origin master
```

## Info
This is an R project. Rmarkdown files (Rmd) has all the necessary parts to run the code. Usually you only need to run the rmarkdown::render command in the first lines. Rmd-files are named by project name, year and version number. Choose the year you want to use and it's largest version number. Checkpoint package ensures that you will use the correct package and R versions. 

At the current stage you need [Rtools](https://cran.r-project.org/bin/windows/Rtools/) to source the github package [JouniVatanen/stools](https://github.com/JouniVatanen/stools). Later stools package will be added to CRAN and then you no longer need Rtools. If you want to write to sql as fast as possible, then you need bcp tool from SSDT which you can get [from Microsoft](https://docs.microsoft.com/en-us/sql/ssdt/download-sql-server-data-tools-ssdt?view=sql-server-ver15#ssdt-for-vs-2017-standalone-installer).

The data and contents of the doc, posted, output, and work folders will not be in github. Currently some data are in the data folder in files. Later most of the data will be saved in the database for easy access. That is why you will need either files or access to the database.

## Folder structure

- data/
- doc/
- output/
- posted/
- R/
- work/

