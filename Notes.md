# Some important pointers for git and github

1. Git tracks not the files but the changes made to them.So, multiple versions of files may exist in the working and changing area.

2. Every text editor provides a git integration which simplifies the gigitty tasks with buttons which replace the commands.

3. If we do a git log, we are met with a string of aplhanumeric characters which is known as a commit hash. We may use the commit hash to uniquely identify the version of our code that we want to revert back to.
 
4. Once revereted to a previous version of our file, we are only able to see the commits made upto that version and not the whole list of commits. To view all the commit/versions of the file we shall do ``git log --all``.

5. Aliases can be used to create short hands for frequently used commands. (note: you have set up s-->status and cm-->commit)

6. you may create a .gitignore file create a list of files to be ignored by git during repo commiting (note: the ignored files may include password files, sensitive text files etc)

7. ``rm -rf .git`` deletes .git file from our directory which causes our folder to become a non-repo directory.

8. Online backup and twoway-sync(update in local repo causes change in remote repo and update in remote repo causes change in local repo) are the main features offered by github.

9. How to link to remote repo:- 
```git remote add <repo nickname> <url>
```

10. when we link a remote repo to our local repo, a remote tracking branch ``Origin/master`` is created in our local repo which might be same as the local master if no newer commits in the local repo have been made.if local repo has been updated and the global repo hasnt been pushed with the update then the two master branches may go out of sync which is fixed once the updated local repo has been pushed.

11. We may set an upstream branch to avoid writing the name of branch topush from everytime we push to the remote repo.After setting the upstream branch we may just write ``git push`` to push to the remote repo.

12. ``-f`` this flag may be implemented to force our way through to overwrite a commit with amend in the remote repo.
(Imagine you have made a commit `cm1` and pushed it remotely and then you decided to *amend* the `cm1` inlocal repo and again pushed it to the remote repo. Here github doesnt allow this *remote amend over *`cm1` to occur as it is considered bad practice. You may oopt to use the `-f` flag to push past this prompt and push the *remote amend* too)

13. ## Some Important commands 
- Move into a directory named repo:-
```bash
cd repo
```
- Move into a subdirectory named src:
```bash
cd src
```
- Move back to the parent directory (repo):
```bash
cd ..
```
- Check your current directory:
```bash
pwd
```
