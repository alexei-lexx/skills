---
name: bump-version
description: "Bump the plugin version in this repo and commit it on the default branch. Use when the user asks to bump, release, or raise the version, or says 'new version' or 'cut a release'."
---

# bump-version

- If the current branch is not the default branch, stop
- Read the commits after the last version change
- Select the level:
  - major, if the commits remove or rename a skill
  - minor, if the commits add a skill
  - patch, for all other changes
- Increase the version in `.claude-plugin/plugin.json` by the level
- Write the same version in `package.json`
- Run `npm install` to update `package-lock.json`
- Commit with the message `bump version to <new version>`
