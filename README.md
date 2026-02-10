## Lecta

Lecta is a long-form web client for the [Nostr](https://nostr.com/) protocol. Unlike most Nostr clients, Lecta aims to make the Nostr part invisible, presenting an technical experience indistinguishable from the traditional web.

### Goals

The technical requirements for Lecta include:
- Low latency, to retain reader attention and provide a good experience
- Self-hostable, to enable author-ownership of content such as according to [POSSE](https://indieweb.org/POSSE) principles.

### Usage

Lecta is currently available as a single HTML file with references to external scripts. This may be served by any typical web server. In the future, a build step might be added.

To serve a [NIP-23](https://nips.nostr.com/23)(long-form content) event using Lecta, simply add the correct query parameters to the base url. If your HTML page is served at `https://example.com`, your content might be available at `https://example.com/?event=cc8fad119d20b6018fceb4def0cee1efa0d11f0f3a298a4f7f268191c23d39f4&relays=wss://relay.damus.io,wss://relay.nostr.band,wss://nos.lol/`.

### License

Lecta is licensed under the open-source, [2-Clause BSD License](./LICENSE.md).
