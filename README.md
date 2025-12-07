# Static Hands for macOS

CapsLock-based keyboard navigation. Keep hands on home row.

<img width="2410" height="958" alt="2_statichands-extended_large_3840x2160 1" src="https://github.com/user-attachments/assets/ed3224a5-952b-4658-b909-78734fd4e49c" />

## 📺 Video Review

[Static-Hands](https://www.youtube.com/@solabhq)

Prerequisites (Требования)

## Installation

**Step 1: Prepare the Environment** 

Ensure [Karabiner-Elements](https://karabiner-elements.pqrs.org/) is installed and running. This tool functions as a configuration profile for Karabiner-Elements, so you must install it first.

**Step 2: Install Static Hands** 

Open your terminal and run the following commands:

 ```bash
cd Advanced/  # or Basic/
chmod +x install.sh
./install.sh
```

**Step 3: Activate**

1. Open Karabiner-Elements.
2. Go to the Complex Modifications tab.
3. Click Add rule.
4. You should see "Static Hands" in the list. Click Enable All.

## Versions

**Basic** - Simple navigation
- Arrows (I/K/J/L)
- Home/End (U/O)
- Page Up/Down (Y/N)
- Files: 3 | Size: 25 KB

**Advanced** - Full power
- Everything in Basic
- Modifier modes (W/S/D/F)
- Text editing (Copy/Paste/Undo)
- Case transformation (UPPER/lower/Title)
- Google Search
- Files: 4 | Size: 82 KB

## 🖼️ Wallpaper Pack

**Keep the keyboard layout always visible on your desktop!**

[Download 4K Wallpaper Pack](https://ko-fi.com/s/d626933c7d)

## Quick Reference

### Navigation (both versions)
```
CapsLock + I/K/J/L = Arrows
CapsLock + U/O = Home/End
CapsLock + Y/N = Page Up/Down
CapsLock + H = Delete
```

### Advanced Only: Modifiers
```
Hold CapsLock → Hold W → Press C = Copy
Hold CapsLock → Hold D → Press L = Select right
Hold CapsLock → Hold S → Press J = Jump word left
```

### Advanced Only: Case Transform
```
Select text → CapsLock + 9 = UPPERCASE
Select text → CapsLock + 0 = lowercase
Select text → CapsLock + - = Title Case
```

## Troubleshooting

**Keys not working?**
1. Check Karabiner-Elements is running
2. Verify permissions granted
3. Open Karabiner → Complex Modifications → check rules enabled

**Auto-enable didn't work?**
1. Open Karabiner-Elements
2. Complex Modifications → Add rule
3. Enable all "Static Hands" rules

**Need to uninstall?**
```bash
rm ~/.config/karabiner/assets/complex_modifications/static-hands-*.json
# Then restart Karabiner-Elements
```

## Requirements

- macOS 10.15+
- [Karabiner-Elements](https://karabiner-elements.pqrs.org/)
- Python 3 (for case transformation in Advanced)

## Docs

- `Basic/README.md` - Basic key mappings
- `Advanced/README.md` - Advanced features
- `Advanced/CHEATSHEET.txt` - Printable reference

---
☕ [Support on Ko-fi](https://ko-fi.com/solab) | 📺 [YouTube Channel](https://youtube.com/@solabhq) 
