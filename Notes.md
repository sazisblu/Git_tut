# Some important pointers for git and github

1. Git tracks not the files but the changes made to them.So, multiple versions of files may exist in the working and changing area.

2. Every text editor provides a git integration which simplifies the gigitty tasks with buttons which replace the commands.

3. If we do a git log, we are met with a string of aplhanumeric characters which is known as a commit hash. We may use the commit hash to uniquely identify the version of our code that we want to revert back to.
 
4. Once revereted to a previous version of our file, we are only able to see the commits made upto that version and not the whole list of commits. To view all the commit/versions of the file we shall do (git log --all).

5. Aliases can be used to create short hands for frequently used commands. (note: youhace set up s-->status and cm-->commit)

6. you may create a .gitignore file create a list of files to be ignored by git during repo commiting (note: the ignored files may include password files, sensitive text files etc)

7. rm -rf .git deletes .git file from our directory which causes our folder to become a non-repo directory.

8. Online backup and twoway-sync(update in local repo causes change in remote repo and update in remote repo causes change in local repo) are the main features offered by github.

9. How to link to remote repo:- 
```
git remote add <repo nickname> <url>

```

10. 
