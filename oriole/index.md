---
layout: default
title: Oriole Guidelines and Resources
---

# O'Reilly Oriole and LaunchBot<a name="about_oriole"></a>

[Installation and Setup](#install)<br/>
[How to Make an Oriole with LaunchBot](#make_oriole)<br/>
[Tips for Creating a Notebook](#tips)

Oriole is a unique new medium that blends code, data, text, and video into a narrated learning experience with executable content. You can <a href="http://www.oreilly.com/oriole/">see a few examples here</a>, or take a look at the <a href="https://www.safaribooksonline.com/oriole/">complete collection on Safari</a>.

LaunchBot helps you discover, build, and run Docker-enabled content, such as Jupyter Notebooks and Orioles. It provides a desktop GUI in place of many of the complex command-line process for installing and running applications. Think of LaunchBot as the place authors and editors will work together to create compelling text and runnable code, and as a tool that will help production ensure that all of the dependencies are captured in the *Dockerfile* so that the Oriole or notebook will run as expected.

You can [learn more about LaunchBot here](http://launchbot.io/docs/). 

# Installation and Setup<a name="install"></a>

## Make Sure Git Is Installed

To check whether you have Git installed already, type `git` at the command line in a terminal window. If you see output that describes common Git commands, you have Git installed.

Use `git config` to specify your email address (you'll need to use the same email address you use to log in to GitLab, which we'll discuss below). [Here are instructions.](https://help.github.com/articles/setting-your-email-in-git/) It's important that you use the same email address here as you do in GitLab, so you'll be able to push changes to the remote GitLab repository.

## Install Docker for Mac

If you already have Docker installed, please make sure it's updated to the latest version.

Docker is needed to build an Oriole, and "Docker for Mac" is an easy way to get Docker up and running on your Mac. [Follow the instructions here](https://docs.docker.com/docker-for-mac/) to download and install Docker for Mac.

## Get a GitLab Account and Access to the Oriole Project 

GitLab makes it easy to get a Git repo and add collaborators to work together on an Oriole project. We'll get you started with a template that includes a base *Dockerfile* that's appropriate for your project, and we'll invite you to create a GitLab account. You'll be able to use HTTPS (preferred) or SSH to clone your project into LaunchBot.

## Install LaunchBot

1. Use Chrome or Firefox (Safari does not render correctly).
2. Download the [latest release of LaunchBot](https://dl.equinox.io/oreillymedia/launchbot/stable) and follow the instructions for installing. Prefix with `sudo` if the error message “Permission denied” is returned for the `unzip` command.
3. Sign up for a LaunchBot account at http://launchbot.io/. “Google sign up” is the easiest. If you decide to manually enter an email and password, you will need to verify your email (you'll receive a verification email) and then refresh the LaunchBot page to sign in.
5. Start LaunchBot by typing `launchbot` at the command line. LaunchBot will start in your default browser (should be Chrome or Firefox).
6. The configuration page is found by clicking on the gear icon in the upper right section of the toolbar. You can [check your settings here](http://oreillymedia.github.io/production-resources/oriole/launchbot-settings).

# How to Make an Oriole with LaunchBot<a name="make_oriole"></a>

Now that all of the pieces are in place, we'll take you through the steps to start a new Oriole project.

## Cloning the Project from GitLab

1. Start Docker if it’s not already running. (When active, a whale icon will appear in your menu bar. Click on it to check Docker’s status.)
2. At the command line type `launchbot` at the terminal prompt, and LaunchBot will open in your default browser (we recommend Chrome or Firefox—don't use Safari).
3. In LaunchBot, on the _Search_ page, paste the HTTPS URL from the GitLab project into the field labeled _clone an external project_ and click `download`. The project will now appear under the _Projects_ page and a project directory will be made in `~/launchbot/<project name>`.
6. Exit LaunchBot (close the browser window) and return to the command line. You now need to switch to the `authoring branch` to do your work.
    1. `cd ~/launchbot/<project name>`<br/>Change into the project directory.
    2. `git branch -r`<br/>Lists all available remote branches.
    3. `git branch`<br/>Lists all available local branches. You should see an asterisk next to Master.
    4. `git checkout authoring_branch`<br/>Moves you to the authoring branch, where you'll do your work.
    5. `git branch`<br/>You should now see an asterisk next to `authoring_branch`.
    5. `launchbot`<br/>Start LaunchBot again
7. In LaunchBot, highlight the project and click _LAUNCH_
    1. Once launched (it might take a while to launch the first time), options will appear under a _Services_ tab. Most likely, this will say “Open Notebook”. Click it.
    2. A window will open in your browser with the directory tree. Navigate to the notebook and open it. Any changes you make will be saved to your local repository.
    3. When you are done with edits, click `Command+S` to save any changes you made.
    4. Go back to the _Projects_ page and click “Stop”.
    5. Exit out of LaunchBot by closing the browser window.
    6. You can now commit the changes back to the GitLab repo, so others can see your work.
    
## Committing Your Changes Back to GitLab

On the command line:

1. `cd ~/launchbot/<project name>`
2. `git status`<br/>This command will list the files you changed
3. `git add <filename>`<br/>Identifies the files you want to push to the GitLab repo
4. `git commit -m "message"`<br/>Adds a message of what this commit contains
5. `git push origin authoring_branch`<br/>Moves the changes to the remote GitLab repo 
6. Let your editor know that you're ready for editorial input.

# Tips for Writing the Notebook Content<a name="tips"></a>

* Import libraries into the cell where they're first needed to make it easier for the customer to follow. 

* Try to condense cells so that each “Run” produces output. 

* Use local data—don't pull from the internet. If including code for downloading data is important, please use an if-statement, e.g., if not exist: code to download.

* Do not interactively save and load data. The customer does not have write permissions.

* When adding links to the text, make sure to use HTML notation rather than markdown. For example, instead of `[go to this link](http:///www.oreilly.com)` use `<a href="http://www.oreilly.com" target="_blank">go to this link</a>`—the `target="_blank"` is very important, to ensure that the link opens in a new window rather than the Oriole window.

* Before submitting your final version, please do a final run through in a fresh container and notebook to make sure everything really does work.


* During the video shoot, please be sure to refer to the cell that the reader should run at that moment.
