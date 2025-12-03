# Dojo Wings 🍗

**Wings Wednesday Leaderboard** - Track the ultimate wings challenge champions!

## About

A static HTML leaderboard inspired by Brew Dog's Wings Wednesday challenge. Features a dark, bold aesthetic with:

- Dark background with teal and yellow accents
- Bold sans-serif typography (Anton & Barlow fonts)
- Responsive design for mobile and desktop
- Gold, silver, and bronze highlighting for top 3 positions

## Hosting

This site is hosted on GitHub Pages. Once enabled, it will be available at:
`https://<username>.github.io/dojo-wings/`

### Enable GitHub Pages

1. Go to repository Settings
2. Navigate to Pages
3. Under "Build and deployment", select "GitHub Actions"
4. The site will deploy automatically on push to main

## Local Development

To run locally:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080` in your browser.

## Customization

Edit `index.html` to update:
- Leaderboard entries (names, dates, wing counts)
- Statistics in the stats bar
- Colors and styling in the `<style>` section
