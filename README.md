
# cherrypypandoc
> CherryPy wrapper for pypandoc

## Getting started

The script requires Python and CherryPy, as well as:
* Pandoc, Pandoc-Citeproc, Pandoc-Crossref, and a TeX installation with XeLaTex
* The pypandoc and validators python libraries

Edit the configuration section to reflect the host and socket of your installation. You may also want to edit the default values for `bib_path` and `csl_path`.

Then run:

```shell
python convert.py
```

You can then access the converter via http. Instructions for using the converter are included there.

### Screenshot

![cherrypypandoc in action](https://raw.githubusercontent.com/tweedyflanigan/cherrypypandoc/master/Screenshot.png)
