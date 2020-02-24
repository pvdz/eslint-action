# Inline ESLint

This Github Action runs ESLint on Gatsby and reports errors inline in any PR.

## Updating

By default the linting points to the master branch but for your test you'll need to change the location in `gatsby/.github/workflows/lint.yml` to point to your branch, rather than `@master`.

After that it should use your branch as source of truth for the lint action.
