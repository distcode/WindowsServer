# Practice: Install Windows Server with Desktop Experience manually

## Task

Run ````C:\Labs\Resources\New-VM.ps1 VN1-SRV20```` to create a new VM and install Windows Server Datacenter Edition with Desktop Experience on it.

## Instructions

Perform these steps on the host.

1. Run **Windows PowerShell** as Administrator.
1. In Windows PowerShell, execute

    ````powershell
    C:\Labs\Resources\New-VM.ps1 -Name VN1-SRV20
    ````

1. In **Hyper-V Manager**, double-click **WIN-VN1-SRV20** to open the console.
1. In WIN-VN1-SRV20 on ... - Virtual Machine Connection, in the menu, click **Media**, **DVD Drive**, **Insert Disk...**
1. In Open, open **C:\\Labs\\ISOs\\2022_x64_EN_Eval.iso**.
1. In **WIN-VN1-SRV20 on ... - Virtual Machine Connection**, click **Start**.
1. In **Microsoft Server Operating Ssystem Setup**, configure **Time and currency format** and the **Keyboard or input method** as you wish and click **Next**.
1. Click **Install now**.
1. In **Select the operating system you want to install**, click **Windows Server 2022 Datacenter Evaluation (Desktop Experience)** and click **Next**.
1. In **Applicable notices and license terms**, click **I accept the Microsoft Software License Terms. If an organization is licensing it, I am autohrized to bind the organization**, and click **Next**.
1. In **Which type of installation do you want?**, click **Custom: Install Microsoft Server Operating System only (advanced)**.
1. In **Where do you want to install the opearting system?**, click **Next**.

Do not wait for the installation to finish.

[Back to Overview](../WinGLA.md)
