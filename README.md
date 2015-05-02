Highlight
=========

Keywords: tldr, tl;dr, article, summarizer, summarization, summary, highlight, highlighting, highlighter

*Highlight* is a Google Chrome extension that automatically highlights
the important content on article sites.

It is available from the Google Chrome Web Store:
https://chrome.google.com/webstore/detail/highlight/dnkdpcbijfnmekbkchfjapfneigjomhh

To use *Highlight*, install the extension, and click the highlighter
icon in the location bar. Clicking multiple times changes the
highlighting coverage.

Screenshot
----------

The following shows the highlighting on an article after clicking the
*Highlight* icon once.

![Screenshot](screenshots/1.png?raw=true)

License
-------

See [LICENSE](LICENSE).
This license does not apply to the libraries. For the library licenses, see the corresponding license files
in [src/lib](src/lib).

Acknowledgments
---------------

*Highlight* contains code from:

1. [readabilitySAX](https://github.com/fb55/readabilitySAX)
  * Modifications (see [other/readabilitySAX.js.diff](other/readabilitySAX.js.diff))
    1. Add getNodes() for returning nodes
    2. Incorporate readabilitySAX/browsers/DOMasSAX.js
2. [Porter-Stemmer](https://github.com/kristopolous/Porter-Stemmer)
