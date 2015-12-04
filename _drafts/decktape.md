---
layout: post
title: Using DeckTape to create PDF versions of reveal.js presentations
---

* [DeckTape](https://github.com/astefanutti/decktape)
* [reveal.js (Github)](https://github.com/hakimel/reveal.js/)
* [reveal.js demo](http://lab.hakim.se/reveal-js/#/)

<q cite="https://github.com/astefanutti/decktape">DeckTape is a high-quality PDF exporter for HTML5 presentation frameworks.</q>

Use [DeckTape](https://github.com/astefanutti/decktape) to convert a [reveal.js](https://github.com/hakimel/reveal.js/) presentation into PDF.

Installation instructions for [DeckTape](https://github.com/astefanutti/decktape) can be found at:

https://github.com/astefanutti/decktape#install

## Running [DeckTape](https://github.com/astefanutti/decktape) under Windows 7:

1. Change directory into the [DeckTape](https://github.com/astefanutti/decktape) directory on your machine, e.g.: `cd \Programs\decktape`
2. Run [DeckTape](https://github.com/astefanutti/decktape) against the presentation file.  The presentation file is located using a URL, so `http://my.sample.presentation.examp.com/` or, if local, `file:///C:/Path/to/my/Presentation.html`.
3. Don't use a drive designator to specify the output; use a path relative to the [DeckTape](https://github.com/astefanutti/decktape) directory

Final example command line for a local file:

`C:\Programs\decktape\phantomjs decktape.js automatic file:///C:/Path/to/my/Presentation.html ../../Users/myname/Documents/Test.pdf`
