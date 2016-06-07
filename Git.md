# Git

## show config
```sh
git config --list
```

## config user.name
```sh
git config --global user.name "happy2discover"
```

## config user.email
```sh
git config --global user.email happy2discover@gmail.com
```

## config excludesfile
```sh
git config --global core.excludesfile ~/.gitignore_global
```
### contents of ".gitignore_global"

>  # .gitignore_global  
>  ################################  
>  ######## OS generated files ########  
>  ################################  
>  .DS_Store`  

## what is ".gitkeep"?
Preserve the current folder only in a repository, always with the use of ".gitignore".

## how to resolve "fatal: remote origin already exists."?
```sh
git remote rm origin
git remote add origin https://github.com/happy2discover/notes.git
```

## how to commit code?
```sh
git add
git commit
git push
```

## how to show the differences of a file("app.js") between local and remote?
```sh
git diff app.js
```

## fatal: filename too long
```sh
git config --global core.longpaths true
```
