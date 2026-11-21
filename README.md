# Kyebando Clean

Kyebando Clean is a lightweight, mobile-friendly information website for waste collection in Kyebando Parish, Kawempe Division, Kampala. It brings together local collection guidance, collection-point references, collector information, waste-sorting tips, community activities, and ways to report sanitation issues.

## Website pages

- **Home** (`index.html`) — project overview and shortcuts to key information.
- **Schedule & points** (`schedule-points.html`) — collection guidance, zone schedules, and the CP-01–CP-05 collection-point reference.
- **Collectors** (`collectors.html`) — local collector directory and listing form.
- **Sort & get involved** (`community.html`) — sorting and composting guidance, cleanup information, volunteer signup, and educational videos.
- **Report a problem** (`report.html`) — guidance and a form for reporting sanitation issues.
- **About & contact** (`about.html`) — project background, contact information, sources, and media notes.
- **Submission confirmation** (`thanks.html`) — confirmation page used by forms.

## Preview locally

No build step or package installation is required. Open `index.html` in a modern web browser, or serve the project folder with a local static web server. The pages use relative links to the `css/` and `assets/` directories.

Google Fonts are loaded from the internet; the site remains viewable offline, but those fonts may not load. Images and videos are stored in `assets/`.

## Project files

```text
.
├── index.html
├── schedule-points.html
├── collectors.html
├── community.html
├── report.html
├── about.html
├── thanks.html
├── css/
│   └── style.css
└── assets/
    ├── images and favicon
    └── educational videos
```

## Deployment and forms

The site is static HTML and CSS and can be deployed to a static hosting provider. Some forms are configured for Netlify Forms; those submissions require a Netlify deployment with form processing enabled. The report form also supports preparing a message in the visitor's email app when used as a local static page. Configure and test the deployed forms and notification routing before relying on them. A confirmation page does not mean that KCCA, an LC1 leader, or a collector has received or acted on a report.

## Content and media notes

Schedules, fees, contacts, and service details should be checked with the relevant local authorities and service providers before publication or use. Photos and videos are illustrative and may not depict Kyebando; confirm permission or licensing for all media before public release. The collection-point graphic is a reference diagram, not an interactive map.
