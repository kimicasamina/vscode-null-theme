# Null Theme for VSCode

A cyberpunk-inspired VSCode theme with bright neon colors, clear contrast, and frameless minimal chrome. Features two variants with absolute black and near-black backgrounds inspired by Cyberpunk 2077 and Level Up aesthetics.

## Features

- 🎨 **Bright Neon Colors**: Eye-catching cyberpunk syntax highlighting
- 🖤 **8 Unique Variants**: Different color intensities and moods
- 🎯 **Clear Contrast**: High contrast for better readability
- 🔲 **Frameless Design**: Minimal chrome with uniform dark backgrounds
- 📁 **Enhanced Git Indicators**: Clear visual indicators for modified/added/deleted files
- 🌈 **Cyberpunk Aesthetic**: Inspired by Cyberpunk 2077 and synthwave aesthetics

## Theme Variants

### **Absolute Black** - Pure void background

- Background: `#000000` (absolute black)
- Primary colors: Cyan, magenta, bright green
- Perfect for OLED displays and maximum contrast

### **Near Black** - Slightly softer darkness

- Background: `#0A0A0A` (near black)
- Similar to Absolute Black but with subtle depth
- Easier on the eyes for extended coding sessions

### **Vivid** - Ultra-bright saturation

- Background: `#0D0D0D`
- Maximum saturation neon colors
- For those who want colors that pop off the screen

### **Muted** - Soft and refined

- Background: `#0F0F0F`
- Desaturated cyberpunk colors
- Professional look with cyberpunk DNA

### **Pastel** - Gentle neon glow

- Background: `#1A1A1F`
- Soft pastel versions of cyberpunk colors
- Easy on the eyes while maintaining the aesthetic

### **Electric** - High-energy brightness

- Background: `#050510`
- Electric blue and yellow focus
- Lightning-inspired color palette

### **Midnight** - Deep blues and purples

- Background: `#0D0D1A`
- Purple and blue dominant palette
- Nighttime coding atmosphere

### **Synthwave** - Classic 80s aesthetic

- Background: `#0F0F1F`
- Pink and cyan 80s synthwave colors
- Pure retro-futurism vibes

## Color Palette

### Primary Colors

- **Cyan**: `#00FFFF` - Functions, main text
- **Magenta**: `#FF00FF` - Keywords, active elements
- **Bright Green**: `#00FF66` - Strings
- **Yellow**: `#FFFF00` - Classes, modified files
- **Orange**: `#FF6600` - Numbers, constants

### Git Status Colors

- **Modified**: `#FFFF00` (Yellow)
- **Added/Untracked**: `#00FF66` (Green)
- **Deleted**: `#FF0066` (Red)
- **Conflicting**: `#FF6600` (Orange)

## Installation

### Method 1: Manual Installation

1. Copy the `null-theme` folder to your VSCode extensions directory:

   - **macOS**: `~/.vscode/extensions/`
   - **Windows**: `%USERPROFILE%\.vscode\extensions\`
   - **Linux**: `~/.vscode/extensions/`

2. Restart VSCode

3. Open Command Palette (`Cmd+Shift+P` / `Ctrl+Shift+P`)

4. Type "Preferences: Color Theme" and select it

5. Choose from any of the 8 variants:
   - "Null Theme - Absolute Black"
   - "Null Theme - Near Black"
   - "Null Theme - Vivid"
   - "Null Theme - Muted"
   - "Null Theme - Pastel"
   - "Null Theme - Electric"
   - "Null Theme - Midnight"
   - "Null Theme - Synthwave"

### Method 2: Package as VSIX (Advanced)

```bash
# Install vsce if you haven't already
npm install -g vsce

# Navigate to the theme directory
cd null-theme

# Package the theme
vsce package

# Install the generated .vsix file
code --install-extension null-theme-1.0.0.vsix
```

## Configuration

For the best frameless experience, add these settings to your VSCode `settings.json`:

```json
{
  "window.titleBarStyle": "native",
  "workbench.colorTheme": "Null Theme - Absolute Black",
  "editor.fontFamily": "'Fira Code', 'Cascadia Code', monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 14,
  "editor.lineHeight": 1.5,
  "workbench.iconTheme": "material-icon-theme",
  "editor.minimap.enabled": true,
  "editor.minimap.showSlider": "always"
}
```

## Screenshots

The theme provides vibrant neon syntax highlighting perfect for:

- JavaScript/TypeScript
- Python
- HTML/CSS
- JSON
- Markdown
- And many more languages

## Contributing

Feel free to open issues or submit pull requests if you find any bugs or have suggestions for improvements.

## License

MIT License - feel free to use and modify as needed.

---

_Embrace the void. Code in neon._
