# TickTOC

Keep your Obsidian docs organized with automatically generated Tables of Contents. Click <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 6H3"/><path d="M7 12H3"/><path d="M7 18H3"/><path d="M12 18a5 5 0 0 0 9-3 4.5 4.5 0 0 0-4.5-4.5c-1.33 0-2.54.54-3.41 1.41L11 14"/><path d="M11 10v4h4"/></svg> in your sidebar anytime you want to refresh your TOCs.

## Features

- Smart placement under headers (after your tags)
- Nested bullet or numbered lists
- Reading time estimates
- File modification timestamps
- One-click refresh with the sidebar button

## Getting Started

1. Install and enable the plugin
2. Hit `Cmd/Ctrl + P` and type "Create TOC" to add your first table of contents
3. Click the refresh button  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 6H3"/><path d="M7 12H3"/><path d="M7 18H3"/><path d="M12 18a5 5 0 0 0 9-3 4.5 4.5 0 0 0-4.5-4.5c-1.33 0-2.54.54-3.41 1.41L11 14"/><path d="M11 10v4h4"/></svg> in your sidebar to update TOCs after making changes

## Commands

- Create a TOC under your first header
- Remove any TOC
- Switch between bullet and numbered formats
- Toggle reading time estimates on/off
- Toggle last modified timestamp on/off

## Settings

Customize your TOCs with these options:

- Bullet or numbered list style
- ISO or locale-based timestamps
- Show/hide reading times
- Show/hide last modified time
- Adjust reading speed (100-400 words per minute)

## Pro Tips

1. Type `{{toc}}` anywhere to create a TOC on the spot
2. Set up hotkeys for commands you use often
3. Your TOC formats update instantly when you change settings
4. Click the sidebar refresh button after adding new headers

## Examples

A numbered TOC with read times:
```markdown
## Table of Contents
*Last modified: 2024-11-26T20:30:00.000Z*

1. Introduction *(2 min read)*
  1.1. Background *(1 min read)*
  1.2. Getting Started *(3 min read)*
2. Main Content *(5 min read)*
  2.1. Details *(2 min read)*
```

Same TOC with bullets:
```markdown
## Table of Contents
*Last modified: 2024-11-26T20:30:00.000Z*

- Introduction *(2 min read)*
  - Background *(1 min read)*
  - Getting Started *(3 min read)*
- Main Content *(5 min read)*
  - Details *(2 min read)*
```

## License

MIT

---
Found a bug? Have an idea? Open an issue on [GitHub](link-to-repo).
