# Pure

![hugo version](https://img.shields.io/badge/Hugo-0.91-09f)
![license](https://img.shields.io/github/license/chrishannah/pure)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat)](https://github.com/prettier/prettier)


A minimal theme for Micro.blog.

This theme was built around a few key ideas:

- HTML should be as semantic and clear as possible.
- The page should be readable without CSS or JavaScript.
- Style should be simplistic.

There is also the desire for this theme to be a good base for other themes. Because of the semantic HTML, it should be relatively easy to modify the CSS to make the theme more personalised.

## Screenshots

![Chris Hannah's site in light mode.](images/light-mode.png "Theme in light mode")

![Chris Hannah's site in dark mode.](images/dark-mode.png "Theme in dark mode")

For a full preview you can check out my [microblog](https://micro.chrishannah.me).

## Code Style
This project makes use of the [Prettier](https://prettier.io) code formatter. This formatting will be done automatically in a GitHub Action, but most IDEs can be configured to run this locally.

There is also a second automated step which also runs as part of a GitHub Action, and that is [Super-Linter](https://github.com/github/super-linter). This runs the code through a whole host of linters, and will report any errors. Some configurations have been changed for this project, which can be found under `.github/linters`. The main change is that this project uses tabs instead of spaces. 