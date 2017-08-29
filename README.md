# StandardsExtractingContentHandler
StandardsExtractingContentHandler is a Java [ContentHandler](http://www.saxproject.org/apidoc/org/xml/sax/ContentHandler.html) that aims at extracting standard references while parsing with Apache Tika. A standard reference is just a reference to a norm/convention/requirement (i.e., a standard) released by a [standard organization](https://en.wikipedia.org/wiki/List_of_technical_standard_organisations).

[Apache Tika](http://tika.apache.org/) is a toolkit for detecting and extracting metadata and structured text content from various documents using existing parser libraries.

The **StandardsExtractingContentHandler** extracts the standard references from text by relying on regular expressions.
