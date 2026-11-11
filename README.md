# Theatron

Theatron is a visual workspace for building NPCs, quests, shops, items, Flows, and world rules for Minecraft servers, then publishing them through a Paper plugin.

> **Status — preparing the open-source release.** This repository currently contains documentation only. The product source, release images, plugin binaries, self-hosting Compose file, and license are not published here yet. There is no installable release from this repository today.

## Intended scope

This will be the public core monorepo: the NestJS engine and API, React panel, Paper plugin, extension standard and SDK, resource-pack compiler, shared contracts, and self-host deployment documentation. A self-hosted installation is intended to let an operator create and publish original content without an Apeyron account or connection to Apeyron Central.

Apeyron Cloud will run this same core. Its payment processing, hosted operations, and private paid-content service remain separate. Self-hosters may optionally connect to Apeyron Central to purchase licensed content; that connection will not be required for local authoring or for running their own extensions.

## Related repositories

- [Launcher](https://github.com/theatronmc/launcher) — desktop app for creating local Minecraft servers and connecting them to Cloud or a self-hosted instance.
- [Extension template](https://github.com/theatronmc/extension-template) — a future starter for independent Kotlin extensions.
- [Extension registry](https://github.com/theatronmc/extension-registry) — a future reviewed index of community extensions.

## What comes next

The first code release needs a tested self-host installation, extension development path, security and contribution policies, dependency and asset review, and an explicit license. We will publish installation and upgrade instructions when those artifacts are ready. Until then, this README describes the intended boundary, not a supported deployment.

For the current product, visit [theatronmc.com](https://theatronmc.com).
