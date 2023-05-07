# 2019 Horiseon Services Solutions

## Refactor of the Horiseon web page to comply with accessibility standards and optimize for search engines.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Changes made

- title is more descriptive
- element tags are more semantic (header, nav, section, article, aside, footer)
- added alt text for images
- addressed header heirarchy
- id selectors are more specific
- correlated css code to match sections in html (header, main, footer, etc)
- trimmed down css code by combining elements into the same class
- added id to article element to link to nav bar
- added comments in HTML and CSS for clarity


## Screenshot

![HoriseonScreen](https://user-images.githubusercontent.com/16748389/85058961-de2a7780-b170-11ea-9607-506f1524d142.jpeg)

## Deployed page

Page published at: https://hinnenk2.github.io/horiseon-accessibility-code-refractor/#social-media-marketing