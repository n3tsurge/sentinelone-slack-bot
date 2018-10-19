# SentinelOne Slack Bot

## Alpha Milestones

- [ ] Basic command interaction (API v2.0 - Central Park+)
- [ ] Slack user to S1 API key mapping (backend postgresdb)

## Envisioned Commands

Action | Command | Description
--- | --- | ---
Disconnect Host | *disconnect <hostname>* | Disconnect a computer from the network
Reconnect Host | *reconnect <hostname>* | Reconnect a computer to the network
Scan Host | *scan <hostname>* | Initiates a full disk scan on the target computer
Blacklist Hash | *hash blacklist <hash> <os> <description>* | Add a hash to the blacklist
Whitelist Hash | *hash whitelist <hash> <os> <description>* | Add a hash to the whitelist
List Applications | *list applications for <hostname>* | Lists the install applications for a host
List Processes | *list processes for <hostname>* | Lists the running processes for a host
List Threats | *list threats* | Lists the open threats
Get Host Passphrase | *passphrase <hostname>* | Displays the passphrase for the target computer
Configure Intergration | *api <key>* | DM me your API key to get started (setup integration)
