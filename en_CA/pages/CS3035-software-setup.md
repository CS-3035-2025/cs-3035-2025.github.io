# CS 3035 Software Setup

## TL;DR

- All course software is free and should run on Windows, Mac, and Linux, as well as personal or lab computers.
- We will develop in Visual Studio Code and deploy to a Chrome/Chromium web browser
- Your web browser will act as an operating system for the interfaces.
- We also use Git, largely through integration within VS Code.
- We will be using the Simplekit interface toolkit, which relies on Typescript, HTML, & CSS.

## Software Accounts and Downloads

### Using lab computers?

- You are free to use either your own computer or the lab computers for the activities and projects.
- If you are using the lab computers, Git, VS Code, Chrome, and Node.js/NPM are already installed and ready to use.

### Visual Studio Code

- We will be using Microsoft's **Visual Studio Code** text editor to write all our code and manage our repos and codebases.
- VS Code is a lightweight but powerful source code editor that runs on your computer and is available for Windows, Mac, and Linux.
- Also, it has a huge library of extensions to help with everything from formatting and running code to integrating with other apps and services.
- _Note_: **Visual Studio Code** and **Visual Studio** are _totally_ different programs.

- [Download and Install Visual Studio Code](https://code.visualstudio.com/download)

### Git and GitHub

- Git is a version control software that allows us to track and manage changes to our code over time.
- GitHub is a service that stores, manages, and distributes Git Repos.
- These tools can be complex, and while there is a lot of software available to assist in working with Git, our use should be relatively straightforward and used largely within VS Code.
- For now, you'll need to make sure you have [Git Installed](https://git-scm.com/downloads) and a [GitHub account created](https://github.com/).
- For more information and for details on how we'll use Git throughout the course, see [Using Git in CS 3035](pages/../CS3035-assignments-with-git.md)

### Chrome / Chromium

- Different browsers are built with different Javascript and Rendering Engines, which, at times, can cause the presentation of your code to vary quite drastically from browser to browser.
- To maintain consistency, the course will only use [Google Chrome](https://www.google.com/chrome/) _(Or if you'd rather avoid the Google ecosystem, its open-source sibling [Chromium](https://chromium.woolyss.com/download/en/#windows))_ which uses the V8 Javascript engine and Blink Rendering Engine.
- All activities and projects will _only_ be graded in Chrome.

### HTML, CSS, & Javascript/Typescript

- **HTML** (Hypertext Markup Language) is the standard markup language for apps and pages displayed in a web browser. It defines the core makeup and structure of web content.
- **CSS** (Cascading Style Sheets) is a style sheet language which is used alongside HTML in the browser. It defines the styles and presentation of the content.
- **Javascript** is a high-level programming language that is embedded into HTML. It defines the logic, behaviour and functionality of the content.
- **Typescript** is a recent(ish) superset of javascript. It brings static types and type annotations (and more) to Javascript.
- Luckily, none of these languages need to be installed and can be written natively in VS Code.
- However, there are VS Code extensions available that can provide syntax highlighting, error checking, formatting, and other features that can make development quicker and easier.

### Node.js and NPM

- Node.js is a Javascript runtime engine that lets developers use JavaScript to make tools for server-side scripting. It is often used to generate dynamic web page content before the page is sent to the user's web browser.
- While we won't write or use Node.js directly in this course, we will use NPM, the Node Package Manager.
- NPM is a library and registry for JavaScript packages that is used and installed alongside Node.js.
- [Download and Install Node.js and NPM](https://nodejs.org/en)

### Simplekit

- Simple Kit is a simple user interface toolkit for building UI architecture.
- It's used to create UI elements in the browser and designed to be quite minimal to highlight UI architecture.
- Uses HTML, CSS, Typescript, and NPM packages like Vite to provide a simple and creative way to explore UI design and structure.
- We'll go through installing and using Simple Kit as a Git Submodule in class, or see [Using Git in CS 3035](pages/../CS3035-assignments-with-git.md)
