# Welcome to Microsoft Learn Student Community - DHA Suffa University

<div align="center">
<img width="1000" alt="Asset 8@2x" src="https://user-images.githubusercontent.com/90326051/232233264-9050fbd4-aa67-4263-9a73-79a549ee4af3.png">
</div>
  

<!-- omit in toc -->
# Contributing to MLSC-DSU-Learning-Contributing-Resource

First off, thanks for taking the time to contribute! ❤️

All types of contributions are encouraged and valued. See the [Table of Contents](#table-of-contents) for different ways to help and details about how this project handles them. Please make sure to read the relevant section before making your contribution. 

> And if you like the project, but just don't have time to contribute, that's fine. There are other easy ways to support the project and show your appreciation, which we would also be very happy about:
> - Star the project
> - Fork the project
<!-- omit in toc -->
## Table of Contents

- [I Have a Question](#I-Have-a-Question)
- [Steps for Contributing To the Repository without Cloning](#Contributing-to-the-Repository-without-Cloning)
- [Steps for Contributing to the Repository by Adding or Improving a Project](#Contributing-to-the-Repository-by-Adding-or-Improving-a-Project)
- [Tips to Contribute](#Tips-to-Contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Your First Code Contribution](#your-first-code-contribution)
  - [Improving The Documentation](#improving-the-documentation)
- [Styleguides](#styleguides)
  - [Commit Messages](#commit-messages)


## I Have a Question

> If you want to ask a question, we assume that you have read the available [Documentation](https://github.com/KiranAminPanjwani/MLSC-DSU-Learning-Contributing-Resources/blob/main/Readme.md).
Before you ask a question, it is best to search for existing [Issues](https://github.com/KiranAminPanjwani/MLSC-DSU-Learning-Contributing-Resources/issues) that might help you. In case you have found a suitable issue and still need clarification, you can write your question in this issue. It is also advisable to search the internet for answers first.

If you then still feel the need to ask a question and need clarification, we recommend the following:

- Open an [Issue](https://github.com/KiranAminPanjwani/MLSC-DSU-Learning-Contributing-Resources/issues/new/choose).
- Provide as much context as you can about what you're running into.

We will then take care of the issue as soon as possible.


## ✅ Basics of Git and GitHub

### Git & GitHub

Before we proceed, it's better to know the difference between Git and Github. Git is a version control system (VCS) that allows us to keep track of the history of our source code , whereas GitHub is a service that hosts Git projects. 

We assume you have created an account on Github and installed Git on your System.

Now enter your name and E-mail (used on Github) address in Git, by using following command.

`$ git config --global user.name "YOUR NAME"`
` $ git config --global user.email "YOUR EMAIL ADDRESS"`
This is an important step to mark your commits to your name and email.

<br />

## ✅ Contributing to the Repository without Cloning

To contribute to a repository without cloning it, follow these steps:

1. **Fork the repository** by clicking on the "Fork" button on the repository's page.

2. **Make your desired changes** to your forked repository.

3. **Create a new branch** for your changes.

4. **Commit your changes** to the new branch.

5. **Open a pull request** to submit your changes to the original repository.

**Note:** This process requires you to have a GitHub account and the necessary permissions to fork and create pull requests for the repository you want to contribute to.

<br />

## ✅ Contributing to the Repository by Adding or Improving a Project

### 1) Fork a project

You can make a copy of the project to your account. This process is called forking a project to your Github account. On Upper right side of project page on Github, you can see -

<p align="center">  <img  src="https://i.imgur.com/P0n6f97.png">  </p>
Click on fork to create a copy of project to your account. This creates a separate copy for you to work on.

<br />
<br />


### 2) Clone the forked project

To add your project to this repository or make improvements to someone else's project, you can clone it using the git clone command to obtain the project on your development machine.

`$ git clone https://github.com/KiranAminPanjwani/MLSC-DSU-Learning-Contributing-Resources` <br/>
Now you have the project on your local machine.

<br />

### 3) Synchronizing your fork

Open Source projects have a number of contributors who can push code anytime. So it is necessary to make your forked copy equal with the original repository. The remote added above called Upstream helps in this.

`$ git checkout main`
`$ git fetch upstream`
`$ git merge upstream/main`
`$ git push origin main` <br/>
The last command pushes the latest code to your forked repository on Github. The origin is the remote pointing to your forked repository on github.

<br />

### 4) Create a new branch for a feature or bugfix

Usually, all repositories have a main branch that is regarded to be stable, and any new features should be developed on a separate branch before being merged into the main branch. As a result, we should establish a new branch for our feature or bugfix and go to work on the issue. 

`$ git checkout -b <feature-branch>`
This will create a new branch out of master branch. Now start working on the problem and commit your changes.

`$ git add --all`
`$ git commit -m "<commit message>"`
The first command adds all the files or you can add specific files by removing -a and adding the file names. The second command gives a message to your changes so you can know in future what changes this commit makes. If you are solving an issue on original repository, you should add the issue number like #35 to your commit message. This will show the reference to commits in the issue.

<br />

### 5) Push code and create a pull request

You now have a new branch containing the modifications you want in the project you forked. Now, push your new branch to your remote github fork. 

`$ git push origin <feature-branch>`
Now you are ready to help the project by opening a pull request means you now tell the project managers to add the feature or bug fix to original repository. You can open a pull request by clicking on green icon -

<p align="center">  <img  src="https://i.imgur.com/aGaqAD5.png">  </p>

Remember your upstream base branch should be main and source should be your feature branch. Click on create pull request and add a name to your pull request. You can also describe your feature.

Fantastic! You've already made your first contribution.🥳🎉

## _Happy Coding_ 🤩

<br />
<br />

## 🌟Tips to Contribute

> ### Legal Notice <!-- omit in toc -->
> When contributing to this project, you must agree that you have authored 100% of the content, that you have the necessary rights to the content and that the content you contribute may be provided under the project license.

### ➡ Reporting Bugs

<!-- omit in toc -->
Before submitting a bug report, it's important to investigate and provide enough information to help us fix the potential bug as fast as possible. Here are the steps you can follow:

- Make sure that you are using the latest version.
- Determine if the issue is really a bug and not an error on your end. Read the documentation and check if others have experienced and potentially solved the same issue.
- Also make sure to search the internet (including Stack Overflow) to see if users outside of the GitHub community have discussed the issue.
- Try to reliably reproduce the issue, and see if it occurs with older versions.

<!-- omit in toc -->
#### How Do I Submit a Good Bug Report?

> You must never report security related issues, vulnerabilities or bugs including sensitive information to the issue tracker, or elsewhere in public. Instead sensitive bugs must be sent by email to <kiranpanjwani220@gmail.com> or <samipak458@gmail.com>.
<!-- You may add a PGP key to allow the messages to be sent encrypted as well. -->
We use GitHub issues to track bugs and errors. If you run into an issue with the project:

- Open an [Issue](https://github.com/KiranAminPanjwani/MLSC-DSU-Learning-Contributing-Resources/issues/new/choose). (Since we can't be sure at this point whether it is a bug or not, we ask you not to talk about a bug yet and not to label the issue.)
- Explain the behavior you would expect and the actual behavior.
- Please provide as much context as possible and describe the *reproduction steps* that someone else can follow to recreate the issue on their own. This usually includes your code. For good bug reports you should isolate the problem and create a reduced test case.
- Provide the information you collected in the previous section.

Once it's filed:

- The project team will label the issue accordingly.
- A team member will try to reproduce the issue with your provided steps. If there are no reproduction steps or no obvious way to reproduce the issue, the team will ask you for those steps and mark the issue as `needs-repro`. Bugs with the `needs-repro` tag will not be addressed until they are reproduced.
- If the team is able to reproduce the issue, it will be marked `needs-fix`, as well as possibly other tags (such as `critical`), and the issue will be left to be implemented by someone.

<!-- You might want to create an issue template for bugs and errors that can be used as a guide and that defines the structure of the information to be included. If you do so, reference it here in the description. -->


### ➡ Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for MLSC @ DSU Repository.

<!-- omit in toc -->
#### Before Submitting an Enhancement

- Use the latest version of the software.
- Read the [documentation](https://github.com/KiranAminPanjwani/MLSC-DSU-Learning-Contributing-Resources/blob/main/Readme.md) and check if the functionality you want to add is already covered.
- Search to see if your enhancement idea has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.
- Check if your idea fits with the project's scope and aims. Make a strong case to convince the developers of the feature's merits. Keep in mind that the feature should be useful to the majority of users.
- If the feature is only useful to a small subset of users, consider writing an add-on/plugin library.


<!-- omit in toc -->
#### ➡ How Do I Submit a Good Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://github.com/KiranAminPanjwani/MLSC-DSU-Learning-Contributing-Resources/issues).

- Use a **clear and descriptive title** for the issue to identify the suggestion.
- Provide a **step-by-step description of the suggested enhancement** in as many details as possible.
- **Describe the current behavior** and **explain which behavior you expected to see instead** and why. At this point you can also tell which alternatives do not work for you.
- **Explain why this enhancement would be useful** to most MLSC repoitory users. You may also want to point out the other projects that solved it better and which could serve as inspiration.

<!-- You might want to create an issue template for enhancement suggestions that can be used as a guide and that defines the structure of the information to be included. If you do so, reference it here in the description. -->

### ➡ Your First Code Contribution
Contributing to open source for the first time can be scary and a little overwhelming. Perhaps you’re a Code Newbie or maybe you’ve been coding for a while but haven’t found a project you felt comfortable contributing to. 

If you have never contributed to an open source project before and you’re just getting started, consider exploring these resources.

[First contributions](https://github.com/firstcontributions/first-contributions) is a hands-on tutorial that walks you through contributions workflow on GitHub. When you complete the tutorial, you have made a contribution to the same project.

### ➡ Improving The Documentation
- **Identify areas that need improvement:** Start by going through the existing documentation and identifying areas that may be unclear or incomplete. Look for gaps in information, inconsistencies, or anything else that could be improved.
- **Suggest changes and additions:** Once you've identified areas for improvement, suggest changes and additions to the documentation. This could include adding more detail, clarifying existing information, or reorganizing the structure of the document. Make sure your suggestions are clear, concise, and easy to understand for other users.

## Styleguides
### Commit Messages
Commit Message should reflect the work you have done (resolve bug or add feature).
<a href="#top"><img src="https://img.shields.io/badge/-Back%20to%20Top-red?style=for-the-badge" align="right"/></a>
