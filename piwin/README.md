# Command Code for piwin

This is a piwin adaptation of [patlux/pi-commandcode-provider](https://github.com/patlux/pi-commandcode-provider), version 0.7.1. The original implementation and MIT license remain with their authors. The adapter keeps the provider transport, model catalog, quota commands, and browser login while aligning credential lookup and model cache with piwin's Host data root.

Install from the piwin extension market, enable it, and apply it to the current Agent. Then open **Settings → OAuth → Command Code**, connect an account, and select Command Code models under **Settings → Models**.

Command Code is an unofficial community integration. You need your own Command Code account with Provider API access. The extension runs with the Host user's OS permissions. Model pricing and access are controlled by Command Code.

The registry installs this `piwin/` directory from an exact Git commit. It does not run npm scripts. `piwin.json` declares the Host auth provider so the OAuth card appears only while the extension is enabled.
