# Title

Slides for the presentation I gave at [IAG][iag]/[USP][usp] on 2022 as invited speaker.

This template uses [reveal.js](https://revealjs.com/) for creating nice looking
slides by only editing a Markdown file, with some html syntax for adding some
cool stuff, like columns, fade-in animations, footnotes and more.

## Content

The template contains the following files and directories:

- `slides.md`: Markdown file with the content of the slides.
- `style.less`: define custom CSS classes using [less](http://lesscss.org/).
- `index.html`: HTML file that can be served to show the slides, also contains
  the configurations for reveal.js.

All the dependencies for build the slides are included in the repo so you can
serve them even without internet connection.
- The `reveal.js` directory contains the source files for running
  [reveal.js](https://revealjs.com).
- The `less` directory contains the sources for running
  [less](https://lesscss.org/).
- The `css/fontawesome` directory stores the
  [fontawesome](https://fontawesome.com/) icons.
- The `katex` directory has the sources for [KaTeX](https://katex.org/), a math
  typesetting library for the web.


## Serving the slides

Install [livereload](https://github.com/lepture/python-livereload):

```
pip install livereload
```

or

```
conda install livereload -c conda-forge
```

Use `make serve` to start a server at `http://localhost:8000`. The page will
automatically reload the page when you update any of the files in the
repository.


## License

The content of the slides (`slides.md`) and their custom configurations
(`index.html`, and `css/style.less`) are licensed under a Creative Commons
Attribution 4.0 International License.
