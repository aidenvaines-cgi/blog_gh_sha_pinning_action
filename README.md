# Hello World GitHub Action

This repository contains a very simple GitHub Action that prints:

Hello World

## Usage

```yaml
name: Example
on: [push]

jobs:
  demo:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: avaines/blog_gh_sha_pinning_action@1.0.0
```
