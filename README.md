# Humorist Bucket

[![Tests](https://github.com/Humorist7336/bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/Humorist7336/bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/Humorist7336/bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/Humorist7336/bucket/actions/workflows/excavator.yml)

Bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add Humorist7336_bucket https://github.com/Humorist7336/bucket
scoop install humorist-bucket/<manifestname>
```

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing
Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md)
and [App Manifests](https://github.com/ScoopInstaller/Scoop/wiki/App-Manifests)
wiki page.
