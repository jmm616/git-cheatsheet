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

HTTPS (https://github.com/)
- Uses password authentication for pushing, and still allows anonymous pull
- You need to enter your Github password on every push
