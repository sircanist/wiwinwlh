<p align="center">
  <a href="http://dev.stephendiehl.com/hask/">
    <img src="http://dev.stephendiehl.com/hask/img/title.png"/>
  </a>
</p>

[![MIT License](http://img.shields.io/badge/license-mit-blue.svg)](https://github.com/sdiehl/wiwinwlh/blob/master/LICENSE)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/sdiehl/wiwinwlh?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://travis-ci.org/sdiehl/wiwinwlh.svg?branch=master)](https://travis-ci.org/sdiehl/wiwinwlh)

Read Online:

* [**HTML**](http://dev.stephendiehl.com/hask/)
* [**PDF**](http://dev.stephendiehl.com/hask/tutorial.pdf)
* [**Example Code**](https://github.com/sdiehl/wiwinwlh/tree/master/src)

Chapter Code Examples:

* [01-basics/            ](https://github.com/sdiehl/wiwinwlh/tree/master/src/01-basics/)
* [02-monads/            ](https://github.com/sdiehl/wiwinwlh/tree/master/src/02-monads/)
* [03-monad-transformers/](https://github.com/sdiehl/wiwinwlh/tree/master/src/03-monad-transformers/)
* [04-extensions/        ](https://github.com/sdiehl/wiwinwlh/tree/master/src/04-extensions/)
* [05-laziness/          ](https://github.com/sdiehl/wiwinwlh/tree/master/src/05-laziness/)
* [06-prelude/           ](https://github.com/sdiehl/wiwinwlh/tree/master/src/06-prelude/)
* [07-text-bytestring/   ](https://github.com/sdiehl/wiwinwlh/tree/master/src/07-text-bytestring/)
* [08-applicatives/      ](https://github.com/sdiehl/wiwinwlh/tree/master/src/08-applicatives/)
* [09-errors/            ](https://github.com/sdiehl/wiwinwlh/tree/master/src/09-errors/)
* [10-advanced-monads/   ](https://github.com/sdiehl/wiwinwlh/tree/master/src/10-advanced-monads/)
* [11-quantification/    ](https://github.com/sdiehl/wiwinwlh/tree/master/src/11-quantification/)
* [12-gadts/             ](https://github.com/sdiehl/wiwinwlh/tree/master/src/12-gadts/)
* [13-lambda-calculus/   ](https://github.com/sdiehl/wiwinwlh/tree/master/src/13-lambda-calculus/)
* [14-interpreters/      ](https://github.com/sdiehl/wiwinwlh/tree/master/src/14-interpreters/)
* [15-testing/           ](https://github.com/sdiehl/wiwinwlh/tree/master/src/15-testing/)
* [16-type-families/     ](https://github.com/sdiehl/wiwinwlh/tree/master/src/16-type-families/)
* [17-promotion/         ](https://github.com/sdiehl/wiwinwlh/tree/master/src/17-promotion/)
* [18-generics/          ](https://github.com/sdiehl/wiwinwlh/tree/master/src/18-generics/)
* [19-numbers/           ](https://github.com/sdiehl/wiwinwlh/tree/master/src/19-numbers/)
* [20-data-structures/   ](https://github.com/sdiehl/wiwinwlh/tree/master/src/20-data-structures/)
* [21-ffi/               ](https://github.com/sdiehl/wiwinwlh/tree/master/src/21-ffi/)
* [22-concurrency/       ](https://github.com/sdiehl/wiwinwlh/tree/master/src/22-concurrency/)
* [23-graphics/          ](https://github.com/sdiehl/wiwinwlh/tree/master/src/23-graphics/)
* [24-parsing/           ](https://github.com/sdiehl/wiwinwlh/tree/master/src/24-parsing/)
* [25-streaming/         ](https://github.com/sdiehl/wiwinwlh/tree/master/src/25-streaming/)
* [26-data-formats/      ](https://github.com/sdiehl/wiwinwlh/tree/master/src/26-data-formats/)
* [27-web/               ](https://github.com/sdiehl/wiwinwlh/tree/master/src/27-web/)
* [28-databases/         ](https://github.com/sdiehl/wiwinwlh/tree/master/src/28-databases/)
* [29-ghc/               ](https://github.com/sdiehl/wiwinwlh/tree/master/src/29-ghc/)
* [30-languages/         ](https://github.com/sdiehl/wiwinwlh/tree/master/src/30-languages/)
* [31-template-haskell/  ](https://github.com/sdiehl/wiwinwlh/tree/master/src/31-template-haskell/)
* [33-categories/        ](https://github.com/sdiehl/wiwinwlh/tree/master/src/33-categories/)

Contributing
------------

If you want to submit a fix for a typo or fix for code then just submit a pull
request, and I'm happy to recompile the resulting document.

If for some reason you want to compile the HTML page yourself, then you'll need
to compile the preprocessor against Pandoc and then run make to build the page.

```bash
$ make
$ firefox tutorial.html
```

Alternatively a PDF or EPUB file can be generated by one of the following
commands:

```bash
$ make tutorial.pdf
$ make tutorial.epub
```

Stack
-----

Alternatively using the stack build system:

```bash
$ stack ghc includes.hs -- -o includes 
$ stack exec make
$ firefox tutorial.html
```

License
-------

Stephen Diehl (2013-2016)

No rights reserved. The person who associated a work with this deed has dedicated the work to the public
domain by waiving all of his or her rights to the work worldwide under copyright law, including all related
and neighboring rights, to the extent allowed by law.

You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking
permission.
