# Demo 2: This repository came from not GitHub

A line of text. To properly initialize a folder to become a repository:

git init - This command will initialize an empy Git repository in the file location of where you currently are
- EX: "git init
Initialized empty Git repository in /Users/ME/Desktop/code/My-local-repo/.git/"

You'll find that you actually recevie an error. Since we've created the repository locally, there isn't the connection between GitHub and Git. We need to make this conneciton to do this...

1. Create an empty Git repository on GitHub
- Make a new repository w/ the same name as your local repository and copy the SSH
- Type "git remote add "origin SSH
  - Typing "git remote -v" will tell you all the remote repositories connected to that current repo
- Now you can use git push as normal
  - Use "git push -u ..." to set the default path so you only need to type "git push"

Sometimes I need to use the command "git push origin master" and sometimes I need to use "git push origin main". I can never tell which I need

## Local Development

1. Open index.html in your browser