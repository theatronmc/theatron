<p align="center">
  <a href="https://www.theatronmc.com/"><img src="https://raw.githubusercontent.com/theatronmc/.github/main/banner-original-cropped.png" alt="Theatron logo above a Minecraft world at night" width="900"></a>
</p>

# Theatron

Theatron is a visual workspace for building NPCs, quests, shops, items, Flows, and world rules for Minecraft servers, then publishing them through a Paper plugin.

[![Join the Theatron Discord](https://img.shields.io/badge/Discord-Join%20community-5865F2?logo=discord&logoColor=white)](https://discord.gg/theatronmc) · [Website](https://www.theatronmc.com/) · [Getting started with the hosted product](https://www.theatronmc.com/en/getting-started)

> **Availability:** This repository currently contains a README only. Source code, binaries, a license, and self-host installation files are not available here yet.

## See it in action

A short clip from the live site shows a catalogue NPC going from the panel into a Paper server. Select the image to play the video.

<p align="center">
  <a href="https://www.theatronmc.com/mini-clips/landing/npc-catalog.mp4"><img src="https://www.theatronmc.com/mini-clips/landing/npc-catalog-poster.jpg" alt="Play the Theatron NPC demo: from panel to Minecraft" width="560"></a>
</p>

## Theatron components

Theatron combines a NestJS engine and API, a React authoring panel, a Paper server plugin, an extension SDK, and a resource-pack compiler and build worker. The engine stores and publishes world content; the plugin applies it in Minecraft. The build worker produces client resource packs for authored assets.

The self-hosted system is designed for creating, publishing, and maintaining original content and extensions under the operator's control. Apeyron Cloud is a hosted way to use Theatron. Apeyron Central provides optional licensed content through a separate service.

## Related repositories

- [Launcher](https://github.com/theatronmc/launcher) — desktop app for creating local Minecraft servers and connecting them to Cloud or a self-hosted instance.
- [Relay](https://github.com/theatronmc/relay) — optional Rust multiplayer address service.
- [Extension template](https://github.com/theatronmc/extension-template) — Kotlin starter for independent extensions.
- [Extension registry](https://github.com/theatronmc/extension-registry) — community extension index.
- [Documentation](https://github.com/theatronmc/docs) — Astro Starlight documentation site source.
