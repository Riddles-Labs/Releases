# Riddles Labs plugin downloads

Official release downloads for Riddles Labs plugins. Source code is maintained separately.

## Downloads

| Plugin | Version | Release | JAR |
| --- | --- | --- | --- |
| Riddles Labs Core | 0.6.20 | [Release notes](https://github.com/Riddles-Labs/Releases/releases/tag/core-v0.6.20) | [Download](https://github.com/Riddles-Labs/Releases/releases/download/core-v0.6.20/RiddlesLabsCore-0.6.20.jar) |
| Riddles Region Manager | 1.1.15a | [Release notes](https://github.com/Riddles-Labs/Releases/releases/tag/region-manager-v1.1.15a) | [Download](https://github.com/Riddles-Labs/Releases/releases/download/region-manager-v1.1.15a/riddlesregionmanager-1.1.15a.jar) |
| Riddles Trails | 1.6.7 | [Release notes](https://github.com/Riddles-Labs/Releases/releases/tag/trails-v1.6.7) | [Download](https://github.com/Riddles-Labs/Releases/releases/download/trails-v1.6.7/RiddlesTrails-1.6.7.jar) |
| Riddles Queue | 1.15.1 | [Release notes and upgrade guide](https://github.com/Riddles-Labs/Releases/releases/tag/queue-v1.15.1) | [Proxy](https://github.com/Riddles-Labs/Releases/releases/download/queue-v1.15.1/RiddlesQueue-1.15.1.jar) / [Backend or standalone](https://github.com/Riddles-Labs/Releases/releases/download/queue-v1.15.1/RiddlesQueueBridge-1.15.1.jar) |

Each plugin uses its own release tag, such as `core-v0.6.20`. Use the link for your plugin; GitHub's repository-wide latest release may belong to a different plugin.

Read the release's installation instructions and compatibility notes before upgrading. SHA-256 checksums accompany the downloads. Keep existing configuration and data unless a release explicitly requires migration.

Queue 1.15.1 includes its own optional waiting engine inside the proxy JAR for Velocity, BungeeCord and Waterfall. It is disabled by default; no separate waiting addon is required. Remove the previous Embedded addon when upgrading and retain its data folder for settings import. See the release's compatibility and migration notes.

TNE 1.0.80 and its developer API downloads are available at [TNE Economy Releases](https://github.com/Riddles-Labs/TNE-Economy-Releases/releases/tag/v1.0.80).
