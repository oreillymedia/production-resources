---
layout: default
title: Oriole Guidelines and Resources
---

# O'Reilly Oriole Guidelines and Resources

Oriole is a unique new medium that blends code, data, text, and video into a narrated learning experience with executable content.

To learn more and see examples, please go <a href="http://www.oreilly.com/oriole/">here</a>. Safari members can also see the complete collection <a href="https://www.safaribooksonline.com/oriole/">here</a>.

# Author's Guide: Creating an Oriole with Atlas and LaunchBot

## Introduction

The following guide will help you get up and running with Atlas and LaunchBot. We'll help you install and set up:

* Git
* Docker
* Atlas
* LaunchBot

## Installation and Configuration

<div data-type="note">
  <p>The following instructions are for Mac. For those Windows users, we're sorry! Please reach out to us directly for help.</p>
</div>

### Make sure Git is installed

<div data-type="note">
  <h5>Why do you need Git?</h5>
  <p>An Oriole is more like software than a manuscript, and software should be managed with something like Git, which provides version control and useful tools such as branching, merging, and diffing.</p>
</div>

To check whether you have Git installed already, type `git` at the command line in a terminal window. If you see output that describes common Git commands, you have Git installed and can move on to installing Docker for Mac.

If you need help finding a terminal window and using the command line, see Appendix A.

If you need to install Git, [follow the instructions here](https://git-scm.com/book/en/v1/Getting-Started-Installing-Git#Installing-on-Mac) (and please reach out to us for help).

Once Git is installed, use `git config` to specify your email address (you'll need to use the same email address you use to log in to Atlas, which we'll discuss below). [Here are instructions.](https://help.github.com/articles/setting-your-email-in-git/) It's important that you use the same email address here as you do in Atlas, so you'll be able to push changes to the remote Atlas repository.

### Install Docker for Mac

<div data-type="note">
<h5>Why do you need Docker?</h5>
  <p>Orioles run in secure, isolated containers that include all of the dependencies and libraries that the application needs to run. These dependencies are defined in a __Dockerfile__ that LaunchBot helps you create. If an Oriole depends on a library that’s not included in the starter templates that LaunchBot provides, it’s easy to add it to the Dockerfile to create a new image.  </p>
</div>

If you already have Docker installed, please make sure it's updated to the latest version. Then skip to Get an Atlas account.

Docker is needed to build an Oriole, and "Docker for Mac" is an easy way to get Docker up and running on your Mac. [Follow the instructions here](https://docs.docker.com/docker-for-mac/) to download and install Docker for Mac.

If you’d like to go a bit further and learn more about Docker, [the Whalesay tutorial](https://docs.docker.com/engine/getstarted/) is a gentle introduction. There’s also this [Introduction to Docker from LaunchBot](http://launchbot.io/docs/tutorial/docker-intro/) that introduces a few Docker/Dockerfile basics.

### Get an Atlas account

<div data-type="note">
  <h5>Why do you need Atlas?</h5>
  <p>Well, to be honest, what you really need to use is Git. But Atlas makes it easy to get a Git repo and also makes it easy to add collaborators to work together on an Oriole project. It’s easy to clone an Atlas repo as a LaunchBot project, and you can then use Git to keep it all in sync. Don’t worry if that sounds daunting. We can help.</p>
</div>

If you're new to Atlas and don't have an account, write to toolsreq@oreilly.com, and they’ll set you up. We offer [official Atlas docs](http://docs.atlas.oreilly.com/), in case you want to dig in and learn more about Atlas (but you can also just reach out to us with your questions).

Once you’re up and running with an Atlas account, ask us to add you to the Atlas project that we've created for your Oriole.

### Configure your public SSH key in Atlas

If you've used Atlas on your current machine before, you can skip this step, as you should already be able to connect.

This can be one of the trickier parts, so it’s totally fine if you’d rather just ask for help right away. What you’re trying to do here, in a nutshell, is to form a trusted bond between Atlas and your machine, so you don’t have to continuously type in your password. Once the trust is formed, you can clone Atlas projects and work locally with Git.

We have a section of the Atlas docs that explains more about [how Git and Atlas work together](http://docs.atlas.oreilly.com/using_git.html#sshkeys), and this section also describes how to check to see if you have an existing key, how to create one if you need to, and finally how to add your key to Atlas.

If the Atlas instructions were confusing, there’s also some helpful instructions from GitHub that describe [how to generate an SSH key](https://help.github.com/articles/generating-an-ssh-key/). If you generate a new key by following the GitHub instructions, you’ll still need to add your key to Atlas, [as described here](http://docs.atlas.oreilly.com/using_git.html#sshkeys).

### Install LaunchBot

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

Sign up for launchbot at http://launchbot.io/. Use your Google email to sign up (Google sign up) and follow the directions about copy/pasting the API key.

1. Use Chrome or Firefox as the browser (Safari does not render correctly).
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

## Make an Oriole with Git, Atlas, and LaunchBot

Now that al of the pieces are in place, we'll take you through the steps to start a new Oriole project.

### 


# Writing the Notebook Content

The text in the notebook isn’t intended to mirror the voice-over in the video—it's not meant to be a transcript. The text should be brief and stand on its own in case a viewer prefers to read through text+code instead of watching the video.

## Recording the Video

The video is intended to guide a viewer as they scroll down the page and try the code examples. It isn’t a mirror of the content, but should always refer to it.

## Introduction in the Video

The introduction should include:
* a brief bio about the author (1 min)
* explain the “big picture” of what the notebook demonstrates, and give a brief outline of what the viewer should expect from the lesson (aim for 1–2 minutes)

The Introduction is the only video segment shown in full-screen width, so it becomes the main opportunity to connect with the viewer; be casual, accessible, and human.

The remainder of the video (~25 minutes) will appear in a smaller window—unless required by the lesson. Body expressions should be BIG rather than small movements, so they get noticed. Even so, keep eye contact with the camera most of the time. The author stands behind their laptop while recording the video, to refer to the context of the text+code while working through the notebook.

Code won't execute automatically as the video plays, so the author should invite viewers to run the code, and even pause the video to experiment on their own with the examples.

It’s possible to enlarge the video in an Oriole on a cue, so the author can explain something outside of the screen. Ideally this would happen on a whiteboard or a large piece of paper. Whatever gets written should be large and simple enough to be read on a small screen.

When you finish a sentence, don’t just look down at the computer. Make a point to pause and smile, breathe, especially during the intro section. We need to plan for sync’ing video with the notebook.
