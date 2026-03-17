# Ziyada — Web

Landing page for [Ziyada](https://ziyada.app), an Islamic learning app for daily growth through short lessons and quizzes.

## Pages

| File | Description |
|------|-------------|
| `ziyada.html` | Main landing page |
| `privacy.html` | Privacy Policy |
| `terms.html` | Terms of Use |

## Structure

```
ziyada-web/
├── ziyada.html
├── privacy.html
├── terms.html
├── css/
│   ├── styles.css     # Global styles
│   ├── ziyada.css     # Beta modal
│   └── policy.css     # Privacy & Terms pages
├── images/            # App screenshots and icons
└── docs/              # Source policy documents
```

## Features

- Dark / light mode with localStorage persistence
- Waitlist form → [Formspree](https://formspree.io) (`mwvrweea`)
- Beta sign-up modal → Formspree (`xojkpaew`)
- Fully static — no build step required
