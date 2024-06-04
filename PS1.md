Powershell
============

### Basic 
| Command | Description |
| ------- | ----------- |
| `Test-NetConnection -ComputerName <IP> -Port <#>` | Test connection to destination IP via specific port |
| `Uninstall-WindowsFeature -Name <Feature Name> -Restart` | Uninstall windows feature |
| `Get-WindowsFeature -ComputerName <servername>` | Install feature remotely |


### Exchange
| Command | Description |
| ------- | ----------- |
| `$<database> = Get-MailboxDatabase` | Connect to on prem mailbox |
| `Connect-ExchangeOnline` | Connect to EOL |
| `Set-Mailbox -Identity <UPN> -Type Room` | Set a mailbox to a room resource |
| `Get-Mailbox -Identity <UPN> \| Format-List RecipientTypeDetails` | To see information about mailbox |
| `Set-CalendarProcessing -Identity "<MailboxName>" -AllowConflicts $false` | Auto decline meeting conflicts |

