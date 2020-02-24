# Inline ESLint

This Github Action runs ESLint on Gatsby and reports errors inline in any PR.

## Updating

Since we are running in a mono-repo changes will need to be made in two steps (no publishing is required).

The first commit to master is to update the Action code. The second commit is to update the location of the action (which requires the specific commit hash to use).

To test changes in a PR, fork the repo and point gatsby/.github/workflows/lint.yml to your Gatsby PR branch to your fork. That should cover it.
