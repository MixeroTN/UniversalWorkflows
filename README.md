# Universal GitHub Actions Workflows

Contains the following:

- `auto_assign.yml + auto_assign_config.yml` - automatically assigns the creator of the pull request on creation.
Useful when PRs are treated like a logs rather than requests where you are assigning someone else to look at it.
- `released_label_pr` - Requires at least the `Released` label present but also checks for `Prerelease` one.
Adds the `Released` label to merged PR when none of following labels are present: `Released`, `Prerelease`.
**Look [here](https://github.com/MixeroTN/github-label-presets) to add these labels to your repo!**

Additionally contains:

- `.editorconfig` - settings for YAML files, some editors like VS Code requires the extension.
