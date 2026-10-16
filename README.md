# NoxCipher Tools

Small browser tools for SOC work on Microsoft Sentinel, Entra and firewalls.

- **Live:** https://tools.noxcipher.site

| Tool | Link |
|---|---|
| CEF parser: CEF line to CommonSecurityLog columns and KQL | `#cef` |
| AMA connectivity planner: endpoints, DNS zones, AMPLS and Arc private link | `#ama` |
| DCR builder: AMA data collection rule JSON and deploy commands | `#dcr` |
| Firewall rule builder: FortiGate, PAN-OS and Azure NSG from one definition | `#fw` |
| Time converter: epoch, ISO, FILETIME, KQL datetime | `#time` |
| CIDR calculator | `#cidr` |
| JWT decoder: Entra token claims explained | `#jwt` |
| Encoder / decoder: Base64, URL, hex, PowerShell -EncodedCommand | `#encode` |

Everything runs client-side in one static `index.html`. Nothing you paste is uploaded.

Endpoint and DCR guidance is based on Microsoft Learn; check the docs before production changes.

## License

MIT
