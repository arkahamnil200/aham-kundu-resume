# Aham Kundu: Personal Resume Website

A single-page personal resume and portfolio website built with HTML5 and CSS3 for the Website Development midterm project, BBA (Digital Business and Entrepreneurship), IIM Bangalore.

## What the site contains

| Section | Content |
| --- | --- |
| Hero | Name, professional tagline and a profile summary panel |
| About | A short personal introduction |
| Education | A timeline of IIM Bangalore, Class XII and Class X |
| Achievements | Results from two national case competitions |
| Research and interests | Areas of interest and independent research work |
| Skills | Skills grouped into four categories |
| Leadership and sport | School leadership roles and sporting record |
| Qualifications in progress | CFA, FRM and CA Foundation candidacies |
| Contact | Public email addresses |

## Technologies used

- **HTML5** with semantic elements: `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`
- **CSS3** in one external stylesheet
  - Custom properties (variables) for colours, fonts and spacing
  - Element, class and ID selectors
  - Flexbox for the navigation bar, buttons, skill tags and footer
  - CSS Grid for the hero, section layout, cards and timeline
  - Pseudo-classes (`:hover`, `:focus-visible`, `:first-child`, `:last-child`, `:nth-child`, `:target`) and pseudo-elements (`::before`, `::after`)
  - Gradients, borders, box shadows and transitions
  - Media queries for tablets and phones, plus a reduced-motion rule
- **Google Fonts**: Cormorant Garamond (headings) and IBM Plex Sans (body text)
- No JavaScript, frameworks or build tools

## Folder structure

```
resume-website/
├── index.html        Page content and structure
├── style.css         All styling and responsive rules
├── README.md         This file
└── assets/
    ├── monogram.svg  "AK" monogram shown in the profile panel
    └── favicon.svg   Browser tab icon
```

## Viewing the site locally

1. Download or clone this repository.
2. Keep all files in the same folder, with `assets` beside `index.html`.
3. Double-click `index.html` to open it in a web browser.

No installation or server is needed. An internet connection is only needed to load the two Google Fonts; without it the site falls back to system fonts.

## Hosting

The site is static, so it can be hosted on Netlify directly from this repository.

1. In Netlify, choose **Add new project** and then **Import an existing project**.
2. Connect GitHub and select this repository.
3. Leave the build command empty and the publish directory as the repository root.
4. Deploy. Every later commit to the repository redeploys the site automatically.

`index.html` must sit at the top level of the repository, not inside a subfolder.

## Making common updates

**Replace the monogram with a photograph**

1. Add a square photo to the `assets` folder, for example `assets/photo.jpg`.
2. In `index.html`, find `src="assets/monogram.svg"` and change it to `src="assets/photo.jpg"`.
3. Change the `alt` text on the same line to `Portrait of Aham Kundu`.

**Add a LinkedIn link**

In the Contact section of `index.html`, copy one of the `contact-link` blocks, change its `href` to the LinkedIn profile address, and update its two labels.

## Author

Aham Kundu
