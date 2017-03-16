## Synopsis

This tool aims to automatically extract events from unstructured datas in online newspaper texts.
The job is done in three steps:
1 - extract main content of articles (url source, title, content, publishing date, location) and store them
2 - classify them according to their subject
3 - populate the event base so that datas could be easily accessible to the interface

## Code Example

- Extraction of main content: mainly done in "collect_articles.py" file using Article and Url classes, including storage to the database too.
- Classification: use of MeanShift algorithm and storage of the result
- Generate the Event collection, which is most useful for the interface

## Motivation

AZOT is the fruit of mind connection of W3A's foundators, who want to do something innovating that consequently improving everyone's everyday life.

## Installation

#Not define yet

## API Reference

## Tests

## Contributors

## License