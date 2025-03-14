# Contributing  to the FHIRest framework
First off, thank you for taking the time to contribute! :+1: :tada:

### Table of Contents

* [Code of Conduct](#code-of-conduct)
* [How to Contribute](#how-to-contribute)
  * [Ask questions](#ask-questions)
  * [Create an Issue](#create-an-issue)
  * [Issue Lifecycle](#issue-lifecycle)
  * [Submit a Pull Request](#submit-a-pull-request)
* [Source Code Style](#source-code-style)
* [Documentation](#documentation)

### Code of Conduct

This project is governed by the [Code of Conduct for Open Source Communities](./CODE_OF_CONDUCT.md).  
By participating you are expected to uphold this code.

### How to Contribute

#### Ask questions

If you believe there is an issue, search through
[existing issues](https://github.com/fhirest/fhirest/issues) trying a
few different ways to find discussions, past or current, that are related to the issue.
Reading those discussions helps you to learn about the issue, and helps us to make a
decision.


#### Create an Issue

Reporting an issue or making a feature request is a great way to contribute. Your feedback
and the conversations that result from it provide a continuous flow of ideas. However,
before creating a ticket, please take the time to take a look at existing issues first.

Once you're ready, create an issue on [GitHub](https://github.com/fhirest/fhirest/issues).

Many issues are caused by subtle behavior, typos, and unintended configuration.
Creating a [Minimal Reproducible Example](https://stackoverflow.com/help/minimal-reproducible-example)
 of the problem helps the team quickly triage your issue and get to the core of the problem.

#### Issue Lifecycle

When an issue is first created, it is in open status and waiting for a team member to review it.
Once the issue has been reviewed, the team may ask for further
information if needed, and based on the findings, the issue is either assigned a target
milestone or is closed with a specific status.

When a fix is ready, the issue is closed and may still be re-opened until the fix is
released. After that the issue will typically no longer be reopened. In rare cases if the
issue was not at all fixed, the issue may be re-opened. In most cases however any
follow-up reports will need to be created as new issues with a fresh description.

#### Submit a Pull Request

1. Should you create an issue first? No, just create the pull request and use the
description to provide context and motivation, as you would for an issue. If you want
to start a discussion first or have already created an issue, once a pull request is
created, we will close the issue as superseded by the pull request, and the discussion
about the issue will continue under the pull request.

1. Always check out the `main` or `master` branch and submit pull requests against it.
Backports to prior versions will be considered on a case-by-case basis and reflected as
the fix version in the issue tracker.

1. Choose the granularity of your commits consciously and squash commits that represent
multiple edits or corrections of the same logical change. See
[Rewriting History section of Pro Git](https://git-scm.com/book/en/Git-Tools-Rewriting-History)
for an overview of streamlining the commit history.

1. By commiting to FHIRest repositories the contributor agrees to [Developer Certificate of Origin](https://developercertificate.org/)

1. For commits please use [Conventional Commits](https://www.conventionalcommits.org/)

1. If there is a prior issue, reference the GitHub issue number in the description of the
pull request.

If accepted, your contribution may be heavily modified as needed prior to merging.
You will likely retain author attribution for your Git commits granted that the bulk of
your changes remain intact. You may also be asked to rework the submission.

If asked to make corrections, simply push the changes against the same branch, and your
pull request will be updated. In other words, you do not need to create a new pull request
when asked to make changes.

#### Participate in Reviews

Helping to review pull requests is another great way to contribute. Your feedback
can help to shape the implementation of new features. When reviewing pull requests,
however, please refrain from approving or rejecting a PR unless you are a core
committer for the FHIRest framework.

### Source Code and Style

Please read through our overall [coding rules](./CODING_RULES.md).   
When writing code, please apply [FHIRest code style](./codestyle).

### Documentation

Documentation is in README.md of each component. If you submit changes, please check first if documentation needs change and submit together with code changes. If you want to get general overview of the framework please look at [main project README](https://github.com/fhirest/fhirest/blob/master/README.md).
