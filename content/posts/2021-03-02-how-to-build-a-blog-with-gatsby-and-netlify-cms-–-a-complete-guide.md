---
layout: blog
title: How to Build a Blog with Gatsby and Netlify CMS – A Complete Guide
date: 2021-03-02T22:40:29.097Z
thumbnail: /images/uploads/5wdv8rm5ai0mb6qfcetq.jpg
---
## **In this article, we are going to build a blog with Gatsby and [Netlify CMS.](https://www.netlifycms.org/) You will learn how to install Gatsby on your computer and use it to quickly develop a super fast blog site.**

### You are also going to learn how to add Netlify CMS to your site by creating and configuring files, then connecting the CMS to your site through user authentication.

### The main benefit of Netlify CMS is you don't have to create markdown files every time you want to write a post. This is useful for content writers who don't want to deal with code, text editors, repositories, and anything to do with tech - they can just focus on writing articles.

## How to set up the environment

### Before we can build Gatsby sites, we have to make sure that we have installed all the right software required for the blog.



### Install Node.js

Node.js is an environment that can run JavaScript code outside of a web browser.

It is a tool that allows you to write backend server code instead of using other programming languages such as Python, Java, or PHP. Gatsby is built with Node.js and that's why we need to install it on our computer.

To install Node.js, go to the [download page](https://nodejs.org/en/download/) and download it based on your operating system.

When you are done following the installation prompts, open the terminal and run `node -v` to check if it was installed correctly. Currently, the version should be 12.18.4 and above.



### Install Git

Git is a free and open-source distributed version control system that helps you manage your coding projects efficiently.

Gatsby starter uses Git to download and install its required files and that's why you need to have Git on your computer.

To install Git, follow the instructions based on your operating system:

* [Install Git on Mac OS](https://www.atlassian.com/git/tutorials/install-git#mac-os-x)
* [Install Git on Windows](https://www.atlassian.com/git/tutorials/install-git#windows)
* [Install Git on Linux](https://www.atlassian.com/git/tutorials/install-git#linux)



### Install Gatsby CLI

Gatsby CLI (Command Line Interface) is the tool that lets you build Gatsby-powered sites. By running this command, we can install any Gatsby sites and the plugins we want.

To install Gatsby CLI, open the terminal and run this command:



```
npm install -g gatsby-cli
```



Once everything is set up successfully then we are ready to build our first Gatsby site.



## How to build a Gatsby site

In this guide, we're going to use the default Gatsby starter theme, but you're free to choose any themes on the [Gatsby starter library](https://www.gatsbyjs.com/starters/?v=2). I personally use the [Lekoart theme](https://github.com/LekoArts/gatsby-starter-minimal-blog) because the design is minimalist and beautiful, and it has a dark mode.

In the terminal, run this command to install the new Gatsby blog:



```
gatsby new gatsby-starter-blog https://github.com/gatsbyjs/gatsby-starter-blog
```



What's does this command line mean exactly? Let me explain.

* **new** - This is the command line that creates a new Gatsby project
* **gatsby-starter-blog** - This is the name of the project. You can name it whatever you want here. I named this project *foodblog* as an example only.
* **The URL** (<https://github.com/gatsbyjs/gatsby-starter-blog>) - This URL specified points to a code repository that holds the starter code you want to use. In other words, I picked the theme for the project.

Once the installation is complete, we'll run the `cd `gatsby-starter-blog command which will take us to the location of our project file.



Then we'll run `gatsby develop` that will start running on the local machine. Depending on the specs of your computer, it will take a little while before it is fully started.



```
gatsby develop
```



Open a new tab in your browser and go to `http://localhost:8000/`. You should now see your new Gatsby site!