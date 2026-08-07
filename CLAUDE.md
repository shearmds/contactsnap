# contactsnap (Snap2 landing page)

A single `index.html` plus the distributed binary `Snap2-1.1.0-universal.dmg`. That's the whole
repo. `github.com/shearmds/contactsnap`.

**It is the download host.** The DMG is served straight out of this repo rather than from a
private GitHub release asset — a deliberate change, because the release asset wasn't publicly
reachable. So **shipping a new Snap2 build means committing the new DMG here**, not just
tagging a release.

The page was rebranded from ContactSnap to **Snap2** when contact capture and event capture were
combined. The repo name is stale; the product is Snap2.

Don't confuse it with `contact-snap` (the older Electron app), `snap2` (the shipping Swift app,
the actual source), or `snap2-modifications` (not a repo).

Published via `mikeshear-site`, which clones this into `/coding/contactsnap` at build time —
pushing here doesn't update mikeshear.com until that rebuilds.
