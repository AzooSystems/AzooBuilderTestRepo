# AzooEmptyModuleForTesting

## ORAS

Download the `.nupkg` without running `oras login`:

```shell
export module_version=0.0.2-preview3
```

```shell
oras pull docker pull ghcr.io/azoosystems/azooemptymodulefortesting:$module_version --output ./artifacts
```

Replace `organization`, `package-name`, and `1.2.3` with the published GHCR
organization, lower-case package name, and version. ORAS writes the original
`.nupkg` file into `./artifacts`.
