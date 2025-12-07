# Static Hands - Advanced Edition

CapsLock-based navigation with modifiers, text editing, and case transformation.

## Installation

```bash
chmod +x install.sh
./install.sh
```

Grant permissions: System Settings → Privacy & Security → Input Monitoring

## Key Mappings

### Navigation
```
CapsLock + I/K/J/L = Arrows
CapsLock + U/O = Home/End
CapsLock + Y/N = Page Up/Down
CapsLock + H = Delete
```

### Modifier Modes

Hold `CapsLock` + modifier to activate:

**Command Mode (W):**
```
CapsLock → W → C = Copy
CapsLock → W → V = Paste
CapsLock → W → X = Cut
CapsLock → W → Z = Undo
CapsLock → W → A = Select All
CapsLock → W → B = Bold
```

**Shift Mode (D):**
```
CapsLock → D → arrows = Select text
```

**Option Mode (S):**
```
CapsLock → S → J/L = Jump by word
```

**Control Mode (F):**
```
CapsLock → F → [key] = Control + key
```

### Case Transformation
Select text first:
```
CapsLock + 9 = UPPERCASE
CapsLock + 0 = lowercase
CapsLock + - = Title Case
```

### Special
```
CapsLock + G = Google Search
CapsLock + P = Insert
CapsLock alone = Escape
```

## Usage Example

**Copy text:**
1. Hold `CapsLock`
2. Hold `W`
3. Press `C`

## Troubleshooting

**Modifiers not working?**
- Ensure "Modifier Keys (W/S/D/F)" rule enabled in Karabiner
- Hold modifier while pressing other keys

**Manual rule enable:**
1. Open Karabiner-Elements
2. Complex Modifications → Add rule
3. Enable all "Static Hands" rules

**Case transform not working?**
- Requires Python 3: `brew install python3`

## Files

- `CHEATSHEET.txt` - Full reference
- `upgrade.sh` - Upgrade script
- `uninstall.sh` - Remove script

---

MIT License | Requires: macOS 10.15+, Karabiner-Elements, Python 3
