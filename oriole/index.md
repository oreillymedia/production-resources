---
layout: default
title: Oriole Guidelines and Resources
---

# O'Reilly Oriole Author Guide to Working with Atlas and LaunchBot

Oriole is a unique new medium that blends code, data, text, and video into a narrated learning experience with executable content.

To learn more and see examples, please go <a href="http://www.oreilly.com/oriole/">here</a>. Safari members can also see the complete collection <a href="https://www.safaribooksonline.com/oriole/">here</a>.

## Installation and Configuration

<div data-type="note">
  <p>The following instructions are for Mac. For those Windows users, we're sorry! Please reach out to us directly for help.</p>
</div>

## Make sure Git is installed

<div data-type="note">
  <h5>Why do you need Git?</h5>
  <p>An Oriole is more like software than a manuscript, and Git provides version control and useful tools such as branching, merging, and diffing.</p>
</div>

To check whether you have Git installed already, type `git` at the command line in a terminal window. If you see output that describes common Git commands, you have Git installed and can move on to Installing Docker for Mac.

Once Git is installed, use `git config` to specify your email address (you'll need to use the same email address you use to log in to Atlas, which we'll discuss below). [Here are instructions.](https://help.github.com/articles/setting-your-email-in-git/) It's important that you use the same email address here as you do in Atlas, so you'll be able to push changes to the remote Atlas repository.

## Install Docker for Mac

<div data-type="note">
<h5>Why do you need Docker?</h5>
  <p>Orioles run in secure, isolated containers that include all of the dependencies and libraries that the application needs to run. These dependencies are defined in a __Dockerfile__ that LaunchBot helps you create.</p>
</div>

If you already have Docker installed, please make sure it's updated to the latest version. Then skip to Get an Atlas account.

Docker is needed to build an Oriole, and "Docker for Mac" is an easy way to get Docker up and running on your Mac. [Follow the instructions here](https://docs.docker.com/docker-for-mac/) to download and install Docker for Mac.

## Get a GitLab Account and Access to the Oriole Project 

<div data-type="note">
  <h5>Why do you need GitLab?</h5>
  <p>GitLab makes it easy to get a Git repo and also makes it easy to add collaborators to work together on an Oriole project. We'll also get you started with a template that includes a base __Dockerfile__ that's appropriate for your project.</p>
</div>

We'll prepare a repo with a starter Oriole template and send you an invitation join the GitLab project. You'll be able to use HTTPS (preferred) or SSH to clone your project into LaunchBot.

## Install LaunchBot

<div data-type="note">
  <h5>Why do I need to use LaunchBot?</h5>
  <p>LaunchBot helps you discover, build, and run Docker-enabled content, such as Jupyter Notebooks and Orioles. It provides a desktop GUI in place of the complex command-line process for installing and running applications. Think of LaunchBot as the place authors and editors will work together to create compelling text and runnable code, and as a tool that will help production ensure that all of the dependencies are captured in the Dockerfile so that the Oriole or notebook will run as expected.
</p>
</div>

Check out these “Getting Started” materials to learn more about LaunchBot and Oriole: 

* [LaunchBot Overview](http://launchbot.io/docs/overview/)
* [Benefits of Using LaunchBot](http://launchbot.io/docs/tutorial/benefits/)
* [Getting Started](http://launchbot.io/docs/tutorial/getting-started/)
* [Publishing Your Content](http://launchbot.io/docs/tutorial/publishing-content-to-launchbot/)
* [A Brief Introduction to Docker](http://launchbot.io/docs/tutorial/docker-intro/)
* [Creating an Oriole in LaunchBot](https://www.youtube.com/watch?v=WJMUkHzAFsg&feature=youtu.be)

1. Use Chrome or Firefox (Safari does not render correctly).
2. Sign up for a LaunchBot account at http://launchbot.io/. “Google sign up” is the easiest. If you decide to manually enter an email and password, you will need to verify your email (you'll receive a verification email) and then refresh the LaunchBot page to sign in.
3. Click “Download the latest release”.
4. Install via the command line. Prefix with `sudo` if the error message “Permission denied” is returned for the `unzip` command.
5. Start LaunchBot by typing `launchbot` at the command line. LaunchBot will start in your default browser (should be Chrome or Firefox).
6. The configuration page is found by clicking on the gear icon in the upper right section of the toolbar. Please check that autofill filled correctly.
   * *Launchbot Host:*<br/>Check that it is http://launchbot.io
   * *API Key:*<br/>Autofilled. You get a key when you sign up. It's on the launchbot.io page under Dashboard -> Profile. Copy/paste it here if not autofilled.
   * *Project Directory:*<br/>This is where LaunchBot will save local copies of projects, using Git. The default location is: `/Users/<your username>/launchbot`
   * *Path to Docker Executable directory:*<br/>Path to where Docker lives on your machine. The default is: `/usr/local/bin`
   * *Path to Git executable directory:*<br/>Use `which git` to find. Enter without the `git` ending. The default is: `/usr/bin/`
   * *Docker Host:*<br/>Autofilled. Should be: `unix:///var/run/docker.sock`
   * *Host IP Address*<br/>Autofilled. Should be: `0.0.0.0`
   * *CA Certificate:*<br/>Leave empty
   * *Certificate:*<br/>Leave empty
   * *Key:*<br/>Leave empty

# How to Make an Oriole with LaunchBot

Now that all of the pieces are in place, we'll take you through the steps to start a new Oriole project.

## Coning the project from GitLab

1. Start Docker if it’s not already running. (When active, a whale icon will appear in your menu bar. Click on it to check Docker’s status.)
2. At the command line type `launchbot` at the terminal prompt, and LaunchBot will open in your default browser (we recommend Chrome or Firefox—don't use Safari).
3. In LaunchBot, on the _Search_ page, paste the HTTPS URL from the GitLab project into the field labeled _clone an external project_ and click `download`. The project will now appear under the _Projects_ page and a project directory will be made in `~/launchbot/<project name>`.
6. Exit LaunchBot (close the browser window) and return to the command line. You now need to switch to the `authoring branch` to do your work.
    1. `cd ~/launchbot/<project name>`<br/>Change into the project directory.
    2. `git branch -r`<br/>Lists all available remote branches.
    3. `git branch`<br/>Lists all available local branches. You should see an asterisk next to Master.
    4. `git checkout authoring_branch`<br/>Moves you to the authoring branch, where you'll do your work.
    5. `git branch`<br/>You should now see an asterisk next to `authoring_branch`.
    5. `launchbot`<br/>Start launchbot again
7. In LaunchBot, highlight the project and click _LAUNCH_
    1. Once launched (it might take a while to launch the first time), options will appear under a _Services_ tab. Most likely, this will say “Open Notebook”. Click it.
    2. A window will open in your browser with the directory tree. Navigate to the notebook and open it. Any changes you make will be saved to your local repository.
    3. When you are done with edits, click `Command+S` to save any changes you made.
    4. Go back to the _Projects_ page and click “Stop”.
    5. Exit out of LaunchBot by closing the browser window.
    6. You can now commit the changes back to the GitLab repo, so others can see your work.
    
## Committing Your Changes back to GitLab

On the command line:

1. `cd ~/launchbot/<project name>`
2. `git status`<br/>This command will list the files you changed
3. `git add <filename>`<br/>Identifies the files you want to push to the GitLab repo
4. `git commit -m "message"`<br/>Adds a message of what this commit contains
5. `git push origin authoring_branch`<br/>Moves the changes to the remote GitLab repo 
6. Let your editor know that you're ready for editorial input.

# Tips for Writing the Notebook Content

* Import libraries into the cell where they're needed rather than including an all-inclusive import cell at the beginning of the notebook. This makes it easier for your audience to follow.
* Try to condense cells so that each “Run” produces output. 
* Refer to the cell that the reader should run at that moment.
* Use local data—don't pull from the internet. You can program as an if-statement if you want code there for downloading, e.g., if not exist: download code.
* Before submitting your final version, please do a final run through in a fresh container and notebook to make sure everything really does work.
* When adding links to the text, make sure to use HTML notation rather than markdown. For example, instead of `[go to this link](http:///www.oreilly.com)` use `<a href="http://www.oreilly.com" target="_blank">go to this link</a>`—the `target="_blank"` is very important, to ensure that the link opens in a new window rather than the Oriole window.
