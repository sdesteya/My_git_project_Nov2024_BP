# Commands lis

- `git init`: initialize a new repository
- `git add`: adding in the staging area to monitor and keep track off (any changes, not only new files)
- `git commit -m "MEANINFUL MSG"` : Saving a point in the timeline with a message that describes (Why, How, Effects and Limitations)

- `git config --global --list` : list all your configs
- `git config --global user.name "My name"` : To have your name in the config
- `git config --global user.email "my_email@vib.be"`: to have my email in the config

- g`it mv old.file.txt new.file.txt` : when changin a name so git knows is the same file. You stil lneed to commit this change.

- `git status`: Check which files are inthe dev area, staging area or are untracked.
- `git mv old_file.md new_file.md`
- `git log`: prints the history of commits
    `git log -n no` : to limit the number of listed commits 
    `git log --abbrev-commit` : to get a shorter unique ID

To compare commit changes
- `git diff HEAD <ID>` | `git diff HEAD~Number` (HEAD~1)
- `git show HEAD <ID> `

- `git remote add origin ssh-adress` : stablish the bridge between the local and the remote
- `git push` : transfers everything that has been commited 
- `git pull` : transfers any updates commited remotely 

Routina Local 2 Remote

```
git stauts
git add <file>
git commit -m "meaninful msg"
git push
```

