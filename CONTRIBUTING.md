# Contributing

Thank you for your interest in contributing! The following sections describe
ways to get involved.

## Code of conduct

Please review and follow our [code of conduct](CODE_OF_CONDUCT.md).

## Feedback

User feedback is the most valuable to us. It's a great way to start
contributing!

-   [File new issues](https://github.com/material-components/material-web/issues/new/choose)
    for bugs you run into or feature requests you have.

-   [Create a discussion](https://github.com/material-components/material-web/discussions/new/choose)
    for help, feedback on changes, or feature proposals.

## Discord

Join the `#material` channel on [Lit's Discord](https://lit.dev/discord) to chat
directly with the team and other users.

## Pull requests

Pull requests are welcome! Keep a few things in mind:

-   Create an
    [issue](https://github.com/material-components/material-web/issues/new/choose)
    or
    [discussion](https://github.com/material-components/material-web/discussions/new/choose)
    before opening a pull request.
-   Trivial changes, such as documentation, don't need an issue.
-   Create draft PRs in the `@material/web/labs` folder for new features.
-   Please be patient! It may take a while for the team to review. Keep changes
    small and scoped to speed things up.

### New components

Please understand that new component implementations are difficult for us to
directly accept. They need to complete several engineer, design, and
accessibility reviews that are not easy with our externally available workflows.

If you want to help build a new component, create a
[new discussion](https://github.com/material-components/material-web/discussions/new/choose).
Add any design docs, code samples, reference implementations in draft PRs, and
get community feedback.

### Material Web Community guidelines
We have created this project to be a community-driven effort to maintain and improve the M3 web components. We encourage contributions from anyone who wants to help.
Every change must be pushed to a separate branch (checked out from the `main` branch), and we will review it before merging it into the `main-fork` branch (the main branch of this fork). This way, we can keep track of all the changes made by the community and ensure that they are compatible with the original repo.
Then that braanch can be used to create a PR to the original repo (M3 web) if needed and `main-fork` can be used to publish new versions of the components to npm faster.
This way we are covered in both cases:
- M3 web (original repo) will be maintained
- M3 web will be discontinued/deprecated

Name template for branches: `feat/<component-name>/<description>` or `fix/<component-name>/<description>` (or some other type of change). If your change is not related to a specific component, you can create a branch with a more general name like `feat/<description>` or `fix/<description>`.

### Contributor License Agreement

Code contributions must
[sign Google's CLA](https://cla.developers.google.com/clas). When you open a
pull request, our friendly bot will check and provide help if you haven't
signed.

[Set your email in git](https://help.github.com/articles/setting-your-email-in-git/)
to the same email used to sign the CLA.
