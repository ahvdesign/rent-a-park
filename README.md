[Live Page](https://ahvdesign.github.io/rent-a-park/index.html)

# Rent-A-Park

## Traditional CSS Showcase - No Flexbox, No Grid, No JavaScript

### What am I looking at here?

This is a project made to show advanced, pure HTML/CSS and what can be achieved without a single line of JavaScript (which is supposed to handle web page behavior, not the look and feel). Hopefully by checking the live example and looking through the code I can show what CSS is capable of alone, and display a high level of understanding when it comes to the visual structure of a website.

### Tech used

- Node.js to manage the CSS precompiler
- VS Code for the editor with live server extension (auto reloads page on code changes)
- That's it! It's a static page, nothing special. No need to get crazy and overcomplicate it

### Principles behind the page

_Responsive design_

- Fluid layouts
- Media queries
- Responsive images
- Desktop-first vs mobile-first

_Maintainable and scalable code_

- Reusable
- Properly structured HTML
- Consistent class names
- Organized files
- Easily imported into new projects

_Web performance_

- Less HTTP requests
- Less code overall (exploiting CSS inheritance)
- Compressed code
- Using a CSS preprocessor
- Lower image count
- Compressed images

### Notable things

- Using rem instead of px for almost all measurements (left px for things 4px and smaller because it barely makes a difference). Using rem because if a user has a low resolution or scales their page using browser zoom controls the page will retain it's intended composition
- HTML: Using the BEM (Block Element Modifier) notation for class names (.block\_\_element--modifier)
- CSS: Using the 7-1 pattern for folder structure
- A bit of extra flashiness for the showcase while keeping a friendly user experience based on current trends
- Project-wide font definitions, colors, and more (for tweaking in one file instead of changing all elements that use specific properties)
- Semantic HTML
- Usage of browser calculated viewport size in header to ensure all people visiting the site see the same thing no matter which device it is on
- Normal \* universal selector used for the style reset because browsers (not IE) are getting better about their initial rendering. There is no need for things like normalize.css or anything like that anymore
- The some properties are set on the specific elements instead of the universal selector or element itself to take advantage of property inheritance intelligently
