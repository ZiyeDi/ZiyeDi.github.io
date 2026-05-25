# ZiyeDi.github.io

Academic CV website for **Ziye Di**, published with GitHub Pages at:

<https://ziyedi.github.io/>

The site is a lightweight static resume/CV page inspired by the visual structure of
[`academicpages/academicpages.github.io`](https://github.com/academicpages/academicpages.github.io):
a top masthead, an author sidebar, a publication-focused content column, project entries,
conference activity, awards, skills, and a downloadable CV.

## Repository Structure

```text
.
├── index.html
├── README.md
├── style.css
├── ziye-di-cv.pdf
└── profile.svg
```

## Technical Details

- **Hosting:** GitHub Pages serves the repository from the `main` branch.
- **Frontend:** The website is plain HTML and CSS, with no build step, package manager, or JavaScript runtime.
- **Page entry:** `index.html` is the only route required by GitHub Pages and loads directly at the domain root.
- **Styling:** `style.css` contains the responsive layout, academic typography, author sidebar,
  masthead navigation, publication list formatting, print styles, and mobile breakpoints.
- **CV download:** `ziye-di-cv.pdf` is linked from the "Download CV PDF" button on the page.
- **Portrait:** `profile.svg` wraps the portrait asset in a text-based SVG container so it can be
  versioned and rendered reliably by GitHub Pages.
- **Design direction:** The layout follows an academic profile pattern: restrained color palette, serif body
  typography, compact navigation, a left author block, and content sections optimized for publications and CV review.

## Content Sections

The page currently includes:

- Education background
- Core courses
- Project experience
- Academic publications
- Conference and academic exchanges
- Professional skills
- Honors and awards
- Leadership and extracurricular activities

## Maintenance Notes

To update the website, edit the relevant static files directly:

- Update resume content in `index.html`.
- Update visual styling in `style.css`.
- Replace the downloadable CV at `ziye-di-cv.pdf`.
- Replace the portrait asset at `profile.svg`.

Because the site is static, GitHub Pages will redeploy automatically after each commit to `main`.
