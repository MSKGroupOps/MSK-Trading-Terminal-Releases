# MSK Trading Terminal — Official Windows Releases

This public repository contains **signed Windows installers and automatic-update metadata only** for MSK Trading Terminal.

## Install

When a production release is available, open **Releases**, select the latest approved version, and download the single Windows installer:

`MSK-Trading-Terminal-Setup-<version>.exe`

Verify that Windows displays the expected MSK publisher before running it.

## Automatic updates

Installed production versions retrieve approved update metadata and signed installers anonymously from this repository. No GitHub account or token is required on the installed PC.

Production publication is deliberate. Ordinary development pushes do not create releases, and unsigned candidates are rejected by the application.

## Repository boundary

Private source code, credentials, API keys, databases, logs, development dependencies, and user data are never published here. Development takes place in a separate private source repository.

No production release has been published yet. The first release will appear only after the Windows Authenticode signing identity and release certification gates are complete.