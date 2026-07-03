# Shekhar Roy Portfolio

Static portfolio website for [Shekhar Roy](https://shekharroy.com/), an Associate Staff Engineer at Nagarro and Microsoft Certified Azure Professional based in New Delhi, India.

The site presents Shekhar's engineering background across .NET, React, Microsoft Azure, microservices, Kafka, Redis, Docker, trading systems, blockchain, and performance-focused product engineering.

## Live Site

- Portfolio: [shekharroy.com](https://shekharroy.com/)
- LinkedIn: [linkedin.com/in/shekharroy](https://www.linkedin.com/in/shekharroy/)
- GitHub: [github.com/kumarshekharroy](https://github.com/kumarshekharroy)
- Email: [contact@shekharroy.com](mailto:contact@shekharroy.com)

## Portfolio Highlights

- Single-page, responsive portfolio with dark and light theme support.
- Resume-driven content sourced from `shekhar-roy.md`.
- Featured outcomes including a 300% year-over-year operating income boost, 50% downtime reduction, 70% system performance improvement, and 300K+ students reached by IGNOU Mate.
- Project sections for a spot and derivatives trading exchange, IGNOU Mate, Crypto Chain, COME, Quote Factory, and MMM.
- Credentials, education, recognition, volunteering, language, and contact sections.
- Static deployment model with no build step required.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Bootstrap Icons CDN
- Google Fonts
- FormSubmit for the contact form
- GitHub Pages-compatible static hosting

## Project Structure

```text
.
├── README.md
├── shekhar-roy.md
├── index.html
├── robots.txt
├── sitemap.xml
├── css/
│   └── styles.css
├── js/
│   └── main.js
└── assets/
    ├── icons/
    └── images/
```

## Run Locally

This is a static site. Open `index.html` in a browser, or serve the folder with any local static server.

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy To GitHub Pages

1. Push this folder to a GitHub repository.
2. Open the repository's **Settings**.
3. Go to **Pages**.
4. Select the main branch and root folder.
5. Save the settings and wait for GitHub Pages to publish the site.

For the custom domain, keep the production URL as `https://shekharroy.com/` so canonical links, Open Graph previews, and the sitemap point to the same preferred address.

## SEO Work Included

- Descriptive page title and meta description aligned with the visible portfolio content.
- HTTPS canonical URL for the homepage.
- Open Graph and Twitter Card metadata with an absolute preview image URL.
- Search-friendly `robots.txt`.
- XML sitemap for the canonical homepage.
- JSON-LD `ProfilePage` structured data for Shekhar Roy and selected project work.
- Updated internal portfolio links from HTTP to HTTPS.
- Removed a low-value Google search URL from the MMM project card.
- Added explicit portrait image dimensions to reduce layout shift.

## Content Updates

- Edit the visible site content in `index.html`.
- Use `shekhar-roy.md` as the resume/profile source of truth.
- Replace `assets/images/profile.jpg` to update the hero portrait and social preview image.
- Keep `sitemap.xml` and the structured data `dateModified` value current when making meaningful public content changes.

## Contact Form

The footer contact form submits through FormSubmit and sends messages to `contact@shekharroy.com`.
