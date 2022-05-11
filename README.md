# Empowering science with open-source software

by [Santiago Soler](https://www.santisoler.com)

**Slides:** https://www.santisoler.com/iag-usp-2022

**Recording:** Coming soon...


## About

This was an invited talk to the [Instituto de Astronomia, Geofísica e Ciências
Atmosféricas (IAG)][iag] of the [Universdade de São Paulo][usp]. Special thanks
to Gabriel Dragone for the invitation.


## Abstract

In this talk I take the opportunity to unravel my career path, to take
a retrospective look on how I got into geoscience and scientific software
development, and what motivated me through this road.
As being involved in the Fatiando a Terra project, I showcase some of the tools
we develop in it, showing how they support my scientific research, how it
feedbacks from it, and highlight the importance of its community.
Finally, I will peak into what the future of science empowered with open-source
software could look like and how we can start making the change today.


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


[iag]: https://www.iag.usp.br/
[usp] : https://www5.usp.br/
