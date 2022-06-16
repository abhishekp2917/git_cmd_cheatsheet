## How to ignore files / folders :

- create '.gitignore' file as a child of current repo

- mention files/ folder inside '.gitignore' file that you want to ignore. This will only ignore untracked files/ folders. eg :

  - .vscode/
  - node_modules
  - config.txt
  - docs/file.txt

- add this file to staging index 

```
git add .gitignore
```

- commit the changes with appropriate commit message

```
git commit -m "<commit message>"
```
