# Change your commits info
When the commits does not reflect who made them.

- When you use lots of environments and sometimes you commit the wrong email or nickname.
- Oh crap the repo have about 50 of your commits.
- Don't worry it happens to me everytimes !

The commit date or sha1 are not altered only the name and email of the author in the current branch. So don't worry that would not screw your logs.

-----------------

### HOW-TO
Just add your infos in ```change.sh``` and run it. If you want to only change mail or nickname. Change only the new variable that will be enough.

If you plan to change your infos on github you obviously need to work on an unprotected branch (log rewrite allowed) and disable the mail in commit protection in your settings. Just do a ```git push origin <branch> --force-with-lease``` your commits would be updated.
