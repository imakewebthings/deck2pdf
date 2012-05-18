## Overview

deck2pdf converts deck.js presentations to PDF using PhantomJS.

## Usage

First, make sure you have PhantomJS installed:

```
brew install phantomjs
```

Second, add `deck2png.js` and `png2pdf.js` to your deck directory.

Third, run this:

```
phantomjs deck2png.js [yourdeckfile.html] && phantomjs png2pdf.js
```

You'll be left with a file named `output.pdf`. If you're lucky, it looks something like your deck.

## Development

The code in this repository is a spike, the result of a few hours of frustrated hacking.  A lot of the code is inspired by an old version of the wonderful [Slippy's](https://github.com/Seldaek/slippy) PDF generator.  Anyone looking to contribute might be able to glean more by looking at the history of that project.

I'm currently accepting just about any pull request. There is no documentation. There are no tests. There are no code comments. I don't even know why half of the code I've written is necessary or why it works. (Like why do I have to set the PDF page size to what it is, while the image sizes are completely different?)

Everything here is MIT license. Use, fork, and sell as you wish and at your own peril.