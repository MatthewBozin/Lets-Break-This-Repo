# Steps
1. Fork this repo: press the Fork button in the top-right-hand corner of your screen
-A Fork is your own version of an existing repo.
-Changes you make to your forked version of the repo will not reflect in the original, but you can submit your changes to the original repo by making a Pull Request. More on that later.

2. Clone your fork!
-This creates a copy of this repo on your local machine.
-Use this command and replace the "YourAccountName" with your github account name: git clone https://github.com/YourAccountName/Lets-Break-This-Repo.git

3. Make some changes!
-Add files, delete files, change some things!
-You'll notice that in vscode, when you change a file its color will change to orange. This is incredibly handy to keep track of what files you have changed.

4. Add your changes to the staging area!
-Use the command: git add .
-This adds all changes you have made to the staging area.

5. Commit your changes!
-To do this, you make what's called a commit. Think of a commit as a bundle of changes.
-Commits have messages attached to them. In your commit message, you can tell other developers on your team (or your future self) what you are changing and why you're making the change.
-Use the command: git commit -m 'Your commit message here.'

6. Push your commit!
-Our repository in the cloud isn't in sync with the changes we just made, so let's change that by pushing those changes!
-The push command sends the changes we've made to the cloud.
-Use the command: git push

7. Create a pull request!
-First off, what are we doing? We're going to go into the original repo, and make a request that applies the changes we made in our forked code, to their original code.
-The name "pull request" is a bit of a misnomer. Think of it as: you are making a request for the other person to pull your changes into their repo. Weird, huh?
-Ok, let's do this!
-Navigate to the link of the main repo: https://github.com/MatthewBozin/Lets-Break-This-Repo
-Click on the "Pull Requests" tab. It will be under the repo name in github, in the tabs bar that starts with "Code"
-Github will offer you a chance to add a description to your pull request. This is a chance to tell the maintainer of the repository what your changes do, why you made changes, and why they should accept your changes!
-Submit your pull request! The repository maintainer will review your pull request and either: accept them, request a change, deny the request. Sometimes it might take a while for the maintainer to get to your pull request, so be patient!

8. Congratulations! You've made a pull request!