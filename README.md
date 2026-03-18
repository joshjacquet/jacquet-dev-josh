![Website](https://img.shields.io/website?url=https%3A%2F%2Fjosh.jacquet.dev&style=flat&label=josh.jacquet.dev)
![Hugo](https://img.shields.io/badge/Hugo-0.143.0+-FF4088?style=flat&logo=hugo&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=flat&logo=bootstrap&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Hosted_on-Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)

# josh.jacquet.dev

Personal portfolio website for **Josh Jacquet** — AI & Agentic Solutions Architect with 12+ years of enterprise leadership in analytics and AI transformation.

**Live site:** [josh.jacquet.dev](https://josh.jacquet.dev/)

## Tech Stack

- **[Hugo](https://gohugo.io/)** — Static site generator (v0.143.0+)
- **[Hugo Profile](https://github.com/gurusabarish/hugo-profile)** — Theme (git submodule)
- **[Cloudflare Pages](https://pages.cloudflare.com/)** — Hosting & CDN
- **Bootstrap 5** / **Font Awesome 6** — UI framework and icons

## Project Structure

```
├── hugo.toml           # Main site configuration
├── content/            # Markdown pages (experience, education, projects, etc.)
├── static/             # Images, custom CSS, and other assets
├── layouts/            # Custom Hugo template overrides
├── themes/hugo-profile # Theme (git submodule)
└── public/             # Built output (gitignored)
```

## Local Development

```bash
# Clone with submodules
git clone --recurse-submodules https://github.com/joshjacquet/jacquet-dev-josh.git

# Start the dev server
hugo server -D
```

The site will be available at `http://localhost:1313/`.

## Building

```bash
hugo --gc --minify
```

Output goes to the `public/` directory.
