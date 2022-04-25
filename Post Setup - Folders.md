# Post install - setting up folders

```markdown
> cd ~
> mkdir dev && cd dev
> mkdir _working && mkdir archive && mkdir testing
```

## Explaination

### _working

_working is where all the current projects go. The underscore keeps the folder at the top of the list and first to be accessed when tabbed.

### archive

All inactive projects go here

### testing

A place to pull random projects or create test projects

### Further

A `side` folder could be added for side projects but that's just for nerds

***

# Setting a global .gitignore

Stop .vscode files and other pre generated folder and files.

To add files follow the patter

> [name].[extension]  eg. `*.ts` exclude all ts files

Current .gitingore

```
.idea/*
.vscode/*
```