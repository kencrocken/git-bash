###Customize the commandline prompt.

Variables allow easy customizing and a git-aware prompt.

```export PS1="$IBlack$date @ $time12a $newLine$ICyan\u $Yellow$pathFull$IWhite\$(parse_git_branch)$IWhite $ "
```


The prompt will show the current branch and its status -- looking something like:

![image](http://)