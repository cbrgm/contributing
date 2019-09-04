# Contributing Guide

Thank you for considering contributing! There are many ways to
contribute, and I'm appreciating all of them. Please have a look at the following sections:

-   [Feature Requests](#feature-requests)
-   [Bug Reports](#bug-reports)
-   [Pull Requests](#pull-requests)
-   [Writing Documentation](#writing-documentation)

If you have questions, please send an email to <mailto:chris@cbrgm.net>.

## Feature Requests

Before opening a new feature request, check the
***existing feature requests*** if there's one already
open on the same topic.

To request new features or enhancements, just open a new
***feature request issue***. Describe your use case, why you need this feature and why this feature is important for this project.

## Bug Reports

Bugs are not a nice thing, but reality in software. Fixing something you don't know about is often very difficult,
so please report liberally. If you're not sure if something is a bug or not, feel free to file a bug report anyway. Before reporting a bug, have a look at ***open bugs***. Maybe
someone has already reported your error.

Once you have verified that they haven't, ***open an issue*** here and fill out the fields.

Each bug report issue uses a template with 5 sections that are there to help
other contributors understand your issue and eventually reproduce it:

    #### Description

    #### Steps to reproduce the issue

    #### Expected results

    #### Actual results

    #### Version

In summary, try to include as much information as possible, to help maintainers or other developers to fix the bug quickly.

## Pull Requests

GitHub's Pull Request (PR) feature is the primary mechanism used to make
contributions to my projects codebase. GitHub itself has some great documentation on ***using the Pull Request feature***.

My projects use the ***fork and pull model***, where contributors push changes to their personal fork and create pull requests to bring those changes into the source repository.

Before opening a new Pull Request, have a look at ***existing ones***. Maybe someone has already opened one
about the same thing. If it's the case, you might be able to help with the
contribution. Just comment on the PR and ask. Old and stalled ***PRs are sometimes archived*** with the "State: archived" label, maybe one of them is also about the same topic.

Each Pull Request form uses a template with 2 sections that are here to help  maintainers understand your contribution and help them testing it:

    #### Contribution description

    #### Issues/PRs references

Please fill each section with as much information as possible. The Pull Request title should reflect what it is about and be in the form `area of change: description of changes`.

Remember that smaller PRs tend to be merged faster, so keep your changes as
concise as possible. They should be confined to a single explainable change, and be runnable on their own. So don't hesitate to split your PRs
into smaller ones when possible.

In general project provide static test tools to verify the quality of changes (linting , documentation, etc). These tools are wrapped in a
single `make` target: `make tests`.

Try to answer reviews as quickly as possible to speed up the review process and avoid stalled PRs.

## Writing Documentation

Documentation improvements are always welcome. This kind of contribution is merged quite quickly in general. If you miss something or want to improve something, do it!
