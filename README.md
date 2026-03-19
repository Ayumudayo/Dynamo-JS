# Dynamo-JS

`Dynamo-JS` is the read-only archive of the legacy JavaScript implementation of Dynamo.

This archive has been realigned to the JavaScript snapshot from the main repository at the requested baseline commit:

- source commit: `8cda461`
- snapshot scope: `src/`, `dashboard/`, `bot.js`, `config.js`, legacy docs, and original Node manifests
- excluded from this resync: `src/commands/gameinfo/maint.js`, `src/commands/gameinfo/pll.js`

## What To Read

- [`LEGACY-README.md`](./LEGACY-README.md): the original project README from the final JS snapshot
- `src/`: legacy Discord.js bot runtime
- `dashboard/`: legacy EJS/Express dashboard
- `docs/commands/`: legacy command documentation

## Status

- No new feature work is expected here.
- No support promise is implied for modern Discord changes or third-party API drift.
- Use this archive for migration reference, behavior comparison, and legacy implementation lookup only.
