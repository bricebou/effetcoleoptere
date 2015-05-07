effetcoleoptere
===============

`effetcoleoptere` is the theme of the [L'effet coléoptère website](http://leffetcoleoptere.bz).

[leffetcoleoptere.bz](http://leffetcoleoptere.bz) uses [PhileCMS](http://philecms.com/) with some additional plugins:

- [phileTags](https://github.com/pschmitt/phileTags) by Philipp Schmitt;
- the [PhileCMS phileRSSFeed plugin](https://github.com/PhileCMS/phileRSSFeed);
- a modified version of the [PhileCMS phileTwigFilters plugin](https://github.com/PhileCMS/phileTwigFilters) with a filter that returns dates in French. Available on [my Github](https://github.com/bricebou/phileTwigFilters);
- a small plugin I've written that parse a CSV file into a HTML table (using the [parseCSV PHP class](https://github.com/parsecsv/parsecsv-for-php)) to display the radio shows' playlists: [ecParseCSV](https://github.com/bricebou/ecParseCSV).

Is uses [jPlayer : HTML5 Audio & Video for jQuery](http://jplayer.org/) to read the audio files.

## Installation

```
git clone --recursive https://github.com/bricebou/effetcoleoptere.git
```
