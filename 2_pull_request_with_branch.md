(WORK IN PROGRESS)

# Steps
1. Fork this repo: press the Fork button in the top-right-hand corner of your screen
-A Fork is your own version of an existing repo.
-Changes you make to your forked version of the repo will not reflect in the original, but you can submit your changes to the original repo by making a Pull Request. More on that later.

2. Clone your fork!
-This creates a copy of this repo on your local machine.
-Use this command and replace the "YourAccountName" with your github account name: git clone https://github.com/YourAccountName/Lets-Break-This-Repo.git

3. Make a branch!
-Think of branches as alternate timelines for your code. If you mess up horribly in a branch, you can always switch back into main and forget it ever happened, heh.
-Use the commend (replace my-branch with whatever you want your branch to be named): git branch my-branch

4. Switch to your branch!
-Use the command (replace my-branch with whatever you named your branch): git checkout my-branch

5. Make some changes!
-Add files, delete files, change some things!
-You'll notice that in vscode, when you change a file its color will change to orange. This is incredibly handy to keep track of what files you have changed.

6. Add your changes to the staging area!
-Use the command: git add .
-This adds all changes you have made to the staging area.

7. Commit your changes!
-To do this, you make what's called a commit. Think of a commit as a bundle of changes.
-Commits have messages attached to them. In your commit message, you can tell other developers on your team (or your future self) what you are changing and why you're making the change.
-Use the command: git commit -m 'Your commit message here.'

8. Push your commit!
-Our repository in the cloud isn't in sync with the changes we just made, so let's change that by pushing those changes!
-The push command sends the changes we've made to the cloud.
-Use the command: git push
-Aaaaand we got got! Git just gave us an error message saying the following: 
"fatal: The current branch has no upstream branch.
To push the current branch and set the remote as upstream, use
git push --set-upstream origin new-branch"
-Why do we get this error? It's because we made a new branch on our local repo, but the cloud doesn't have that branch yet! So when we pushed our changes, the cloud didn't know where to put them.
-Luckily git gives us the solution to fix this error. Run the command (replace my-branch with your branch name): git push --set-upstream origin my-branch
-This lets the cloud repo know to create a new branch, and then update it with our changes.

9. Merge your branch with the main branch!
-If we're satisfied with the code on our branch, then it's time to update our main branch code to reflect the changes we made in the branch.
-We do this by making a pull request.
-The name "pull request" is a bit of a misnomer. Think of it as: you are making a request for the other person to pull your changes into their repo. Though in this case, since you're doing a pull request into your own fork, you are going to be playing both parties in this request.
-To do this, find the "Pull Requests" tab. It will be under the repo name in github, in the tabs bar that starts with "Code"
-Click the button that says "New Pull Request"
-Github will prompt you to select which branches. Make sure the branch you're pulling into is main, and the branch you're pulling out of is my-branch.