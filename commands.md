---
layout: default
title: Commands
nav_order: 3
description: "Commands"
permalink: /commands
---
# Commands

Kommand has an array of useful commands to use.

---
<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>
---

## Global
---
`clr`/`clear`
Clears output.

---

## System `*`

## `settings`

`blur <boolean>`
Enables/Disables UI blur
```
settings blur true
```

---

`safehop`/`serverhop`
Disconnects the client before teleporting them back into the game, potentially into the same server.

---

## Special `!`

## `moduleinstaller`

`install <string>`
Calls `Lib.PluginInstaller.InstallFromRepository()`, which pulls and installs the module name provided from the Kommand Github repository
```
moduleinstaller install module
```
---
`installfromlink <string>`
Calls `Lib.PluginInstaller.InstallFromLink()`, which pulls and installs the module from the link
```
moduleinstaller installfromlink https://raw.githubusercontent/module/module/
```
---
## `kommand`

`remotespy`
Calls `Lib.RemoteSpy.Load()`, which if not installed, installs and executes the built-in RemoteSpy module made to integrate seamlessly with Kommand
```
kommand remotespy
```
---
`dex`
Calls `Lib.Dex:Load()`, which if not installed, installs and executes the built-in Dex module
```
kommand dex
```
