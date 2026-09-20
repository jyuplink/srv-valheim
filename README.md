# srv-valheim

A one-page picklist of the **server-only** mods available on a small private Valheim server.

Live page: https://jyuplink.github.io/srv-valheim/

Everything listed is from ArgusMagnus's [ServersideQoL](https://github.com/ArgusMagnus/ValheimServersideQoL)
family: the mods run on the server alone, so players — console players included — install nothing.
Each row links to that module's page, shows how many settings it has, and says whether it only
saves clicks or genuinely makes the game easier.

Download counts and setting counts were read on 2026-09-20. Setting counts are measured from the
config files the modules actually wrote, not from their descriptions.

## What belongs in this repo

`index.html` and this README. Nothing else.

No server address, account, password, alert topic, log or backup goes in here, in any file, ever —
this repo is public and git remembers deleted files. `.gitignore` blocks the documentation folders
by name, and `.githooks/pre-commit` refuses a commit that contains an address, an alert topic or a
password flag. Turn the hook on once per clone:

```
git config core.hooksPath .githooks
```

## Editing the page

`index.html` is generated from a source page kept outside this repo, so edit it there and
regenerate rather than patching this copy by hand.
