CMD
============

### Basic 
| Command | Description |
| ------- | ----------- |
| `ping -a <ip address>` | Resolves FQDN from IP |
| `sfc /scannow` | System file checker |
| `gpresult /user <username> /scope computer /h c:\temp\gpr.html` | Get gpresult of ADM account |
| `gpresult /scope <computer> /h c:\temp\gpr.html` | Get gpresult of computer |
| `dism /online /set-edition:serverstandard /productkey:<key> /accepteula` | CMD to activate product key |

### Networking
| Command | Description |
| ------- | ----------- |
| `ipconfig /release` | Releases IP |
| `ipconfig /renew` | Renew IP |
| `ipconfig /flushdns` | Flush DNS cache |
| `netsh winsock reset` | Undo configurations made to the Winsock Catalo |
| `netsh int ip reset` |  Rewrites the rules, resetting it to factory default, that are followed by devices to connect to the internet |
| `netsh advfirewall reset` | Reset Windows firewall |
| `ipconfig /release` | Releases IP |
| `ipconfig /renew` | Renew IP |
| `netsh interface ipv6 show prefixpolicies` | Show ipv6 prefix policies |
| `netsh interface ipv6 set prefixpolicy ::ffff:0:0/96 46 4` | Prioritize ipv4 |

