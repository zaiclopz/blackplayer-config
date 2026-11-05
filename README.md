# Black Player – bootstrap config

`config.json` holds the current list of API addresses for the Black Player app, **signed with Ed25519**.
The app reads it only when none of the API addresses it knows answers, and accepts it only if the
signature is valid. Do not edit it by hand: it is generated and signed on the server
(`scripts/publish-config.sh` in the portal repo).
