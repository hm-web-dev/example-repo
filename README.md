# Git worksheet 

This repo allows you to: 
- Use Git to version control their files
- Use Github to host their Git repositories

## Basic Commands
Git is a version control system that you can use to manage your files. Watch for the bolded words: the vocabulary is slightly different from the previous Version Control worksheet! Git keeps track of the contents of a *single folder*, which is called a **repository**. 

Using your terminal, make an empty folder on your desktop named GitSandbox. Then, move to that folder and type in the following command: `git init`
What happens?

Now put some files (any files) into GitSandbox. Type the command: `git status`
What do you see?

`git add <specific file name>`
`git add .`	*(add entire repository to the stage)*
In Git, changes must be staged before they are allowed to be committed. You can add specific files to the stage, or the entire repository. 
Why might this intermediate staging be useful?

Add the entire repository, and then commit via this terminal command: (replace the message with something appropriate)
`git commit -m “Made new file”`
What feedback do you get from the terminal afterward?

Put some more files into GitSandbox, then add and commit with a different message. Afterward, type in the following command: `git log`
What do you see? (You can press q to quit.)
	
While staging is necessary, it is often excluded from timeline diagrams, since everything on the stage will end up in the next commit. 

## Try a git push for yourself
In the “Basic Commands”  section of this exercise, you made a new git commit. We’ll commit that to a new git repository you made. You can set this folder to pull and push changes `git remote add origin <ssh url> `
1. What do you see when you write the command `git remote -v`?
2. What is `origin`? Could you add another repo with a different name than origin? 
3. When would it be helpful to  push to multiple repositories? 

Now, you can push your changes to the repo for all to see with `git push --set-upstream origin main`

From now on, you can push changes with just `git push` changes. 