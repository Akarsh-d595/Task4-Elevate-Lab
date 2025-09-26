# Windows Firewall Setup (PowerShell & GUI)

## 1. List existing rules
```powershell
Get-NetFirewallRule | Format-Table -Property DisplayName, Direction, Action, Enabled -AutoSize
