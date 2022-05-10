# My title

by [Santiago Soler](https://www.santisoler.com)

**Slides:** https://www.santisoler.com/iag-usp-2022

**Recording:** Coming soon...

Presentation for the [IAG](https://www.iag.usp.br/)/[USP](https://www5.usp.br/)
on 2022-05-19 as an invited speaker.


## Serving the slides

These slides were built using [reveal.js](https://revealjs.com/).
Sadly, we cannot open the index.html file in a browser to see them, we need to
run a local web server instead.

Install [livereload](https://github.com/lepture/python-livereload):

```
pip install livereload
```

or

```
conda install livereload -c conda-forge
```

Then start a local webserver by running:

```
python serve.py
```

Open `http://localhost:8000` in your browser to see the slides. The page will
automatically reload the page when you update any of the files in the
repository.

## Acknowledgements

These slides are built upon the
[`talk-template`](https://github.com/santisoler/talk-template), which is
inspired on [Leonardo Uieda](https://www.leouieda.com)'s
[`talk-template`](https://github.com/leouieda/talk-template).

## License

The content of the slides (`slides.md`, `images/`) and the slides
configurations (`serve.py`, `index.html`, and `css/style.less`) are licensed
under a Creative Commons Attribution 4.0 International License.
