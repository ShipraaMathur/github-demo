## Clone Repository

```git clone https://github.com/ShipraaMathur/github-demo.git```

## To stage files

To stage particular file 
```git add <filename>```

To stage all files
```git add .```

To create and switch to new branch

```git checkout -b <name>/<feature>```

To switch to new branch 
``` git checkout <branch-name>```

To install requirements:
```pip install -r requirements.txt ```

## Other useful commands:

1. To check which files are staged for commit/push: `git status`

2. To check which branch you are on: `git branch`

3. To pull latest changes from any branch:

```git checkout <branch-name> && git pull```

Note: Usually switch to `main` branch and pull latest changes from there and then create a new branch.

4. To commit your staged changes: `git commit -m "description of changes in one line"`

5. To push changes to your branch: `git push origin <branch-name>`