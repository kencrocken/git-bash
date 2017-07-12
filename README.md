### Customize the commandline and display git branch with status.

Some functions to give some details about the current git status, including if dirty, if ahead, is thereuntracked, renamed, or deleted files, etc ...   The use of variables for colorcodes and common items allow easy customizing.  For example:

```bash
export PS1="\n\[$IBlack\]$date | $time12a\n\[\033[38;5;24m\]\u \[\033[38;5;208m\]\w\[$IWhite\]\$(parse_git_branch)\[$Color_Off\]\n🚀  
```

Mostly based on Customize BASH PS1 prompt to show current GIT repository and branch by Mike Stewart - http://MediaDoneRight.com.  

The rest is from a series of Google searches and sources I can't quite recall.  
