# Awesome Octoherd Scripts [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


[<img src="https://raw.githubusercontent.com/octoherd/octoherd/main/assets/octoherd-flipped.gif">](https://github.com/octoherd/octoherd)

> Carefully curated list of awesome Octoherd scripts for GitHub automation.

Octoherd is a framework that allows you to run a script (written in JavaScript) against multiple GitHub repositories. This list contains the most awesome Octoherd scripts to help you manage multiple repositories as a maintainer.

Contributions welcome. Add links through pull requests or create an issue to start a discussion.

## Contents

- [Writing your own scripts](#writing-your-own-scripts)
- [Tools](#tools)
- [Scripts](#Scripts)

## Writing your own scripts
- [Create new Octoherd Script](https://github.com/octoherd/create-octoherd-script) - CLI to create a new folder and repository for an Octoherd Script.
- [Hello world](https://github.com/octoherd/script-hello-world) - The "Hello, World!" of all Octoherd Scripts!

## Tools
- [Repo Meister](https://repomeister.com) - Run Octoherd scripts from your browser, Repo Meister makes GitHub repository management easy for everyone.

## Scripts

- [Rename master branch to main](https://github.com/octoherd/script-rename-master-branch-to-main) - Renames the default branch to main if it is currently set to master.
- [Sync branch protections](https://github.com/octoherd/script-sync-branch-protections) - Apply branch protection settings from one repository to others.
- [Close renovate dashboard issues](https://github.com/octoherd/script-close-renovate-dashboard-issues) - Close all Renovate Dashboard issues.
- [Set PR merge config](https://github.com/MunifTanjim/octoherd-script-set-pr-merge-config) - Set pull request merge config.
- [Add cache to Node GitHub action](https://github.com/oscard0m/octoherd-script-add-cache-to-node-github-action) - Add cache parameter to GitHub Actions using setup-node.
- [Validate contribution](https://github.com/bdougie/octoherd-script-validate-contribution) - Validate contributions.
- [Copy labels](https://github.com/bdougie/octoherd-script-copy-labels) - Copy labels from one repo to the next.
- [Add Octoherd CLI to script](https://github.com/octoherd/script-add-octoherd-cli-to-script) - Upgrade Octoherd scripts to use the built-in CLI.
- [Create repositories from folder](https://github.com/octoherd/script-create-repositories-from-script-folders) - Creates new repositories from folders.
- [Bump Node version in workflows](https://github.com/gr2m/octoherd-script-bump-node-version-in-workflows) - Set the node-version input for actions/setup-node to the latest LTS major version.
- [Star/unstar repository](https://github.com/octoherd/script-star-or-unstar) - Add or remove GitHub repository star.
- [Remove dependabot](https://github.com/octoherd/script-remove-dependabot) - Delete the `.github/dependabot.yml` file.
- [Sync repository settings](https://github.com/oscard0m/octoherd-script-sync-repo-settings) - Takes Repository Options from a Repository passed as argument and apply same Options to other repositories.
- [Watch, unwatch or ignore repositories](https://github.com/oscard0m/octoherd-script-watch-unwatch-or-ignore) - Watch, unwatch or ignore repositories.
- [Find releases](https://github.com/octoherd/script-find-releases) - Find GitHub releases.
- [Setup renovate](https://github.com/octoherd/script-setup-renovate) - Setup renovate.
- [Remove required CI check](https://github.com/octoherd/script-remove-required-ci-check) - Remove a required status check from all protected branches.
- [Security analysis](https://github.com/stoe/octoherd-script-security-analysis) - Enable security and analysis features.
- [Repo settings](https://github.com/stoe/octoherd-repo-settings) - Apply my default settings.
- [Fix prettier update](https://github.com/wolfy1339/octoherd-script-fix-prettier-update) - update the `.github/workflows/update-prettier.yml` file with the branch name for renovate.
- [Delete repository](https://github.com/octoherd/script-delete-repository) - Delete repositories.
- [Remove topics](https://github.com/gr2m/octoherd-script-remove-topics) - Remove topic(s) from repositories.
- [Merge Pull Requests](https://github.com/gr2m/octoherd-script-merge-pull-requests) - Merge a bunch of pull requests based on parameters.
- [Organization setup](https://github.com/MadJlzz/octoherd-script-organization-setup) - Configure default settings for a repositories within an organization.
- [Rename labels](https://github.com/gr2m/octoherd-script-rename-labels) - Rename a multiple labels in a repository using find & replace.
- [Replace all repository topics](https://github.com/oscard0m/octoherd-script-replace-all-repository-topics) - Replace all repository topics.
- [Sync labels](https://github.com/stoe/octoherd-script-sync-labels) - Sync labels accross repositories.
- [Normalize package repository field](https://github.com/gr2m/octoherd-script-normalize-package-repository-field) - Remove redundant information from repository, homepage, bugs fields in `package.json`.
