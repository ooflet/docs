---
layout: default
title: Prefix
nav_order: 2
description: "Prefix"
parent: Quickstart
permalink: /prefix
---
# Prefix
{: .no_toc }
Prefixes are your main way of interacting with Kommand. They show which mode the command will be running in.

---

| Prefix     | Description  |
|:-----------|:-------------|
| >          | Lua mode, executes Lua code     |
| *          | System mode, modify and run system commands|
| !          | Special mode, run custom modules and commands |
| ?          | Help mode, run help wizard commands |

---

By default, Kommand opens with the Lua mode prefix (>) which allows you to execute lua code. This uses the `loadstring()` feature on your executor.  
System mode (\*) allows you to modify settings, and execute commands which modifies Kommand  
Special mode (!) allows you to execute custom modules, and modules contained in the Kommand [library](https://ooflet.github.io/docs/library/).  
Help mode (?) accesses the documentation module (also known as the help wizard) which provides help. Its literally the docs but outputted into the output.
