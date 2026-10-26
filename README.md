# Riddles Labs plugin downloads

Official release downloads for Riddles Labs plugins. Source code is maintained separately.

## Downloads

| Plugin | Version | Release | JAR |
| --- | --- | --- | --- |
| Riddles Labs Core | 0.6.19 | [Release notes](https://github.com/Riddles-Labs/Releases/releases/tag/core-v0.6.19) | [Download](https://github.com/Riddles-Labs/Releases/releases/download/core-v0.6.19/RiddlesLabsCore-0.6.19.jar) |
| Riddles Region Manager | 1.1.15q | [Release notes](https://github.com/Riddles-Labs/Releases/releases/tag/region-manager-v1.1.15q) | [Download](https://github.com/Riddles-Labs/Releases/releases/download/region-manager-v1.1.15q/riddlesregionmanager-1.1.15q.jar) |
| Riddles Trails | 1.6.6 | [Release notes](https://github.com/Riddles-Labs/Releases/releases/tag/trails-v1.6.6) | [Download](https://github.com/Riddles-Labs/Releases/releases/download/trails-v1.6.6/RiddlesTrails-1.6.6.jar) |
| Riddles Queue | 1.15.0 | [Release notes and upgrade guide](https://github.com/Riddles-Labs/Releases/releases/tag/queue-v1.15.0) | [Proxy](https://github.com/Riddles-Labs/Releases/releases/download/queue-v1.15.0/RiddlesQueue-1.15.0.jar) / [Backend or standalone](https://github.com/Riddles-Labs/Releases/releases/download/queue-v1.15.0/RiddlesQueueBridge-1.15.0.jar) |

Each plugin uses its own release tag, such as `core-v0.6.19`. Use the link for your plugin; GitHub's repository-wide latest release may belong to a different plugin.

Read the release's installation instructions and compatibility notes before upgrading. SHA-256 checksums accompany the downloads. Keep existing configuration and data unless a release explicitly requires migration.

Queue 1.15.0 includes its own optional waiting engine inside the proxy JAR for Velocity, BungeeCord and Waterfall. It is disabled by default; no separate waiting addon is required. Remove the previous Embedded addon when upgrading and retain its data folder for settings import. See the release's compatibility and migration notes.

TNE's existing downloads remain available at [TNE Economy Releases](https://github.com/Riddles-Labs/TNE-Economy-Releases).
