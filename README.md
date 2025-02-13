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

## Running
To run this code, simply clone the repository in vscode and, after clicking on the index.html file, start the vscode livepreview server. 

## Accessibility Lab Answers
Color: Black and green are 2 non very well contrasting colors which make it fail the contrast test with a 2.08:1 ratio. The rest of the test is pretty decent with it being a 10+ (or 21 for the black and white ratios).

Semantic html: Nothing really happens when i try to use the keyboard to navigate. I can use tab to skip around the page, but the search functionality doesnt really work. I decided to update the navigation eaders from a standard div elemnt to then include a <nav> element as it is a navigation bar, which would mean that <nav> is the element that makes the most sense.

Audio: TO allow access to audio, all you would need to do is to throw a download prompt for the user to just download the audio instead of using the html player. 



Other consideratiosn: I would persoanlly include a player at the very top that would prompt the user if they are using any accessibility feautres, and if they do not repsond within 10 seconds, then it would start reading off the site elements automatially. I would also include a generci sumary of the site in the auto playing site readout.