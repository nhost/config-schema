# JSON schema for Nhost `config.yaml`

1. Clone this repo
2. Open with VS code (make sure you have the [Yaml extension installed](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml))
3. Open `config.yaml`. What's red won't be taken into account when using the CLI
4. See [this PR](https://github.com/nhost/nhost-config/pull/1/files#diff-5eeedcdc1cc8716f825d02fb2a490d6b6a7ad41d559285a63a583b6702113ec8)


## Problems
- There is too little documentation about how `config.yaml` works
- Incorrect configuration goes silent
- As Nhost `config.yaml` extends Hasura's, the `version` field is Hasura config's version, not Nhost's 
- the variables hierarchy can be somehow improved
- comma-separated values are strings whereas it could be yaml arrays

