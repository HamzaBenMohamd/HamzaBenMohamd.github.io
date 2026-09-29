---
layout: page
title: Uses
permalink: /uses/
---

The tools and environment I actually work in. Details change; the shape of it doesn't —
fundamentals first, then whatever removes friction.

## System

- **Parrot OS** as the daily driver — a Debian-based security distribution, which suits
  the kind of work I do.
- **KDE Plasma** as the desktop environment: predictable, keyboard-driven, and doesn't
  get in the way.
- I keep the system configuration in text files and versioned, so it's reproducible
  rather than whatever state the machine drifted into.

## Editor

- **VS Code** with a trimmed-down extension set. C/C++ support via the Microsoft
  extension, plus whatever fits the current task.
- I work in the editor, but the **terminal is where I'm most comfortable** — the editor
  is a view onto the same commands.

## Terminal & CLI

- **lazygit** for version control — reviewing diffs and staging without leaving the
  terminal.
- **lazydocker** for the same reason with containers and compose stacks.
- `gcc` / `g++`, `make`, `cmake`, `gdb`, and the usual GNU coreutils.

## Containers & networking

- **Docker** and **Docker Compose** for isolated, reproducible build and test
  environments.
- **Wireshark** and `tcpdump` for packet capture and protocol analysis.
- Monitor mode and packet injection on an external wireless adapter, for getting hands-on
  with how traffic actually behaves on the wire.

## Principles

- Build strictly to the **C++98** standard, and keep everything in **Orthodox Canonical
  Form**. Constraints make the design legible.
- Optimize for memory safety and clear architecture first; micro-optimizations come
  after.

This is a snapshot, not a rulebook — it will drift as the work does. Corrections welcome.
