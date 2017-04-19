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

GitLab makes it easy to get a Git repo and add collaborators to work together on an Oriole project. We'll get you started with a template that includes a base *Dockerfile* that's appropriate for your project, and we'll invite you to create a GitLab account. You'll use HTTPS to clone your project into LaunchBot.

## Install LaunchBot

1. Use Chrome or Firefox (Safari does not render correctly).
2. Go to [launchbot.io](launchbot.io) and follow the instructions for installing. 
3. Start LaunchBot by typing `launchbot` at the command line or double clicking the icon. LaunchBot will start in your default browser (should be Chrome or Firefox).

# How to Make an Oriole with LaunchBot<a name="make_oriole"></a>

Now that all of the pieces are in place, we'll take you through the steps to start a new Oriole project.

## Cloning the Project from GitLab

1. Start Docker if it’s not already running. (When active, a whale icon will appear in your menu bar. Click on it to check Docker’s status.)
2. Start LaunchBot
3. In LaunchBot, click the **Projects** tab. Under _Your Projects_, paste the HTTPS URL from the GitLab project into the field _Clone a project from a git url_ and click `download`. The project will now appear under _Your Projects_ and a project directory will be made in `~/launchbot/<project name>`.
4. Double click the project
5. Select the branch you want to work on under _Working Branch_ (probably `authoring_branch`).
6. Click LAUNCH PROJECT
    
## Committing Your Changes Back to GitLab

After you are satisfied with the changes you have made:

1. Close jupyter notebook
2. Type in commit message
3. Click COMMIT
4. PUSH to remote repositor
5. Let your editor know that you're ready for editorial input.

# Tips for Writing the Notebook Content<a name="tips"></a> 

* The Oriole notebook should read like an article. Make sure the notebook "stands alone" with subtitles and headers, with  text referring to what the blocks do. Feel free to mention specifics in the text that you may not have time for in the video (which should be kept between 20-30 minutes).

* Find a balance between short code blocks and making sure there is output for code blocks. If the code is too long, break it into multiple blocks. 

* Be sure to *explicitly* mention when the user should click Run during recording. The user does not see you scrolling and clicking through the notebook - they respond to your audio cues.

* Keep output to a reasonable length. For rows, 3-5 should suffice. For columns, display just the ones you are talking about if not all are relevant.

* Use local data — don't pull from the internet. If including code for downloading data is important, please use an if-statement, e.g., if not exist: code to download.

* Keep datasets small and quickly executable. Create a subset and refer to the larger dataset for viewers to use on their own. Long datasets cause long execution times and confuse viewers.

* When referring to results, make sure they are repeatable time and again.

* When adding links to the text, make sure to use HTML notation rather than markdown. For example, instead of `[go to this link](http:///www.oreilly.com)` use `<a href="http://www.oreilly.com" target="_blank">go to this link</a>`—the `target="_blank"` is very important, to ensure that the link opens in a new window rather than the Oriole window.

* Import libraries into the cell where they're first needed to make it easier for the viewer to follow.

* Consider that the user may go back to re-run individual cells. For example, if you create a dataframe and decide to "clean it" by deleting a column, then the user can't re-run the cell that loaded the previous version of the dataframe without re-creating the original version first. 

* Before submitting your final version, please do a final run through in a fresh container and notebook to make sure everything really does work.

* When recording, refer specifically to "Run" cells when you are talking about them, in a way that makes them easily identifiable for cuing and for viewers.
