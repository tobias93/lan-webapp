Small Flask webapp for the LAN

- Reads server info using node-gamedig (via bash) and exposes it to `/game`
- Reads messages from a config file and exposes them to `/status`
- Serves webapp that polls these API for updates

The Frontend is mostly okay, but could use refactoring. Backend works (and is surprisingly reliable), but is messy and is still missing features.