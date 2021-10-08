# sfdx-version-updater

This Github Action is a helper action to update the version number in `sfdx-project.json`. Forked from [trailheadapps/github-action-sfdx-packaging-updater](https://github.com/trailheadapps/github-action-sfdx-packaging-updater). All credits goes to [trailheadapps](https://github.com/trailheadapps).

## Outputs

This action provides one output:

-   `isSuccess` - true if the result status code equals 0.

## Example

```yml
# Update sfdx-project.json version number (e.g., 0.9.0.NEXT to 0.10.0.NEXT)
- name: 'Extract package:version:create result data'
  id: version-updater
  uses: johnforeland/github-action-check-updated-files-for-substring
```
