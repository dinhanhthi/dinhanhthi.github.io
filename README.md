# Dblore update feed mirror

This repository serves `Dblore/appcast.xml` at <https://dinhanhthi.github.io/Dblore/appcast.xml>, the update feed that Dblore builds 0.10.1 and older read. Dblore now lives at [Coprimal/Dblore](https://github.com/Coprimal/Dblore) and its feed at <https://dblore.coprimal.dev/appcast.xml>; GitHub does not redirect `github.io` pages after a repository transfer, so this copy keeps older builds updating.

- `Dblore/appcast.xml` is written by `scripts/sync-feed-mirror.sh` in Coprimal/Dblore on every release. Never edit it by hand.
- Keep this repository forever.
- Never give this site a custom domain.
- Never create a repository named `dinhanhthi/Dblore`: it would break GitHub's redirect to Coprimal/Dblore that older builds rely on.
