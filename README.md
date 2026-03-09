# MeetupSlides

Presentation decks for the **Western Mass Bitcoin Meetup (WMBTCM)**, built with [Slidev](https://sli.dev/).

## Structure

```
decks/
  WMBTCM-44/
    slides.md       ← the full deck as a single Markdown file
    assets/         ← images, QR codes, etc.
  WMBTCM-45/
    ...
```

## Viewing a Deck

```bash
# Install dependencies (first time only)
npm install -g @slidev/cli

# Serve a deck locally
cd decks/WMBTCM-44
slidev slides.md
# → opens at http://localhost:3030
```

## Exporting

```bash
# Export to PDF
slidev export slides.md

# Export to static HTML
slidev build slides.md
```

## Slide Format

Most slides are plain Markdown:

```md
---

# Slide Title

- Bullet one
- Bullet two

---
```

Rich visual slides (charts, diagrams) use inline HTML/SVG blocks — they render natively in Slidev with no quality loss.

## Workflow

1. Bob generates a `slides.md` file for the requested topic/meetup number
2. File is committed here
3. Reed previews at `localhost:3030`, edits `.md` directly before presenting
4. Bob can run `slidev build` to produce a static export for sharing
