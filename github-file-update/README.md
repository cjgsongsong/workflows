# [GitHub File Update](../.github/workflows/github-file-update.yaml)

This workflow automates pull request creation in a target repository when updating its GitHub-specific files (e.g. code owner specifications, pull request templates).

## Prerequisites

- Target repository
  - must have already set its upstream branch.
  - must have its visiblity match the visibility of the workflow repository.
  - under `Settings > Actions > General`,
    - under `Workflow permissions`, `Read and write permissions` must have been selected.
    - under `Access`, `Accessible from repositories owned by the user...` must have been selected.
