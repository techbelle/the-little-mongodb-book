## About ##
The Little MongoDB Book is a free book introducing MongoDB.

The book was written shortly after the creation of the MongoDB interactive tutorial. As such, the two can be seen as complementary.

The book was written by [Karl Seguin](http://openmymind.net), with [Perry Neal](http://twitter.com/perryneal)'s assistance.

If you liked this book, maybe you'll also like [The Little Redis Book](http://openmymind.net/2012/1/23/The-Little-Redis-Book/).

The book was updated for MongoDB 6.0 by [Asya Kamsky](https://twitter.com/asya999)

## Translations ##

* [Russian](https://github.com/jsmarkus/the-little-mongodb-book/tree/master/ru)
* [Chinese](https://github.com/geminiyellow/the-little-mongodb-book/tree/master/zh-cn) updated for 2.6
* [Chinese](https://github.com/justinyhuang/the-little-mongodb-book-cn)
* [Italian](https://github.com/nicolaiarocci/the-little-mongodb-book/tree/master/it) updated for 2.6
* [Spanish](https://github.com/uokesita/the-little-mongodb-book/tree/master/es)
* [Brazilian Portuguese](https://github.com/danielmelogpi/the-little-mongodb-book/tree/master/pt_BR)
* [Japanese](https://github.com/Makopo/the-little-mongodb-book/wiki) updated for 2.6
* Japanese [Version 1](http://www.cuspy.org/diary/2012-04-17) - [Version 2](https://github.com/ma2/the-little-mongodb-book)
* [German](https://github.com/pythononwheels/the-little-mongodb-book/tree/master/de)
* [Burmese](https://github.com/nainglinaung/the-little-mongodb-book/tree/master/mm)

## License ##
The book is freely distributed under the [Attribution-NonCommercial 3.0 Unported license](<http://creativecommons.org/licenses/by-nc/3.0/legalcode>).

## Formats ##
The book is written in [Markdown](http://daringfireball.net/projects/markdown/) and converted to PDF using [Pandoc](http://johnmacfarlane.net/pandoc/).

The TeX template makes use of [Lena Herrmann's JavaScript highlighter](http://lenaherrmann.net/2010/05/20/javascript-syntax-highlighting-in-the-latex-listings-package).

Kindle and ePub format provided using [Pandoc](http://johnmacfarlane.net/pandoc/).

## Generating books ##
Packages listed below are for Ubuntu. If you use another OS or distribution names would be similar.

### PDF

#### Dependencies

Packages:

* `pandoc`
* `texlive-xetex`
* `texlive-latex-extra`
* `texlive-latex-recommended`

You should have Microsoft fonts installed too. But you could change fonts in `common/pdf-template.tex` file if you want.

#### Building

Run `make en/mongodb.pdf`.

### ePub

#### Dependencies

Packages:

* `pandoc`

#### Building

Run `make en/mongodb.epub`.

### Mobi

#### Dependencies

Packages:

* `pandoc`

You should have [KindleGen](http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000765211) installed too.

#### Building

Run `make en/mongodb.mobi`.

## Title Image ##
A PSD of the title image is included. The font used is [Comfortaa](http://www.dafont.com/comfortaa.font).
