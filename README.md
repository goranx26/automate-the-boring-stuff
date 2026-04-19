# automate-the-boring-stuff
Lab files from the book Automate the boring stuff with Python
https://automatetheboringstuff.com

VS Code has a built-in Git panel (the branch icon in the left sidebar). Your loop will be:

Write some code in your chapter folder
Save the file (Ctrl+S)
Open the Source Control panel (Ctrl+Shift+G)
You'll see your changed files listed — click + to stage them
Type a short commit message like ch01: add hello world exercise
Click the ✓ Commit button
Click Sync (or the cloud icon) to push to GitHub


A few good habits to build early

Commit often — after each exercise, not just at the end of a chapter. Small commits are easier to understand later.
Write meaningful commit messages — ch03: add function exercise for coin flip beats update.
Don't commit broken code (or if you do, note it in the message: wip: debugging the loop).
Use the integrated terminal in VS Code (Ctrl+``  ``) — you can also run git status, git log, etc. there, which is great for learning the underlying commands.

Bonus: Learn the terminal commands too
Even though VS Code's GUI is convenient, it's worth knowing the basics. In the terminal:
bashgit status          # see what's changed
git add .           # stage all changes
git commit -m "msg" # commit with a message
git push            # push to GitHub
git log --oneline   # see your commit history
This way you understand what VS Code is doing under the hood, which will help a lot as you grow.