---
title: Oxide API Reference

includes:
  - overview
  - supported_games
  - getting_help
  - contributing
  - compiling_source

search: true
---
# Overview

>
[![7 Days to Die](7-days-to-die/favicon-96x96.png)](/7-days-to-die/)
[![Blockstorm](blockstorm/favicon-96x96.png)](/blockstorm/)
[![Hurtworld](hurtworld/favicon-96x96.png)](/hurtworld/)
[![Reign of Kings](reign-of-kings/favicon-96x96.png)](/reign-of-kings/)
[![Rust](rust/favicon-96x96.png)](/rust/)
[![Rust Legacy](rust-legacy/favicon-96x96.png)](/rust-legacy/)
[![The Forest](the-forest/favicon-96x96.png)](/the-forest/)
[![Unturned](unturned/favicon-96x96.png)](/unturned/)

Oxide is a complete rewrite of the popular, original Oxide API and Lua plugin framework. Previously only available for the legacy Rust game, Oxide now supports numerous games. Oxide's focus is on modularity and extensibility. The core is highly abstracted and loosely coupled, and could be used to mod any game that uses the .NET Framework.

Plugins can currently be developed in [C# (CSharp)](https://en.wikipedia.org/wiki/C_Sharp_(programming_language)) for the games [7 Days to Die](#7-days-to-die), [Blockstorm](#blockstorm), [Hide & Hold Out](#hide-hold-out), [Hurtworld](#hurtworld), [Reign of Kings](#reign-of-kings), [Rust](#rust), [Rust Legacy](#rust-legacy), [The Forest](#the-forest), and [Unturned](#unturned), with support for more on the way!

Database support for plugins is also available in the [MySQL](https://www.mysql.com/) and [SQLite](https://www.sqlite.org/) varieties, so if JSON files aren't enough, you have options! If you'd prefer another database type, those can always be accessed via web requests and your own custom bridge script on your site.
