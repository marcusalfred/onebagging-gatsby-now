

# Lumen

Lumen is a minimal, lightweight and mobile-first starter for creating blogs using
[Gatsby](https://github.com/gatsbyjs/gatsby).

This is a fork of
[gatsby-starter-lumen](https://github.com/alxshelepenok/gatsby-starter-lumen)
updated for Gatsby v2 by the team at
[GatsbyCentral](https://www.gatsbycentral.com/).

## Features
+ Lost Grid ([peterramsing/lost](https://github.com/peterramsing/lost)).
+ Beautiful typography inspired by [matejlatin/Gutenberg](https://github.com/matejlatin/Gutenberg).
+ [Mobile-First](https://medium.com/@mrmrs_/mobile-first-css-48bc4cc3f60f) approach in development.
+ Stylesheet built using SASS and [BEM](http://getbem.com/naming/)-Style naming.
+ Syntax highlighting in code blocks.
+ Sidebar menu built using a configuration block.
+ Archive organized by tags and categories.
+ Automatic RSS generation.
+ Automatic Sitemap generation.
+ Offline support.
+ Google Analytics support.
+ Disqus Comments support.

## Folder Structure

```
└── src
    ├── assets
    │   ├── fonts
    │   │   └── fontello-771c82e0
    │   │       ├── css
    │   │       └── font
    │   └── scss
    │       ├── base
    │       ├── mixins
    │       └── pages
    ├── components
    │   ├── CategoryTemplateDetails
    │   ├── Disqus
    │   ├── Links
    │   ├── Menu
    │   ├── PageTemplateDetails
    │   ├── Post
    │   ├── PostTemplateDetails
    │   ├── Sidebar
    │   └── TagTemplateDetails
    ├── layouts
    ├── pages
    │   ├── articles
    │   │   ├── 2016-01-09---Perfecting-the-Art-of-Perfection
    │   │   ├── 2016-01-12---The-Origins-of-Social-Stationery-Lettering
    │   │   ├── 2016-02-02---A-Brief-History-of-Typography
    │   │   ├── 2017-18-08---The-Birth-of-Movable-Type
    │   │   └── 2017-19-08---Humane-Typography-in-the-Digital-Age
    │   └── pages
    │       ├── 2015-05-01---about
    │       └── 2015-05-01---contact
    └── templates
```

## Getting Started
Install this starter (assuming Gatsby is installed) by running from your CLI:
`gatsby new lumen https://github.com/GatsbyCentral/gatsby-v2-starter-lumen`

#### Running in Development
`gatsby develop`

#### Building
`gatsby build`
