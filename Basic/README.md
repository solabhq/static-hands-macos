# Static Hands - Basic Edition

Simple CapsLock-based keyboard navigation for macOS.

## Installation

```bash
chmod +x install.sh
./install.sh
```

Grant permissions when prompted: System Settings → Privacy & Security → Input Monitoring

## Key Mappings

### Navigation
```
CapsLock + I = ↑ Up
CapsLock + K = ↓ Down
CapsLock + J = ← Left
CapsLock + L = → Right

CapsLock + U = Home
CapsLock + O = End

CapsLock + Y = Page Up
CapsLock + N = Page Down
```

### Editing
```
CapsLock + H = Delete (forward)
CapsLock + ; = Backspace
CapsLock + P = Insert
```

### Modifiers
```
CapsLock + W = Hold Command (⌘)
CapsLock + D = Hold Shift (⇧)
CapsLock + S = Hold Option (⌥)
CapsLock + F = Hold Control (⌃)
```

### Speed Navigation
```
CapsLock + 8 = Up ×5
CapsLock + , = Down ×5
CapsLock + M = Left ×6
CapsLock + . = Right ×6
```

## Usage Example

**Navigate and select a line:**
1. Hold `CapsLock` + `U` (Home)
2. Hold `CapsLock` + `D` (Shift) + `O` (End)
3. Line selected!

## Troubleshooting

**Keys not working?**
- Check Karabiner-Elements is running
- Verify Input Monitoring permissions granted
- Open Karabiner → Complex Modifications → ensure rule is enabled

**Want more features?**
Check out `../Advanced/` for text editing, case transformation, and more.

---

MIT License
