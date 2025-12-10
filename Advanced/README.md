CapsLock-based navigation with modifiers, text editing, and case transformation.

## Installation
```bash
chmod +x install.sh
./install.sh
```

**Important:** After installation, you must manually enable all 9 rules in Karabiner-Elements:
1. Open Karabiner-Elements
2. Go to "Complex Modifications" tab
3. Click "Add rule"
4. Find "Static Hands - Advanced (macOS)"
5. Enable ALL 9 rules

Grant permissions: System Settings → Privacy & Security → Input Monitoring

## Key Mappings

### Navigation
```
CapsLock + I/K/J/L = Arrows
CapsLock + U/O = Line Start/End (⌘←/⌘→)
CapsLock + Y/N = Page Up/Down
CapsLock + H = Delete
```

**Note on macOS Home/End behavior:**
- `U` jumps to **start of line** (not document start)
- `O` jumps to **end of line** (not document end)
- For document start/end: use `CapsLock + W + I/K`

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
CapsLock → W → I = Document Start (⌘↑)
CapsLock → W → K = Document End (⌘↓)
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
CapsLock + G = Google Search (select text first)
CapsLock + P = Insert
CapsLock + Q = Escape
CapsLock + R = Rename (F2)
CapsLock + T = Select Line
CapsLock + 7 = Tab
CapsLock + ` = Quit App (⌘Q)
CapsLock alone = Escape
```

## Usage Examples

**Copy text:**
1. Hold `CapsLock`
2. Hold `W`
3. Press `C`

**Select word and make uppercase:**
1. Hold `CapsLock`
2. Hold `S` (Option mode)
3. Press `L` (select word right)
4. Release all keys
5. Hold `CapsLock`
6. Press `9` (uppercase)

**Jump to document start:**
1. Hold `CapsLock`
2. Hold `W` (Command mode)
3. Press `I`

## Troubleshooting

**Modifiers not working?**
- Ensure ALL 9 rules are enabled in Karabiner-Elements
- "CapsLock as Modifier" must be enabled FIRST
- Hold modifier key while pressing other keys

**Manual rule enable:**
1. Open Karabiner-Elements
2. Complex Modifications → Add rule
3. Enable all "Static Hands - Advanced" rules in order

**Case transform not working?**
- Requires Python 3: `brew install python3`
- Must select text before transforming

**Keys not responding?**
- Grant Input Monitoring permissions
- Restart Karabiner-Elements
- Check if all 9 rules are enabled (not just added)

## Files

- `CHEATSHEET.txt` - Printable full reference
- `static-hands-advanced-macos.json` - Configuration file
- `install.sh` - Installation script

---

MIT License | Requires: macOS 10.15+, Karabiner-Elements, Python 3
