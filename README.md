# traceable-identifier-action

Generate traceable identifier optimized for GitHub Actions.

<!-- actdocs start -->

## Description

This action generates a traceable identifier optimized for use with GitHub Actions.
The identifier contains the following information:

- **Timestamp**: the date-time indicating when the action was invoked
- **Job id**: the id of the current job
- **Workflow run id**: a unique number for each workflow run within a repository
- **Workflow run attempt**: a unique number for each attempt of a particular workflow run in a repository
- **Commit SHA**: the commit SHA that triggered the workflow
- **Actor id**: the account id of the person or app that triggered the initial workflow run
- **Random value**: a random string generated for each action execution

## Usage

```yaml
  steps:
    - name: Traceable Identifier
      uses: tmknom/traceable-identifier-action@v0
```

## Inputs

N/A

## Outputs

| Name | Description |
| :--- | :---------- |
| identifier | Generated traceable identifier. |

<!-- actdocs end -->

## Permissions

N/A

## FAQ

N/A

## Related projects

N/A

## Release notes

See [GitHub Releases][releases].

## License

Apache 2 Licensed. See [LICENSE](LICENSE) for full details.

[releases]: https://github.com/tmknom/traceable-identifier-action/releases
