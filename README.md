[![Codacy Badge](https://app.codacy.com/project/badge/Grade/b166179a80574a7882bf7d4a8e9b3fea)](https://app.codacy.com/gh/Mathmagicians/codacy/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)

# How to Execute a GitHub Action with Codacy Scanning
This guide will walk you through the steps to execute a GitHub Action that uses Codacy for scanning your code.

This example utilize the trial [app.codacy.com](https://app.codacy.com) service but the concept is identical for the payed version.

## Prerequisites

- An account on [app.codacy.com](https://www.sonarsource.com/products/sonarcloud/) tied to your github organization.
- In the organization add (this) repository.
- In repository, go to `Settings > General > Repository analysis on your server` and and enable run `Run analysis on build server`

## Steps

1. Commit and push the changes to your repository.

You can find the results [here](https://github.com/Mathmagicians/codacy/security/code-scanning) or at the [codacy](https://app.codacy.com/gh/Mathmagicians/codacy/dashboard)
          