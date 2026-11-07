# Interactive Portfolio Website

A responsive, animated portfolio starter built with **HTML5, CSS3, jQuery, Bootstrap 5, and Font Awesome**.

## Included features

- Responsive navigation and mobile menu
- Animated hero section and floating profile card
- Scroll progress indicator and active navigation state
- Scroll-reveal section animations
- Project category filters
- Interactive project detail modal
- Animated statistics and skill bars
- Dark / light theme toggle (saved in local storage)
- Contact form that prepares an email in the visitor's default mail app
- Reduced-motion accessibility support

## Folder structure

```text
interactive_portfolio/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── style.css
    └── js/
        └── main.js
```

## Run locally

1. Extract the ZIP file.
2. Open `index.html` in a browser.

For a local PHP/XAMPP environment, copy the `interactive_portfolio` folder into `htdocs` and visit:

`http://localhost/interactive_portfolio/`

No database or build process is required. Bootstrap, Font Awesome, and Google Fonts are loaded from CDNs, so an internet connection is needed for those external assets.

## Personalize before publishing

Search and replace these sample details in `index.html`:

- `Alex Morgan` — your name / brand
- `hello@example.com` — your email address (also update it in `assets/js/main.js`)
- Social links (`href="#"`) — your real profile URLs
- Hero description, skills, statistics, and project descriptions
- Project cards — add real screenshots, live demos, and repository links

The project examples are editable sample content. Keep only projects you want to publicly showcase, and adjust technology labels and descriptions to match the actual work.

## Contact form note

The contact form uses a `mailto:` link and does not send messages through a server. To send messages directly from the website, connect it to a backend endpoint or a trusted form service.
