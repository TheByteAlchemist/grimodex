# Grimodex

## The Idea

Welcome to Grimodex! This project is setting out to be a self-hosted homepage dashboard, drawing inspiration from apps like Homarr, Heimdall, and Flame. The key difference? It's being built in Rust with a strong focus on performance and efficiency – the goal is to make it run smoothly even on modest hardware like a Raspberry Pi.

Tying into "The Byte Alchemist" theme, think of Grimodex as an "indexing grimoire": a handy tool to automatically discover and keep track of all the web services running on your local network.

## Core Goals

- A clean, simple web interface to see your services.
- Automatic discovery of web services on the LAN (finding those hidden ports!).
- Keep resource usage (RAM/CPU) super low for SBCs.

## Tech Plan

- **Backend:** Rust, most likely using the Axum web framework built on Tokio.
- **Frontend:** Standard web technologies (HTML, CSS, JavaScript) – specific framework or vanilla JS TBD.
- **Target Platform:** Primarily Linux on ARM devices (like the Raspberry Pi).

## Current State

- The name is set: Grimodex!
- The basic project folder was created with `cargo new grimodex --bin`.
- A local Git repository is initialized.
- **Important:** There's no actual application code written yet, nor have dependencies been added. It's a clean slate!

## Getting Set Up to Develop

If you want to build or contribute to Grimodex, you'll need these tools on your system:

1.  **The Rust Toolchain:** This gives you `rustc`, `cargo`, and `rustup`. The best way to get it is from the official site: [rustup.rs](https://rustup.rs/).
2.  **Git:** Essential for code version control. You can download it from [git-scm.com](https://git-scm.com/) or install it using your system's package manager (`apt`, `brew`, `pacman`, etc.).
3.  **A Code Editor:** Whichever one you like for Rust! [VS Code](https://code.visualstudio.com/) paired with the `rust-analyzer` extension is a very popular and effective setup.
