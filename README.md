# NixOS Configuration with GNOME Desktop Environment 🌐🐧

Welcome to the nix-config-gnome repository! This repository contains the NixOS configuration files tailored for a user-friendly setup featuring the GNOME desktop environment. 🌟

## Overview 🖥️

This configuration is designed for a smooth NixOS experience with the GNOME desktop environment, development tools, multimedia applications, and ThinkPad-specific optimizations. It includes support for Flatpak, PipeWire for audio, and various additional tools to enhance usability.

## Features ✨

  * Desktop Environment: GNOME with GDM as the display manager. 🖥️
  * Localization: 
    * Default locale: `en_US.UTF-8` 🌍
    * Additional Bosnian locale settings (`bs_BA.UTF-8` for measurement, monetary, etc.). 🇧🇦
  * Networking: Managed via NetworkManager 🌐.
  * Packages: Pre-installed system-wide packages for development, productivity, and entertainment 💻🎶🎮.
  * ThinkPad Optimizations: Includes TLP and support for non-free firmware 💡.
  * Flatpak Support: Easy access to a wide range of additional applications 📦.
  * PipeWire Audio: Modern and efficient audio management 🎧.

## User Account 👤

  * Default user: `racoon` 🦝
  * User is part of `networkmanager` and `wheel` groups for networking and administrative privileges 🔧.
  * Default user packages: 
    * `gnome-text-editor`, `vim` 📝

## Pre-Installed Packages 📦

The following are some of the key packages included in the configuration:

  * Development Tools: 
    * `vscode`, `git`, `github-cli`, `github-desktop`, `arduino-ide` 👨‍💻
  * Productivity: 
    * `obsidian`, `dropbox`, `gnome-tweaks`, `nautilus` 📅
  * Multimedia: 
    * `obs-studio`, `discord`, `cava`, `polybar` 🎥🎶
  * Utilities: 
    * `fastfetch`, `cmatrix`, `pipes` 🛠️
  * System Tools: 
    * Flatpak, PipeWire, TLP ⚙️
