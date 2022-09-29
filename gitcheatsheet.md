# Git Cheatsheet

## Environment Set Up
### Setting up Authenication

[HTTPS vs SSH Protocols for Git](https://git-scm.com/book/en/v2/Git-on-the-Server-The-Protocols )
#### SSH
Preferred method is to use SSH keys instead of passwords

SSH (git@github.com: or ssh://git@github.com/)
- Uses public-key authentication
- Generate key pair and add to your Github access
- Very secure

[Documentation for setting up Github for SSH keys](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

[Free Code Camp SSH instructions](https://www.freecodecamp.org/news/git-ssh-how-to/ )

#### HTTPS

## Basic commands to make first commit
Once you create a repository in Github
```
touch README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:<username>/<project-name>.git
git push -u origin main
```


HTTPS (https://github.com/)
- Uses password authentication for pushing, and still allows anonymous pull
- You need to enter your Github password on every push

## Resources

- [Pro Git Book, PDF or ePub - free](https://git-scm.com/book/en/v2) 
- [Visualizing Git](https://git-school.github.io/visualizing-git/) 
- [Learn Git Branching](https://learngitbranching.js.org/) 
- [Microsoft VS Code - IDE](https://code.visualstudio.com) 