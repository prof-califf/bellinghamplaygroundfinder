# 🛝 Bellingham Playground Finder

A little love letter to Bellingham playgrounds — built by a local family for local families.

🌐 **Live site:** (#) *(update with real URL)*

## What is this?

A simple, hand-built site that helps Bellingham families pick the right playground for their day. Each playground has its own page with the things we'd want to know before driving over: shade, swings, accessibility, parking, restrooms, fencing, and any insider tips that only locals would tell you.

## Why?

Bellingham has SO many great playgrounds, but it can be hard to figure out which one fits the moment. Toddler that needs a fence? A playground with shade in August? A spray park for a heat wave? This site is trying to make that easy — based on what real local families actually care about.

## Built with AI 🤖

This whole site was built using GenAI (Claude) as a side project — equal parts "go to playgrounds with my kid" and "see what's possible with AI as a collaborator." It's plain HTML/CSS/JS, no framework, no build step. Just files.

## Playgrounds covered (so far)

- **Cornwall Park** — Parkview School Playground
- **Sunnyland** — Sunnyland Park, Sunnyland Elementary School, Shadyland
- **Columbia** — Elizabeth Park (Lizzy Park)
- **Whatcom Falls** — Upper Playground
- **Samish** — Lake Padden Playground
- **Fairhaven** — Fairhaven Park

More to come as we visit them!

## Structure

```
.
├── index.html              # Homepage with playground grid + filters
├── about.html              # About page
├── parkview.html           # Individual playground pages
├── shadyland.html
├── sunnyland-park.html
├── sunnyland-elementary.html
├── elizabeth-park.html
├── whatcom-falls-upper.html
├── lake-padden.html
└── fairhaven.html
```

Each playground page is a self-contained HTML file with inline CSS and JS — easy to read, easy to edit, easy to add to.

## Features

- 🔍 **Filterable homepage** — find playgrounds by features (slides, shade, fenced, baby swings, etc.)
- 🗺️ **Neighborhoods dropdown** — browse by area
- 🏫 **School playground vs. public park badges** — at a glance know what kind of playground you're heading to
- ♿ **Accessibility settings** — high contrast, larger text, reduce motion
- 📱 **Mobile friendly** — works on the phone you're already holding while at the playground

## Contributing

Spotted an error? Know a playground we should cover? Have a tip we should add? Email us at **bellinghamplaygroundfinder@gmail.com** — we'd love to hear from you. This site is built by families, for families.

## Local development

It's just static HTML. Open `index.html` in a browser and you're good. No build step, no dependencies.

For local serving with proper relative paths:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## License

Free to use, copy, fork, learn from. Built with love for Bellingham families.

---

*Made by a local Bellingham fam trying to have fun and go to all the playgrounds 🌲💛*
