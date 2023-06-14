# How to upgrade the version

- Run `yarn changesets`, and describe you change. 
- Commit the `.md` file generated by `changeset` together with your code changes. And merge your change.
- Github Workflow will create a PR to change the version in `package.json`.
- Github Workflow will publish a new version to NPM after we merge the PR.

# Changesets

Hello and welcome! This folder has been automatically generated by `@changesets/cli`, a build tool that works
with multi-package repos, or single-package repos to help you version and publish your code. You can
find the full documentation for it [in our repository](https://github.com/changesets/changesets)

We have a quick list of common questions to get you started engaging with this project in
[our documentation](https://github.com/changesets/changesets/blob/main/docs/common-questions.md)