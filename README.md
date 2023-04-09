# GitHub actions

A collection of GitHub actions to be shared across projects.

# Usage

```sh
- name: Setup runme
  uses: vrunoa/github-actions/runme@base-actions
  with:
    go-version: '1.19'
    runme-version: 'v1.0.0'

- name: Setup node
  uses: vrunoa/github-actions/node@base-actions
    with:
      node-version: '16'
```
