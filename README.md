# Muse Ember demo

A motion graphics demo video made with Muse Ember (via OpenRouter) for the Build Day: OpenRouter × Meta hackathon.

- **Brief**: https://app.notion.com/p/openrouter/Build-Day-OpenRouter-x-Meta-4102fd57c4dc808da9c8eaa351d460ad

## What it is

A HyperFrames composition — HTML, CSS and seekable GSAP animations that render to MP4.

- Entry: `muse-ember-demo/index.html` (1920×1080, 10s)
- Stack: HyperFrames 0.9.28, GSAP 3.15.0

## Run

```bash
cd muse-ember-demo
npm run dev      # preview in browser
npm run check    # lint + runtime + layout checks
npm run render   # render to MP4
npm run publish  # shareable link
```

## Model

All sessions run on `meta/muse-ember` through OpenRouter (see `.claude/settings.local.json`).

Sign-off: Karl Villanueva
