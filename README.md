# PowerShell <--> Bash Equivalent Command Cheat Sheet

PowerShell commands are with PowerShell 5.1 running on Windows 10 Pro (version 1903)

    PS C:\Users\kcsha> $PSversionTable
    
    Name                           Value
    ----                           -----
    PSVersion                      5.1.18362.145
    PSEdition                      Desktop
    PSCompatibleVersions           {1.0, 2.0, 3.0, 4.0...}
    BuildVersion                   10.0.18362.145
    CLRVersion                     4.0.30319.42000
    WSManStackVersion              3.0
    PSRemotingProtocolVersion      2.3
    SerializationVersion           1.1.0.1


Bash is tested with `git-bash` v2.23.0 installation on Windows 10 Pro (version 1903)

    admin@w10-pc5 MINGW64 ~
    $ sh -version
    GNU bash, version 4.4.23(1)-release (x86_64-pc-msys)
    Copyright (C) 2016 Free Software Foundation, Inc.
    License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>
    
    This is free software; you are free to change and redistribute it.
    There is NO WARRANTY, to the extent permitted by law.



| Action | PowerShell  | Bash   | Difference |
|---|---|---|---|
| Find executable | `get-command <cmd>`   | `which <cmd>`  |   |
| Find shell version  | `$PSversionTable`   | `sh -version`  |   |
|   |   |   |   |
