# Scoop Bucket for Windows Server Apps

<!-- Uncomment the following line after replacing placeholders -->
[![Build Status](https://ci.appveyor.com/api/projects/status/tj68se0eicusq5w8?svg=true)](https://ci.appveyor.com/project/rr0001/scoop-srv-bucket "Build Status") [![Excavator](https://github.com/rr0001/scoop-srv-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/rr0001/scoop-srv-bucket/actions/workflows/excavator.yml)

Based on the Template bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## General Info

*ADMIN RIGHTS* is **REQUIRED** for proper windows service installation of the applications. Some will also require NSSM to be installed in the system.

## Featured Apps

Manifest | Description
---------|------------
caddy | Caddy Web Server
oic21 | Oracle Instant Client 21
pg14 | PostgreSQL server v14
php81-nts | PHP 8.1 NTS
php81-xdebug | PHP 8.1 xDebug

## How do I install these manifests?

To add this bucket, run `scoop bucket add srv https://github.com/rr0001/scoop-srv-bucket`. To install, do `scoop install <manifest>`.

## How do I contribute new manifests?

To make a new manifest contribution, please read the [Contributing Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md).

----
