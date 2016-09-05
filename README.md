# Solarized HTML Stylesheet

[![Join the chat at https://gitter.im/thomasf/solarized-css](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/thomasf/solarized-css?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This project aim is to provide general [solarized](http://ethanschoonover.com/solarized) light and dark colorshcemes
for HTML documents that mostly relies on standard HTML elements.

For examples and some more info, visit the [Solarized-CSS GitHub page](https://liweitianux.github.io/solarized-css/)

## Specific Targets
* Org mode HTML exports
* Markdown
* Any HTML document that mostly relies on standard HTML elements

## Development
[Stylus](https://github.com/stylus/stylus) is the style language used for building the CSS files.

To be able to build you need to have [nodejs](http://nodejs.org/) installed.

To install dependencies, run this from the repository root:

    npm install

Then you should be able to rebuild using:

    grunt

where the ``grunt`` can be installed:

    npm install grunt-cli

## Acknowledgments
* Ethan Schoonover: [solarized](http://ethanschoonover.com/solarized) color scheme
* Sebastian Rose: [org-info.js](http://orgmode.org/worg/code/org-info-js/index.html), [Worg Git](http://orgmode.org/w/worg.git?p=worg.git;a=tree;f=code/org-info-js;hb=HEAD) (maybe newer?), [GitHub](https://github.com/SebastianRose/org-info-js) (may have some extensions?)

## License
MIT License
