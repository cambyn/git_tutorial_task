If you don't have git on your machine, [install it]( https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the *copy to clipboard* icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```
where "url you just copied" (without the quote marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

For example:
```
git clone https://github.com/this-is-you/git_tutorial_task.git
```
where `this-is-you` is your GitHub username. Here you're copying the contents of the git_tutorial_task repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd git_tutorial_task
```
Now create a branch using the `git checkout` command:
```
git checkout -b <your-name>
```

For example:
```
git checkout -b mitanshiK
```
(The purpose of this branch is to recognize your contribution.)

## Add your Text File and commit the change

Create a new text file in textfiles folder.


If you go to the project directory and execute the command `git status`, you'll see there are changes.


Add those changes to the branch you just created using the `git add` command:

```
git add .
```
or<br/>

```
git add filename

```

Now commit those changes using the `git commit` command:
```
git commit -m "<your-name> submitting the task"
```
replacing `<your-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:
```
git push -u origin <your-name>
```
replacing `<add-your-new-branch-name-with-your-name>` with the name of the branch you created earlier.

For example:
```
git push -u origin mitanshiK
```

## Submit the task

If you go to your repository on GitHub, you'll see a  `Compare & pull request` button. Click on that button.

Now submit the pull request.

