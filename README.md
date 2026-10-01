# cnbx — Inbox

Member-device composition over Contacts, Threads, Delivery and Waves.

## Scope

Wire contact and outcome operations, direct/fork/room conversations, accepted
history and live/offline delivery status. Wallet owns balance/proof capability;
Groups supplies verified membership decisions from Board. Read state from the
owners and publish combined candidates through the same Vault checkpoint.

Never duplicate a relationship journal, MLS ratchet, accounting state, ACK or
group policy. No Forum connection, frontend privilege, raw MLS/balance-store
bypass or Wave release before accepted evidence and durable publication.
All product frontends use the cmsg door.

## Status

Stream A was committed first. Established-contact send/receive/ACK composition
and owner-derived views are implemented locally but unvalidated. First-contact,
room, live-session and record-network routes still await owner integration. No
full reservation-to-release-to-Answer/direct-chat acceptance. See
[contract](docs/CONTRACT.md) and [FSL license](LICENSE.md).
