# ItemX

**Minecraft Version:** 1.18.2  

## Overview

ItemX is a lightweight Minecraft plugin that allows server administrators to create custom items with special behaviors. It supports executing commands when items are used, displaying custom item names and lore, and more.

## Features

- Custom item behaviors  
- Execute server commands when items are used  
- Custom item names and lore  
- Lightweight and efficient  

## Installation

1. Place `ItemX.jar` into your server's `plugins/` folder.  
2. Restart or reload your server to generate default config files.  
3. Configure your custom items in `plugins/ItemX/items.yml`.  

## Configuration Example

```yaml
name: "&9Abyssal Edge"
material: IRON_SWORD
type: SWORD
rarity: RARE
lore:
  - "&7Forged in the trenches of the abyss."
stats:
  damage: 31
  strength: 14
