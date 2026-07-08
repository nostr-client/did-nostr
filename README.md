# did:nostr explorer

**Whois for nostr.** One keypair, four faces: a W3C DID, a nostr profile, a
bitcoin address, and a social graph you can walk — paste any npub / hex /
`did:nostr:…` and explore. One buildless HTML page over
[did](https://github.com/nostr-client/did),
[wallet](https://github.com/nostr-client/wallet) and the
[nostr-client](https://nostr-client.github.io/) components.

**Live:** https://nostr-client.github.io/did-nostr/

- live-resolved **DID document** (offline derivation + relay enhancement:
  kind 0 → `alsoKnownAs`, kind 10002 → relay services)
- **identity facts**: did, npub, hex, and the taproot bitcoin addresses
  (testnet4 + mainnet) derived from the key — nothing published, all computed
- **browsable social graph**: center identity + follow ring, identity-colored
  nodes, click any node to recenter (`#<hex>` deep links)

Built to pair with the [did:nostr spec](https://did-nostr.com/) — attach the
custom domain in repo settings when DNS is ready.

AGPL-3.0-or-later.
