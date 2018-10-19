# SentinelOne Slack Bot

## Alpha Milestones

- [] Basic command interaction (API v2.0 - Central Park+)
- [] Slack user to S1 API key mapping (backend postgresdb)

## Envisioned Commands

*disconnect <hostname>* - Disconnect a computer from the network
*reconnect <hostname>* - Reconnect a computer to the network
*scan <hostname>* - Initiates a full disk scan on the target computer
*hash blacklist <hash> <os> <description>* - Add a hash to the blacklist
*hash whitelist <hash> <os> <description>* - Add a hash to the whitelist
*list applications for <hostname>* - Lists the install applications for a host
*list processes for <hostname>* - Lists the running processes for a host
*list threats* - Lists the open threats
*passphrase <hostname>* - Displays the passphrase for the target computer
*api <key>* - DM me your API key to get started (setup integration)
