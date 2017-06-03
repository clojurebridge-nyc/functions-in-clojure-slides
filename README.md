# Intro to Functions in Clojure

A slide deck for a little session introducing Clojure functions to beginning
programmers, written for ClojureBridge NYC 2017.

View these slides online: https://workframers.github.io/functions-in-clojure-slides/

Slides created via [AsciiDoc](http://www.methods.co.nz/asciidoc/index.html).
All images from wikimedia commons.

To build locally:

    brew install asciidoc               # Or apt-get or whatnot
    pip install pygments
    asciidoc index.adoc && open index.html

To publish to github:

    asciidoc index.adoc
    git checkin -m "Updating compiled slides" index.html
    git push origin master
