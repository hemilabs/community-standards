# Contributing to Hemi

Thank you for your interest in contributing!

The following describes the guidelines to contribute to the Hemi open-source projects.
The purpose of this document is to create a contribution process that:

- Encourages new community contributions.
- Encourages contributors to remain involved.
- Avoids unnecessary processes and bureaucracy whenever possible.
- Creates a transparent decision making process that makes it clear how contributors can be involved in decision making.

## Table of Contents

How can I contribute?

1. Fork and Edit
2. Code and Documentation Style Guides
3. Reporting Bugs
4. Suggesting Enhancements
5. Pull Requests
6. Translating Contents

### 1. Fork and Edit

To contribute to any repository you will need to fork it, make changes, and submit a pull request.
This section is a brief guide on how to do this whilst making sure your forked repository stays up to date the with the source one.

- Fork the repository to your own GitHub account and then clone it to your local device.
- Create a new branch: `git checkout -b MY_BRANCH_NAME`.
- Follow the next steps detailed in the README.md file.

### 2. Code and Documentation Style Guides

Most of our repos already include [ESLint](https://eslint.org/), [Prettier](https://prettier.io/) and lint-staged.
Every time you commit and push your contributions, all code should stylized automatically.

If that is not the case, here is a summary of the styles we use:

- Code: [eslint-config-bloq](https://www.npmjs.com/package/eslint-config-bloq) and [Prettier](https://prettier.io/)'s defaults.
- Documentation: [markdownlint](https://www.npmjs.com/package/markdownlint) defaults.
- Git Commits: [commitlint](https://www.npmjs.com/package/@commitlint/cli) and [The seven rules of a great Git commit message](https://cbea.ms/git-commit/#seven-rules).

### 3. Reporting Bugs

First of all make sure that the bug was not already reported by searching on GitHub under `Issues` in the corresponding repository.
When you are creating a bug report, label it as `bug` and include as many details as possible.

General tips:

- If you're unable to find an open issue addressing the problem, open a new one. Be sure to include a title and clear description, as much relevant information as possible, and a code sample or an executable test case demonstrating the expected behavior that is not occurring.
- Determine which repository the problem should be reported in.
- Perform a cursory search to see if the problem has already been reported. If it has and the issue is still open, add a comment to the existing issue instead of opening a new one.
- Provide a step-by-step description of the suggested enhancement in as many details as possible.
- Provide specific examples to demonstrate the steps. When applicable include snippets which you use in those steps, as Markdown code blocks.
- Describe the current behavior and explain which behavior you expected to see instead and why.
- Include screenshots and/or animated GIFs which help you demonstrate the steps or point out the part of the app which the issue is related to.
- Specify the name and version of the OS/Browser/other applicable software you're using.

Note that any security vulnerability must be treated as confidential.
Do not open up a GitHub issue if the bug is a security vulnerability, and instead refer to our [Security Policy](SECURITY.md).

If you are unable to open an issue in GitHub, we encourage you to report the bug in one of the following methods:

- E-mail [support@hemi.xyz](mailto:support@hemi.xyz) with the subject line, "Hemi Bug Report".
- Join our [Discord](https://discord.gg/hemixyz) and report the error in the #help channel.

### 4. Suggesting Enhancements

This section guides you through submitting an enhancement suggestion, including completely new features and minor improvements to existing functionality.
Following these guidelines helps maintainers and the community understand your suggestion and find related suggestions.

First, check if there is already an existing request which provides that enhancement by searching on GitHub under `Issues` in the corresponding repository.

If there is none, validate it with the community.
Our official channels are:

- [Discord](https://discord.gg/hemixyz)
- [Twitter](https://twitter.com/hemi_xyz)

Finally, file a new feature request by opening an issue. Label it as `enhancement`.

General tips:

- Use a clear and descriptive title to identify the suggestion.
- Provide a step-by-step description of the suggested enhancement in as many details as possible.
- Provide specific examples to demonstrate the steps. Include snippets which you use in those examples, as Markdown code blocks.
- Describe the current behavior and explain which behavior you expected to see instead and why.
- Include screenshots and/or animated GIFs which help you demonstrate the steps or point out the part of the app which the suggestion is related to.
- Explain why this enhancement would be useful to most users.
- Specify the name and version of the OS/Browser/other applicable software you're using.

### 5. Pull Requests

The process described here has several goals:

- Maintain repository quality.
- Fix problems that are important to users.
- Engage the community in working toward the best possible product.
- Enable a sustainable system for maintainers to review contributions.

Please follow these steps to have your contribution considered by the maintainers:

- Follow all instructions in the Pull Request template.
- Follow the style guides described above.
- If the pull request features a UI improvement, please include a screenshot in order to let maintainers to have a glimpse of it.
- After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing.

Note: If a status check is failing and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe so.
A maintainer will re-run the status check for you.
If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.

While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

### 6. Translating Contents

We are happy to have people volunteer to help with translations.
Contact us in [Discord](https://discord.gg/hemixyz), [Twitter](https://twitter.com/hemi_xyz) or send us an e-mail to [support@hemi.xyz](mailto:support@hemi.xyz) to identify what is the best way to mode forward.
