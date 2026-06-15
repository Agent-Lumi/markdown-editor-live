# 📝 Markdown Editor Live

A beautiful, real-time markdown editor with live preview, auto-save, and export capabilities.

> **Live Demo:** https://agent-lumi.github.io/markdown-editor-live/

## ✨ Features

- 🔄 **Live preview** as you type
- 💾 **Auto-save** to browser storage
- 📊 **Word count** & statistics (words, characters, lines, read time)
- 📄 **Export to PDF** with syntax highlighting
- 💾 **Export to Markdown** (.md file)
- 🌐 **Export to HTML** (.html file)
- 📁 **Import** .md, .txt, and .markdown files
- 🎨 **GitHub-flavored** markdown support
- 📱 **Mobile responsive** design
- ⌨️ **Keyboard shortcuts** - Full support for common actions
- 🌓 **Dark/Light theme** toggle with persistent preference
- ✨ **Smooth animations** for improved UX
- ↩️ **Undo/Redo** functionality with history (up to 50 states)
- ⌨️ **Keyboard shortcuts help** - Click ⌨️ button to see all shortcuts

## 🚀 Quick Start

1. Open the editor
2. Start typing markdown on the left
3. See the live preview on the right
4. Your work auto-saves every 3 seconds!

## 🛠️ Toolbar Actions

| Button | Action |
|--------|--------|
| H1/H2 | Insert heading |
| Bold | Insert bold text |
| Italic | Insert italic text |
| Link | Insert link |
| Code | Insert code block |
| List | Insert list item |
| Quote | Insert blockquote |
| Clear | Clear all content |
| Example | Load example markdown |
| 📁 Import | Import .md file |
| 💾 Save .md | Export as Markdown |
| 🌐 Save HTML | Export as HTML |
| 📄 Export PDF | Export as PDF |

## 📊 Statistics

The stats bar shows:
- **Words** - Total word count
- **Characters** - Total character count
- **Lines** - Total line count
- **Read time** - Estimated reading time

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| Ctrl+Shift+S | View Writing Statistics |
| Ctrl+S | Export Markdown |
| Ctrl+O | Import file |
| Ctrl+Z | Undo |
| Ctrl+Y | Redo |
| Ctrl+B | Insert bold |
| Ctrl+I | Insert italic |
| Ctrl+K | Insert link |
| Ctrl+P | Export PDF |
| Ctrl+Shift+C | Clear editor |
| Ctrl+/ | Toggle preview pane |
| Escape | Close modals |

## 🎨 Code Highlighting

Syntax highlighting supported for:
- Keywords (function, const, let, etc.)
- Strings
- Functions
- Comments
- Numbers

## 📊 Writing Statistics

Track your writing progress over time!

Click the 📊 button in the header or press **Ctrl+Shift+S** to view:

### Session Tracking
- **Total Words** - Cumulative words written across all sessions
- **Sessions** - Total number of writing sessions
- **Avg Words/Session** - Average words per session
- **Longest Session** - Your most productive session

### Daily Word Count Chart
- Visual bar chart showing the last 7 days of writing activity
- Each bar represents words written that day
- Hover to see exact word counts

### How It Works
- Tracks actual writing (counts words you type, not just open the editor)
- Records after 10 seconds of inactivity (prevents counting pasted content)
- Stores up to 100 sessions in browser storage
- Works across all your devices with the same browser sync

### Reset Statistics
- Click "Reset Statistics" to clear all data
- Confirmation required before deletion

## 📱 PWA Support

This app works offline! Install it on your device:
- **Chrome:** Click "Add to Home Screen" in menu
- **Safari:** Tap Share → "Add to Home Screen"

## 🐛 Fixed Issues (v2.0)

- ✅ Fixed duplicate manifest/service worker tags
- ✅ Fixed broken auto-save functionality
- ✅ Removed duplicate script blocks
- ✅ Added proper word count statistics
- ✅ Added file import/export functionality
- ✅ Added read time estimation
- ✅ Improved keyboard shortcuts

## 🆕 New in v2.1

- 🌓 **Dark/Light theme toggle** - Click the 🌙/☀️ button in the header
- ✨ **Smooth animations** - Fade-in effects and button hover animations
- 🎨 **Persistent theme preference** - Your choice is saved across sessions

## 🆕 New in v2.3

- 📊 **Writing Statistics** - Track your writing progress with session tracking and visual charts
- 📈 **Daily Word Count Chart** - 7-day bar chart showing your writing activity
- 📊 **Stats Button** - New 📊 button in the header for quick access
- 🎹 **Statistics Shortcut** - Ctrl+Shift+S to open statistics modal
- 💾 **Session Storage** - Tracks words written across sessions with localStorage
- 🔄 **Smart Tracking** - Records only actual writing (10s debounce)
- 🗑️ **Reset Functionality** - Clear statistics with confirmation
- 🎨 **Theme Support** - Stats modal works in both dark and light themes

## 🆕 New in v2.2

- ↩️ **Undo/Redo functionality** - Full history management with 50-state buffer
- ⌨️ **Keyboard shortcuts modal** - Click the ⌨️ button to see all available shortcuts
- 🎹 **Extended shortcuts** - Ctrl+B (bold), Ctrl+I (italic), Ctrl+K (link), Ctrl+P (PDF)
- 🧹 **Code cleanup** - Removed unused backup files
- 🔄 **History auto-save** - Tracks changes every 500ms for precise undo/redo
- 🎯 **Toggle preview** - Ctrl+/ to show/hide preview pane

## 📝 License

MIT © [Agent-Lumi](https://github.com/Agent-Lumi)

Made with 💡 by Lumi for @shalkith