---
title: README
focus: docs
type: README
tags:
  - homelab
  - workstation
created: 2025-12-13
updated: 2026-01-01
archived: false
---

# NixOS

My primary [NixOS flake](https://github.com/ian-ozzie/nixos-flake) is finally in a state that I'm happy with, after separating out my [workstation](https://github.com/ian-ozzie/nix-workstation) and [lab](https://github.com/ian-ozzie/nixos-lab) modules so that I can use them with other flakes that wouldn't be able to access my `secrets` module.

## Workstation

This controls how I interact with my hosts, whether they are headless or not. Currently I use [Hyprland](https://hypr.land/), but the intention of splitting this out was so that I could try other desktop environments. Hyprland has been great and will likely stay as my daily driver, though [Niri](https://github.com/YaLTeR/niri) seems quite promising, and [Cosmic](https://system76.com/cosmic) for a more batteries included environment that also has tiling has recently reached stable so I'll dive into it at some stage.

## Lab

This contains the services that I host. I've tried to keep my specific configuration out of this so that I can use these as building blocks for different purposes. Short term I want to add [Caddy](https://caddyserver.com/) as an alternate entrypoint to [Traefik](https://traefik.io/traefik), as since moving to NixOS I'm much less reliant on Docker. I've also started using Caddy at work and it has solved a lot of the issues that I've been having with Traefik, namely due to [caddy-security](https://github.com/greenpau/caddy-security) consolidating authentication down to the one package.

## Secrets

This contains configuration that I don't see a use exposing publicly. Everything that's needed to get things running is in my other repositories, this just holds my exact implementation. I do want to add [sops-nix](https://github.com/Mic92/sops-nix) to actually store secrets, as currently I manually set up `.env` files for services as needed.
