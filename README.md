<div align="center">

# 👑 ASHEN CROWN
### Knight's Last Stand

**A fast, brutal, procedural 2D action roguelite, in a single HTML file.**
No assets. No build step. No dependencies. Just open it and fight.

![HTML5](https://img.shields.io/badge/HTML5-Canvas-e34f26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/Vanilla-JavaScript-f7df1e?logo=javascript&logoColor=black)
![Size](https://img.shields.io/badge/Files-1-8a2be2)
![Platform](https://img.shields.io/badge/Desktop%20%7C%20Mobile%20%7C%20Gamepad-supported-blue)

<br>

<a href="https://ramihast.github.io/ASHEN-CROWN/">
  <img src="https://img.shields.io/badge/▶%20PLAY%20NOW-in%20your%20browser-ffb830?style=for-the-badge&labelColor=2a1a3a" alt="Play Now">
</a>

</div>

---

## 📖 The Story

> A kingdom has fallen. The cursed **Ashen Crown** has awakened the dead and twisted the beasts of the land. One knight remains to cross five cursed regions and destroy the crown.

---

## ✨ Highlights

- **4 playable knights**, each with a unique passive, special move, dash and combo chain
- **5 regions, 20 stages, 5 multi-phase bosses**
- **Perfect Parry** combat: every attack is telegraphed, and timing is rewarded
- **Roguelite progression**: upgrade cards, synergies, a blacksmith shop and a permanent meta-upgrade tree
- **100% procedural**: pixel-art sprites are drawn with canvas code, and all sound effects and music are synthesized with the Web Audio API
- **Adaptive Director** that watches your stress level and adjusts enemy waves
- **Full input support**: keyboard (rebindable), gamepad and on-screen touch controls
- **Accessibility options**: colorblind telegraphs, screen-shake slider, damage-number toggle

---

## 🖼️ Screenshots

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/88fbbd1b-e391-45e5-9313-8dcc388c6e76"></td>
    <td><img src="https://github.com/user-attachments/assets/4227de0c-159c-4ded-ab7a-d5a4c0d6e012" alt="Combat"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/c184dec0-fced-48a0-9715-43ff0ff311fd"></td>
    <td><img src="https://github.com/user-attachments/assets/6477ee66-3b28-4076-8967-9368cb6854f9"></td>
  </tr>
</table>

---

## 🚀 Quick Start

### ▶️ Play online

<a href="https://ramihast.github.io/ASHEN-CROWN/">
  <img src="https://img.shields.io/badge/▶%20PLAY%20NOW-in%20your%20browser-ffb830?style=for-the-badge&labelColor=2a1a3a" alt="Play Now">
</a>

Runs directly in your browser via GitHub Pages. Nothing to install.

### 💻 Run locally

```bash
# Option 1: just double-click the file
index.html

# Option 2: serve it locally
python3 -m http.server 8000
# then open http://localhost:8000
```

That's it. The game scales automatically to any screen (internal resolution 480×270, displayed at up to 960×540 and beyond), with a built-in fullscreen button.

> 🔊 Browsers require a click or key press before audio can start. Press any key on the title screen.

---

## 🎮 Controls

| Action | Keyboard | Gamepad |
|---|---|---|
| Move | `A` `D` / `←` `→` | Left stick / D-pad |
| Jump (hold = higher) | `W` / `Space` / `↑` | `A` |
| Attack (chain combos) | `J` / `Z` | `X` / `RT` |
| Dash (i-frames) | `K` / `X` | `B` |
| Block / Parry (hold) | `L` / `C` | `LB` / `LT` |
| Special | `I` / `V` | `Y` |
| Potion | `Shift` | `RB` |
| Pause | `P` / `Esc` | `Start` |

All keyboard bindings can be changed in **Settings**. Touch buttons appear automatically on touch devices.

---

## ⚔️ The Knights

<p align="center">
  <img src="https://github.com/user-attachments/assets/d5d973f3-6377-4121-8d6d-4102b0e1431b" alt="Character select" width="820">
</p>

| Knight | Role | Passive | Special |
|---|---|---|---|
| **Sir Arthorius** *The Oathbound* | Balanced all-rounder | **Resolve**: +25% damage for 5s after 5 kills in a row | **Holy Slash**: a piercing wave of light |
| **Lady Seraphina** *The Gale Blade* | Fast duelist | **Featherfoot**: double jump and 2 dash charges with i-frames | **Whirlwind**: spinning flurry that pulls small foes in |
| **Gronn** *The Ironwall* | Slow heavy tank | **Bulwark**: block cuts 80% damage, parry stuns and refunds big stamina | **Earthquake**: shockwave that launches foes and breaks shields |
| **Kael** *The Night Blade* | Glass cannon assassin | **Umbral Step**: dash is a teleport, plus lifesteal | **Shadow Feast**: 4s of faster, stronger, lifesteal Shadow Mode |

Each knight also has **4 skins** (Classic, Verdant, Royal, Void), unlocked with Soul Shards.

---

## 🛡️ Combat System

- **Perfect Parry**: tap Block right as a hit lands to negate damage, stun melee attackers, refund stamina and charge your special. Yellow `●` marks are parryable, red `▲` marks are not, so dodge those.
- **Everything is telegraphed**: dash through attacks, jump waves, and step out of ground markers.
- **Style Rank (D → C → B → A → S → SS)**: land hits without being hit to raise your rank for bonus score and gold. Getting hit resets it.
- **Special meter** charges as you both deal and take damage.
- **Potions** heal over 2 seconds and are interrupted by damage, so get safe first.
- **Shield Revenants** block frontal hits: dash behind them, parry, or use heavy finishers.
- **Elite enemies** spawn with modifiers: `frenzied`, `armored`, `vampiric`, `volatile`, `phantom`.
- **Enemy token system**: enemies take turns attacking instead of dogpiling you.

---

## 🌍 Regions and Bosses

| # | Region | Hazard | Boss |
|---|---|---|---|
| 1 | Ruined Kingdom Gates | Falling rubble | **Gravewarden Mortus**, the Skeleton King |
| 2 | Rotwood Swamp | Mud and poison pools | **Bloat Queen Vessa**, Swamp Abomination |
| 3 | Frozen Abyss | Ice, icicles, blizzard gusts | **Frostbound Colossus**, Heart of the Abyss |
| 4 | Molten Citadel | Lava geysers, collapsing platforms | **Infernal Duke Malgrath**, the Burning Knight |
| 5 | Hollow Throne | Gravity-flip zones, shadow tendrils, darkness | **The Ashen King**, Wearer of the Crown |

Each region has 3 stages (including special events like *Survive 30 seconds*, *Defend the Lantern*, and *Kill the Hex Priest first*), then a boss. Bosses have **3 phases** and unique mechanics, such as breakable armor, weak points, clones that mimic your moves, and a final **parry-the-finisher** duel.

Secret breakable walls hide treasure chests in some stages.

### Bestiary

Rotting Skeleton · Skeleton Archer · Ghoul Runner · Shield Revenant · Bat Swarm · Cursed Wisp · Bone Hound · Plague Spitter · Grave Digger · Hex Priest · Cinder Imp · Wraith Knight · Shadow Clone

---

## 🃏 Progression

<p align="center">
  <img src="https://github.com/user-attachments/assets/51a763fc-b68e-4096-bfda-9ed6b1776d18" alt="Upgrade cards" width="46%">
  <img src="https://github.com/user-attachments/assets/a5032f45-d8ba-41c6-98c4-cff7971c0a1d" alt="Soul Forge" width="46%">
</p>

### During a run
- **20 upgrade cards** across Common, Rare, Epic and Legendary rarities, picked after each stage (with rerolls)
- **5 hidden synergies**, for example *Blood Chalice*, *Storm Step*, *Mirror Guard*, *Headsman* and *Cheap Thrills*
- **Blacksmith shop** after every boss: potions, healing, damage, HP, stamina, crit and rerolls

### Between runs
- **Soul Forge**: spend Soul Shards on 9 permanent upgrades (Vitality, Might, Fortune, Alchemy, Endurance, Precision, Swift Boots, Soul Hunter, Second Chance)
- **14 achievements**
- Per-knight records for best score, time and rank
<p align="center">
  <img src="https://github.com/user-attachments/assets/3ced526c-daf5-46f4-9d5c-63c2d02a25c9" alt="Character select" width="820">
</p>

---

## 🔥 Difficulty

| Mode | Description |
|---|---|
| **Squire** | Forgiving. Weaker foes, 5 continues |
| **Knight** | The intended challenge. 3 continues |
| **Champion** | Tougher and faster. 1 continue |
| **Ashen Lord** | Extreme. **One life.** New attack patterns |

Harder modes pay out more Soul Shards.

---

## 🧩 Under the Hood

Everything lives in one self-contained `index.html`, organized into clean modules:

| Module | Responsibility |
|---|---|
| `CONFIG` | Every tweakable number: knights, enemies, bosses, upgrades, regions |
| `Utils` / `Save` | Helpers, and `localStorage` persistence with in-memory fallback |
| `AudioManager` | Synthesized SFX and a procedural music sequencer per region |
| `InputManager` | Keyboard, touch and gamepad, with input buffering and rebinding |
| `Camera` | Smooth follow, lookahead, shake, zoom pulses, cinematic focus |
| `ParticleSystem` / `ProjectileSystem` | Pooled objects, so there are no per-frame allocations |
| `Player` / `Enemy` / `Boss` | State-machine-driven entities with a data-driven AI table |
| `Director` | Tracks player stress and scales wave budgets and pacing |
| `LevelManager` | Stages, waves, events, hazards, platforms and parallax backgrounds |
| `UIManager` | HTML menus (keyboard, mouse and gamepad navigable) and the canvas HUD |
| `Game` | Fixed-timestep main loop, hitstop and slow-mo, combat glue, rendering |

Technical notes:
- **Fixed 60 Hz timestep** with a delta-time clamp for stable gameplay
- **Pixel-perfect rendering** with an offscreen lighting layer and dynamic lights
- **Auto-pause** when the tab loses focus
- Progress and settings are saved to `localStorage` under the key `ashen_crown_v1`

---

## 💡 Tips

1. **Dash has invincibility frames.** Use it *through* attacks, not away from them.
2. Kill **Hex Priests** first, since they summon and shield other enemies.

3. Parry the **yellow flashes**, and dodge the red ones.
4. Special charges from damage taken too, so a risky fight can pay off.
5. Heavy finishers break shields, and Gronn's Earthquake breaks them all.

