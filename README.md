[Repository](https://github.com/VelzCode/Week3.Bootstrap-JQuery)<br>
[Live Page](https://velzcode.github.io/Week3.Bootstrap-JQuery/)

# Bootstrap-JQuery — Athena Systems

A website created for week three of my coding bootcamp, exploring Bootstrap components and jQuery UI. The page combines a dark theme, red borders and glowing headings with a tabbed information panel, card blocks and a contact form layout.

## Disclaimer

Athena Systems is a fictional company created for this educational project. Its company history, client numbers, business claims and service descriptions are illustrative and do not represent a real business. Any real product or brand names included are used as example content and do not imply affiliation or endorsement.

## About the project

This project focuses on using Bootstrap to structure a page and custom CSS to give it a consistent design. It is one of my favourite designs from the earlier part of the course, before moving on to more substantial JavaScript work.

The main interactive feature is a jQuery UI tab selection panel. A small JavaScript file sets up the tabs and allows their headings to be reordered. The rest of the project centres on HTML, CSS and Bootstrap components.

## Features

- A Bootstrap navigation bar with a collapsible menu for smaller screens.
- A dark theme with custom red borders, rounded corners and glowing headings.
- A jQuery UI panel containing **About Us**, **History** and **Services** tabs.
- Tab headings that can be dragged horizontally to change their order.
- Four Bootstrap card blocks covering brands, infrastructure, game benchmarks and laptops.
- A Bootstrap grid that arranges the cards in four columns at medium screen sizes and above, and stacks them on smaller screens.
- A styled contact form with name, email, subject and message fields.
- A shared CSS colour variable for the red borders and text glow.

## Built with

- **HTML5** — Page structure, content and form controls.
- **CSS3** — Custom borders, spacing, colours and text effects.
- **Bootstrap 5.3.8** — Layout, navigation, cards, buttons and form styling.
- **jQuery 3.7.1** and **jQuery UI 1.14.2** — Tab selection and draggable tab ordering.

The project includes minimal custom JavaScript for the jQuery UI tabs. Bootstrap's bundled JavaScript supports the collapsible navigation menu. There is no backend or application logic for search, contact submissions or the placeholder navigation links.

## Interactive and visual-only elements

The **tabs and tab reordering are functional**, along with Bootstrap's collapsible navigation menu.

The following elements are visual demonstrations only:

- **Search bar** — Accepts text but does not perform a search.
- **Contact form** — Demonstrates form layout and styling. It has no submission support and does not send or store messages.
- **Navigation and contact links** — The brand, Home, Cards, Contact Form, Email and Phone links are placeholders with no destination or contact action.

## Getting started

Use the Live Page link at the top of this README to view the website.

To run it locally:

1. Clone the repository or download and extract the ZIP file.
2. Open `index.html` in your browser.
3. Select the information tabs or drag their headings to explore the jQuery UI functionality.

Keep `index.html`, `style.css` and `script.js` in the same folder. No installation or build step is required.

An internet connection is needed to load Bootstrap, jQuery and jQuery UI from their external content delivery networks.

## Project structure

```text
Week3.Bootstrap-JQuery/
├── index.html    # Page content and Bootstrap components
├── style.css     # Custom styling and theme details
├── script.js     # jQuery UI tabs and sortable tab headings
└── README.md     # Project documentation
```

## Learning focus

- Building layouts with Bootstrap containers, rows and columns.
- Combining navigation, cards, buttons and forms in one page.
- Customising Bootstrap and jQuery UI with CSS.
- Adding a small amount of library-based interaction through jQuery UI.
- Keeping page structure, custom styling and tab behaviour in separate files.

## Author

**Jason Dewhurst** — [VelzCode on GitHub](https://github.com/VelzCode)
