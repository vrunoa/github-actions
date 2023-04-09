# GitHub actions

A collection of GitHub actions to be shared across projects.

# Usage

```sh
- name: Setup runme
  uses: vrunoa/github-actions/runme@main
  with:
    go-version: '1.19'
    runme-version: 'v1.0.0'

- name: Setup node
  uses: vrunoa/github-actions/node@main
    with:
      node-version: '16'
```
