# Tech card

A simple HTML/CSS card component.

This project is part of the [Learn Responsive Web Design](https://scrimba.com/learn/responsive) course on [Scrimba](https://scrimba.com).

[Live version](https://tasxatzial.github.io/tech-tips-card/src/index.html)

## Implementation

* Responsive.
* Accessible + screen reader friendly.
* Mobile first approach.

While my implementation follows the course content loosely, it isn't an exact match of the design or the implementation shown in the course. I created the project from scratch and made some intentional changes with the aim of improving upon the provided design. Here's a non-exhaustive list:

* The button now has hover and focus states.
* The size of the button has been adjusted so that it has better proportions.
* The spacing of the elements has been adjusted.
* The letter spacing in the card title was too small and has been increased.
* The card now has a max width for both desktop and mobile views. This prevents the card from appearing overly long.
* The low contrast of the '15 minute read' text has been fixed.

## Dependencies

The project is written in HTML, CSS, JavaScript.

The following dependencies require an online connection:

* [:focus-visible](https://github.com/WICG/focus-visible) polyfill.

## Run locally

Download the 'src' folder and open 'index.html' in the browser.

## Screenshots

See [screenshots](screenshots/).

For comparison purposes, I've added extra screenshots that show the original Scrimba implementation. Note that the final built page on Scrimba is missing a `<meta name="viewport">` tag and was displaying incorrectly on mobile. This has been fixed for the purposes of taking screenshots.
