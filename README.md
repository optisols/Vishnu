# Soul.Vishnu_ — Personal Portfolio

A static personal portfolio site for **Vishnu** (Soul Vishnu): ride showcase, ChatGPT compositing prompt, and an About page. Built with HTML, Tailwind CSS (CDN), and vanilla JavaScript — no build step required.

## Live preview

Open [`index.html`](index.html) in a browser, or serve the folder locally:

```bash
# Python
python -m http.server 8080

# Node (npx)
npx serve .
```

Then visit `http://localhost:8080`.

## Pages

| Page | File | Description |
|------|------|-------------|
| **Prompt / Showcase** | [`index.html`](index.html) | Ride gallery (AR composite, maps, POV) with image swap, Wheelsafar-style prompt panel, copy-to-clipboard |
| **About Me** | [`about.html`](about.html) | Bio, journey, tech stack, travel, and creative work |

## Features

- Dark charcoal + steel glassmorphism UI
- Header navigation with profile photo: About Me, Prompt, Connect (hamburger menu on mobile)
- Three-image gallery with **swap** behavior (primary ↔ secondary; all images stay visible)
- Copy Prompt button for the ChatGPT ride-composite instructions
- Responsive layout for mobile and desktop

## Project structure

```
MySite/
├── index.html          # Home / prompt & ride showcase
├── about.html          # About me
├── README.md
└── assets/
    └── images/
        ├── hero-ar.png       # AR ride composite (default hero)
        ├── ride-maps.png     # Google Maps route
        ├── ride-pov.png      # POV handlebars
        ├── about-work.png    # About page — workspace
        └── about-travel.png  # About page — travel
```

## Tech stack

- HTML5
- [Tailwind CSS](https://tailwindcss.com) (CDN)
- Google Fonts: Hanken Grotesk, Inter, JetBrains Mono
- Material Symbols icons

## Links

- Instagram: [@soul.vishnu_](https://www.instagram.com/soul.vishnu_)
- LinkedIn: [vishnu-shanmugamm](https://www.linkedin.com/in/vishnu-shanmugamm/)

## Deploy

Upload the entire folder to any static host:

- [GitHub Pages](https://pages.github.com/) — enable Pages on the repo root or `/docs`
- [Netlify](https://www.netlify.com/) — drag-and-drop or connect the repo
- [Vercel](https://vercel.com/) — import as static site

For GitHub Pages from the repo root, set the source branch to `main` and folder to `/ (root)`.

## License

Personal portfolio — all rights reserved by the owner unless stated otherwise.
