# 🧱 ItemX Plugin Items

This repository contains **168 `.yml` files** that define custom items for the **ItemX Minecraft plugin**.

Each YAML file represents a unique weapon, armor piece, or utility item — including stats, abilities, lore, and crafting recipes used by the ItemX system.

---

## 🔹 Categories

### ⚔️ Weapons
Examples:  
`abyssal_edge.yml`, `crimson_cleaver.yml`, `ebonbrand.yml`, `rusty_dagger.yml`  
These files define melee and ranged weapons with custom damage, attack speed, and special effects.

### 🛡️ Armor
Examples:  
`caver_boots.yml`, `farmer_helmet.yml`, `dented_chestplate.yml`, `mystic_leggings.yml`  
Armor items specify defense values, enchantments, and bonuses when worn as a full set.

### 🧰 Tools & Misc
Examples:  
`firewood_axe.yml`, `evergreen_plow.yml`, `caver_pickaxe.yml`, `miner's_glove.yml`  
These YAMLs define tools, accessories, and other interactive items with unique utility effects.

---

## ⚙️ Purpose

Each `.yml` file configures a single custom item for ItemX, defining:
- Custom item **name**, **material**, and **rarity**
- **Lore** and flavor text
- Optional **stat modifiers**

---

## 🧩 Example YAML Structure

```yaml
name: Abyssal Edge
material: NETHERITE_SWORD
rarity: EPIC
lore:
  - "Forged in the depths of the void."
damage: 15
