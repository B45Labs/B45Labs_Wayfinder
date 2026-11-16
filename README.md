# B45 Labs | Wayfinder: Navisworks Add-in

![Navisworks](https://img.shields.io/badge/Navisworks%20Manage-2026-0696D7?style=flat-square&logo=autodesk&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?style=flat-square)
![License](https://img.shields.io/badge/License-Proprietary-red?style=flat-square)
![Version](https://img.shields.io/badge/Version-0.0.1-EE6C1E?style=flat-square)
![.NET](https://img.shields.io/badge/.NET-net48-512BD4?style=flat-square)

> B45 Labs | Wayfinder is the B45 Labs add-in for Autodesk Navisworks Manage 2025, 2026 and 2027: fly through the model in first person, group clashes with a preview before anything changes, and put a section box around a clash, together with the B45 Labs tools you already know from Revit.

> **Part of the B45 Labs suite.** Wayfinder is the Navisworks product of the suite, next to **Coordination**, **Library** and **Connect** for Revit. It installs and updates **independently** and adds its own **B45 Labs | Wayfinder** tab to the Navisworks ribbon, with Main, Navigation, Models, Clash, Settings and Help panels.

This repository is the public home of Wayfinder's **releases and documentation**. The source code is proprietary and is not published here.

---

## Who it is for

BIM coordinators and model reviewers who work in Navisworks and spend their time moving through federated models and sorting out Clash Detective results.

---

## Key Features

- **FlyNav, first-person navigation.** Move with W, A, S and D, go up with Q and down with E, hold the right mouse button to look around and click with the left button to select. Shift or Ctrl runs, Alt slows down. While it is on, press 1 to 9 to fly to the first nine saved viewpoints, PageUp and PageDown for the previous and the next one, and F to fly to the selected item and frame it. FlyNav Settings (invert axes, look sensitivity, speeds, run key) stays open while you fly and every change applies at once.
- **Group by Element.** Group the clashes of one, several or all clash tests by the single element they hit. You see the groups that would be created before anything changes, check or uncheck each one, and then create them.
- **Group by Item.** Select an item and group every loose clash that involves it, in as many tests as you choose, with the same preview. Clashes keep their status, assignee and comments: they are moved into the group, not copied.
- **Clash Box.** A section box centered on the clash selected in Clash Detective, or on all the clashes of a group. It wraps the whole element and sits parallel to it, and it can follow each new selection. Clash Box Settings sets the margin and the longest element kept whole; Remove Box turns sectioning off.
- **Reload From.** Replace the file of the selected model with another one you choose in Explorer.
- **The B45 Labs tools you know.** About Me, My Profile, Tips & Tricks, Plug-in Info, B45 Labs Docs and YouTube Tutorials work as in the other B45 Labs products. Change Theme (Navisworks Light or Dark), Change Language and Plug-in Settings sit in their own Settings panel.

See [CHANGELOG.md](CHANGELOG.md) for the full list and the known limits of this first release.

---

## Requirements

| Requirement | Details |
|---|---|
| Autodesk Navisworks | Manage 2025, 2026 and 2027 (one build per year) |
| Operating System | Windows 10 / Windows 11 |
| .NET | net48 |
| Installation | Per-user, no administrator rights required |

No other Navisworks version is supported.

---

## Installation

1. Download the installer from [**Releases**](https://github.com/B45Labs/B45Labs_Wayfinder/releases/latest) or from [**b45labs.com/download**](https://b45labs.com/download).
2. Close Navisworks before installing.
3. Run the installer and follow the setup wizard.
4. Start Navisworks: the **B45 Labs | Wayfinder** tab appears on the ribbon.

> **Note:** the installer for v0.0.1 arrives with this repository's first GitHub Release. Until that Release is published, the Releases page has no installer to download; [b45labs.com/download](https://b45labs.com/download) shows the current state.

---

## Languages

English, plus **Português (BR), Español, Français, and Русский as BETA**: AI-assisted drafts pending native review. If a translation reads wrong, tell us at support@b45labs.com.

---

## Updates

At startup, Wayfinder quietly checks in the background whether a newer version exists, using a signed message from B45 Labs. A newer version shows a small notice; a version below the minimum shows a window that asks you to update; and a version that B45 Labs has withdrawn for safety turns the Wayfinder tools off until you update. If there is no connection, or the message cannot be verified, nothing happens and Wayfinder keeps working.

---

## Data and privacy

Wayfinder sends a small amount of usage and error data, tied to a random install ID, to B45 Labs. It is **on by default** and you can **turn it off at any time** with the "Share usage data to help improve B45 Labs" switch in My Profile > Privacy. When it is off, nothing is sent and anything still waiting to be sent is discarded. It covers:

- a random installation ID, shared by the B45 Labs products on your computer,
- the Navisworks and Wayfinder versions and the interface language,
- an approximate region (continent, country, region), looked up from your IP address, which is not stored,
- one event for each Wayfinder ribbon button you click,
- errors of Wayfinder itself.

Wayfinder does **not** send model or file names, paths, your Windows or computer name, the items you select or group, or anything you type. Your profile (name, email, company, role) is sent only if you also turn on **"Also sync my profile"**, which is **off by default**. My Profile can export and erase your data. The update check and the Tips & Tricks content download are separate background requests that the switch does not control. See [PRIVACY.md](PRIVACY.md) for full details.

---

## Documentation

| Document | Description |
|---|---|
| [TERMS.md](TERMS.md) | Terms of Use / EULA |
| [PRIVACY.md](PRIVACY.md) | Privacy Policy |
| [CHANGELOG.md](CHANGELOG.md) | Version history |
| [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) | Open-source licenses |
| [SUPPORT.md](SUPPORT.md) | Support information |
| [SECURITY.md](SECURITY.md) | Security policy |
| [LICENSE](LICENSE) and [LICENSE_PROPRIETARY.md](LICENSE_PROPRIETARY.md) | Proprietary license notices |

Product documentation lives on [b45labs.com](https://b45labs.com).

---

## Support

Email: **support@b45labs.com**

When reporting issues, include: B45 Labs | Wayfinder version, Navisworks version and build number, steps to reproduce, timestamp and screenshot (redact sensitive details).

---

## Copyright

Copyright (c) 2026 B45 Labs. All rights reserved.
Use of this Software is governed by [TERMS.md](TERMS.md).
