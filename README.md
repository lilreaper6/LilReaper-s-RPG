# 🎮 LilReaper's RPG

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Minecraft](https://img.shields.io/badge/minecraft-1.21.3-green)
![Server](https://img.shields.io/badge/server-Paper-orange)

> Komplexní RPG plugin s class systémem, leveling systémem, custom itemy a spawn areas

---

## 📋 Obsah

- [Funkce](#funkce)
- [Požadavky](#požadavky)
- [Instalace](#instalace)
- [Konfigurace](#konfigurace)
- [Příkazy](#příkazy)
- [Permissions](#permissions)
- [Class Systém](#class-systém)
- [FAQ](#faq)

---

## ✨ Funkce

### 🎭 Class Systém
- **3 Unique Classes:** Warrior, Archer, Magick
- **Permanentní výběr** při prvním připojení
- **Class-specific bonusy** a omezení
- **ONLY MAGICK** combat items
- **Custom GUI** pro výběr classy

### 📊 Leveling System
- **100 levelů** s customizovatelnou XP křivkou
- **Stat Points** při každém level up
- **4 hlavní staty:** Damage, Health, Resistance, Mana
- **Class bonusy** k statům
- **GUI pro správu stats**

### 🗺️ Area System
- **WorldEdit integrace** pro výběr oblastí
- **MythicMobs spawn** s customizovatelným spawn rate
- **Rarita mobů** (Common, Uncommon, Rare, Epic, Legendary)
- **Custom XP rewards** z mobů
- **Auto-respawn** systém

### 💎 Item System
- **Oraxen integrace** pro custom itemy
- **5 rarities** s různými bonusy
- **8 kategorií** itemů
- **Class restrictions** na itemy
- **Magic combat items** pouze pro Magick
- **Auto-sorting** inventáře
- **Custom stats** na itemech

### 📦 Drop System
- **Custom drops** z MythicMobs
- **Percentage-based** drop chance
- **Min/Max** množství dropů
- **Rare drop** oznámení

---

## 🔧 Požadavky

### Vyžadované Pluginy:
- **Paper** 1.21.3+ (nebo Purpur/Pufferfish)
- **WorldEdit** 7.3.0+
- **MythicMobs** 5.6.1+
- **Oraxen** 1.171.0+

### Doporučené Pluginy:
- **PlaceholderAPI** 2.11.5+ (pro placeholdery)
- **DeluxeMenus** (pro quest systém)

### Server Requirements:
- **Java:** 21+
- **RAM:** Minimum 2GB (doporučeno 4GB+)
- **Paper/Purpur:** Latest build

---

## 📥 Instalace

1. **Stáhni plugin** a vlož do složky `/plugins`

2. **Nainstaluj závislosti:**
   - WorldEdit
   - MythicMobs
   - Oraxen
   - (Volitelně) PlaceholderAPI

3. **Restartuj server**

4. **Konfigurace:**
   ```bash
   /plugins/LiReapersRPG/
   ├── config.yml         # Hlavní konfigurace
   ├── classes.yml        # Class nastavení
   ├── messages.yml       # Zprávy
   ├── areas.yml          # Spawn areas (auto-generated)
   ├── items.yml          # Custom items (auto-generated)
   ├── drops.yml          # Drop tables (auto-generated)
   └── playerdata.yml     # Player data (auto-generated)
