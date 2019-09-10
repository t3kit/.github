# Contributing to t3kit

Welcome, and thank you for your interest in contributing to **t3kit**

As a contributor, here are the guidelines we would like you to follow:

- [Questions and Support](#found-an-issuebug)
- [Bug Report](#found-an-issuebug)
- [Feature Requests](#want-to-add-new-featurefix-bug)
- [Submission Guidelines](#submission-guidelines)
- [Coding Rules](#general-coding-rules)
- [Commit Message Guidelines](#git-commit-message-conventions)
- [Browsers and Devices](#coc)
- [Code of Conduct](#coc)

***

## ❓If you have question or need a Support

Do not open issues for general support questions as we want to keep **t3kit GitHub issues** for bug reports and feature requests. [t3kit Slack channel](SUPPORT.md) is a much better place to ask questions and get support.

To save your and our time, **we will regulary close all issues** that are requests for general support and redirect people to t3kit Slack.

## 🐞Add a Bug report

If you find a bug in the code or a mistake in the documentation, you can help us by submitting an issue to particular t3kit repository, or even better, you can submit a Pull Request with a fix.

## 🚀Add a new Feature

You can request a new feature by submitting an issue to our t3kit repository. If you would like to implement a new feature, please submit an issue with a proposal for your work first, to be sure that we can use it. Please consider what kind of change it is:

- For a **Major Feature**, first open an issue and outline your proposal so that it can be discussed. This will also allow us to better coordinate our efforts, prevent duplication of work, and help you to craft the change so that it is successfully accepted into the project.
- **Small Features** can be crafted and directly submitted as a Pull Request.

***

## Submission Guidelines

### Submitting an Issue

Before you submit an issue please check that you've considered the following steps:

- File a single issue per problem
- Check **duplicates** - use the search feature to ensure that the problem hasn't been reported before.
- Check **dependencies** - make sure you're on the right version of dependencies.
- Check [Browsers and devices](#browser-and-device-support)
- Use **Issue templates** - Please add new issues by filling out the issue template.

Unfortunately, we are not able to investigate / fix bugs without a minimal reproduction, so if we don't hear back from you **we are going to close an issue** that doesn't have enough info to be reproduced.

### Submitting a Pull Request

Before you submit your Pull Request (PR) please check that you've considered the following steps:

- ❗️**Please ask** first before embarking on any significant pull request, otherwise you risk spending a lot of time working on something that the project's developers might not want to merge into the project. [Create an Issue](submitting_an_issue) to disscuse potential big PR.
- Search in GitHub for an open or closed Pull Request that relates to your submission.
- Provide plenty of context and reasoning around your changes, to help us merge quickly.
- Follow our [Coding Rules](#coding-rules)
- Follow our [Commit message conventions](#commit-message-conventions)
- Close related issue in PR header message using [GitHub keywords](https://help.github.com/articles/closing-issues-via-commit-messages).
- If your PR gets out of date, we may ask you to rebase as you are more familiar with your changes than we will be.
- If your PR fail on CI tests, we may ask you to fix it.
- [Check documentation about Pull Request in Github](https://help.github.com/articles/using-pull-requests/)

***

## Coding Rules

***

## Commit Message Guidelines

Each commit message consists of a **[label](#labels)** and short **[message](#message)**.

Also it is possible to use special keywords for [closing Github issues](https://help.github.com/articles/closing-issues-via-commit-messages).

### Git message

- Use the imperative, present tense: "change" not "changed" or "changes"
- don't capitalize first letter
- no dot (.) at the end

### Labels

Please use semantic labels for your messages, but if commit message is not very important, you can skip labels. **All commits with labels will be added in CHANGELOG file, that's why it is important to use predefined labels on your commits.**

- **[FEATURE]** - A new feature
- **[BUGFIX]** - A bug fix
- **[TASK]** - Any task, which is not a **new feature** or **bugfix**
- **[TEST]** - Adding missing tests
- **[DOC]** - Documentation only changes
- **[!!!]** - Breaking Changes
- **[WIP]** - Work in progress tag, should not be present when creating pull requests
- **[SECURITY]** - To mark important updates, when evaluating when we should update older sites

**Important:** Commit label must be **only one**, except if it Breaking Changes, then we will need to add _"Breaking Changes"_ label `[!!!]` at front.

For example (Breaking Changes):

``` git
[!!!][BUGFIX] change default css styling for Text and Image CE
```

***

## Browsers and Devices

t3kit supports the **latest browser versions** of each major mobile and desktop platforms.

### Mobile devices

|📱        |Chrome|Safari|Android Browser|
|----------|------|------|---------------|
|Android 8+|✅    |N/A   |✅             |
|iOS 12+   |✅    |✅    |N/A            |

### Desktop browsers

|🖥         |Chrome|Firefox|Safari|Microsoft Edge|IE |
|-----------|------|-------|------|--------------|---|
|Mac 10.14+ |✅    |✅     |✅    |N/A           |N/A|
|Windows 10+|✅    |✅     |N/A   |✅            |❌ |

***

## Code of Conduct

This project has a [Code of Conduct](CODE_OF_CONDUCT.md). By interacting with this repository, organization, or community you agree to abide by its terms.
