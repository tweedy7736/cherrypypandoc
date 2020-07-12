
# cherrypypandoc
> A CherryPy wrapper for pypandoc

## Getting started

The script requires Python and the [CherryPy](https://cherrypy.org) framework, as well as:
* [Pandoc](http://pandoc.org)
* [pandoc-citeproc](https://github.com/jgm/pandoc-citeproc), [pandoc-crossref](https://github.com/lierdakil/pandoc-crossref), and a [LaTeX](https://www.tug.org/begin.html) installation with XeLaTex — if you want to use these options
* [pypandoc](https://github.com/bebraw/pypandoc) and [validators](https://github.com/kvesteri/validators) for python

## Configuring and running

Edit the configuration section of `convert.py` to reflect the host and socket of your installation. You may also want to edit the default values for `bib_path` and `csl_path`.

Then run:

```shell
python convert.py
```

You can then access the converter via http. Instructions for using the converter are included there.

## Screenshot

![cherrypypandoc in action](https://raw.githubusercontent.com/tweedyflanigan/cherrypypandoc/master/Screenshot.png)
