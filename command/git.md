# Git

## Configuration
### Setting up name and email
Check your name and email

```
git config user.name && git config user.email
```

Set globally your name and email

```
git config --global user.name <your name>
```
```
git config --global user.email <your email>
```

Set your name and email locally (to be launched in the project folder)
```
git config user.name <your name>
```
```
git config user.email <your email>
```
Or you can simply edit the `.git\config` file

### Setting up main branch
By default git initializes new repository with the main branch called `master`. To set up another name
```
git config --global init.defaultBranch main
```
This configuration variable only affects new repositories, and does not cause branches in existing projects to be renamed.

### Remote branch

```
git remote add origin https://github.com/<name>/<repo>.git
```

Git push with option `-u` sets Github as the *upstream repository*, it means that by runnign  `git pull` you will be able to download all changes automatically

```
git push -u origin main
```