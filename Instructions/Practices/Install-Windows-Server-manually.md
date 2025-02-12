# Practice: Install Windows Server manually

## Task

Run ````C:\Labs\Resources\New-VM.ps1 -Name VN1-SRV21```` to create a new VM and install Windows Server Datacenter Edition on it.

## Instructions

Perform these steps on the host.

1. Run **Windows PowerShell** as Administrator.
1. In Windows PowerShell, execute

    ````powershell
    C:\Labs\Resources\New-VM.ps1 -Name VN1-SRV21
    ````

1. In **Hyper-V Manager**, double-click **WIN-VN1-SRV21** to open the console.
1. In WIN-VN1-SRV21 on ... - Virtual Machine Connection, in the menu, click **Media**, **DVD Drive**, **Insert Disk...**
1. In Open, open **C:\\Labs\\ISOs\\2022_x64_EN_Eval.iso**.
1. In **WIN-VN1-SRV21 on ... - Virtual Machine Connection**, click **Start**.
1. In Microsoft Server Operating System Setup, configure **Time and currency format** and the **Keyboard or input method** as you wish and click **Next**.
1. Click **Install now**.
1. On page Select the operating system you want to install, click **Windows Server 2022 Datacenter Evaluation** and click **Next**.
1. On page Applicable notices and license terms, click **I accept the Microsoft Software License Terms. If an organization is licensing it, I am autohrized to bind the organization**, and click **Next**.
1. On page Which type of installation do you want, click **Custom: Install Microsoft Server Operating System only (advanced)**.
1. On page Where do you want to install the operating system, click **Next**.

Do not wait for the installation to finish.

[Back to Overview](../WinGLA.md)