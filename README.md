# ox_inventory - UI Redesign

Discord: https://discord.com/invite/YUBpUeSGMV

Este repositorio contiene una **modificación visual** (Redesign) del recurso [ox_inventory](https://github.com/communityox/ox_inventory), desarrollada con el objetivo de mejorar la apariencia y experiencia de usuario del inventario en FiveM.

🔧 **Importante:**  
Esta versión **no modifica la funcionalidad interna ni la lógica del inventario original**, únicamente cambia el diseño de la interfaz (HTML, CSS, JS).

📁 **Basado en:**  
Fork de [communityox/ox_inventory](https://github.com/communityox/ox_inventory), que continúa el desarrollo del proyecto original archivado.  
El recurso permanece bajo la licencia [GNU GPL v3.0](https://www.gnu.org/licenses/gpl-3.0.html).  
Todos los créditos corresponden a sus respectivos autores.

<img width="1920" height="1080" alt="Desktop Screenshot 2025 07 20 - 07 15 04 77" src="https://github.com/user-attachments/assets/a6a882cf-62a7-4d6d-a603-b7dcc70dd7ca" />

<img width="1920" height="1080" alt="Desktop Screenshot 2025 07 20 - 07 15 27 19" src="https://github.com/user-attachments/assets/010b0eaf-99b1-4671-8d73-a861e05c92aa" />

# ox_inventory

A complete inventory system for FiveM, implementing items, weapons, shops, and more without any strict framework dependency.

![](https://img.shields.io/github/downloads/communityox/ox_inventory/total?logo=github)
![](https://img.shields.io/github/downloads/communityox/ox_inventory/latest/total?logo=github)
![](https://img.shields.io/github/contributors/communityox/ox_inventory?logo=github)
![](https://img.shields.io/github/v/release/communityox/ox_inventory?logo=github)

## 📚 Documentation

https://coxdocs.dev/ox_inventory

## 💾 Download

https://github.com/communityox/ox_inventory/releases/latest/download/ox_inventory.zip

## Supported frameworks

We do not guarantee compatibility or support for third-party resources.

- [ox_core](https://github.com/communityox/ox_core)
- [esx](https://github.com/esx-framework/esx_core)
- [qbox](https://github.com/Qbox-project/qbx_core)
- [nd_core](https://github.com/ND-Framework/ND_Core)

## ✨ Features

- Server-side security ensures interactions with items, shops, and stashes are all validated.
- Logging for important events, such as purchases, item movement, and item creation or removal.
- Supports player-owned vehicles, licenses, and group systems implemented by frameworks.
- Fully synchronised, allowing multiple players to [access the same inventory](https://user-images.githubusercontent.com/65407488/230926091-c0033732-d293-48c9-9d62-6f6ae0a8a488.mp4).

### Items

- Inventory items are stored per-slot, with customisable metadata to support item uniqueness.
- Overrides default weapon-system with weapons as items.
- Weapon attachments and ammo system, including special ammo types.
- Durability, allowing items to be depleted or removed overtime.
- Internal item system provides secure and easy handling for item use effects.
- Compatibility with 3rd party framework item registration.

### Shops

- Restricted access based on groups and licenses.
- Support different currency for items (black money, poker chips, etc).

### Stashes

- Personal stashes, linking a stash with a specific identifier or creating per-player instances.
- Restricted access based on groups.
- Registration of new stashes from any resource.
- Containers allow access to stashes when using an item, like a paperbag or backpack.
- Access gloveboxes and trunks for any vehicle.
- Random item generation inside dumpsters and unowned vehicles.

## Copyright

Copyright © 2024 Overextended <https://github.com/overextended>

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see <https://www.gnu.org/licenses/>.
