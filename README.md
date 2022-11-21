## Git Basic Commands

Cloning source code from repository
```
git clone https://github.com/EagleVector/aiops_project.git
```

Checking the status of files.
```
git status
```

Tracking the file or Staging it
```
git add <file_name> 
git add .
```

To remove file from the staging area
```
git rm --cached <file_name>
```

Commiting the staged file with the message
```
git commit -m "meaasage"
```

Adding developer credentials
```
git config --global user.name <name>
git config --global user.email <email>
```

Rename the current branch
```
git branch -M <branch_name>
```

To list the branch name
```
git branch
```
To check remote branch URL and variable name
```
git remote -v
```

Pushing the files to the repository
```
git push <remote_branch_variable> <branch_name>
```

## Setting up the Conda Environment

To create a Conda environment in the same project directory
```
conda create --prefix ./<env_name> python=<python_version> -y
```

To activate the Conda environment
```
conda activate <env_name>
```
