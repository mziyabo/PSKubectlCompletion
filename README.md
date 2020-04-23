# PowerShell auto-completion for kubectl
[![powershellgallery](https://img.shields.io/powershellgallery/v/PSKubectlCompletion.svg)](https://www.powershellgallery.com/packages/PSKubectlCompletion)
[![downloads](https://img.shields.io/powershellgallery/dt/PSKubectlCompletion.svg?label=downloads)](https://www.powershellgallery.com/packages/PSKubectlCompletion)

`kubectl` command auto-completion for `PowerShell 5.1` and `PowerShell Core 6.0` and higher. Auto-completion is based on Kubernetes 1.18 client version.

## Installation from PowerShell Gallery:
`Install-Module -Name PSKubectlCompletion`

## Features and Usage:
Import module and register completions as shown below.

After registering tab-completion use kubectl` with <TAB>'s to complete commands.

``` powershell
Import-Module PSKubectlCompletion
Register-KubectlCompletion
```

## Licence:
Apache-2.0

## Release Notes: 
🚧 Prelease Version 🚧
Module is largely complete but if you have any issues- PRs and issues are welcome.

## Known Issues:
- If you run this on PowerShell Core in Linux you may need to upgrade `PSReadline` to version [2.0.1](https://www.powershellgallery.com/packages/PSReadline/2.0.1).