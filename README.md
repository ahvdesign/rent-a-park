[Live Page](https://ahvdesign.github.io/rent-a-park/index.html)

# Rent-A-Park

## Traditional CSS Showcase - No Flexbox, No Grid, No JavaScript

### What am I looking at here?

This is a project made to show advanced, pure HTML/CSS and what can be achieved without a single line of JavaScript (which is supposed to handle web page behavior, not the look and feel). Hopefully by checking the live example and looking through the code I can show what CSS is capable of alone, and display a high level of understanding when it comes to the visual structure of a website.

### Tech used

- Node.js for a local development environment which auto compiles SASS code to normal CSS
- That's it! It's a static page, nothing special. No need to get crazy and overcomplicate it

### Notable achievements

- A bit of extra flashiness for the showcase while keeping a friendly user experience based on current trends
- Basic reset done with the universal selector
- Project-wide font definitions, colors, and more (for tweaking in one file instead of changing all elements that use specific properties)
- The latest (yet still widely compatible) CSS tools
- Semantic HTML
- Usage of browser calculated viewport size in header to ensure all people visiting the site see the same thing no matter which device it is on

### Reasoning behind some code choices

- Normal \* universal selector used because browsers (not IE) are getting better about their initial rendering. There is no need for things like normalize.css or anything like that anymore
- The some properties are set on the <body> instead of the universal selector to take advantage of property inheritance
-
