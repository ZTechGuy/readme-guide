![alt text](img/and-digital.png?v=3&s=200 "AND Digital")

![alt text](img/build-passing.png "Build Passing")

# README Guide

This repository contains a guide for creating `README.md` files for new and existing repositories. The sections below contain suggestions for different areas that can be covered in a README file where appropriate.


## Project Name
Kind of obvious but a README file should contain the project name, e.g. the top of this guide. If the project also has a tagline or slogan, then you could add that too e.g.
> Making READMEs easy!


## Project Logo
If the repository is associated with a particular company or brand, then it is often nice to include the relevant logo image, e.g. the top of this guide.


## Project Description
After the project name, a brief description is usually a good idea to let the reader know what the project is about and why it might be useful to them, e.g. the top of this guide.


## Project Features

In this section, you can provide a description of the main pieces of functionality your project offers:
* Main functionality
* Secondary functionality
* You can also do...


## Project Structure
A walkthrough the project's structure is often a good idea, to let developers know the design patterns and directory structure in use so they know where to find and add things.


## Build Status
If your project has some sort of automation server set up to run tests against the project's latest build, then it is a good idea to include an image in your repository showing the status of the latest build e.g. the top of this guide. See the *Useful Resources* section below for some links to documentation on how to do this with popular build tools.


## Prerequisites
Many README files launch straight into installation instructions without considering the assumptions made about the reader and their system. This is easy to do when you have been working in a particular stack for a while but it is always good practice to consider things from a novice's perspective and provide instructions to setup from a basic system to the point that the installation instructions can take over, e.g.

Ensure you have the following installed:

* [Docker](https://www.docker.com/) Docker Community Edition version => 17
* [Node.js](https://nodejs.org/en/) version >= 6
* [npm](https://www.npmjs.com/) version >= 3 OR [Yarn](https://yarnpkg.com/) version >= 0.21.*


## Installation

This section should be a requirement. It provides the reader with instructions on how to get your code and run it, e.g.

```shell
$ git clone https://github.com/username/reponame && cd reponame
$ npm install
```

It is usually good practice to explain these steps so novice users know what is happening and why they are performing them.


## Developing

This section can contain a few different subsections, including:

* Building - Instructions for the developer to build the project if additional steps need to be followed

* Configuration - Instructions on which parameters can be configured within the project. These should usually include type e.g. `String` and default value e.g. `root` information

* Run - How to actually run the project code and see its output

* Packaging - How to package up the app ready for deployment

* Deploying - How the project can be deployed, either using scripts provided or preconfigured CI tools 

As with the installation instructions, it is good practice to explain any commands provided in these sections so that the user knows what happens when they run them and why they are needed.


## Other possible sections

There are many other potentially useful sections to a `README` file depending on the specifics of the project, e.g. type, size, ownership, open-source. Some of these might include:

### Documentation
Whilst quite a bit of information can be included in the project's `REAMDE` file, it is probably not the best place for extensive project documentation. If this is available on a separate system (e.g. Confluence, MediaWiki), it is better to provide a link to this resource for the more indepth documentation.

### Style guide
If the code is written in a particular style or with particular formatting and this needs to be maintained, then it is important to inform other collaborators of this fact. Many projects will have a front end with user facing components that must stay on brand and adhere to a company visual style guide too.

### Contributing
One of the main purposes of source-control is to make collaboration with others easy. To aid this process, it is often a good idea to include instructions on how other developers can contribute to the project's codebase. Explaining the GIT branching model in use is usually a good start as well as explaining the process for submitting and approving pull requests.

### Licensing
Depending on the ownership of the repository and who might have access to it, a README section that might be important is that of the license. This should state what the license is and how to find a detailed version of it. There are various types of license that can be used and a link to the relevant Wikipedia article has been included in the *Useful Resources* section below.


## Useful Resources
* [Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Software-Licenses](https://en.wikipedia.org/wiki/Software_license)
* [Jenkins Build Status Plugin](https://wiki.jenkins-ci.org/display/jenkins/embeddable+build+status+plugin)
* [Travis Build Status](https://docs.travis-ci.com/user/status-images/)
