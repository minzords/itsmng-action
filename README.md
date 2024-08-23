# Usage
```yml
name: "Continuous integration"

on:
  pull_request:

jobs:
  ci:
    uses: "minzords/itsmng-action/.github/workflows/plugininstall.yml@main"
    with:
      # plugin name
      plugin-key: "myplugin"
      # Github organization or user name
      repository: "itsmng"
```