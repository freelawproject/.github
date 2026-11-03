# Contributing to Free Law Project

Thanks for your interest in contributing! Please start with our [developer guide](https://wiki.free.law/c/courtlistener/dev-guide/getting-started), which covers setup, our contribution guidelines, and the Contributor License Agreement. Some repositories have their own CONTRIBUTING.md with project-specific details.

## Finding something to work on

Look for [issues labeled `good first issue` or `help wanted`](https://github.com/search?q=org%3Afreelawproject+label%3A%22good+first+issue%22%2C%22help+wanted%22+state%3Aopen&type=issues), or check our [volunteer project board](https://github.com/orgs/freelawproject/projects/31/views/1/).

Many volunteers may want the same issue, so **comment on it before you start**, and check that nobody else has claimed it. For new features or large changes, open an issue to discuss them before writing code.

## Guidelines for contributions

Here's a summary. The [developer guide](https://wiki.free.law/c/courtlistener/dev-guide/getting-started#guidelines-for-contributions) covers each of these in more detail.

We use [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow). In practice, that means:

- Nearly everything you do should have an issue. Name your branch `<issue-number>-short-description-YYYYMMDD`, for example `123-fix-date-parsing-20260115`, with no dashes in the date. If a change is too small to need an issue, name the branch `tweak-<description>`, such as `tweak-fix-typo`.
- Each commit should be a unit of work. Clean up experimental commits with an interactive rebase before you open the PR.
- Once review has started, don't force push. A messy commit log during review is better than making your reviewer re-read the whole PR to find what changed.
- Write commit messages in the [Conventional Commits](https://www.conventionalcommits.org/) format, such as `fix(search): Handle empty queries`. Long explanations in the body are welcome.
- If your PR changes anything visual, include a screenshot or GIF.
- Keep PRs small. A good PR lands one specific thing cleanly, even if the larger feature isn't finished yet.
- If the repository has a `.pre-commit-config.yaml`, install [pre-commit](https://pre-commit.com/) and run `pre-commit run --all-files` before pushing.
- The first time you contribute to any of our repositories, a bot will ask you to sign our Contributor License Agreement.

## Interacting with FLP staff

Your contributions will be reviewed by FLP staff. Note that code review may be slow due to competing priorities. We'll do our best to keep you updated, but if your issue or pull request hasn't gotten a response in a while, feel free to tag a maintainer as a reminder.

If you get stuck or have a question, ask in a comment on the issue you're working on, or in [GitHub Discussions](https://github.com/freelawproject/courtlistener/discussions).

## Using AI tools

You're welcome to use AI tools, but a person must stand behind every contribution. Please read our [AI policies for volunteers](https://wiki.free.law/c/ai-policies-resources/policies/artificial-intelligence-policies-for-volunteers-working-with-free-law-project) first.

## Security issues

Don't report vulnerabilities in public issues. Follow our [vulnerability disclosure policy](https://free.law/vulnerability-disclosure-policy/) instead.
