---
layout: default
title: Oriole Guidelines and Resources
---

# O'Reilly Oriole and LaunchBot<a name="about_oriole"></a>

[Installation and Setup](#install)<br/>
[How to Make an Oriole with LaunchBot](#make_oriole)<br/>
[Tips for Creating a Notebook](#writing)<br/>
[Tips for Recording an Oriole](#recording)<br/>

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
2. Go to [launchbot.io](https://launchbot.io/) and follow the instructions for installing. 
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

# Tips for Writing the Notebook Content<a name="writing"></a> 

* __20-30 minutes__ The Oriole should not be longer than 30 minutes; explicit details can be put in the text. Essentially, an Oriole is the author explaining the progress of code through the notebook.

* __Write an article__ The Oriole notebook should read like an article and "stand alone" with subtitles and headers. The text refers to what the code does; feel free to mention specifics in the text that you may not have time for in the video.

* __Cell output I__ It is more interesting for the user when running the cell to see output. Find a balance between short code blocks and making sure there is output for code blocks. If the code is too long, break it into multiple blocks. 

* __Cell output II__ Keep output to a reasonable length. For rows, 3-5 should suffice. For columns, display just the ones you are talking about, if not all are relevant. 

* __Data/files must be local__ Don't pull anything from the internet. If code for downloading is important for your Oriole, please use an if-statement, e.g., if not exist: code to download.

* __Small datasets__ Keep datasets small and quickly executable. Create a subset and refer to the larger dataset for viewers to use on their own. Long datasets cause long execution times and confuse viewers.

* __Exercises__ Having exercises, or suggesting specific parameters to change in the code, is an excellent use of the Oriole format. Try to be explicit about what output/solution is expected.

* __Links__ When adding links to the text, make sure to use HTML notation rather than markdown. For example, instead of `[go to this link](http:///www.oreilly.com)` use `<a href="http://www.oreilly.com" target="_blank">go to this link</a>` The `target="_blank"` is very important, to ensure that the link opens in a new window rather than the Oriole window.

* __Math__ When formatting equations, please use a markdown editor, such as http://dillinger.io/, to check it is formatted correctly. For example, `$\Theta(n^2)$` will render correctly in the jupyter notebook, but to render correctly in the final version, it should be `$$\Theta(n^2)$$`.

* __Importing libraries__ Import libraries into the cell where they're first needed to make it easier for the viewer to follow.

* __Re-running cells__ Consider that the user may go back to re-run individual cells.

* __Final check__ Before submitting, please do a final run through in a fresh container and notebook to make sure everything really does work.


# Tips for Recording the Oriole<a name="recording"></a> 

* __Be explicit I__ Be sure to *explicitly* mention, out loud, when the user should click Run during recording. The user does not see you scrolling and clicking through the notebook - they can only respond to your audio cues.

* __Be explicit II__ When recording, refer specifically to "Run" cells when you are talking about them, in a way that makes them easily identifiable for cueing and for viewers.

* __Repeatable results__ If you refer to a specific result, make sure what you say will happen each and every time the code is executed. 

* __Exercises__ If you have exercises, tell the viewers to pause the video while they work on the exercise. Take a second or two and then continue talking (perhaps starting with a "welcome back"); this makes the final cut of the video smoother.

* __Conclusion__ Feel free to conclude your recording by thanking the audience. You do not need to add a written conclusion within the notebook.
