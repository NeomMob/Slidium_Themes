# Slidium_Themes


This is the home of Slidium open sourced themes.
[Slidium](http://www.neomobili.com/products/slidium-markdown-presentation/) is a markdown presentation editor for Mac.
Themes are Html based and use regular web technologies (HTML, CSS, SVG, ...)

## Why open sourcing themes?

Even if [Slidium](http://www.neomobili.com/products/slidium-markdown-presentation/) is a commercial application, we believe that open sourcing themes will allow everybody to:
- Improve existing themes
- Adapt or create your own theme

In addition, most of the themes are based on open source products and even if their licenses allow to keep modifications private, it make sense to stay with open source.

## Themes
- Reveal, based of Reveal.js
- Gertrude based on the [Slidecarnival theme](http://www.slidescarnival.com/gertrude-free-presentation-template/1763) with the same name
- Fidele based on the [Slidecarnival theme](http://www.slidescarnival.com/fidele-free-presentation-template/971) with the same name
- Modern based on [webslides](https://webslides.tv/)

## Theme structure

Each theme is a set of files grouped in one directory having the name of the theme. There is not yet support of compressed theme if bundle but this is on our todolist.
Each theme must contain the following files:
- theme.json : this file contains all the meta data of the theme. It also hold the different layout definitions
- theme.png : The thumbnail of the theme 
- Theme.css ; Style sheet of the theme. It is strongly advised  to merge all your css file into a single one

Theme can also contain a subdirectory containing all the assets (image, ...) used by the theme.

## Contributing to Slidium themes
You can fork and create pull request if you made enhancement or create new themes.

## License
Depending of the theme: MIT License or Creative Commons.





