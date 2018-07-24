#### Name

Windows - Get JCagent.log | v1.0 JCCG

#### commandType

windows

#### Command

```
Get-content -Path 'C:\Windows\Temp\jcagent.log'
```

#### Description

Returns the jcagent.log from a Windows system. If the jcagent.log is larger than 1 MB the most recent 1 MB of data from the log will be returned.

#### *Import This Command*

To import this command into your JumpCloud tenant run the below command using the [JumpCloud PowerShell Module](https://github.com/TheJumpCloud/support/wiki/Installing-the-JumpCloud-PowerShell-Module)

```
Import-JCCommand -URL 'https://git.io/jccg-Windows-GetJCagent.log'
```
