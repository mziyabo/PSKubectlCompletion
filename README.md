# PowerShell auto-completion for kubectl
[![powershellgallery](https://img.shields.io/powershellgallery/v/PSKubectlCompletion.svg)](https://www.powershellgallery.com/packages/PSKubectlCompletion)
[![downloads](https://img.shields.io/powershellgallery/dt/PSKubectlCompletion.svg?label=downloads)](https://www.powershellgallery.com/packages/PSKubectlCompletion)

`kubectl` tab-completion for PowerShell. Auto-completion is based on Kubernetes 1.18 client version. 
> **Minimum PowerShell version:** PowerShell 5.1

## Installation from PowerShell Gallery:
`Install-Module -Name PSKubectlCompletion`

## Features and Usage:
Import module and register completions as shown below.

After registering tab-completion use Tab to complete kubectl commands.

``` powershell
Import-Module PSKubectlCompletion
Register-KubectlCompletion
```

## Licence:
Apache-2.0

## Release Notes:
Largely stable but PRs and Issues are welcome.

## Known Issues:
- If you run this on PowerShell Core in Linux you may need to upgrade `PSReadline` to version [2.0.1](https://www.powershellgallery.com/packages/PSReadline/2.0.1).