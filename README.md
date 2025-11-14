# React Demo (HTML)

A minimal, single-page demo that shows how to use React (UMD build) directly inside an HTML file. The project demonstrates a light, Vercel-like landing layout with a centered hero, navigation, avatar (Dicebear), and a small features section.

<img width="1620" height="742" alt="image" src="https://github.com/user-attachments/assets/ce071000-5875-42db-b941-8c8e9ebb0f1d" />

> [Deployed Link]()
> [Github Link](https://github.com/fasakinhenry/react-demo-html)

Live preview: Open `index.html` in your browser

## Contents

- `index.html` — The demo page using React and ReactDOM from UNPKG and JSX via `@babel/standalone`.
- `style.css` — Global styles (light, Vercel-like landing layout, responsive).
- `README.md` — This file.

## Features

- Centered hero with large typographic heading and subheading.
- Top navigation with logo, links and a Dicebear avatar.
- Chip-style list and primary CTA button.
- Subtle divider lines and a two-column feature grid (responsive to single column on small screens).

## Quick start

- Clone or download the repository, then preview locally.

- simply open `index.html` directly in your browser (double-click), though using a local server is recommended for compatibility with some browser features.

## Development notes

- The page uses the UMD builds of React and ReactDOM and `@babel/standalone` so you can write JSX inside a `<script type="text/jsx">` tag. That keeps this demo zero-config and easy to edit.
- To change the avatar, edit the Dicebear URL in `index.html` (the `seed` query parameter controls the generated image).
- If you want to convert this into a Next.js project for Vercel deployment, move `style.css` into `styles/globals.css`, create pages (`pages/_app.js`, `pages/index.js`) and paste the JSX into a React component.

## Files changed during styling

- `index.html` — added semantic classes and sections: `.site-nav`, `.site-header`, `.lead`, `.content`, `.chip`, `.cta-row`, `.feature-grid`.
- `style.css` — rewritten to provide a clean, light landing-page look and responsive behavior.

## Contributing

Contributions are welcome. Simple issues, improvements to the design, or converting to a Next.js scaffold are great next steps.

Steps to contribute:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feat/your-change`.
3. Make changes and commit using conventional commits: `git commit -am "Describe your change"`.
4. Push and open a pull request.

## License

MIT License. See `LICENSE` file for details.


