# Scoop Bucket Template

<!-- Uncomment the following line after replacing placeholders -->
[![Build Status](https://ci.appveyor.com/api/projects/status/tj68se0eicusq5w8?svg=true)](https://ci.appveyor.com/project/rr0001/scoop-srv-bucket "Build Status") [![Excavator](https://github.com/rr0001/scoop-srv-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/rr0001/scoop-srv-bucket/actions/workflows/excavator.yml)

Template bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

How do I install these manifests?
---------------------------------

To add this bucket, run `scoop bucket add scoop-srv-bucket https://github.com/rr0001/scoop-srv-bucket`. To install, do `scoop install <manifest>`.

How do I contribute new manifests?
----------------------------------

To make a new manifest contribution, please read the [Contributing Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md).

----

#### To use this template

- Modify the Readme.md and the bin/auto-pr.ps1 files accordingly.
- Enable GitHub Actions for this repository.
- Login to AppVeyor and import this repository.
