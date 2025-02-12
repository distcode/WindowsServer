# Practice: Install Windows Terminal

## Required VMs

* VN1-SRV1
* VN2-SRV1

## Introduction

Install Windows Terminal on VN2-SRV1.

## Instructions

Perform these steps on VN2-SRV1.

1. Logon as **ad\Administrator**.
1. In Microsoft Edge, navigate to https://github.com/microsoft/terminal/releases.
1. Find the latest version.
1. Download the files **Microsoft.Windows.Terminal.\*.msixbundle** and **Microsoft.WindowsTerminal.\*_PreInstallKit**.
1. Run **Windows PowerShell** as Administrator.
1. Change to the **Downloads** folder.

    ````powershell
    Set-Location $env:USERPROFILE\Downloads
    ````

1. Expand the zip file **Microsoft.WindowsTerminal_Win10_\*PreinstallKit.zip**

    ````powershell
    Expand-Archive `
        .\Microsoft.WindowsTerminal_*.msixbundle_Windows10_PreinstallKit.zip
    ````

1. Change to the folder of the extracted preinstall kit.

    ````powershell
    Set-Location `
        .\Microsoft.WindowsTerminal_*.msixbundle_Windows10_PreinstallKit
    ````

1. Install the preinstall kit.

    ````powershell
    Add-AppxPackage Microsoft.UI.Xaml.*_x64__*.appx
    ````

1. Change to the folder of the downloaded Windows Terminal.

    ````powershell
    Set-Location ..
    ````

1. Install Windows Terminal

    ````powershell
    Add-AppxPackage Microsoft.WindowsTerminal_*.msixbundle
    ````

[Back to Overview](../WinGLA.md)