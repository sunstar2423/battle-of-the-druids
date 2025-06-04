# Battle of the Druids

A fantasy turn-based RPG battle game built with Python and Pygame. Choose your character, battle enemies, collect Dragon Shards, and upgrade your equipment in the mystical Druid Store!

## Features

🗡️ **Four Character Classes**
- **Knight** - Fast warrior with a strong sword
- **Wizard** - Magic wielder with lightning spells
- **Rogue** - Quick assassin with twin daggers  
- **Soldier** - Heavily armored spear fighter

⚔️ **Combat System**
- Turn-based tactical battles
- Attack, Special Attack, and Heal abilities
- Dynamic damage calculation with defense
- Animated battle sequences

🏪 **Druid Store**
- Upgrade weapons and armor
- Purchase the legendary DRUID CLOAK
- Buy health potions
- Dual currency system (Dragon Shards & Gold)

🎮 **Game Features**
- Beautiful gradient backgrounds
- Character sprites and animations
- Sound effects and background music support
- Player stats tracking
- Battle log system

## Screenshots

*Add screenshots of your game here when you upload them to GitHub*

## Installation & Setup

### Prerequisites
- Python 3.6 or higher
- Pygame library

### Quick Start
1. **Clone the repository**
   ```bash
   git clone https://github.com/sunstar2423/battle-of-the-druids.git
   cd battle-of-the-druids
   ```

2. **Install Pygame**
   ```bash
   pip install pygame
   ```

3. **Run the game**
   ```bash
   python "Battle of the Druids - Pygame Graphics Version.py"
   ```

### Optional: Add Assets
For the full experience, you can add these optional files to the game directory:

**Character Images** (80x80 PNG files):
- `knight.png`
- `wizard.png` 
- `rogue.png`
- `soldier.png`
- `goblin.png`
- `dark_mage.png`
- `skeleton.png`
- `orc.png`

**Sound Effects** (WAV files):
- `attack.wav`
- `special.wav`
- `heal.wav`
- `victory.wav`
- `defeat.wav`
- `buy.wav`
- `click.wav`

**Background Music**:
- `background_music.mp3` (or .ogg, .wav)

## How to Play

### Character Selection
Choose from four unique character classes, each with different stats and abilities.

### Combat
- **Attack** - Deal damage based on your weapon
- **Special** - Use your character's unique special ability
- **Heal** - Restore health points

### Progression
- Defeat enemies to earn Dragon Shards and Gold
- Visit the Druid Store to purchase upgrades
- Build the ultimate warrior and claim the DRUID CLOAK!

### Controls
- Mouse clicks to navigate menus and select actions
- All interactions are point-and-click based

## Game Mechanics

### Character Stats
- **Health** - Your life points
- **Attack** - Base damage dealt
- **Defense** - Damage reduction from enemies
- **Speed** - Turn order in combat (future feature)

### Currency System
- **Dragon Shards** - Primary currency earned from battles
- **Gold** - Secondary currency for premium purchases

### Store Items
| Item | Cost | Effect |
|------|------|--------|
| Iron Sword | 50 shards, 20 gold | +5 Attack |
| Steel Armor | 80 shards, 30 gold | +8 Defense |
| Lightning Wand+ | 100 shards | +10 Attack |
| Dragon Scale Armor | 150 shards, 50 gold | +15 Defense |
| **DRUID CLOAK** | 500 shards, 200 gold | +20 Attack, +15 Defense |
| Health Potion | 20 shards, 10 gold | Instant heal |

## Technical Details

- **Engine**: Pygame
- **Resolution**: 1400x900 pixels
- **Frame Rate**: 60 FPS
- **Audio**: Pygame mixer support

## Project Structure

```
battle-of-the-druids/
├── Battle of the Druids - Pygame Graphics Version.py  # Main game file
├── README.md                                          # This file
├── requirements.txt                                   # Python dependencies
├── LICENSE                                           # MIT License
└── assets/                                          # Optional asset folder
    ├── images/                                      # Character sprites
    ├── sounds/                                      # Sound effects
    └── music/                                       # Background music
```

## Contributing

Contributions are welcome! Here are some ways you can help:

- 🎨 Create character sprites or UI improvements
- 🔊 Add sound effects and music
- 🐛 Report bugs or suggest features
- 📝 Improve documentation
- ⚔️ Balance gameplay mechanics

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Future Enhancements

- [ ] Multiplayer battles
- [ ] More character classes (Paladin, Necromancer, etc.)
- [ ] Quest system
- [ ] Save/load game functionality
- [ ] More enemy types and boss battles
- [ ] Equipment visual effects on characters
- [ ] Mobile-friendly controls

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [Pygame](https://www.pygame.org/)
- Inspired by classic turn-based RPGs
- Created as a learning project for game development

## Contact

If you have questions, suggestions, or just want to chat about the game, feel free to open an issue or reach out!

---

*Happy battling, and may the Dragon Shards be with you! 🐉*
