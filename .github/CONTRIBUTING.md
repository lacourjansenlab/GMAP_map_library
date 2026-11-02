<!-- omit in toc -->
# Contributing to GMAP map library

First off, thanks for taking the time to contribute! ❤️

All types of contributions are encouraged and valued. See the [Table of Contents](#table-of-contents) for different ways to help and details about how this project handles them. Please make sure to read the relevant section before making your contribution. It will make it a lot easier for us maintainers and smooth out the experience for all involved. The community looks forward to your contributions. 🎉

> And if you like the project, but just don't have time to contribute, that's fine. There are other easy ways to support the project and show your appreciation, which we would also be very happy about:
> - Star the project
> - Share it on (research related) social media
> - Refer this project in your project's readme
> - Mention the project at conferences, local meetups and tell your colleagues

<!-- omit in toc -->
## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [I Have a Question](#i-have-a-question)
- [I Want To Contribute](#i-want-to-contribute)
- [Reporting Bugs](#reporting-bugs)
- [Contributing by creating a new map](#contributing-by-creating-a-new-map)
- [Your First Code Contribution](#your-first-code-contribution)
- [Improving The Documentation](#improving-the-documentation)
- [Styleguides](#styleguides)
- [Commit Messages](#commit-messages)
- [Join The Project Team](#join-the-project-team)


This project and everyone participating in it is governed by the
[GMAP map library Code of Conduct](https://github.com/lacourjansenlab/GMAP_map_library/blob/main/.github/CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code. Please report unacceptable behavior
to t.l.c.jansen@rug.nl.


## I Have a Question

> If you want to ask a question, we assume that you have read the available [Documentation](https://lacourjansenlab.github.io/GMAP/).

Before you ask a question, it is best to search for existing issues in both [GMAP](https://github.com/lacourjansenlab/GMAP/issues) and [the GMAP map library](https://github.com/lacourjansenlab/GMAP_map_library/issues), as well as [Discussions](https://github.com/lacourjansenlab/GMAP_map_library/discussions) that might help you. In case you have found a suitable issue/discussion and still need clarification, you can write your question in this issue/discussion.

If you then still feel the need to ask a question and need clarification, we recommend the following:

- Open a [Discussion](https://github.com/lacourjansenlab/GMAP_map_library/discussions/new/choose).
- Provide as much context as you can about what you're running into, using one of the available formats.
- Provide project versions and scientific (GMAP, specific molecule, challenge at hand, etc), depending on what seems relevant.

We will then take care of the issue as soon as possible.

<!--
You might want to create a separate issue tag for questions and include it in this description. People should then tag their issues accordingly.

Depending on how large the project is, you may want to outsource the questioning, e.g. to Stack Overflow or Gitter. You may add additional contact and information possibilities:
- IRC
- Slack
- Gitter
- Stack Overflow tag
- Blog
- FAQ
- Roadmap
- E-Mail List
- Forum
-->

## I Want To Contribute

> ### Legal Notice <!-- omit in toc -->
> When contributing to this project, you must agree that you have authored 100% of the content, that you have the necessary rights to the content and that the content you contribute may be provided under the project licence. You do not need to have created the data used by any map yourself, but you must give proper credit to the data source!

### Reporting Bugs

<!-- omit in toc -->
#### Before Submitting a Bug Report

A good bug report shouldn't leave others needing to chase you up for more information. Therefore, we ask you to investigate carefully, collect information and describe the issue in detail in your report. Please complete the following steps in advance to help us fix any potential bug as fast as possible.

- Make sure the bug is actually with the map, and not GMAP itself. If it is the latter, please visit the GMAP repo, and look at it's contributing.md file.
- Make sure that you are using the latest version, of both GMAP and the relevant map.
- Determine if your bug is really a bug and not an error on your side e.g. using incompatible environment components/versions (Make sure that you have read the [documentation](https://lacourjansenlab.github.io/GMAP/). If you are looking for support, you might want to check [this section](#i-have-a-question)).
- To see if other users have experienced (and potentially already solved) the same issue you are having, check if there is not already a bug report existing for your bug or error in the [bug tracker](https://github.com/lacourjansenlab/GMAP_map_library/issues?q=label%3Abug).
- Also make sure to search the internet (including Stack Overflow) to see if users outside of the GitHub community have discussed the issue.
- Collect information about the bug:
- Stack trace (Traceback)
- OS, Platform and Version (Windows, Linux, macOS, x86, ARM)
- Version of the interpreter, compiler, SDK, runtime environment, package manager, depending on what seems relevant.
- Your input files (only 2 frames of your trajectory that reproduce the issue) and the output files (again, only 2 frames in output files that can contain multiple).
- Can you reliably reproduce the issue? And can you also reproduce it with older versions?

<!-- omit in toc -->
#### How Do I Submit a Good Bug Report?

> You must never report security related issues, vulnerabilities or bugs including sensitive information to the issue tracker, or elsewhere in public. Instead sensitive bugs must be sent by email to t.l.c.jansen@rug.nl.
<!-- You may add a PGP key to allow the messages to be sent encrypted as well. -->

We use GitHub issues to track bugs and errors. If you run into an issue with the project:

- Use the bug_report template, when:
- Open an [Issue](https://github.com/lacourjansenlab/GMAP/issues/new). (Since we can't be sure at this point whether it is a bug or not, we ask you not to talk about a bug yet and not to label the issue.)
- Explain the behavior you would expect and the actual behavior.
- Please provide as much context as possible and describe the *reproduction steps* that someone else can follow to recreate the issue on their own. This usually includes your code. For good bug reports you should isolate the problem and create a reduced test case.
- Provide the information you collected in the previous section.

Once it's filed:

- The project team will label the issue accordingly.
- A team member will try to reproduce the issue with your provided steps. If there are no reproduction steps or no obvious way to reproduce the issue, the team will ask you for those steps and mark the issue as `needs-repro`. Bugs with the `needs-repro` tag will not be addressed until they are reproduced.
- If the team is able to reproduce the issue, it will be marked `needs-fix`, as well as possibly other tags (such as `critical`), and the issue will be left to be [implemented by someone](#your-first-code-contribution).

<!-- You might want to create an issue template for bugs and errors that can be used as a guide and that defines the structure of the information to be included. If you do so, reference it here in the description. -->


### Contributing by creating a new map
As GMAP can't function without maps, this mapping repository is essential to allow a wide community to make use of GMAP. We hope these kinds of contributions will be the main kind to this repository.

The tutorial files for creating new maps can be found in the [documentation - adding a new map](https://lacourjansenlab.github.io/GMAP/stable/Adding_a_new_map/index.html) page. If you have questions when working on maps, see the [questions](#i-have-a-question) section. If you have suggestions/bugs that require changes in the GMAP documentation/code, submit those issues to the main GMAP repository instead.

When you have created a map, check the readme for instructions how to have it added to this repository.


### Your First Code Contribution
If you would like to help by improving the GMAP program itself, please have a look at the CONTRIBUTING.md in the [main GMAP repository](https://github.com/lacourjansenlab/GMAP).



## Styleguides
### Commit Messages
Commit messages should describe what has been changed, how, and why.


## Join The Project Team
Currently, all team members are members of the [lacourjansenlab](https://github.com/lacourjansenlab) organization, and of the Computational Spectroscopy group in Groningen. Others are still very welcome to contribute to GMAP through any of the means listed above.

<!-- omit in toc -->
## Attribution
This guide is based on the [contributing.md](https://contributing.md/generator)!
