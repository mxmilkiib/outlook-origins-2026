# Outlook Origins 2026 Lineup Guide

AI-generated interactive guide for the Outlook Origins 2026 lineup, held at The Garden in Tisno, Croatia from July 23-27, 2026.

## Features

- **Interactive cards** displaying artist information, descriptions, and profile links
- **Multiple view modes**: cards, compact two-line, and list views
- **Responsive font sizing** from XS to XL
- **Theme system** with 15+ themes including shade variations (Light, Mid, Dark, OLED, B&W), colour themes (Purple/Gold, Gold/Green, Red/Black, Blue/White, Poster, Origins), and stylized themes (Neon, Pastel, Ocean, Hatched)
- **Genre sections** for Drum & Bass, Jungle, Dubstep, Grime, Sound System, Techno, Breaks, Club, UK Garage, Jazz, and Afro
- **Collapsible sections** with persistent fold state
- **Countdown timer** to festival start
- **Link verification system** with visual indicators for confirmed vs. search-fallback links
- **All 8 platform buttons** on every card (SoundCloud, Bandcamp, Instagram, YouTube, Spotify, Discogs, MusicBrainz, RateYourMusic)

## Structure

Single-file HTML application with embedded CSS and JavaScript. Artist data is stored in a JavaScript array with the following fields:

- `name`: Artist name
- `genre`: Primary umbrella genre (dnb, jungle, dubstep, grime, etc.)
- `desc`: Three-sentence description
- `styles`: Comma-separated subgenres/styles
- `from`: Location/origin
- `since`: Career start year
- `releases`: Approximate release count
- `collab`: Notable collaborations
- `conf`: Confidence level (1-5) for data accuracy
- `links`: Object containing profile slugs for various platforms (sc, bc, ig, yt, sp, dc, mb, ry, scRef)

## Links

- **Festival**: [Outlook Origins](https://www.outlookorigins.com/)
- **Deployment**: [outlook-origins-2026.vercel.app](https://outlook-origins-2026.vercel.app/)
- **Repository**: [github.com/mxmilkiib/outlook-origins-2026](https://github.com/mxmilkiib/outlook-origins-2026)

## Local Development

No build process required. Serve the `index.html` file with any static server:

```bash
python3 -m http.server 9123
```

Then open `http://localhost:9123` in a browser.

## Notes

This is an AI-generated guide. Links and details may contain errors and should be verified independently. The project includes AI task prompts in the appendix section for systematic improvement of artist data, link verification, and description quality.
