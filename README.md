# Oblox | OPML Blogging with XSL

## History

- [oblox.bsd.am](https://oblox.bsd.am)
- [Blogging on static generated sites with OPML and XSLT in 2022](https://weblog.antranigv.am/posts/2022/04/opml-xslt-2022/)

## Usage

1. First, copy the XSL template file  
   For a website  
   `cp opml.xsl.site opml.xsl`  
   For a blog  
   `cp opml.xsl.blog opml.xsl`  
2. Open an Outliner (e.g. Drummer / Electric Drummer) and create an outline file named `index.opml`
3. Run `make`

## Attributes

- `head/title` for the website title.
- `head/logo` for the website logo.
- `head/license` for the license (e.g. `CC BY 4.0`)
- `head/copyleft` for the copy~~right~~left (e.g. ` All Rights Reverse Engineered`)

## Roadmap

- Need to generate an RSS feed for `opml.xsl.blog`
- Need to merge the codebases together, or figure out how XSL **really** works
- A simple command line (actually, Makefile targets) to archive old blog posts and make pages

