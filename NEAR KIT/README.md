# NEAR KIT OBSIDIAN PLUGIN
a plugin for obsidian that adds near blockchain interaction for function views, calls and transactions

> [!NOTE] SECURITY
> THIS NEAR PLUGIN SAVES PRIVATE KEYS TO OBSIDIAN BROWSER LOCAL STORAGE. IT WILL NOT BE SYNCED WITH YOUR VAULT. IT IS ACCESSIBLE TO ALL PLUGINS

---
##### DOWNLOAD THE PLUGIN
```sh
cd path/to/vault
mkdir .obsidian/plugins
cd .obsidian/plugins

git clone https://github.com/obsidianplayground/obsidian-plugin-near-kit
cd .obsidian/plugins/obsidian-plugin-near-kit
bun i
bun run build

```

---
## USE THE PLUGIN
use via command palette (⌘ + p on mac)

##### COMMANDS

TOGGLE NETWORK (mainnet/testnet)
- toggles the network
- saves network to local storage

SIGN IN
- sign in so you can do transactions
- saves info to local storage

SIGN OUT
- clears plug created local storage items

VIEW METHOD
- for view only methods
- does not require sign in

CALL METHOD
- for function call transactions
- requires sign in with account id and private key

---



---

copyright 2025 by sleet.near