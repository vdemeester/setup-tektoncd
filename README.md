# setup-tektoncd

An action to setup tekton on a kubernetes instance in a GitHub workflow

```yaml
- uses: vdemeester/setup-tektoncd@main
  with:
    # Version is the version of tektoncd/pipeline to install.
    # For example, v0.37.5
    # Required.
    pipeline: v0.40.x
    # Pipeline features
    # For example, {"enable-api-fields": "alpha"}
    pipeline-feature-flags: '{}'
```
