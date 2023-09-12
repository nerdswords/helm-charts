# Releasing a new chart version

- Create a branch that contains the new release version name, e.g. `<yourname>/release-1.2.3`
- Update the `Chart.yaml` file with the desired `version` and `appVersion`
- Make sure to run `helm-docs` from the root directory
- On merge, the `chart-releaser-action` will create a new tag and update the `index.yaml` file in branch `gh-pages`
