# CS 3035 Software Setup

## TL;DR

- We will be using IntelliJ with Java 17 (or the latest version possible)
- If at all possible, install all course software on your own computer
- All course software is free and should run on Windows, Mac and Linux
- We also use git through the version built into IntelliJ
- Alternatives are available in the lab environment

## Installing Software for your own computer

### Using lab computers?

 - Please let your instructor know if you do not have your own computer available for the course, and instead will be using the lab computers.
 - However, in general everything can be completed using the tools on the lab computers Java 17, the command line, and git, and/or other tools that you may have used in your previous courses with Java.
 - IntelliJ is the preferred tool and will be the primary one supported, but other tools can work.  
 - Unfortunately, IntelliJ does not work well in the lab environment. So, an editor and the command line would be used in the lab.

### Install IntelliJ Community Edition

- We will be using IntelliJ for writing Code, and there are a number of helpful extensions that should be installed
- [Download and Install IntelliJ Community Edition](https://www.jetbrains.com/idea/download/) - make sure it is Community Edition! Scroll down past the Ulitimate Edition.
- Once you install you will need to associate a Java Development Toolkit
- The easiest way to do this is to create a new JavaFX project and download it automatically
  - From the launch window, choose "New Project"
  - Choose "JavaFX" for the project type
  - Name the project anything you like
  - For the JDK dropdown, choose "Download JDK"
  - From the list of available JDKs choose "17.0.8 JetBrains"
  - Once it finishes downloading and opens your new project, try running it; you should get a notification that you need to download JavaFX
  - Download JavaFX when you are prompted and wait patiently, eventually, everything will be ready, and you will be able to run the project

### Install Scene Builder

- Scene Builder is a JavaFX app for building JavaFX interfaces that can be integrated into IntelliJ
- The easiest way to do this is to create a new JavaFX project and download it automatically
  - From the launch window choose "New Project"
  - Choose "JavaFX" for the project type
  - Name the project anything you like
  - Find and open the hello-view.fxml file, which is found under the resources folder
  - At the bottom of the editor window click the "SceneBuilder" tab
  - Click the "Download Scene Builder Kit" link, and wait a few moments while it installs.

Alternatively, if this does not work:
 - SceneBuilder can be downloaded separately [https://gluonhq.com/products/scene-builder/]
 -SceneBuilder is also pre-installed in the labs

## Git

There is a lot of software available to assist in working with Git. Our use should be relatively straightforward and so the version built into IntelliJ will be the one that is supported for the course. See [Using Git in CS 3035](pages/../CS3035-assignments-with-git.md)
