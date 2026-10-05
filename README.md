# ObsidianSnippets

CSS snippets for [Obsidian](https://obsidian.md).

## Installation

1. Copy the `.css` files into your vault's `.obsidian/snippets/` folder.
2. In Obsidian, go to **Settings → Appearance → CSS snippets** and enable them.

## `tasks.css`: custom task states

Round checkboxes with [Heroicons](https://heroicons.com) icons for alternative task states.

| Syntax  | Meaning               | Icon           |
| ------- | --------------------- | -------------- |
| `- [x]` | Done                  | filled         |
| `- [-]` | Canceled              | dash           |
| `- [/]` | Partial               | half-filled    |
| `- [&]` | Overrun               | return arrow   |
| `- [!]` | Urgent                | bolt (purple)  |
| `- [*]` | Important             | star (yellow)  |
| `- [>]` | Current task          | play (blue)    |
| `- [=]` | Paused / simultaneous | pause (blue)   |
| `- [»]` | Postponed             | forward arrows |
| `- [«]` | Anticipated           | back arrows    |
| `- [#]` | Blocked / waiting     | lock           |
| `- [o]` | Recurrent             | refresh (blue) |
| `- [~]` | Snoozed               | clock          |
| `- [p]` | Project               | grid           |
| `- [u]` | Urgent project        | grid + bolt    |
| `- [i]` | Important project     | grid + star    |

- Done, canceled, overrun, postponed and anticipated tasks get muted text. This is skipped when the Tasks plugin is active.
- The `#routine` tag is hidden in live preview but still shows in source mode.

## `ui.css`: interface tweaks

- **Typography:** a 900px line width, a tighter header scale, justified paragraphs, heavier bold and internal links.
- **Colours:** text colours derived from the theme background in `oklch`, with light and dark variants.
- **Properties:** shown as a rounded pill with the heading hidden and keys aligned.
- **Media:** images are centred with rounded corners and dimmed in dark mode until hovered. PDFs have a capped height and YouTube embeds play at 16:9.
- **Embeds:** an embedded note's duplicate first heading is hidden.
- **Code:** compact code block fences and larger math blocks.
- **Workspace:** thin scrollbars that match the theme, no horizontal overflow in sidebars, and theme-aware backgrounds in settings and Bases.

All sizes, radii and colours live as variables at the top of `ui.css`, so you can tweak them in one place.

## License

See [LICENSE](LICENSE).
