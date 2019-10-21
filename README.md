# GitHub Workshop

This material is based on [Rachael Ainsworth's 4IR GitHub workshop](https://github.com/rainsworth/4IR-GitHub-Workshop).

This workshop gives an introduction to GitHub and how one would interact with it in a typical pipeline to create own project or contribute to an existing project. We recommend for it to be followed by a workshop on how to work with git from a command line, for example see [Software Carpentry's git workshop](https://swcarpentry.github.io/git-novice/).

Agenda:

- [Friendly intro to GitHub](#friendly-intro-to-github)
  * [What is GitHub?](#what-is-github)
  * [Examples of how GitHub is used](#examples-of-how-github-is-used)
  * [Interface Tour and Jargon Busting](#interface-tour-and-jargon-busting)
  * [Markdown](#markdown)
- [Hands-on activities](#hands-on-activities)
  * [Hello world](#hello-world)
  * [Building a website in GithHub](#build-a-website-in-gitHub)
  * [Personal website](#personal-website)
- [More Resources](#more-resources)

<!-- toc -->

## Friendly intro to GitHub :octocat:

A brief tutorial inspired by the [Mozilla Science Lab Friendly Intro to GitHub](https://github.com/mozillascience/friendly-github).

### What is GitHub?
* Git is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.
* GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.
* Open and reproducible science/code/research
   * Open source software is software that can be [freely used, modified, and shared (in both modified and unmodified form) by anyone](http://opensource.org/definition). Today the concept of "open source" is often extended beyond software, to represent a philosophy of collaboration in which working materials are made available online for anyone to fork, modify, discuss, and contribute to.
   * For more information on open source, specifically how to create and grow an open source project, GitHub have created [Open Source Guides](https://opensource.guide/) that will help you foster a healthy open source community.

### Examples of how GitHub is used

* Project Management
* Websites
* Code documentation
* Open Educational Resources
* Open Data
* Online portfolio of your work
* All the things

### Interface Tour and Jargon Busting
Glossary via [Mozilla Science Lab's GitHub Essentials](http://joeyklee.github.io/friendly-github-intro/guides/github-essentials/#glossary)

* **repository**, or **repo** - a collection of documents related to your project, in which you create and save new code or content.
* **markdown** - a lightweight way of annotating a document with instructions that tell a web browser how to format and display text.
* **version control** - a way of tracking changes to a document or collection of documents. Version control is like a time machine, it can take you back to the moment your document was created, or any other point in time when you or a collaborator saved that document.
* **Git** - the command-line software that tracks all changes to a collection of documents.
* **GitHub** - a service that hosts your repository online and helps you work with contributors. GitHub adds a web-based interface to version control.
* **fork** - a copy of a repository that is saved in another user's GitHub account.
* **branch** - a copy of a repo that is contained within the original repo. Branches are used to work on a project features without altering the original or "master" repo.
* **commit** - a saved change to a document in a repository.
* **issue** - a message on GitHub that outlines a task that needs to be completed.
* **pull request** - a request to add a commit or collection of commits to a repository.
* **merge** - the act of incorporating new changes (commits) into a repository.
* **README** - a document that introduces an open project to the public and any potential contributors; the first thing you see in a repo; usually written in Markdown


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/), [Markdown cheat sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) and [Emoji cheat sheet](http://www.webpagefx.com/tools/emoji-cheat-sheet/).

## Hands-on activities

### Hello world!
We will begin by following the GitHub Guides [Hello-World tutorial](https://guides.github.com/activities/hello-world/) where everyone will create a repository calle `hello-world` and edit the `README` to become more familiar with the GitHub platform.

We will also cover creating a new branch, comparing changes and merging changes from the new branch into the main resitory branch `master` via a pull request.

Finally, we will play with forking someone else's repository, doing a pull request upstream (to the repository we forked from).

In the process, we will also explore various GitHub features, such as projects, wikis, teams and pinned repositories.

### Build a website in GitHub
This is a collaborative group exercise to build a webpage using GitHub.

1. Identify what information/sections/tabs/pages you want to include on the website (e.g. an About page, an events page, a list of projects, a blog, contact info, etc.).
2. Choose a theme (e.g. from [http://jekyllthemes.org/](http://jekyllthemes.org/)) that will best present that information.
3. Go to your chosen theme's GitHub repository (e.g. [Project Pages](https://github.com/projectpages/project-pages) used in our example [here](https://rainsworth.github.io/4IR-GitHub-Workshop/)).
4. **Fork** the theme repository. This makes your own version of the content that you can edit and use while maintaining credit to the theme authors.
5. Go to Settings to update the repository name (e.g. to `username.github.io`) and enable GitHub Pages by selecting a branch (e.g. `master` or `gh-pages`) as a source for your webpage.
6. Edit the `_config.yml` file to point to your repository, change the title and any other user information.
7. Edit the `README` to include information about the website or project repository (read more about `README` files [here](https://help.github.com/articles/about-readmes/)).
8. **Make your changes**! In this case, add or change elements to the website as you see fit (e.g. add relevant information to the About page, add an events page with upcoming 4IR CDT workshops, create student profiles). For this workshop, we will make our changes in the GitHub interface. Once you're happy with your changes...
9. Submit a **pull request**. This opens a discussion around your project and lets the project lead know you are proposing changes.
10. Merge the pull request and check out your website! :tada:

### Personal website
Is there still time left in the workshop? Try making a website for your personal GitHub account following these steps! :sunglasses:

## More Resources

* GitHub Guides - https://guides.github.com/
* GitHub Glossary - https://help.github.com/articles/github-glossary/
* Understanding the GitHub flow - https://guides.github.com/introduction/flow/
* Mastering Markdown - https://guides.github.com/features/mastering-markdown/
* How to choose a license for your GitHub repository - https://choosealicense.com/
* Mozilla Science Lab GitHub Essentials - http://joeyklee.github.io/friendly-github-intro/guides/github-essentials/
* Software Carpentry's git workshop - https://swcarpentry.github.io/git-novice/
* Visual explanations of git:
  - https://onlywei.github.io/explain-git-with-d3/
  - https://agripongit.vincenttunru.com/
  - https://marklodato.github.io/visual-git-guide/index-en.html

