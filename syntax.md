---
layout: default
title: Syntax
nav_order: 2
description: "Syntax"
permalink: /syntax
---
# Syntax
{: .no_toc }
Kommand uses a command prompt style interface, a TUI if you will, and uses prefixes to access different commands.

| Prefix     | Int   | Description  |
|:-----------|:------|:-------------|
| >          | 0     | Lua mode, executes Lua code     |
| *          | 1     | System mode, modify and run system commands|
| !          | 3     | Special mode, run custom modules and commands |
| ?          | 2     | Help mode, run help wizard commands |
| =          | 4     | Response mode, 
When inputting commands, Kommand ignores characters other than the command and arguments, so you are free to type the command and it's arguments in any way. You can do `command argument` or `command(argument)`, whatever floats your boat.

