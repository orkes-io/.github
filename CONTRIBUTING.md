# Contributing to Orkes.io


The following is a set of guidelines for contributing to Orkes' projects and docs.

#### Table of contents

[Code of Conduct](#code-of-conduct)

[I just have a question!](#i-just-have-a-question)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Pull Requests](#pull-requests)

[Styleguides](#styleguides)
  * [Git Commit Messages](#git-commit-messages)
  * [Documentation Styleguide](#documentation-styleguide)

## Code of conduct

This project and everyone participating in it is governed by a [Code of Conduct](CODE_OF_CONDUCT.md) based on the [Contributor Code of Conduct](https://www.contributor-covenant.org/). By participating, you are expected to uphold this code. Please report unacceptable behavior to [devrel@orkes.io](mailto:devrel@orkes.io).

## I just have a question!

> **Note:** [Please don't file an issue to ask a question.] You'll get faster results by using the resources below.

We have an official Slack message board where the community chimes in with helpful advice if you have questions.

* [The Orkes Slack Community](https://join.slack.com/t/orkes-conductor/shared_invite/)


## How can I contribute?

### Reporting bugs

This section guides you through submitting a bug report for Orkes. Following these guidelines helps maintainers and the community understand your report :pencil:, reproduce the behavior :computer:, and find related reports :mag_right:.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report) as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). 

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### Before submitting a bug report

* **Determine which repository the problem should be reported in**.
* **Perform a [cursory search](https://github.com/search?q=is%3Aissue+user%3Aorkes-io)** to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.

#### How do I submit a (good) bug report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined which repository your bug is related to, create an issue on that repository and provide the following information:

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. When listing steps, **don't just say what you did, but explain how you did it**.
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots or videos** which show you following the described steps and clearly demonstrate the problem.
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

* **Did the problem start happening recently** (e.g. after updating to a new version of Conductor) or was this always a problem?
* If the problem started happening recently.**
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.

Include details about your configuration and environment:

* **Which version of the package are you using?** 
* **What's the name and version of the OS you're using?**

### Suggesting enhancements

This section guides you through submitting an enhancement suggestion for Orkes' projects, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion :pencil: and find related suggestions :mag_right:.

#### How do I submit a (good) enhancement suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined which repository your enhancement suggestion is related to, create an issue on that repository and provide the following information:

* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include copy/pasteable snippets which you use in those examples, as [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Include screenshots** which help you demonstrate the steps or point out the part of Orkes's project which the suggestion is related to.
* **Explain why this enhancement would be useful** to most Orkes users and isn't something that can or should be implemented as a community package.
* **Specify which version of the Orkes package you're using.**
* **Specify the name and version of the OS you're using.**


### Pull requests

The process described here has several goals:

- Maintain Orkes' quality
- Fix problems that are important to users
- Engage the community in working toward the best possible experience using Orkes' repos and docs.
- Enable a sustainable system for Okres' maintainers to review contributions

Please follow these steps to have your contribution considered by the maintainers:


1. After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing <details><summary>What if the status checks are failing?</summary>If a status check is failing, and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.</details>

While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

## Style guides

### Git commit messages

* Use the present tense ("Add feature" not "Added feature")
* Limit the first line to 72 characters or less
* Reference issues and pull requests after the first line
* Consider starting the commit message with an applicable emoji:
    * :art: `:art:` when improving the format/structure of the code
    * :racehorse: `:racehorse:` when improving performance
    * :non-potable_water: `:non-potable_water:` when plugging memory leaks
    * :memo: `:memo:` when writing docs
    * :penguin: `:penguin:` when fixing something on Linux
    * :apple: `:apple:` when fixing something on macOS
    * :checkered_flag: `:checkered_flag:` when fixing something on Windows
    * :bug: `:bug:` when fixing a bug
    * :fire: `:fire:` when removing code or files
    * :green_heart: `:green_heart:` when fixing the CI build
    * :white_check_mark: `:white_check_mark:` when adding tests
    * :lock: `:lock:` when dealing with security
    * :arrow_up: `:arrow_up:` when upgrading dependencies
    * :arrow_down: `:arrow_down:` when downgrading dependencies
    * :shirt: `:shirt:` when removing linter warnings

### Documentation style guide

* Use [Markdown](https://daringfireball.net/projects/markdown).


