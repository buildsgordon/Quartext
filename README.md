# Quartext  
**Quartext: Capture thoughts instantly**

Quartext is a single-pane, in-browser Markdown editor thats fully local.

It's made with vanilla JavaScript, modern HTML5, and CSS and packed in an easy-to-download HTML file.

[**Live Demo**](https://buildsgordon.github.io/Quartext/) 

[Download here](https://github.com/buildsgordon/Quartext/releases/download/v3.0.0/QuartextV3.html)

---

## Overview
**Quartext** is a minimalist Markdown editor built for *speed and simplicity*.  
Unlike full-featured apps such as Obsidian or MarkText, Quartext focuses on **instant note-taking**
(jotting down quick thoughts, lists, or ideas)

---

## Features
- Single-page, live Markdown preview  
- Three modes: **Edit** (type & preview), **View** (formatted read-only), **Source** (raw Markdown)  
- Minimap(VS CODE style) & line numbering  
- Auto-save via localStorage (using StorageManager.persist())  
- Export as .md
- Keyboard shortcuts (Ctrl+B, Ctrl+I, Ctrl+S)  
- Settings panel: light/dark theme, fonts, minimap toggle, margins, and more  
- Embeds: images, code blocks, tables  

---

##  Markdown Support
```markdown
# Header 1
## Header 2
### Header 3
Headers are collapsible!

**Bold** · *Italic* · ==Highlight== · ~~Strikethrough~~

- Bullet list item  
- Also known as unordered list  

1. Numbered list item  
2. Also called ordered list  

--- Separators  
---
Code blocks(beta) with ``` to start and ``` to end.
Tables: Insert Only, no manual recognition
Images: ![text](image_url)
```
# Philosophy

Quartext isn’t designed for heavy research or long documents.
It's always there when you need it, and it will always work, even without wifi!

⚠️ Known Issues:
- Some cases require clicking a “broken” line (not rendering) and clicking off to correct rendering.
- Notes are stored as plain text in localStorage(No sensitive data + **export before clearing browser cache**)
- There’s no full version history or snapshot system yet.
- Limited support for files > 2MB
- Collapsed header states aren’t preserved after reload.

I'd love your feedback!
[Feedback Form](https://docs.google.com/forms/d/e/1FAIpQLSchIUP0AwQ6Cm89Ru1QYdfAKE78Lw_CmVa9rAmn7YPJHHIlKg/viewform?usp=header)
For collaboration or business inquiries: buildsgordon@gmail.com

