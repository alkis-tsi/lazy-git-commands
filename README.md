# lazy-git-commands
I wanted to create some commands as I want to type less when executing commands via the CLI. Yes I can use a GUI, but I prefer CLI a bit more some times.

### Usage
Those are bash scripts. Convert them into executables first and then you can either add them on your local bin and execute as commands:

```
chmod a+x gitcommit
chmod a+x gitpush
mv gitcommit /usr/local/bin
mv gitpush /usr/local/bin
```

### gitcommit
Will simply ask for your commit message, then it will add any new files and commit with the typed message.

### gitpush
Will grab the current branch you are working on and will push to that using it as origin.
