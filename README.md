# web-dev-starter

This is a starter project for web development with no frameworks and minimal
dependencies. It is intended to be a starting point for web development projects
that are written in plain HTML, CSS, and JavaScript.

## Getting Started

To get started, clone this repository and run the following commands:

```bash
npm install
```
This will install the necessary dependencies for the project.

## Development

It is recommended to use the VSCode Live Server extension to run the project
locally. This will allow you to see changes in real-time as you make them. There
is no need to run a build process or refresh the page manually. Additionally,
you do not need to setup a local server to run the project.

## Testing

To run the tests for the project, run the following command:

```bash
npm test
```

## Accessibility Lab Answers

Color
1.) The green background is #008000 and the text is #2a2a2a, which has a color contrast ratio of 2.79:1, which failed
the WebAIM contrast checker test. I decided to keep the green idea from the original, but change the background to #e8f5e9 for the main content, and #004d40 for the nav. I also changed the nav text to white.

Semantic HTML
1.) The original text was not accessible for screen readers, but navigating around with the tab key seemed to work fine.
2.) I changed the <font> tags to various heading and <p> tags.
3.) I changed the <div> that the navigation bar was in to <nav>.

The Images
1.) I added some alt text to the bear images to explain what they show.

The Audio Player
1.) I added a <figcaption> tag for hearing impaired people to be able to read.
2.) I added options to download the bear audio files for browsers that can't use HTML audio.

The Forms
1.) I added the label with the sr-only label so that only the screen reader users would encounter it
2.) I changed the formatting of the labels so they were less ambiguous.

The Show/Hide Comment Control
1.) I changed the Show Comments button to an actual button, instead of a <div>

The Table
1.) I added a caption and scopes to the columns and rows to make it clear which items belong where.

Others
1.) I added some explicit roles to the site so that screen readers will be able to jump around to various areas more easily.
2.) I added a couple more labels to the comments section to make it more clear to screen reader users that both fields are required.

## Running
Use Codespace Live Preview, and navigate to accessibility-lab-files/ then to assessment-files/ which opens the site.

