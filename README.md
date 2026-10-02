# Maerka plugin pilot sample

This repository contains the `io.maerka.example.installapp` plugin package for a limited Maerka SDK pilot.

## Test only

This is an initial-development sample (`0.1.0`), not a stable SDK or production plugin. Use it only in the designated Maerka test workspace and pilot. The package format and host integration may change without compatibility guarantees.

No license or permission to reuse, modify, redistribute, or publish this sample is granted by this repository. Do not treat its public availability as a reuse grant.

The plugin requests `network.public_https` for its release-lookup action. Review and approve that capability only in the designated test workspace. Keep the plugin SDK feature flag disabled outside the pilot.

## Package

The `v0.1.0` GitHub release contains `maerka-plugin-sdk-pilot.mrkp` for plugin ID `io.maerka.example.installapp`.
