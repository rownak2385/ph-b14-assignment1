# DEVCONF 2026

DEVCONF 2026 is a beginner-friendly responsive landing page for a fictional developer conference, built step by step from a supplied Figma-style UI reference.

## Completed Sections

- Header and responsive navigation
- Full-width photographic hero section
- Meet the Speakers section
- Secure Your Spot pricing section
- Site footer with social links
- AI Challenge section placeholder only

## Technology Stack

- HTML5
- CSS3
- Local image and icon assets
- No JavaScript
- No external frameworks or libraries

## Folder Structure

```text
.
├── index.html
├── style.css
├── README.md
├── PROMPTS.md
└── assets/
    ├── images/
    └── icons/
```

## Image Asset Checklist

Place these files in `./assets/images/`:

- `hero-conference.jpg`
- `speaker-maya.jpg`
- `speaker-daniel.jpg`
- `speaker-sofia.jpg`
- `speaker-marcus.jpg`

## Local Usage

Open `index.html` in a web browser to view the page. Keep image and icon paths local and begin them with `./`.

## Responsive Breakpoints

The layout is designed and checked around these viewport widths:

- 1440px desktop
- 1200px desktop
- 1024px laptop
- 768px tablet
- 390px mobile
- 320px small mobile

The navigation wraps without JavaScript, the speaker grid changes from two columns to one column, and pricing cards move from three columns to smaller stacked layouts as the viewport narrows.

## Accessibility Features

- Semantic page regions for header, navigation, main content, sections, and footer
- One `h1` followed by logical `h2` and `h3` headings
- Skip link to the main content
- Visible `:focus-visible` keyboard styles
- Meaningful image alt text
- Accessible labels for icon-only social links
- Decorative SVGs hidden from assistive technology
- List markup for navigation, pricing features, and social links
- Reduced-motion support for hover movement

## GitHub Pages Deployment

1. Push the project to a GitHub repository.
2. Open the repository on GitHub.
3. Go to **Settings** > **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the root folder.
6. Save the settings and wait for GitHub Pages to publish the site.
7. Add the published URL to the links section below.

## Submission Checklist

- `index.html` is lowercase and located in the project root
- `style.css` is linked with `./style.css`
- All local image paths begin with `./`
- No JavaScript is used
- No CSS framework or external icon library is used
- No Lorem Ipsum text remains
- Speaker and pricing content is unique and accurate for a fictional event
- The page works at desktop, tablet, mobile, and small-mobile widths
- The AI Challenge prompt will be added later in Step 6

## Links

- GitHub repository URL: _Add link here_
- GitHub Pages URL: _Add link here_
