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
  <p>Orioles run in secure, isolated containers that include all of the dependencies and libraries that the application needs to run. These dependencies are defined in a **Dockerfile** that LaunchBot helps you create. If an Oriole depends on a library that’s not included in the starter templates that LaunchBot provides, it’s easy to add it to the Dockerfile to create a new image.  </p>
</div>

If you already have Docker installed, please make sure it's updated to the latest version. Then skip to Get an Atlas account.

Docker is needed to build an Oriole, and "Docker for Mac" is an easy way to get Docker up and running on your Mac. [Follow the instructions here](https://docs.docker.com/docker-for-mac/) to download and install Docker for Mac.

If you’d like to go a bit further and learn more about Docker, [the Whalesay tutorial](https://docs.docker.com/engine/getstarted/) is a gentle introduction. There’s also this [Introduction to Docker from LaunchBot](http://launchbot.io/docs/tutorial/docker-intro/) that introduces a few Docker/Dockerfile basics.


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
