# AzooEmptyModuleForTesting

## ORAS

Download the `.nupkg` without running `oras login`:

```shell
export module_version=0.0.2-preview3
```

```shell
oras pull ghcr.io/azoosystems/azooemptymodulefortesting:$module_version --output ./artifacts
```
