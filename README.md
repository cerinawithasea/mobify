mobify [![Build Status](https://api.travis-ci.org/macbre/mobify.png?branch=master)](http://travis-ci.org/macbre/mobify)
------

Download a webpage as an e-book

## Install

[![PyPI version](https://img.shields.io/pypi/pyversions/mobify.svg)](https://pypi.python.org/pypi/mobify)

```
pip install mobify
```

You may need to run `sudo apt-get install zlib1g-dev` if `lxml` install fails.

### For Kindle users

You need to install `calibre` package to be able to convert epub to mobi (using `ebook-convert`)

```
apt-get install calibre
```

## Usage

```
mobify "http://histmag.org/william-wallace-bohater-szkotow-bohater-popkultury-11698"
```

Or you can render a multi-chapter ebook from several URLs (simply separate them with spaces):

```
mobify "http://histmag.org/william-wallace-bohater-szkotow-bohater-popkultury-11698" "http://histmag.org/Historia-Szkocji-10-dat-ktore-powinienes-znac-10028"
```

epub and mobi files will be saved in your working directory

## Supported sources

* Blogspot
* histmag.org
* Tumblr
* Wikipedia
