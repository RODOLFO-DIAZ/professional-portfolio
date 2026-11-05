# Professional Portfolio

Personal portfolio of **Rodolfo Díaz Solano**, Financial Analyst | BI & Automation.
Academic project built with semantic HTML5 and CSS3 only, without JavaScript or frameworks.
The site content is in Spanish.

- **Live site:** https://rodolfo-diaz.github.io/professional-portfolio/
- **Video presentation:** https://youtu.be/juXCBD9Uh5g
- **LinkedIn:** https://cr.linkedin.com/in/rodolfod%C3%ADazsolano

## Video presentation

A two-minute [video](https://youtu.be/juXCBD9Uh5g) explains two design decisions taken in the project:

1. **Design tokens: scalability and maintenance.** Colors, type scale, spacing and z-index layers
   are defined once as CSS custom properties, so a change in one place updates the whole site.
2. **Menu without JavaScript: simplicity and robustness.** The mobile menu relies on a hidden
   checkbox and its `<label>`, so it works with HTML and CSS only and has no scripts to fail.

## Sections

| Section | Content |
|---|---|
| Hero | Name, role, motto, call to action to the contact form and a profile illustration |
| About | Professional story, focus and three interpersonal skills |
| Skills | Microsoft ecosystem tools and programming languages in progress |
| Projects | Three financial projects with image, status, technologies and a details link |
| Education | Degrees, the PL-300 certification and complementary training |
| Contact | Demo form with native validation and an alternative contact on LinkedIn |

## Technical highlights

- **Mobile first:** base styles target phones; `min-width` media queries at 768px, 1024px and 1440px
  move the card lists from one to two and three columns and scale the typography.
- **Flexbox layout:** navigation, card galleries, skills, hero and a three-column footer.
- **Menu without JavaScript:** on small screens a hidden checkbox and its `<label>` open and close
  the navigation, and the label shows a keyboard focus outline.
- **Design tokens:** colors, type scale, spacing and z-index layers live in CSS custom properties.
- **Stacking:** sticky header, cards that lift above their neighbours on hover, and a decorative
  `::before` ring kept behind the hero content with `isolation`.
- **Accessibility:** landmarks with labels, one `h1`, descriptive `alt` text, labelled form fields,
  visible focus states, AA color contrast and `prefers-reduced-motion` support.
- **Privacy:** the form is a demo and does not send data; no personal email or phone number is
  published, and the site makes no requests to third-party services.

## Project structure

```
professional-portfolio/
├── index.html      # Single page with all sections
├── styles.css      # Stylesheet: variables, reset, base, layout, components, media queries
├── images/
│   ├── profile.jpg     # Profile illustration (hero)
│   ├── project1.jpg    # Budget process automation
│   ├── project2.jpg    # Topline and PVM analysis engine
│   └── project3.jpg    # Smart income statement
└── README.md
```

## Run locally

No build step or dependencies are needed. Clone the repository and open `index.html` in a browser:

```
git clone https://github.com/RODOLFO-DIAZ/professional-portfolio.git
```

## Workflow

Each work session used its own branch, small commits following
[Conventional Commits](https://www.conventionalcommits.org/) and a pull request merged into `main`.
The site is published with GitHub Pages from the `main` branch.

## Author

Rodolfo Díaz Solano · [LinkedIn](https://cr.linkedin.com/in/rodolfod%C3%ADazsolano)

© 2026 Rodolfo Díaz Solano
