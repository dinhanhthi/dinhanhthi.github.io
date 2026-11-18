# Update feed mirrors

This repository serves Sparkle update feeds for apps that moved from `dinhanhthi` to the [Coprimal](https://github.com/Coprimal) org. GitHub does not redirect `github.io` pages after a repository transfer, so these copies keep older builds updating.

- `Dblore/appcast.xml` at <https://dinhanhthi.github.io/Dblore/appcast.xml>: the feed that Dblore builds 0.10.1 and older read. Dblore now lives at [Coprimal/Dblore](https://github.com/Coprimal/Dblore) and its feed at <https://dblore.coprimal.dev/appcast.xml>. Written by `scripts/sync-feed-mirror.sh` in Coprimal/Dblore on every release.
- `FastMoji/appcast.xml` at <https://dinhanhthi.github.io/FastMoji/appcast.xml>: the feed that FastMoji builds 1.0.1 and older read. FastMoji now lives at [Coprimal/FastMoji](https://github.com/Coprimal/FastMoji) and its feed at <https://fastmoji.coprimal.dev/appcast.xml>. Written by `scripts/sync-feed-mirror.sh` in Coprimal/FastMoji on every release.
- `SimpleMapper/appcast.xml` at <https://dinhanhthi.github.io/SimpleMapper/appcast.xml>: the feed that SimpleMapper builds 1.1.4 and older read. SimpleMapper now lives at [Coprimal/SimpleMapper](https://github.com/Coprimal/SimpleMapper) and its feed at <https://simplemapper.coprimal.dev/appcast.xml>. Written by `scripts/sync-feed-mirror.sh` in Coprimal/SimpleMapper on every release.

Rules:

- Never edit these appcast files by hand.
- Keep this repository forever.
- Never give this site a custom domain.
- Never create a repository named `dinhanhthi/Dblore`, `dinhanhthi/FastMoji` or `dinhanhthi/SimpleMapper`: it would break GitHub's redirect to the Coprimal repository that older builds rely on.

