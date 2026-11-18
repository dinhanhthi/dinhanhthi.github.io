# Update feed mirrors

## Dblore

This repository serves `Dblore/appcast.xml` at <https://dinhanhthi.github.io/Dblore/appcast.xml>, the update feed that Dblore builds 0.10.1 and older read. Dblore now lives at [Coprimal/Dblore](https://github.com/Coprimal/Dblore) and its feed at <https://dblore.coprimal.dev/appcast.xml>; GitHub does not redirect `github.io` pages after a repository transfer, so this copy keeps older builds updating.

- `Dblore/appcast.xml` is written by `scripts/sync-feed-mirror.sh` in Coprimal/Dblore on every release. Never edit it by hand.
- Keep this repository forever.
- Never give this site a custom domain.
- Never create a repository named `dinhanhthi/Dblore`: it would break GitHub's redirect to Coprimal/Dblore that older builds rely on.

## SegDown

This repository also serves `SegDown/appcast.xml` at <https://dinhanhthi.github.io/SegDown/appcast.xml> and `SegDown/firefox-updates.json` at <https://dinhanhthi.github.io/SegDown/firefox-updates.json>: the Sparkle feed that SegDown builds 0.7.5 and older read, and the update manifest of their Firefox add-ons. SegDown now lives at [Coprimal/SegDown](https://github.com/Coprimal/SegDown) and its feeds at <https://segdown.coprimal.dev/appcast.xml> and <https://segdown.coprimal.dev/firefox-updates.json>.

- Both files are written by `scripts/sync-feed-mirror.sh` in Coprimal/SegDown on every release. Never edit them by hand.
- Never create a repository named `dinhanhthi/SegDown`: it would take over these paths and break GitHub's redirect to Coprimal/SegDown that older builds rely on.
