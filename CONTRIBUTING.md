# Contributing to Raspberry Pi Documentation

The Raspberry Pi Documentation website is built from Asciidoc source using a Jekyll and Python toolchain. The website is automatically deployed to the raspberrypi.org site — pushed to production — using GitHub Actions when a push to the `master` branch occurs.

Full instructions for building and running the documentation website locally can be found in the top-level [README.md](README.md) file.

## How to Contribute

In order to contribute new or updated documentation, you must first create a GitHub account and fork the original repository to your own account. You can make changes, save them in your repository, then [make a pull request](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork) against this repository. The pull request will appear [in the repository](https://github.com/raspberrypi/documentation/pulls) where it can be assessed by the maintainers, copy edited, and if appropriate, merged with the official repository.

**NOTE:** Unless you are opening a pull request which will only make small corrections, for instance to correct a typo, you are more likely to get traction for your changes if you [open an issue](https://github.com/raspberrypi/documentation/issues) first to discuss the proposed changes.

**NOTE:** The default [branch](https://github.com/raspberrypi/documentation/branches) of the repository is the `develop` branch, and this should be the branch you get by default when you initially checkout the repository. You should target any pull requests against the `develop` branch, pull requests against the `master` branch will automatically fail checks and not be accepted.

**NOTE:** Issues and Pull Requests older than 60 days will [automatically be marked as stale](https://github.com/actions/stale) and then closed 7 days later if there still hasn't been any further activity.

## Type of Content

We welcome contributions from the community, ranging from correcting small typos all the way through to adding entire new sections to the documentation. However going forward we're going to be fairly targetted about what sort of content we add to the documentation. We are looking to keep the repository, and the documentation, focussed on Raspberry Pi-specific things, rather than having generic Linux or computing content.

**NOTE:** We are willing to consider toolchain-related contributions, but changes to the toolchain may have knock-on effects in other places so it is possible that apparently benign pull requests that make toolchain changes could be refused for fairly opaque reasons. 

## Third-Party Services

In general we will not accept content that is specific to an individual third-party service or product. We will also not embed, or add links, to YouTube videos showing tutorials on how to configure your Raspberry Pi.

## Licensing 

The documentation is under a [Creative Commons Attribution-Sharealike](https://creativecommons.org/licenses/by-sa/4.0/) (CC BY-SA 4.0) license. By contributing content to this repository you are agreeing to place your contributions under this license.
