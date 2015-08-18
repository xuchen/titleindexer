# UPDATE #

**This project has been merged with [OxygenGuide](http://code.google.com/p/oxygenguide/) v0.4! Please use v0.4 directly!**

## Index for offline world travel guide ##

This is a project created specifically for [OxygenGuide](http://code.google.com/p/oxygenguide/), the offline and text-only version of [WikiTravel](http://www.wikitravel.org). The aim is to provide indices for all (over 20,000) destinations of [OxygenGuide](http://code.google.com/p/oxygenguide/) so embedded devices have easier access to these destinations through indices.

The Python script can also be used with general purpose: it recursively reads all HTML pages in a certain directory, classifies all files by the initials of their titles, and output an index HTML page for all pages traveled.

Hopefully this project will be merged with [OxygenGuide](http://code.google.com/p/oxygenguide/) in the future.

## How to Use it ##

  1. Download [OxygenGuide](http://code.google.com/p/oxygenguide/) and unzip it to your computer. You should now have a directory named "oxygenguide\_0.3"
  1. Go to [Downloads](http://code.google.com/p/titleindexer/downloads/list) section and grab the index files.
  1. Unzip the index files and put all `*`.html files inside the "index" directory (NOT 'index' itself, otherwise your relative paths will be broken) into "oxygenguide\_0.3".
  1. Transfer "oxygenguide\_0.3" to your portable device (200~300 MB of disk space is needed).
  1. Access destination names by "all.html" (longer loading time) or "A-Z.html" (much smaller file size) from your browser or file system.

## How to Use it Effectively ##

The generated index page "all.html" is about 1.2MB, on some devices it takes a considerable time to load or even fails to load. Thus the index pages by initials, such as A.html, B.html, ... (most of which is smaller than 100KB), can be used as alternatives. Feel free to use any of these 2 kinds of indices on your portable device.

The content of all index pages is kept as simple as possible: as different devices have various screen sizes, it tries to fit in the smallest screen size horizontally.