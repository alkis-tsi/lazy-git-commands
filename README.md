# lazy-git-commands
I wanted to create some commands as I want to type less when executing commands via the CLI. Yes I can use a GUI, but I prefer CLI a bit more some times.

### Usage
Those are executable bash scripts. You can either add them on your local bin and execute as commands:

```
mv gitcommit /usr/local/bin
mv gitpush /usr/local/bin
```

### gitcommit
Will simply ask for your commit message and execute using the parameters:
-a, add file contents to the index  
-m, commit message to follow

### gitpush
Will grab the current branch you are working on and will push to that using it as origin
